## Soldering and installing the push-buttons

We have created two different front panel options to accomodate two popular sizes of buttons. Most of the photos show the shiny APEM SPDT Momentary Push Buttons as used on the ISS Flight Units. However you can use any similar button as long as it has the correct thread for the version of the flight case that you have printed. You may need to adapt the tasks in this section to refelct the buttons you have chosen.


## Solder the button wires

Firstly, you need to prepare the button wires to be able to attach them to the buttons. In the real flight unit, we soldered the button wires on to make them more reliable. This is the most straightforard method, but you could also use connectors if you desire a less-permenant solution.    The colour of the wires is not important, as they are all exactly the same inside.

![Photo showing the componets used in this step. Wires, buttons and heatshrink tubing](images/button_kit.JPG)

--- task ---

Take a coloured wire and remove the black plastic sheath from **one** end. If your wire has a one pointy (male) end, and one end with a hole (female), you should remove the male end connector. You can do this by pulling it off with pliers, or by cutting the wire just below the connector. Strip back approximately 1 cm of the insulating sheath from your wire.  Repeat this for 3 additional wires. 

![Photo showing a jumper wire with the male connector removed](images/button_wire_strip.JPG)

--- /task ---

--- task ---

The APEM buttons have 3 terminals. You're going to only connect wires to 2 of these, but they need to be the correct ones. The swtich between the terminals labelled 1 and 3 is closed when the button is pressed, and these are the terminals to which you should connect your wires.

![Photo showing an APEM button with terminals 1 and 3 indicated by a red arrows](images/button_labels.JPG)

--- /task ---

--- task ---

Twist the exposed copper wires so that all the individual strands are tightly entwined. Then thread the end through a small (1cm long) piece of heatshrink tubing. 

![Photo showing a partially stripped wire with with a 1cm piece of red heatshrink tubing slipped over it ](images/button_wire_hs_slip.JPG)

--- /task ---

--- task ---

Secure a button using a vice, a set of "helping hands" (not attached to a human) or just a blob of sticky tac, to hold it steady while you solder.

Thread a wire through one of the correct terminals (see above) and loop it over as shown below. Carefully [solder](https://www.raspberrypi.com/news/getting-started-soldering/) the wire to the terminal. 

Before the solder cools and hardens, pull the wire gently upwards so that it is pointing straight up. This will make is much eaisre to slide the heatshrink tubing down.

![Photo showing a wire soldered to one terminal of a button ](images/buttons_solder2.JPG)

--- /task ---

--- task ---

Slide the heatshrink tuing down over the terminal. Makse sure any loose strands of wire are tucked up under sleeve to prevent accidental shorting of the buttons. 


![Photo showing a a soldered wire with the heatshrink tubing pulled down over the button terminal ](images/button_wire_hs_over.JPG)

--- /task ---

--- task ---

Now repeat these steps for the second button


![Photo showing the second button wire soldered to the second terminal ](images/button_solder_2nd_wire.JPG)

--- /task ---

--- task ---

Use a heatgun to soften and shrink the heatshrink tubing. 


![Photo showing both wires soldered and the termninal and exposed copper sheathed in heatshrink tubing  ](images/buttons_2_wires_hs.JPG)

--- /task ---

If you are using different buttons, the process should be the same, although you will possibly have only two terminals on the button. 

![Photo showing a smaller button with a wires soldered to its terminal ](images/buttons_small_solder.JPG)

Use heatshrink tubing to protect the contacts in the same way.

![Photo showing a small button with one wire soldered and the termninal and exposed copper sheathed in heatshrink tubing  ](images/buttons_small_1_wire_hs.JPG)

+ Take a button, then unscrew and remove the nut. Sometimes the nut will get stuck on the button cap, but it should come off if you wiggle it.

![Remove nut from button](images/buttons1.png)

+ Keeping the washer on the thread, insert the button from the underside of the lid.

+ Then on the top side of the lid, put the nut back on and tighten it with your fingers. Check that the connectors are aligned horizontally on the underside before tightening fully.

![Insert button and screw on nut](images/buttons2.png)

+ Do the same for the remaining buttons; when you are done it should look like this:

![Finished front and back](images/buttons3.png)