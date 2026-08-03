# TWRP Device Tree for Samsung Galaxy Z Flip3 5G

## Bugs

- /data decryption
- Cover screen will be stuck at Galaxy Logo and may burn in!

## How to build

This device tree was tested and is fully compatible with [minimal-manifest-twrp](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp).

1. Set up the build environment following the instructions [here](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp/blob/twrp-12.1/README.md#getting-started)

2. In the root folder of the fetched repo, clone the device tree:

```bash
git clone https://github.com/AlexFurina/twrp_device_samsung_b2q.git device/samsung/b2q
```

3. To build:

```bash
. build/envsetup.sh
lunch twrp_b2q-eng
mka recoveryimage
```
