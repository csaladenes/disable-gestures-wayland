# Disable Gestures Wayland

A GNOME Shell extension that completely disables all touchpad gestures on Wayland.  
Inspired by the approach taken on https://extensions.gnome.org/extension/5233/swap-finger-gestures-3-to-4/  
by https://github.com/icedman/swap-finger-gestures-3-4

## Features

- Disables all touchpad gestures (swipes, pinches, etc.)
- Works specifically on Wayland - and it disables the newly introduced 3-finger swipe gestures!
- Preserves keyboard shortcuts and mouse functionality

## Installation

### From extensions.gnome.org

1. Visit [extensions.gnome.org](https://extensions.gnome.org)
2. Search for "Disable Gestures Wayland"
3. Click the install button

### Manual Installation

1. Download the extension zip file
2. Extract it to `~/.local/share/gnome-shell/extensions/disable-wayland-gestures@zonetra/`
3. Restart GNOME Shell (Alt+F2, type 'r' and press Enter) - or Log in and out
4. Enable the extension in GNOME Extensions at `https://extensions.gnome.org/local/`

## Usage

Once enabled, all touchpad gestures will be disabled. The Windows/Super key and other keyboard shortcuts will continue to work normally.

## Requirements

- GNOME Shell 42, 43, or 44
- Wayland display server

## License

GPL-2.0-or-later 
