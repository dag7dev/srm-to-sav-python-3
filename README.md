# srm-to-sav
Convert RetroArch SRM files to raw GBA SAV files and viceversa

# Requirements
Original work was for Python2, this repo now supports Python3.

Tested on Python 3.12+


# Usage
```
srm-to-sav.py -i <input.sav> -o <output.srm> [--byteswap]
sav-to-srm.py -i <input.sav> -o <output.srm> [--byteswap]
```

# Byte Swapping
Some games, such as The Minish Cap write their save data backwards in RetroArch.

Use the `--byteswap` argument to write the data in the correct order.
