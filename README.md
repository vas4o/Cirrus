# Cirrus

![Linux](https://img.shields.io/badge/Linux-Compatible-brightgreen)
![QEMU](https://img.shields.io/badge/QEMU-Required-blue)

**Cirrus** is a minimal Linux system that boots a `bzImage` kernel with an `initramfs.gz` directly using QEMU, without creating an ISO or disk image if you want to make it an iso

---

## Requirements

### Linux
- `qemu-system-x86_64`

Installation for linux:
```bash
git clone https://github.com/vas4o/Cirrus.git
cd Cirrus

sudo apt install qemu-system-x86

qemu-system-x86_64 -kernel bzImage -initrd initramfs.gz -append "console=ttyS0" -nographic
