# blueBerryOS 1.0 Boreale

## Quick start

blueBerryOS Boreale is a Debian 13 (trixie) desktop distribution with GNOME. The AMD64 live ISO includes Berry‑AI and a bundled model that you can try offline.

### 1. Choose an image

| Edition | What you need |
| --- | --- |
| AMD64 live/install ISO | An Intel or AMD x86‑64 PC, a USB drive large enough for the 4.31 GB image, and free disk space if you choose to install. Use the live session to check Wi‑Fi, audio and graphics. |
| VirtualBox OVA | VirtualBox on an x86‑64 host. The appliance includes a 32 GiB virtual disk for testing installation. |
| Raspberry Pi ARM64 | A Raspberry Pi 4 or 5 with at least 4 GB RAM and a microSD card large enough for the image. |

[Official downloads and SHA‑256 checksums for all editions](https://blueberrylinux.com/en/get-bluberry/) · [Direct AMD64 ISO](https://blueberrylinux.com/downloads/boreale/blueberryos-v1.0-boreale-amd64.iso)

### 2. Verify the download

For the AMD64 ISO, save the image and [SHA256SUMS](https://blueberrylinux.com/downloads/boreale/SHA256SUMS) in the same directory. From that directory run:

```sh
sha256sum -c SHA256SUMS
```

For VirtualBox or Raspberry Pi, use the matching checksum file on the download page. The [English verification record](https://blueberrylinux.com/boreale/verification/) documents the published ISO checksum and earlier build tests.

### 3. Try or install Boreale

- **PC:** Write the ISO to the USB drive, boot from it, then select **Try blueBerryOS** for a live session or **Install blueBerryOS** for the graphical installer. Back up important files and confirm the target disk before partitioning.
- **VirtualBox:** Import the OVA as an appliance and start the VM. The boot menu offers the live session and installer.
- **Raspberry Pi:** Write the ARM64 image to a microSD card, insert it and power on the Pi.

[Installation instructions](https://blueberrylinux.com/en/get-bluberry/#avvio) · [Installation FAQ](https://blueberrylinux.com/en/faq/)

### Support

[Report a bug on GitHub](https://github.com/iervadev/blueberryOS-boreale/issues/new?template=bug-report.yml). Include your edition, hardware or hypervisor, the steps that reproduce the issue, and any relevant logs with personal information removed.

[Release notes](https://blueberrylinux.com/en/boreale/) · [Project website](https://blueberrylinux.com/en/) · [Debian Derivatives Census](https://wiki.debian.org/Derivatives/Census/blueBerryOS)
