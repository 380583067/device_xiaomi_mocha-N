# Device configuration for XiaoMi MiPad Tablet

## Spec Sheet
| Feature                 | Specification                     |
| :---------------------- | :-------------------------------- |
| CPU                     | Quad Core 2.2GHz                  |
| Chipset                 | NVIDIA® Tegra K1 T124             |
| GPU                     | NVIDIA® GK20A (Kepler)            |
| Memory                  | 2GB RAM                           |
| Shipped Android Version | 4.4.2                             |
| Storage                 | 16/32/64GB                           |
| MicroSD                 | Up to 128GB                       |
| Battery                 | 5197 mAh                          |
| Dimentions              | 221 x 126 x 9.2 mm                |
| Display                 | 1536 x 2048 pixels                |
| Release Date            | July 29, 2014                     |

## Copyright

```
#
# Copyright (C) 2015 The CyanogenMod Project
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#
```

## Build cm-14.1 for mocha (Use the following command in the source code root directory)

m device/xiaomi/mocha/flex-2.5.39 prebuilts/misc/linux-x86/flex/flex-2.5.39

. build/envsetup.sh

bash device/xiaomi/mocha/patches/check.sh

bash device/xiaomi/mocha/patches/install.sh

brunch mocha
