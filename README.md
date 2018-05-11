# TWRP Device configuration for Motorola Moto G6 Plus (evert)

Copyright 2018 - The OmniROM Project

For building TWRP for Motorola Moto G6 Plus ONLY.

### Kernel Source
Check here: https://github.com/ixmoe/android_kernel_motorola_sdm630

### How to compile

```sh
. build/envsetup.sh
lunch omni_evert-eng
make -j4 recoveryimage
```

### Device specifications
=====================================

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core (8x2.21 GHz Cortex A53)
CHIPSET | Qualcomm SDM630 Snapdragon 630
GPU     | Adreno 508
Memory  | 3, 4, 6 GB
Shipped Android Version | 8.0 (Oreo)
Storage | 32, 64GB
Battery | 3000 mAh
Dimensions | 148.4 x 73.4 x 8 mm
Display | 1080 x 1920 pixels, 5.2" LTPS IPS LCD
Rear Camera  | Dual 12 MP
Front Camera | 8 MP
