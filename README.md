[![License][LicenseBadge]][LicenseURL]
![Github Actions status, Windows][WinBuildBadge]
![Github Actions status, Flatpak][FlatpakBuildBadge]

# Tape Deck (WIP)

Modern music player, with MPD support

## Building

You'll need:

 * `meson >=0.56.0`
 * `gtk4 >=4.4`
 * `libadwaita-1 >=1.0`
 * `gstreamer-1.0 >=1.18`
 * `libmpdclient >=2.19`

Then:

```
git clone https://github.com/Miqueas/TapeDeck.git
cd TapeDeck
meson . _BUILD
ninja -C _BUILD
```

[LicenseBadge]: https://img.shields.io/github/license/Miqueas/TapeDeck?label=License
[LicenseURL]: https://opensource.org/licenses/Zlib
[WinBuildBadge]: https://img.shields.io/github/workflow/status/Miqueas/TapeDeck/Windows?label=Build&logo=windows
[FlatpakBuildBadge]: https://img.shields.io/github/workflow/status/Miqueas/TapeDeck/Flatpak?label=Build&logo=linux&logoColor=white
