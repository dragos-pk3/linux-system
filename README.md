### Repository Purpose

This repository serves as a structured backup and version-tracking solution for personalized configuration files used on my Fedora i3 Spin Linux installation. The aim is to maintain a minimal, stable, and efficient computing environment, customized specifically to my workflows involving coding, writing, and continuous learning.

### Context and Motivation

After experimenting with various Linux distributions (Arch, Debian) and desktop environments/window managers (KDE, XFCE, GNOME, Hyprland), I've settled on **Fedora i3 Spin** due to its optimal balance of simplicity, stability, and ease of customization. These configurations reflect precise adjustments tailored to enhance my productivity and maintain flexibility.

### System Information

* **OS**: Fedora Linux 42 (Adams), periodically updated for essential stability and security patches.
* **Desktop Environment**: i3 (X11), selected for minimalism and performance.
* **Laptop**: Lenovo IdeaPad Pro 5i (Intel Core i5-13500H, NVIDIA RTX 3050 GPU, 32 GB RAM, details provided via `fastfetch`).
* **Themes and Icons**:

  * **GTK Theme**: Adwaita-dark
  * **Icon Theme**: breeze-dark (lightdm) and Adwaita (GTK apps)
  * **Fonts**: Sans 10pt
* **Terminal**: xfce4-terminal
* **Login Manager**: LightDM with GTK Greeter (`lightdm-gtk-greeter.conf`), background and icons personalized.

### Configuration Files Included

* `settings.ini`: GTK-specific theme, icon, and font preferences.
* `lightdm-gtk-greeter.conf`: Customized login interface with visual enhancements.

### Usage and Maintenance

These configuration files are designed as a stable baseline. Changes will be minimal, intended primarily for occasional essential updates or as a reliable fallback in the event of system instability. Users aiming for similar lightweight, productivity-focused setups may utilize or reference these configurations directly.
