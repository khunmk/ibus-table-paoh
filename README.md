# ibus-table-paoh
PaOah Keyboard - For Ubuntu

# Requirements
ibus-table

# Installation
sudo ibus-table-createdb -n /usr/share/ibus-table/tables/paoh.db -s paoh.txt
sudo cp paoh.png /usr/share/ibus-table/icons/paoh.png
ibus-daemon -rdx

