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
