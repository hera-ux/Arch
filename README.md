# MR PURFRD

> Instalador automatizado de Arch Linux con alto nivel de personalización.

MR PURFRD es un script de instalación para Arch Linux que automatiza el proceso completo de instalación permitiendo elegir drivers, paquetes, entorno gráfico y herramientas adicionales.

---

# ✨ Características

- Particionado automático GPT
- Configuración UEFI con GRUB
- Instalación base de Arch Linux
- Configuración de swap
- Configuración regional en español
- Creación de usuario y contraseña
- Configuración de sudo
- Activación de multilib
- Instalación automática de drivers
- Instalación de entornos gráficos
- Instalación de paquetes opcionales
- Instalación de yay (AUR helper)
- Instalación opcional de Wine y Proton

---

# 🖥️ Entornos gráficos soportados

## Entornos de escritorio

- LXDE
- LXQt
- XFCE
- MATE
- GNOME
- KDE Plasma
- Cinnamon
- Budgie

## Window Managers X11

- i3
- Openbox
- bspwm
- AwesomeWM

## Wayland

- Hyprland
- Sway
- River
- Niri

---

# 🎮 Drivers soportados

## NVIDIA

- Drivers modernos
- NVIDIA 470xx
- NVIDIA 390xx

## AMD

- Mesa
- Vulkan Radeon
- OpenCL Mesa

---

# 📦 Paquetes opcionales

El instalador permite instalar:

- Herramientas de desarrollo
- Chromium
- Utilidades de discos
- Fastfetch
- Fonts
- Audio y multimedia
- Herramientas de compresión
- Utilidades de red
- Herramientas del sistema

---

# 🎮 Gaming

Instalación opcional de:

- Steam
- Proton
- Wine Staging
- Lutris
- Gamescope
- Gamemode

---

# 🔧 Componentes instalados

- GRUB
- PipeWire
- NetworkManager
- Yay
- sudo
- nano

---

# 🚀 Instalación

```bash
git clone https://github.com/usuario/mr-purfrd.git

cd mr-purfrd

chmod +x install.sh

sudo ./install.sh
```

---

# ⚠️ Advertencia

Este script elimina completamente el disco seleccionado durante el particionado.

---

# 📜 Licencia

MIT License
