---
description: "Ferrydisk is a Mac app that copies encrypted HFS+ Time Machine disks into encrypted disk images that macOS 28 still opens."
---
# Ferrydisk

Ferrydisk is a Mac app that copies encrypted HFS+ Time Machine disks into encrypted disk images that macOS 28 still opens.

macOS 28 drops encrypted Mac OS Extended (CoreStorage) volumes. Apple's decrypt and convert path excludes encrypted Time Machine disks, and its only advice is to start a new backup. Years of backup history stay behind unless you keep an old Mac.

## What it does
- Lists every encrypted HFS+ volume on connected drives, with its name, drive and size. Free.
- Unlocks a volume with its password, which proves the password and the disk still work. Free.
- Lists the Time Machine backups on an unlocked volume, by Mac and date. Free.
- Copies the volume block by block into an AES-256 encrypted sparse bundle, with the old disk's password. Pro.
- Resumes a copy after sleep, an unplugged disk or a quit. Pro.
- Verifies every copied block against the old disk, and copies differing blocks again. Pro.

Ferrydisk Pro is a one-time purchase of $3.99 in the US. The license key arrives by email within 24 hours of payment.

## Works with
- Encrypted Mac OS Extended (HFS+) volumes on USB, Thunderbolt and internal drives, including Time Machine backup disks.
- The copy opens in Finder as the old volume, with every backup date and hard link.
- The old disk is read only. Ferrydisk never writes to it.

Ferrydisk is not made by or affiliated with Apple.

## What it does not do
- It does not decrypt a disk in place.
- It does not restore single files. It copies the whole volume.
- It does not open encrypted network backups (sparse bundles). macOS 28 still opens them.
- It does not list APFS or unencrypted disks. macOS 28 still opens them.
- It cannot open a disk without its password. A recovery key does not work either.

## Requirements
macOS 26 or later, on Apple silicon or Intel.
The destination disk needs as much free space as the old volume uses.
Ferrydisk reads disks through a helper that runs as root. macOS asks you to allow it in Login Items & Extensions.

## Questions
**Can I keep my encrypted Time Machine backups after upgrading to macOS 28?**
Yes. Ferrydisk copies the encrypted HFS+ volume into an encrypted disk image, and macOS 28 opens that image.

**Can I decrypt an encrypted Time Machine drive when Disk Utility has no Decrypt option?**
Yes. Ferrydisk unlocks the volume with its password and copies it into an encrypted disk image. The old drive stays as it is.

**Do I keep every backup date?**
Yes. Ferrydisk copies the volume block for block, so every backup date stays browsable in Finder.

**Can I check that my old password still works before I pay?**
Yes. Finding, unlocking and listing the backups are free in Ferrydisk.

**Does Ferrydisk change my old disk?**
No. Ferrydisk only reads the old disk. It needs no account and has no tracking.

## Get it
Ferrydisk is not out yet. The download link and the Pro checkout for $3.99 go here at launch.

[Support](support.html) · [Privacy Policy](privacy-policy.html)
