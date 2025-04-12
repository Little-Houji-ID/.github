
HorizonDroid
===========

![**HorizonBanner**](../horizon.svg)

Welcome to HorizonDroid!

HorizonDroid is based on AOSP and PixelOS, allows users to experience Google's latest Pixel updates while integrating useful features from known custom ROMs.
We currently support Android 15, with the latest security patches from Google.

### Quick Source Initialization ###

```bash
repo init -u https://github.com/HorizonDroidLab/manifest.git -b fifteen --git-lfs
```

```bash
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune --retry-fetches=5 -j10
```

```bash
. build/envsetup.sh
```

```bash
lunch horizon_devicecodename-bp1a-buildtype
```

```bash
mka horizon
```

[More build information](https://github.com/HorizonDroidLab/manifest)

### Official Support Group & Channel

* [**Telegram Channel**](https://t.me/horizondroid)
* [**Telegram Group**](https://t.me/HorizonDroidChat)

-----------------------------------------------------------------------------
![CreditsImg](../credit.svg)
 Special thanks to All ROM Developers in this community
 * [**PixelOS**](https://github.com/PixelOS-AOSP)
 * [**CLO**](https://git.codelinaro.org)
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)

-----------------------------------------------------------------------------
