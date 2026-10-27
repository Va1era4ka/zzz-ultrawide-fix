# ZZZ Ultrawide Fix

[Русский](README.ru.md)

An experimental ZZMI mod for removing side black bars in Zenless Zone Zero at **5120×1440 / 32:9**. It targets the side-bar geometry instead of replacing the shared black texture used by menu panels and loading fades.

## Installation

Requires [XXMI Launcher](https://github.com/SpectrumQT/XXMI-Launcher) with ZZMI and the game running in **DirectX 11**.

1. Close the game and disable any other black-bar removal mod.
2. Copy **BlackBarsRemoval** into **ZZMI/Mods**.
3. Launch through XXMI. For the Steam edition, select **Settings → General → Game Launch → Steam**.

The installed file should be `ZZMI/Mods/BlackBarsRemoval/BlackBars.ini`.

## Controls

- **F7** — toggle this fix. Enabled by default at game launch.
- **F10** — reload ZZMI configuration after editing the INI.

To uninstall, close the game and remove the **BlackBarsRemoval** folder.

## Limitations

Version 0.1 was checked against recorded frames from the city, Esc menu and battle pass at 5120×1440. Loading transitions, cutscenes, other resolutions and DX12 are unverified.

Game updates or resolution changes may invalidate the matching rule. The mod does not expand menu layouts or change camera FOV. This is an unofficial mod with no guarantee of compatibility or account safety.

## Credits and license

Inspired by [JamesWander's 32:9 Super ultrawide Fix](https://gamebanana.com/mods/554974). Uses XXMI/ZZMI and 3Dmigoto. No original DDS or game resources are included.

[MIT License](LICENSE).
