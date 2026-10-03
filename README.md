# Overdrive releases

Finished, signed packages of the Overdrive dashboard software for the Raspberry Pi (ARMv7).
This repository contains **no source code**, only the release files.

- Each release has `Overdrive-<version>-armv7.tar.gz`, its `.sha256` and an Ed25519 `.sig`.
- Devices install updates themselves (Setup page -> "Nach Updates suchen"); they only accept packages
  whose signature matches the key built into the image.
- The app asks for a per-device licence key at first start.
