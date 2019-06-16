# workstation
Auto-installer and declarative configuration for my personal computers

## How to create and boot an install disk
1. Create a standard Fedora Silverblue 30 install disk using the Fedora Media Writer or downloading the .iso manually
2. Mount the fat32 EFI partition
3. Copy the EFI directory onto the partition, overwriting the grub configuration
4. Boot the "partition 1" boot option in the UEFI, which should bring up a GRUB menu with the modified configuration (avoiding the GRUB config on the iso9660 partition)
5. Start an install without verifying the install disk (verification fails after modifying GRUB)
