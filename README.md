# SkreenApp

SkreenApp es una aplicación de escritorio para Linux que permite crear monitores virtuales y extender tu pantalla, transmitiendo el contenido a un dispositivo Android sin necesidad de hardware adicional (cables, dongles HDMI, etc.).

El sistema funciona capturando la pantalla mediante PipeWire/GStreamer en el lado de escritorio (compatible con Wayland), codificando el video en H.264 y transmitiéndolo por red (TCP) hacia un cliente Android desarrollado en Flutter, que decodifica el stream usando MediaCodec para mostrarlo en tiempo real.

---

## Instalación

### Debian / Ubuntu (`.deb`)

```bash
sudo dpkg -i skreenapp_0.1.0_amd64.deb
```

Si hay dependencias faltantes, ejecútalas con:

```bash
sudo apt-get install -f
```

### Fedora / RPM (`.rpm`)

```bash
sudo rpm -i skreenapp-0.1.0-1.fc43.x86_64.rpm
```

O usando `dnf` para resolver dependencias automáticamente:

```bash
sudo dnf install ./skreenapp-0.1.0-1.fc43.x86_64.rpm
```

---

## Desinstalación

### Debian / Ubuntu (`.deb`)

```bash
sudo dpkg -r skreenapp
```

### Fedora / RPM (`.rpm`)

```bash
sudo rpm -e skreenapp
```

O con `dnf`:

```bash
sudo dnf remove skreenapp
```
