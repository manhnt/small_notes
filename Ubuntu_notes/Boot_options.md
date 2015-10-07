Showing GRUB mene at boot by default
====================================
If Ubuntu is the only OS on the machine, the GRUB boot menu may not show at
boot time. But in some cases, it is desirable to have the menu displayed so
you could add some kernel boot configurations, or do something to particular
requirements. So in order to make the GRUB menu be visible by default, make
edit to the file /etc/default/grub to comment out the line which has
GRUB_HIDDEN_TIMEOUT=0, then run update-grub to apply changes.

Boot into virtual console mode by default
=========================================
(Get from [ubuntuhandbook][1])

To boot your Ubuntu system directly into command line (text mode or console),
do the following changes:
- Comment the line GRUB_CMDLINE_LINUX_DEFAULT=”quiet splash”, by adding # at
the beginning, which will disable the Ubuntu purple screen.
- Change GRUB_CMDLINE_LINUX=”" to GRUB_CMDLINE_LINUX=”text”, this makes Ubuntu
boot directly into Text Mode.
- Uncomment this line #GRUB_TERMINAL=console, by removing the # at the
beginning, this makes Grub Menu into real black & white Text Mode (without
background image).

[1]:http://ubuntuhandbook.org/index.php/2014/01/boot-into-text-console-ubuntu-linux-14-04/

