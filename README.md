# a simple & minimalist theme for grub.
## to install:
- clone this repo
- replace images named 'grub-4x3.png' and 'grub-16x9.png' with those of your choice.
  (but name them as mentioned, otherwise will not work)
- add the following line in `/etc/default/grub` :
  ```GRUB_THEME=/boot/grub/themes/mytheme/theme.txt```

  (you might wish to rename the `mythemes` directory to anything you like, but mention the exact path to `theme.txt`)
- then do `sudo update-grub` or `sudo grub-mkconfig -o /boot/grub/grub.cfg`
- now simply reboot and you'll be greeted like this:
  ![grub_simple_1](https://github.com/21-0075-disha/grub-config-files-ds/blob/main/custom-grub-menu.png)
  
  or...
  
  ![grub_simple_2](https://github.com/21-0075-disha/grub-config-files-ds/blob/main/grub_theme_simple.png)

  (background image and Linux distribution may vary depending on your choice)
