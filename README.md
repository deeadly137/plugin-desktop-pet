# Desktop Pet

A draggable desktop-widget plugin for Caelestia Shell. The pet bobs above the wallpaper and below normal windows; drag it anywhere on the desktop.

## Requirements

- A plugin-enabled Caelestia Shell build with the `desktop-widget` entry point, such as `caelestia-shell-plugins-git`.

## Install

```sh
mkdir -p ~/.config/caelestia/plugins
git clone https://github.com/deeadly137/plugin-desktop-pet.git ~/.config/caelestia/plugins/plugin-desktop-pet
```

Enable the plugin in `~/.config/caelestia/plugins.json`:

```json
{
    "enabled": ["deeadly137/desktoppet"]
}
```

The shell watches the config and plugin directory, so a reload is usually automatic. Restart the shell if the pet does not appear.

## Plugin details

- Manifest id: `deeadly137/desktoppet`
- Entry point: `desktop-widget`
- Source: `DesktopPet.qml`

## License

GPL-3.0-only. See `LICENSE`.
