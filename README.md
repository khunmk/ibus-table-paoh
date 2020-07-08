# ibus-table-paoh

PaOah Keyboard - For Ubuntu

## Requirements

ibus-table
```
sudo apt install ibus-clutter ibus-gtk ibus-gtk3
```

## Installation
```
sudo ibus-table-createdb -n /usr/share/ibus-table/tables/paoh.db -s paoh.txt
sudo cp paoh.png /usr/share/ibus-table/icons/paoh.png
ibus-daemon -rdx
```

**Note and credit**
This keyboard is modified version of <mm-smart.txt> for my personal use.
I am very thank to original creator of Naing Ye Minn <naingyeminn@gmail.com>.
Please Go check mm-kb-master on their github repo on https://github.com/naingyeminn/mm-kb.
