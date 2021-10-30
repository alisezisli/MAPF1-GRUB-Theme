# MAPF1-GRUB-Theme

Mercedes-AMG Petronas Formula One Team GRUB theme

## Disclaimer

This project is **not affiliated** with [Mercedes-AMG Petronas Formula One Team (Mercedes-AMG F1)](https://www.mercedesamgf1.com) or [Petroliam Nasional Berhad (Petronas)](https://www.petronas.com) in any way.

As a fan, I've wanted to create a GRUB theme for myself and then share it with the world for free (as in freedom).

## Installation (For Ubuntu 20.04)

1. `git clone https://github.com/alisezisli/MAPF1-GRUB-Theme.git` (or download the project as a zip)
2. `cd MAPF1-GRUB-THEME`
3. `sudo cp -r MAPF1/ /boot/grub/themes/`
4. `sudo vi /etc/default/grub`
5. Change the corresponding lines. If the lines don't exist, add them into file:
    + `GRUB_TIMEOUT_STYLE=menu`
    + `GRUB_THEME="/boot/grub/themes/MAPF1/theme.txt"`
6. `sudo update-grub`

## Installation (For other distros)

It's pretty much the same. But you might have to use some something else instead of `sudo update-grub`, like `sudo grub2-mkconfig -o /boot/grub2/grub.cfg`.

## Notes

This is my first GRUB theme and I'm sure it needs a lot of improvement. I've tested this theme with Ubuntu 20.04 in 1920x1080 resolution. Feel free to create issues and PR's.