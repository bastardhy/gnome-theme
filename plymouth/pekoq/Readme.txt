sudo update-alternatives --config default.plymouth

sudo update-initramfs -u

sudo locale-gen --purge --no-archive

sudo update-initramfs -u -t