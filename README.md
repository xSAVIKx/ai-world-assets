# Agents World assets

This repository holds the asset files that the Planet screen of
[Agents World](https://github.com/xSAVIKx/ai-world) can download. The `aw`
binary does not contain these files. The hub downloads them only when the
operator turns on the setting `planet.models`.

## planet-pack-v1

The release `planet-pack-v1` has 8 character models (GLB, 3,986,840 bytes
in total). Each model has the animation clips `Idle`, `Walk` and `SitDown`.
The file `planet-pack-v1/SHA256SUMS` gives the SHA-256 of each file. The hub
checks the size and the SHA-256 of each file before it serves the file.

Do not change a file in a release. To change a file, make a new release.

## Source and licence

Pack:    Ultimate Animated Character Pack, November 2019
Author:  Quaternius (https://quaternius.com)
Page:    https://quaternius.com/packs/ultimatedanimatedcharacter.html
Licence: CC0 1.0 Universal (CC0-1.0), see `LICENSE`

The GLB files were converted from the FBX files of the pack with
FBX2glTF 0.9.7. They are byte-for-byte copies of the files at
`https://cdn.jsdelivr.net/gh/Polarjona/Proyecto-1@ca139cd32421415473a3990ea77b48828ce51ea9/proyecto/assets/characters/ultimate/`.

The author dedicated the pack to the public domain under CC0 1.0 Universal.
