# MR PURFRD

> Instalador avanzado de Arch Linux con personalización extrema.

MR PURFRD es un instalador automatizado para Arch Linux que permite construir un sistema completamente personalizado, desde el particionado hasta el entorno gráfico y drivers.

Diseñado para usuarios que quieren la libertad de Arch Linux sin repetir manualmente todo el proceso de instalación.

---

# ✨ Características

## 🧱 Instalación completa automatizada

- Particionado automático GPT
- Configuración UEFI
- Swap automática
- Instalación base de Arch Linux
- Configuración regional en español
- Configuración de usuarios
- Configuración de sudo

---

# 🐧 Kernels soportados

Actualmente:

- linux
- linux-lts *(próximamente)*
- linux-zen *(próximamente)*
- linux-hardened *(próximamente)*

---

# 🎮 Drivers soportados

## NVIDIA

- Drivers modernos
- NVIDIA 470xx
- NVIDIA 390xx

## AMD

- Mesa
- Vulkan
- OpenCL
- VA-API

## Configuración híbrida

- NVIDIA + AMD

---

# 🖥️ Entornos gráficos soportados

## Entornos ligeros

- LXDE
- LXQt
- XFCE
- MATE

## Entornos completos

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

# 📦 Paquetes opcionales

El instalador permite seleccionar categorías completas:

- Desarrollo
- Navegadores
- Multimedia
- Audio PipeWire
- Herramientas de red
- Compresión
- Bluetooth
- Utilidades del sistema
- Fonts
- Gaming

---

# 🎮 Gaming Ready

Soporte integrado para:

- Steam
- Proton
- Wine
- Lutris
- Gamescope
- Gamemode

---

# 🔧 Tecnologías incluidas

- GRUB
- PipeWire
- NetworkManager
- Yay (AUR helper)
- Multilib
- Vulkan
- OpenCL

---

# 🚀 Instalación

```bash
git clone https://github.com/usuario/mr-purfrd.git
cd mr-purfrd

chmod +x install.sh

sudo ./install.sh
```

---

# ⚠️ Advertencias

- Este instalador BORRA completamente el disco seleccionado.
- Pensado para sistemas UEFI.
- Uso recomendado en hardware x86_64.
- Algunas opciones Wayland requieren configuración manual posterior.

---

# 📂 Estructura del proyecto

```text
mr-purfrd/
├── install.sh
├── README.md
└── assets/
```

---

# 🛣️ Roadmap

- [ ] Soporte Btrfs
- [ ] Snapshots automáticos
- [ ] Cifrado LUKS
- [ ] Soporte dual boot
- [ ] Interfaz TUI avanzada
- [ ] Configuración modular
- [ ] Perfiles preconfigurados
- [ ] Soporte automático para laptops

---

# ❤️ Filosofía

MR PURFRD busca combinar:

- La simplicidad de un instalador moderno
- La libertad total de Arch Linux
- La personalización extrema
- La velocidad de despliegue

---

# 📜 Licencia

MIT License

---

# 🐧 Arch Linux, pero a tu manera.
