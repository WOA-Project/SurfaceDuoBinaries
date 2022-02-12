# Firmware Binaries

This repository contains various UEFI firmwares extracted using https://github.com/theopolis/uefi-firmware-parser

## How to reproduce

```
uefi-firmware-parser -o ./Output -O -b -g BOOT.XF.3.0-00527-SM8150LZB-1 ./11
```

Where ```./11``` is an UEFI image.