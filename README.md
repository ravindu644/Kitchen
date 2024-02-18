## Kitchen (Boot image unpacker and repacker)

**Description :** This script can unpack, repack, and sign the boot images of Android without breaking Android Verified Boot (AVB).

**Requirements :** Linux Environmnt (Termux/PC)
<hr>

### Usage :
**01.** Clone this Repository.

**02.** Navigate to Repo's directory and put your boot.img there.

**03.** To Unpack the boot image, use this command :

```
./kitchen unpack boot.img
```

- Replace boot.img with your boot image's name.
- Make edits to the unpacked boot image in the "workspace" folder.

**04.** To Repack the boot image, use this command :
```
./kitchen repack
```
<hr>

- Contributions are Welcome.
- Join my <a href="https://t.me/SamsungTweaks">Telegram</a> for more Android tips.
- Credits : <a href="https://github.com/topjohnwu/Magisk">Magisk</a> for magiskboot binary.