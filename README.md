# Palmy
rm -rf rtl8812au/
```
git clone https://github.com/gnab/rtl8812au.git

sudo cp -r rtl8812au  /usr/src/rtl8812au-4.2.2

sudo dkms add -m rtl8812au -v 4.2.2

sudo dkms build -m rtl8812au -v 4.2.2

sudo dkms install -m rtl8812au -v 4.2.2
```
dconf-editor
This will makes windows appeared at center `/org/gnome/mutter/center-new-windows`

# Redshift
```
redshift -l 13.1:100.1 -t 5800:4500 -m randr -v
```
