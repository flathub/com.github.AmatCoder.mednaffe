# Mednaffe packaged for Flatpak

This is a Flatpak for [Mednaffe](https://github.com/AmatCoder/mednaffe).

[Mednafen emulator](https://mednafen.github.io) is included.

## Installing from Flathub

This package is available on [Flathub](https://flathub.org/apps/details/com.github.AmatCoder.mednaffe).

To install, enter the following command in your terminal:

```bash
flatpak install flathub com.github.AmatCoder.mednaffe
```

Once installed, you can open it through your system's application manager or from the terminal with this command:

```bash
flatpak run com.github.AmatCoder.mednaffe
```

## Open included Mednafen emulator directly

You can open the Mednafen emulator directly from the terminal with this command:

```bash
flatpak run --command=mednafen com.github.AmatCoder.mednaffe [FILE]
```

Use this command to get the valid option parameters and their usage:

```bash
flatpak run --command=mednafen com.github.AmatCoder.mednaffe -help
```
