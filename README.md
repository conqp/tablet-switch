# tablet-mode

Allow users to toggle a convertible laptop between laptop and tablet mode.

## Configuration

The keyboard device to be deactivated in tablet mode must be specified in `/etc/tablet-mode.conf`:

    [Device]
    keyboard = /dev/input/by-path/platform-i8042-serio-0-event-kbd
    
## Usage

You must be a member of the group `tablet` to toggle between tablet and laptop mode.
You can toggle between tablet and laptop mode by running `toggle-tablet-mode` or use the desktop icon provided with this package.