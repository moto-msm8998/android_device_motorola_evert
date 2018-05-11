# TWRP Device configuration for Motorola Moto G6 Plus

## Device specifications

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

![Device Picture](https://cdn2.gsmarena.com/vv/pics/motorola/motorola-moto-g6-plus-2.jpg)

### Kernel Source
Check here: https://github.com/ixmoe/android_kernel_motorola_sdm630

### How to compile

```sh
. build/envsetup.sh
lunch omni_evert-eng
make -j4 recoveryimage
```
### Copyright
 ```
  /*
  *  Copyright (C) 2013-17 The OmniROM Project
  *
  * This program is free software: you can redistribute it and/or modify
  * it under the terms of the GNU General Public License as published by
  * the Free Software Foundation, either version 3 of the License, or
  * (at your option) any later version.
  *
  * This program is distributed in the hope that it will be useful,
  * but WITHOUT ANY WARRANTY; without even the implied warranty of
  * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  * GNU General Public License for more details.
  *
  * You should have received a copy of the GNU General Public License
  * along with this program.  If not, see <http://www.gnu.org/licenses/>.
  *
  */
  ```
