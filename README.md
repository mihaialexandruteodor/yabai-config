# yabai-config

<img src="./screenshot.png" />

[step-by-step](https://medium.com/unixification/yabai-the-macos-tiling-window-manager-c5bda9d60bfc)

Notes:

- install via brew with ```brew install koekeishiya/formulae/yabai```
- create config in ```~/.config/yabai/yabairc```
- start with ```yabai --start-service``` , use restart-service or stop-service accordingly

# skhdrc

Yabai itself does not handle hotkeys.
You use a separate daemon called skhd (Simple HotKey Daemon) to define keybindings that trigger yabai commands.

```brew install skhd```
```skhd --start-service```

add the config in this repo to ```~/.config/skhd/skhdrc```

start, restart and stop services are the same as for yabai

