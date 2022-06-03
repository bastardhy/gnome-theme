# Starry Night Plymouth Theme

Starry night is a simple but elegant Plymouth theme, showing the word
"linux" and a diving penguin. A moving star indicates that the boot
process is still running.


## How to install

**WARNING:** Do not install unless you know what you do and how to repair a non-booting system.

* Download and unpack [Starry-Night-Plymouth.tar.gz](https://bitbucket.org/gemlion/aurora-penguinis/raw/master/Starry-Night-Plymouth.tar.gz "Install package").

* Copy the whole folder **Starry-Night-Plymouth** with root privileges to **/usr/share/plymouth/themes/**

```bash
$ sudo cp -R Starry-Night-Plymouth /usr/share/plymouth/themes/
```

* Then run the following commands in a terminal:

```bash
$ sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/star/star.plymouth 100

$ sudo update-alternatives --config default.plymouth

$ sudo update-initramfs -u
```


## Sources

Starry-Night-Plymouth is based on the Xubuntu Logo Plymouth Theme by the
Xubuntu Developer Team

