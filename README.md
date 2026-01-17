
# Cirrus

**Cirrus** is a minimal Linux system that boots a `bzImage` kernel with an `initramfs.gz`
directly using QEMU, without creating an ISO or disk image.

---

## Requirements

### Linux
- `qemu-system-x86_64`

Debian / Ubuntu:
```bash
sudo apt install qemu-system-x86
