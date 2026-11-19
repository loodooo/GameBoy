# GameBoy Emulator (C#)

A Game Boy emulator built from scratch in C# using GTK for the graphics and interface.
I [Theo Nito](https://github.com/Theonito08) made this for my computer science NEA project.

### Features:

- **CPU:** fully functioning and accurate.
- **Graphics:** PPU rendering using GTK, accurate enough to run games.
- **Audio:** 4-Channel Audio, with basic timing but its good enough
- **Controls:** D pad = WASD, A button = Z, B button = X, START = C, SELECT = V

#### Cartridge types supported:
Although all cartridge types are recognised, since different cartridge types work differently, this emulator cannot support them all.
Currently it supports No MBC, MBC1, MBC5 (with all their variants).

### Dependencies

- **GTK:**

Arch   ```sudo pacman -S gtk4```

Debian ```sudo apt-get install libgtk-4-dev```

Fedora ```sudo dnf install gtk4-devel```

Gentoo ```emerge --ask dev-libs/gtk```

- **DotNet 9:**

Arch   ```sudo pacman -S dotnet-sdk```

Debian ```sudo apt-get install dotnet-sdk-9.0```

Fedora ```sudo dnf install dotnet-sdk-9.0```

Gentoo --Good luck :/

### How to Run


## Authors

* [Theo Nito](https://github.com/Theonito08) - original creator of the emulator
* [looodoooo](https://github.com/loodooo) - modified to run natively on Linux using DotNet-9.0

This project is created strictly for educational purposes. No copyrighted ROM files or Nintendo trade secrets are included in this repository. Please provide your own legally obtained ROMs or open-source homebrew software to test.
