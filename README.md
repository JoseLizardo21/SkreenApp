# SkreenApp

SkreenApp es una aplicación que permite utilizar un dispositivo Android como pantalla para un equipo Linux mediante una conexión USB.

El proyecto está compuesto por dos aplicaciones:

* **SkreenApp Desktop**: aplicación de escritorio para Linux.
* **SkreenApp Mobile**: aplicación Android encargada de recibir la imagen y enviar los eventos táctiles al equipo.

Además de la transmisión de pantalla, SkreenApp permite interactuar con el sistema utilizando la pantalla táctil del dispositivo móvil.

Actualmente, el proyecto se encuentra en desarrollo activo y se están implementando nuevas funcionalidades, como la creación de monitores virtuales para ampliar el espacio de trabajo.

---

## Características

* Transmisión de pantalla de Linux a dispositivos Android.
* Conexión mediante cable USB.
* Soporte para interacción táctil desde el dispositivo móvil.
* No requiere conexión Wi-Fi.
* Baja latencia gracias a la comunicación por USB.
* Próximamente: creación de monitores virtuales.

---

## Requisitos

Para utilizar SkreenApp es necesario:

* Instalar **SkreenApp Desktop** en el equipo Linux.
* Instalar **SkreenApp Mobile** en el dispositivo Android.
* Activar la **Depuración USB** en Android.
* Permitir la conexión cuando Android solicite autorización para depuración USB.

---

## Instalación

### Debian / Ubuntu (`.deb`)

```bash
sudo apt install ./skreenapp_0.1.0_amd64.deb
```

### Fedora / RPM (`.rpm`)

```bash
sudo dnf install ./skreenapp-0.1.0-1.fc43.x86_64.rpm
```

### Aplicación Android

Instale el APK de SkreenApp Mobile en su dispositivo Android.

---

## Configuración de Android

Antes de conectar el dispositivo, active la opción **Depuración USB** desde las Opciones de desarrollador.

<img width="340" height="700" alt="Depuración USB" src="https://github.com/user-attachments/assets/161c1381-d8d7-430f-b50b-72da9386d7fa" />

---

## Desinstalación

### Debian / Ubuntu (`.deb`)

```bash
sudo apt remove skreenapp
```

### Fedora / RPM (`.rpm`)

```bash
sudo dnf remove skreenapp
```

---

## Estado del proyecto

🚧 En desarrollo activo.

Las próximas versiones incluirán soporte para monitores virtuales, mejoras de rendimiento y compatibilidad con más distribuciones Linux.
