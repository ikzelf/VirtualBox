VirtualBox
==========

scripted vm creation and prepare for PXEboot install

usage: mkvm vmname iso_to_create_from pxe_boot_label

the script assumes the iso images are collected in a location: /Users/Shared/software/oracle/OEL or ${ISO_BASE}
the script assumes that the ${HOME}/Library/VirtualBox/TFTP directory contains pxelinux.cfg/default
the script will create a vm with specified name that has 2 network adapters and 3 disks

have fun!
