# hypr-darkwindow
Hyprland plugin that adds possibility to invert the color of specific windows.

![preview](./res/preview.png)

## Configuration
This Branch adds config, that use the rulev2 syntax:
```conf
# hyprland.conf
plugin {
    dark_window {
        invert = class:(pb170.exe)
        invert = fullscreen:1
    }
}
```

Also adds 2 Dispatches `invertwindow WINDOW` and `invertactivewindow`

## Installation
Confirmed not working on < v0.28.0
Wokrs on v0.28.0
```sh
make all && make load
```
