# Bépo-Code

Keyboard layout for code, English, and French.

## Key features

- **Bépo layout**, slightly modified.
- **Qwerty shortcuts**, `Ctrl+X/C/V` are still together under the left hand.
- **Arrow keys** under the right hand, accessible with `AltGr`.
- **Number pad** under the right hand, accessible with `Meta` (`Alt`).
- **Code symbols** under the left hand, accessible with `Meta` (`Alt`).
- Modifier keys, as well as `Escape`, `Delete`, `Backspace`, and `Enter` brought closer to where the fingers rest.

Used everyday since 2019, this layout allows me to barely move my hands while touch-typing code, English, or French, and navigating and selecting text by characters, words, line, etc.

## Installation on Linux

Set up [keyd](https://github.com/rvaiya/keyd), place the file [default.conf](https://github.com/Zwyx/bepo-code/tree/master/src/keyd/default.conf) in `/etc/keyd/default.conf`, and run `sudo keyd reload`. Then add the content of the [xkb-\*](https://github.com/Zwyx/bepo-code/tree/master/src/keyd) files in their corresponding locations, and run `setxkbmap us bepo-code-keyd` (or select the layout in your system settings; note that a reboot might be necessary).

> [!NOTE]
> Before using keyd, Bépo-Code was made with an XKB configuration which you can find [here](https://github.com/Zwyx/bepo-code/tree/master/src/xkb). Note that it is no longer maintained.

## Layout

<div align="center">

![](/src/keyfab/Bepo-Code.png)

Image created using [jaroslaw-weber.github.io/keyfab](https://jaroslaw-weber.github.io/keyfab).

</div>
