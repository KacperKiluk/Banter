# Banter

Publiczne wydania komunikatora Banter dla Windows i Arch Linux.

## Polski

| System | Plik do zainstalowania |
| --- | --- |
| Windows x64 | [Banter-Setup.exe](./Banter-Setup.exe) |
| Arch Linux x86_64 | [Banter-ArchLinux-x86_64.pkg.tar.zst](./Banter-ArchLinux-x86_64.pkg.tar.zst) |

### Windows

1. Pobierz `Banter-Setup.exe`.
2. Uruchom instalator i wykonaj jego instrukcje.
3. Po instalacji uruchom Banter z menu Start.

### Arch Linux

1. Pobierz `Banter-ArchLinux-x86_64.pkg.tar.zst`.
2. Otwórz terminal w katalogu z pobranym plikiem.
3. Zainstaluj aplikację:

```bash
sudo pacman -U ./Banter-ArchLinux-x86_64.pkg.tar.zst
```

Pliki `.sig` zawierają podpisy aktualizacji, pliki `.sha256` sumy kontrolne, a `latest.json` dane dla automatycznego aktualizatora. Nie są to instalatory.

Jeśli masz wersję starszą niż 0.6.1, zainstaluj bieżące wydanie ręcznie jeden raz. Wersja 0.6.1 i nowsze sprawdzają dostępność podpisanych aktualizacji przy uruchomieniu aplikacji.

## English

| System | File to install |
| --- | --- |
| Windows x64 | [Banter-Setup.exe](./Banter-Setup.exe) |
| Arch Linux x86_64 | [Banter-ArchLinux-x86_64.pkg.tar.zst](./Banter-ArchLinux-x86_64.pkg.tar.zst) |

### Windows

Download and run `Banter-Setup.exe`, then follow the installer.

### Arch Linux

Download `Banter-ArchLinux-x86_64.pkg.tar.zst` and install it with:

```bash
sudo pacman -U ./Banter-ArchLinux-x86_64.pkg.tar.zst
```

The `.sig`, `.sha256`, and `latest.json` files support signature verification and automatic updates; they are not installers.

Versions 0.6.1 and newer check for signed updates when the application starts. Older installations must be upgraded manually once.

