## Test the buttons

+ Once you have assembled the Astro Pi, start it up with a monitor, keyboard, and mouse connected.

If you have the ESA-branded Astro Pi kit, the rainbow pattern on the LED matrix should disappear a few seconds after you turn the Astro Pi on, and the push-buttons should now type letters. You can test this in the terminal by running the test program at the bottom of this section.

If you don't have the ESA-branded Astro Pi kit, the rainbow pattern on the LED matrix will remain visible after you turn the Astro Pi on, and the buttons will not work yet.

You will need to download some files and change a few configuration settings, so make sure your Astro Pi is online.

+ Firstly, download the Device Tree overlay that maps the push-buttons to the corresponding keyboard keys. To do this, open a terminal window and enter these commands:

```bash
cd /boot/overlays
sudo wget https://github.com/raspberrypilearning/astro-pi-flight-case/raw/master/data/dtb/astropi-keys.dtbo --no-check-certificate
```

+ Type `ls` and check that the file `astropi-keys.dtbo` is now showing in the list of files.

+ Next, configure `config.txt` to load this overlay. Open the text file by typing:

```bash
sudo nano /boot/config.txt
```

+ Go to the bottom of the file and enter the two lines below:

```bash
dtoverlay=rpi-sense
dtoverlay=astropi-keys
```

+ Press `Ctrl` + `O`, and then `Enter` to save, followed by `Ctrl` + `X` to quit.

+ Now reboot the Astro Pi.

```bash
sudo reboot
```

Now let's download and run a Python test program to check everything is working. The test code uses [Pygame](http://pygame.org/wiki/tutorials){:target="_blank"}, which means you need to do this test on a directly connected monitor. It will not work via remote access.

+ Open a terminal window and enter these commands:

```bash
cd ~
wget https://github.com/raspberrypilearning/astro-pi-flight-case/raw/master/data/test_code/pygame_test.py --no-check-certificate
chmod +x pygame_test.py
./pygame_test.py
```

+ Wiggle the joystick and press all push-buttons. If everything is working, the joystick will give a direction indication, and the buttons will show the corresponding letter on the LED matrix. Press `Escape` to exit.
