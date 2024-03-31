# Blackbriar GTK theme

A black-background white-outline GTK theme. Meant to match
[Blackbriar KDE theme](https://github.com/swomf/Blackbriar-kde-theme).

## Previews

### KDE 6

![KDE6 preview](kde6-preview.png)

### XFCE 4

![XFCE preview](xfce-preview.png)

- `Wallpapers` [Graphite Wallpapers](/wallpaper)

## Installation

Ensure that GTK >= 3.20 and `sassc` are installed.  
The [Papirus](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) icon theme is recommended.

```bash
# use sudo if system-wide installation is desired
./install.sh
```

Run `install.sh --help` for more information.

### IMPORTANT NOTE

Sometimes, libadwaita apps such as Celluloid do not
respect the system's GTK theme. To avoid this, you can
run `./install.sh -l` -- this option creates symlinks
within `~/.config/gtk-4.0` to `$theme_dir/gtk-4.0`.
