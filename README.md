# VoidUI Eternity Project - Weekly Updates Branch

![Picsart_22-06-16_04-16-29-275](https://user-images.githubusercontent.com/34755141/174213996-2a08b196-2fd0-49af-8f17-3fe5f7cd2bd7.png)

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/VoidUI/manifest -b aosp-12.1-weekly

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

# Telegram Support Groups
* [**Telegram Support Group**](https://t.me/VoidUI)
 * [**VoidUI Alioth/In Group**](https://t.me/VoidUI_Alioth)
 * [**Russian Speaking Alioth/In**](https://t.me/VoidUI_Alioth_RU)
 * [**VoidUI Apollo/n Group**](https://t.me/VoidUI_Apollo)
 * More Devices, Features and Groups Sooon
