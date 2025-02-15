# Bazzite Wolfy Custom

This is my own custom Universal Blue image, that is based off of the bazzite-nvidia image. I have customised the <https://github.com/ublue-os/image-template> template to build this image.

# Custom software

- **Visual Studio Code** - While both flatpak and rpm-ostree options are available, the rpm-ostree version offers better integration with the system.
- **gparted** - This lightweight partition editor is my preference over the KDE alternative.
- **qdirstat** - Very useful space monitoring tool
- **nemo** - Prefer this to gnome-files

# Rebasing to this image

Feel free to use this image if you wish, but I will not be providing support for this image

```bash
rpm-ostree rebase ostree-unverified-registry:ghcr.io/wolfyreload/bazzite-wolfy:stable
```