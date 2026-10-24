# Installation — v1.0

[Download the v1.0 patch](https://github.com/PhabejSam/pokemon-zero-to-legend-release/releases/tag/v1.0) · [Home](README.md)

Use your own clean **Pokémon Emerald Version (USA, Europe), revision 0**:

| Check | Required value |
| --- | --- |
| Size / game code | 16,777,216 bytes / BPEE |
| CRC32 | `1F1C08FB` |
| SHA-256 | `a9dec84dfe7f62ab2220bafaef7479da0929d066ece16a6885f6226db19085af` |

1. Check the downloaded UPS against the release's checksum file. Filename: `Pokemon-Zero-to-Legend-v1.0.ups`, SHA-256 `7cf2a43cc6c5e3eb4af8ac099ea97f0a2c75e74648c4a418e8518911fb17307a`.
2. Use [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/) with checksum validation enabled. Apply the patch directly to clean Emerald; do not apply Heart & Soul first or patch an older Zero to Legend ROM.
3. Save the patched result separately. Expected size: **33,554,432 bytes**. Expected SHA-256: `b0c9d480fe2d64ca607522a0d6a5e152f1fa47721a66d8434e65101289a85d1c`.
4. Cold-launch in your GBA emulator and use native New Game or Continue as appropriate. Save through the game's menu.

## Existing progress

Back up your own working ROM and battery save first. Use a copy through your emulator's normal save association/import procedure; changing the ROM basename may change which save is selected. Check trainer, map, original partner, party and inventory before saving. If Continue is missing or incorrect, stop and keep the original files. Do not start a new game over an unexpected save.

Use native Continue instead of an old emulator save state. The owner reports existing-progress acceptance on exact RC1. This does not certify every historical version, save wrapper or emulator. Do not truncate/convert a save solely because of its file size. Emerald/HnS saves and cross-edition DSi transfers are not certified.

No base ROM, playable ROM, BIOS or save is supplied. The separately experimental DSi candidate is not part of the main package. Read [compatibility](COMPATIBILITY.md) and [known limitations](KNOWN-LIMITATIONS.md).
