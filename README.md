# cachyos-umbriel-settings

[**Umbriel**](https://github.com/noctalia-dev/umbriel) is a Wayland compositor with *scrolling*, *dwindle*, *master* and *stacking* layouts, independent workspaces per monitor, and configurable visual effects.

This repository contains `Umbriel` specific settings, like `config.toml` and `xdg-desktop-portal`.

Dependencies:

```sh
umbriel xdg-desktop-portal-umbriel
```

## Repository tree

### Path `.config/umbriel`:

in `config.toml` you can find all `includes` from the `config/` directory.

### Path `.config/umbriel/config`

| config | purpose |
| ------ | ------- |
| `animations.toml` | default animations; beziers and springs       |
| `appearance.toml` | look and feel; no theming                      |
| `general.toml`    | compositor's basics; mod key, xwayland         |
| `inputs.toml`     | libinput settings; mouse, keyboard, cursor     |
| `keybinds.toml`   | compositor's keybinds; customize to your liking |
| `layout.toml`     | layouts; dwindle, stacking, scrolling, master  |
| `overview.toml`   | compositor's overview settings; look and feel  |
| `workspaces.toml` | general settings and workspace rules;         |

### Path `.config/xdg-desktop-portal`

In `umbriel-portals.conf` you can configure `xdg-desktop-portal` directives for `umbriel`; Default portal already set

<br/>

Thank you for using CachyOS Umbriel Settings.
