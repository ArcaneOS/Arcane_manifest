# ArcaneOS #
<p align="center">
  <img src="https://i.imgur.com/up0ipZh.png" />
</p>
### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/dlwlrma123/Arcane_manifest -b R

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```
## Credits
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**CipherOS**](https://github.com/CipherOS)
 * [**WaveOS**](https://github.com/Wave-Project)
 * [**HyconOS**](https://github.com/HyconOS)
 * [**SpiceOS**](https://github.com/SpiceOS)
 * [**P-404**](https://github.com/P-404)
 * [**PixelBlaster-OS**](https://github.com/PixelBlaster-OS)
 
and the list goes on..

