## Kitchen (Boot image unpacker and repacker)
![Preview IMG](https://github.com/ravindu644/Kitchen/assets/126038496/61fc39dd-5fe6-4fb5-8c06-0b6a6b2c937b)
**Description:** This script can unpack, repack, and sign the boot images of Android without breaking Android Verified Boot (AVB).

**Requirements:** Linux Environment (Termux/PC)

---

### Usage :
**01.** Clone this Repository.

**02.** Navigate to Repo's directory and put your boot.img there.

**03.** To Unpack the boot image, use this command :

```
./kitchen unpack boot.img
```

- Replace boot.img with your boot image's name.
- Make edits to the unpacked boot image in the "workspace" folder. <br>

> **❗Notes:** You can only use the **OEM boot image** which is provided by your manufacturer inside your firmware package. Else, the script will throw an error while signing the modified boot image.

**04.** To Repack the boot image, use this command :

```
./kitchen repack
```

---

- Contributions are Welcome.
- Join my [Telegram](https://t.me/SamsungTweaks) for more Android tips.
- Credits : [Magisk](https://github.com/topjohnwu/Magisk) for magiskboot binary.
