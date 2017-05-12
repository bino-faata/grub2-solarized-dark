# grub2-solarized-dark
Grub2 theme based in StylishDark

 ![My image](http://orig12.deviantart.net/d0fa/f/2017/132/8/a/solarized_dark_by_glacto-db8xndz.png)

 How To:
======

 1. Unzip
 2. Go to unzipped folder
 3. in terminal run the command **`sudo ./install.sh`**
 4. Follow the messages
 5. Reboot && Enjoy :)

or u can do this manually:
----

 1. Unzip and copy theme folder in **`/boot/grub2/themes/`**
 2. add (or edit existing lines) this to **`/etc/default/grub`**:

 `GRUB_THEME=/boot/grub2/themes/grub2-solarized-dark/theme.txt`

 3. update your grub:
   1. for Fedora `grub2-mkconfig -o /boot/grub2/grub.cfg`
UEFI
`grub2-mkconfig -o /boot/efi/EFI/fedora/grub.cfg`

   2. for Debian `update-grub`
4. Done!