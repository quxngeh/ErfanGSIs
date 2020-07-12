# ErfanGSIs Tool - Hitsuki Edition

This repository is a fork of a fork of the ErfanGSIs Tool for private use, you are free to create your fork and make your changes (at least give the credits to all contributors of the ErfanGSIs Tool project).

See also the [ErfanGSIs-Builder](https://github.com/HitaloSama/ErfanGSIs-Builder) repository where you can see GSIs being made with GitHub Actions.

## How to use

### Download tools

```
git clone --recurse-submodules https://github.com/HitaloSama/ErfanGSIs.git
cd ErfanGSIs
```

### For setting up requirements
    bash setup.sh

### Generating GSI from stock firmware URL

Example: for making OxygenOS of OnePlus 7 pro firmware, you can use this command:
```
sudo ./url2GSI.sh https://oxygenos.oneplus.net/OnePlus7ProOxygen_21.O.07_OTA_007_all_1905120542_fc480574576b4843.zip OxygenOS
```
check url2GSI.sh for more info
