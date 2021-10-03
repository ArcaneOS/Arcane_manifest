# ArcaneOS #
<p align="center">
  <img src="https://i.imgur.com/zKqfYIb.png" />
</p>

```bash
* ArcaneOS is a simple rom, fueled by Pixel Experience that aims to be simple yet cunning. ArcaneOS provides necessary
  customizations that is needed for every day life, from your traffic indicator down to your favorite icon styles. 
  While also promising to be simple, ArcaneOS was made to be aesthetic without making its users go through a lot 
  of configurations. ArcaneOS is a fan LineageOS; simple, bloatfree and fast.
  
* This custom-ROM has no affiliations or connections to the ArcaneOS described here:(https://www.xda-developers.com/fbi-backdoor-pixel-arcaneos-anom). The brand name was inspired by the terminology "Arcane" from the game called "dota 2".

```
  
### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/ArcaneOS/Arcane_manifest -b R

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
### Build ###
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**CipherOS**](https://github.com/CipherOS)
 * [**WaveOS**](https://github.com/Wave-Project)
 * [**HyconOS**](https://github.com/HyconOS)
 * [**SpiceOS**](https://github.com/SpiceOS)
 * [**P-404**](https://github.com/P-404)
 * [**PixelBlaster-OS**](https://github.com/PixelBlaster-OS)
 * [**ProtonAOSP**](https://github.com/ProtonAOSP)
 * [**DerpFest-11**](https://github.com/DerpFest-11)
 
### and the list goes on.. ### 

