# SkreenApp

SkreenApp is an application that lets you use an Android device as a display for a Linux computer over a USB connection.

The project consists of two applications:

* **SkreenApp Desktop**: desktop application for Linux.
* **SkreenApp Mobile**: Android application that receives the image and sends touch events back to the computer.

In addition to screen streaming, SkreenApp lets you interact with the system using the mobile device's touchscreen.

The project is currently under active development, and new features are being implemented, such as creating virtual monitors to extend your workspace.

---

## Features

* Screen streaming from Linux to Android devices.
* Connection via USB cable.
* Touch interaction support from the mobile device.
* No Wi-Fi connection required.
* Low latency thanks to USB communication.
* Coming soon: virtual monitor creation.

---

## Requirements

To use SkreenApp you need to:

* Install **SkreenApp Desktop** on the Linux computer.
* Install **SkreenApp Mobile** on the Android device.
* Enable **USB Debugging** on Android.
* Allow the connection when Android asks for USB debugging authorization.

---

## Installation

### Debian / Ubuntu (`.deb`)

```bash
sudo apt install ./skreenapp_0.1.1_amd64.deb
```

### Fedora / RPM (`.rpm`)

```bash
sudo dnf install ./skreenapp-0.1.0-1.fc43.x86_64.rpm
```

### Android App

Install the SkreenApp Mobile APK on your Android device.

---

## Android Setup

Before connecting the device, enable **USB Debugging** from Developer Options.

<img width="340" height="700" alt="USB Debugging" src="https://github.com/user-attachments/assets/161c1381-d8d7-430f-b50b-72da9386d7fa" />

---

## Uninstallation

### Debian / Ubuntu (`.deb`)

```bash
sudo apt remove skreenapp
```

### Fedora / RPM (`.rpm`)

```bash
sudo dnf remove skreenapp
```

---

## Project Status

🚧 Under active development.

Upcoming releases will include virtual monitor support, performance improvements, and compatibility with more Linux distributions.

---

## Contributing

Want to join? All help is welcome — check out the repositories and send us your PR 🚀

- 🖥️ [SkreenApp Desktop](https://github.com/JoseLizardo21/SkreenAppDesktop)
- 📱 [SkreenApp Mobile](https://github.com/JoseLizardo21/SkreenAppMobile)
