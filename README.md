# Realtek drivers for RTL8192Cxx and RTL8188Cxx

These are the vendor drivers modified to run on more recent kernels (3.14+). Currently it is quite buggy, but does seem to work in station and AP modes.

## Compilation and Installation

You may need to blacklist the in-kernel driver (rtlwifi and rtl8192cu) to stop it from being loaded instead of this
driver.

```
make
sudo make install
```
