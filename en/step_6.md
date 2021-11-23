## Install the Raspberry Pi 4 

--- task ---

Firstly, ensure there's no residual scaffolding material around the SD card slot or LED holes that might prevent the Raspberry Pi from lining up with the mounting pillars.

--- /task ---

--- task ---

Once you're happy, line the Raspberry Pi up and do a fit check.  Don't insert the camera ribbon cable just yet.

--- /task ---


--- task ---

Next, screw the M2.5 11mm stand-offs into each corner of the Pi. With some light finger pressure they will cut their own thread in the support pillar pilot holes.


![Photo showing the Raspberry Pi in the bottom case part, with a spacer screwed in to the top left corner mounting hole](images/pi_spacer_corner.jpg)

After a few turns you'll need to use a small pair of pliers or a nut-driver to continue turning them. Try to get the stand-offs to go into the support pillars straight down, and not at a slight angle, because that can lead to alignment issues with the Sense HAT later on. Be careful while you do this and, again, stop turning as soon as the stand-off touches the Raspberry Pi to avoid splitting the pillars horizontally along the grain of the print.

![Photo showing a nut driver being used to screw a spacer into place through the mouting hole in the Raspberry Pi PCB](images/pi_spacer_driver.jpg)

If you are having trouble screwing in the stand-offs, screw one of the silver M2.5 cross-head screws into the stand-off, then use the screw head to screw the stand-off into the case. Once the stand-off is in place, don't forget to remove the screw.

--- /task ---

![Photo showing the Raspberry Pi in the bottom case part, with a spacer screwed into each corner mounting hole](images/pi_spacer_corner.jpg)


--- task ---

You can now insert the camera ribbon cable into the CSI port of the Raspberry Pi. 

![Photo showing the Raspberry Pi in the bottom case part, with the camera cable inserted](images/camera_cable_pi.jpg)



--- /task ---

### Install the tall header

--- task ---

Bend a pin which is the second from the end of the 23-pin tall header out by 90 degrees as shown below. This will enable you to connect the PIR to 5v. 

--- /task ---

--- task ---

Add the extended 23-pin header to the Raspberry Pi GPIO pins, at the end away from the USB ports. The bent pin should be at the end furthest away from the USB ports, facing outwards into the case. 

--- /task ---

### Install stand-offs for the Sense HAT

The Astro Pi Flight Units onboard the ISS have another custom circuit board in between the Raspberry Pi and Sense HAT which holds a real-time clock with backup battery. This mezzanine board also has some pins to allow easy connection to the push-buttons and the PIR. Unfortunately, the board is not mass-produced and available to the public.

![3d cutaway diagram of a Flight Unit, showing the mezzanine board](images/3d_cutaway_mezz.png)


Then, take an 8mm M2.5 stand-off and put a hex nut onto its thread before screwing it into the hole of the 11mm stand-off, as shown below. Do the same for the remaining three stand-offs.

![Add standoffs](images/add-header-standoffs.png)