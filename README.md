# iOS 5 - 6 Hacktivation
## Features
- Untethered hacktivate iOS 5 - 6 devices
- Useful for bypassed A5 - A6 (X) devices
- Supports sideloading .ipa files with AppSync installed
## Usage
- Make sure target device has an untethered jailbreak
- Enter pwnDFU mode, boot an SSH ramdisk, SSH into device, mount system partition. This can be done with [Legacy iOS Kit](https://github.com/LukeZGD/Legacy-iOS-Kit), a powerful tool for legacy iDevices
  - For coolbooter partition, run `mount_hfs /dev/disk0s1s3 /mnt1` instead of `mount.sh`
- Replace original `/mnt1/usr/libexec/lockdownd` with this patched one
- Chmod it to 0755, reboot
- Enjoy!
