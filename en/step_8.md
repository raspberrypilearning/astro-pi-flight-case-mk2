## Connect internal wiring to the Raspberry Pi

+ Fit the middle section of the Astro Pi case onto the base. You should do this now, because the GPIO wires will prevent it from being fitted later.

Now you are going to wire the buttons to the free GPIO pins at the bottom of the header.

+ Turn the Astro Pi case so that the Ethernet and USB ports are at the bottom, and the GPIO pins are on the right of the Raspberry Pi.

![GPIO diagram](images/buttons_GPIO.png)

The pins marked in red are where you will wire up the buttons, with the bottom of the diagram being the pins closest to the USB ports.

+ Look at the **underside** of the lid, with the buttons on the left and the display hole on the right. Connect the coloured wire from each button to the corresponding pin below:

- Top four buttons
    - Top: **GPIO 26**
    - Bottom: **GPIO 13**
    - Left: **GPIO 19**
    - Right: **GPIO 20**
- Bottom pair of buttons
    - Left: **GPIO 21**
    - Right: **GPIO 16**

+ Finally, connect the ground wire to either pin 34 or 39 (labelled **Ground** on the GPIO diagram).

The lid will now be a bit awkward until we finish, but try to position it gently so it is not in the way.

The picture below shows one of the flight units that went into space. On the right, you can see the base of the RTC board with the connector pins for the buttons. If you look at the button contacts on the left, you'll see we used only one black ground wire going from button to button.

![Flight unit wiring](images/flight_unit_wiring.jpg)

Then, take a 10mm M2.5 stand-off and screw it into the hole of the 11mm stand-off, to make a single tall header as shown below. Do the same for the remaining three stand-offs.

![Add standoffs](images/add-header-standoffs.png)

## Install the Sense HAT

+ Remove the GPIO connector that comes with the Sense HAT. You can wiggle it from side to side, and it will come off without too much force.

+ The Sense HAT can then be attached onto the extended header. Note that the header pins should not protrude through the top of the Sense HAT. If they do, then the height is not correct.

![Remove the header from the Sense HAT](images/remove-sense-hat-header.png)

+ Finally, use the M2.5 cross-head screws to secure the Sense HAT to the stand-offs below.

![All buttons connected](images/buttons-connected.png)
