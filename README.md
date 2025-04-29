# rEFInd-USB Boot Manager
If you have a computer with several SSDs with different operating systems, using your BIOS to switch between them can be very annoying.   
rEFInd solves this issue, but has a sketcy looking website that doesn't have a pre-built full version of the USB version of their product.   
If you try the USB download on rods offical website, it's unable to be customized with grub skins.   

This is the default skin, it's god awful.   
<img src='https://www.rodsbooks.com/refind/refind.png' alt='rEFInd Default Skin'>

Even with terminal commands copying your grub skin into it and somehow managing to compress your files down to it's tiny memory size, it doesn't work.   

There is no documentation on how to create your own USB file structure from scratch, so after some trial and error, I was able to get this fully working with thier desktop EFI.   
The files are very simple, you can easily modify the reskins, settings, and download your own bootx64.efi from the source if your desire.   

This repo is ready to use and also serves as a reference on how to initialize your own boot manager quickly from scratch.   

To use this product:
1. buy a cheap USB that you think will generate the least heat
1. drop the EFI folder inside the usb and delete the readme
1. open your BIOS on boot and select your boot priority to read that USB first

What you'll get is modern icons with this background.   
<img src='https://github.com/dankswoops/rEFInd-USB/blob/main/EFI/BOOT/themes/background.png' alt='I have no clue what this pack is called'>

If you want some edgy anime shit instead you can pick your own skins from here: [Grub Themes](https://www.gnome-look.org/browse?cat=109&ord=latest)

Enjoy   
