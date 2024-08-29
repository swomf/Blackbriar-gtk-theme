# Blackbriar GTK theme

A black-background white-outline GTK theme. Meant to match
[Blackbriar KDE theme](https://github.com/swomf/Blackbriar-kde-theme).

## Previews

### KDE 6

![KDE6 preview](kde6-preview.png)

### XFCE 4

![XFCE preview](xfce-preview.png)

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

## Licensing/Attribution

GNU GPL v3

| Resource             | Source               | License             |
|----------------------|----------------------|---------------------|
| Main forked theme    | [Graphite-gtk-theme] | GPLv3               |
| Crystal wallpaper    | [articted]           | "no commercial use" |
| [Lagtrain] wallpaper | edit of a frame      | ?                   |

* The Lagtrain wallpaper is a derivative work edited from a
  frame from the *inabakumori - Lagtrain* music video.

[Graphite-gtk-theme]: https://github.com/vinceliuice/Graphite-gtk-theme
[articted]: https://www.behance.net/gallery/10876531/FLATzero-Wallpaper-Pack
[Lagtrain]: https://youtube.com/watch?v=UnIhRpIT7nc
