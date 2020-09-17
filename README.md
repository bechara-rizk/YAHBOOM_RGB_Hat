# YAHBOOM_RGB_Hat

I've created this file to modify the yahboom rgb hat.

I added a way to turn off the rgb automatically at a defined time and also made the fan change speed with each temp.

It uses the same code base I just made the modifications above.

If you want to use my code clone this repository to your raspberry pi, move the entire folder to /home/pi/.config then move the start.desktop file to a folder called autostart (its path should be /home/pi/.config/autostart) and finally reboot your pi.

You can modify the fan speeds for every temp you want and also the RGB ON time in the while loop at the end of the code.
