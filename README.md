# FIP-Player

A simple FIP radio (and Radio France) player with mpris metadata

White theme
<p align="center">
  <img src="docs/screenshot.png" />
</p>

Dark theme
<p align="center">
  <img src="docs/screenshot-dark.png" />
</p>

# How to use

## Dependencies

* Go >= 1.19
* You need to have **libmpv** installed on your system.

**Arch**
```shell
pacman -S mpv go
```

**Ubuntu**
```shell
apt install libmpv-dev golang
```

## Build and run

`go run .`

Run in debug mode (creates a log file in /tmp)

`go run . -d`

## Install

```shell
go build
sudo cp fip-player /usr/local/bin
```

# Credits

* A cool dbus lib: https://github.com/godbus/dbus
* Nice libmpv bindings: https://github.com/aykevl/plaincast
* Awesome mpris implementation using godbus: https://github.com/natsukagami/mpd-mpris
* Pretty TUI lib: https://github.com/charmbracelet/bubbletea
