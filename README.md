# cachyos-umbriel-settings

[**Umbriel**](https://github.com/noctalia-dev/umbriel) is a Wayland compositor with *scrolling*, *dwindle*, *master* and *stacking* layouts, independent workspaces per monitor, and configurable visual effects.

This repository contains `Umbriel` specific settings, like `config.toml` and `xdg-desktop-portal`.

Dependencies:

```Sh
umbriel xdg-desktop-portal-umbriel
```

## Reposotiry tree

### Path [`.config/umbriel/`](./etc/skel/.config/umbriel/):

in `config.toml` you can find all `includes` from directory `config/`

### Path [`.config/umbriel/config`](./etc/skel/.config/umbriel/config/):

| config | purpose |
| ------ | ------- |
| [`animations.toml`](./etc/skel/.config/umbriel/config/animations.toml.) | default animataions; beziers and springs       |
| [`appearance.toml`](./etc/skel/.config/umbriel/config/appearance.toml) | look and feel; no theming                      |
| [`general.toml`](./etc/skel/.config/umbriel/config/general.toml)    | compositor's basics; mod key, xwayland         |
| [`inputs.toml`](./etc/skel/.config/umbriel/config/general.toml)     | libinput settings; mouse, keyboard, cursor     |
| [`keybinds.toml`](./etc/skel/.config/umbriel/config/inputs.toml)  | compositor's keybinds; customize to you liking |
| [`layout.toml`](./etc/skel/.config/umbriel/config/keybinds.toml)     | layouts; dwindle, stacking, scrolling, master  |
| [`overview.toml`](./etc/skel/.config/umbriel/config/overview.toml)   | compositor's overview settings; look and feel  |
| [`workspaces.toml`](./etc/skel/.config/umbriel/config/workspaces.toml) | general settings and workspaces rules;         |

### Path [`.config/xdg-desktop-portal`](./etc/skel/.config/xdg-desktop-portal/):

In [`umbriel-portals.conf`](./etc/skel/.config/xdg-desktop-portal/umbriel-portals.conf) you can configure `xdg-desktop-portal` directives for `umbriel`; Default portal already set

<br/>

Thank you for choosing CachyOS!
