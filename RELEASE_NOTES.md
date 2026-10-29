# LineageOS 24.0 GSI by Aizner

Unofficial Android 17 Generic System Image.

## Build information

- LineageOS: 24.0
- Android: 17
- Build date: 2026-10-29
- Security patch: 2026-10-01
- Architecture: ARM64
- Variant: arm64_bvN
- System-as-Root / A/B-style GSI
- Vanilla: no bundled Google apps
- No bundled PHH SU
- TrebleDroid Settings included

## Device compatibility

GSI for ARM64 devices supporting Project Treble with a System-as-Root (A/B-style) layout.

Tested on Nothing A009P / SuperContra.
Compatibility and hardware functionality may vary by device and vendor firmware.

## Download

Download the compressed system image and SHA256SUMS.txt from:
https://github.com/eyzner/LineageOS-GSI/releases

Verify the download:

    sha256sum -c SHA256SUMS.txt

Decompress:

    unxz -k lineage-24.0-20261029-UNOFFICIAL-arm64_bvN.img.xz

Installation instructions depend on your device.
Back up your data before installing.

## Credits and upstream projects

- LineageOS: https://github.com/LineageOS
- TrebleDroid: https://github.com/TrebleDroid
- PHH: https://github.com/phhusson
- Android 17 Treble device tree:
  https://github.com/cawilliamson/android_device_phh_treble
- RestlessOS build resources:
  https://github.com/cawilliamson/treble_restlessos

Maintainer: Aizner / eyzner.

This is a community build, not an official LineageOS release.
