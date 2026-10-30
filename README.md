# GTK4 configuration

Getrennte GTK4-Einstellungen und CSS für kompatible Anwendungen.

**[Dokumentation](https://arch-dotfiles.readthedocs.io/en/latest/components/#gtk4)** ·
[Installation und Updates](https://arch-dotfiles.readthedocs.io/en/latest/arch-package/)

```bash
curl -fsSL https://raw.githubusercontent.com/MichaelWeissDEV/dotfiles/main/install.sh | bash -s -- gtk-4.0
```

Paket: `arch-dotfiles-gtk-4.0`. Dateien: `~/.config/gtk-4.0/settings.ini` und `gtk.css`.
Quellen und `packaging/arch/PKGBUILD` werden hier gepflegt. Nach Push auf `main`
und erfolgreichem Registry-Build aktualisiert `sudo pacman -Syu` das Paket.
Entwicklung und Builds: [PACKAGING.md](PACKAGING.md).

[![Package safety](https://github.com/MichaelWeissDEV/gtk4-config/actions/workflows/package.yml/badge.svg)](https://github.com/MichaelWeissDEV/gtk4-config/actions/workflows/package.yml)

[MIT-Lizenz](LICENSE).
