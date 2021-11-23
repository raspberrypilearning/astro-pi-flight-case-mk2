## Print each part

**It is important that you observe the correct safety procedures specified in the data sheet for your specific 3D printer.**

Potential hazards include:

- Hot surfaces and thermoplastics (print head block and lamp)
- Moving parts (printing assembly)

We tried this project on a range of 3D printers including:

 [Cel Robox](https://cel-uk.com/shop/roboxdual/){:target="_blank"}.
 [Lulzbot Taz 6](https://www.lulzbot.com/store/printers/lulzbot-taz-6)
 [Lulzbot Mini](https://www.lulzbot.com/store/printers/lulzbot-mini)

![Photo showing a 3d printed Flight Unit top panel sitting on the bed of a Lulzbot Mini printer ](images/lulbotmini.JPG)

 We mainly used PLA filament in our prints, but we have also printed test cases using ABS.  There are many different 3D printer models so you should make any necessary adaptations to the instructions in order to get the best results from your particular machine.  

All three parts will need to be printed with support scaffolding as there is no completely flat surface with any orientation. For most printers you don't need to add a raft although this may make it much easier/quicker to remove the scaffolding from the heat sink fins on the Flight Unit base. It will, however increase the print time. 

--- task ---

The STL files have been generated from the original CAD designs used to make the Mark II aluminium Flight Unit cases on the International Space Station. 

Depending on your printer and how you use it, you may be able to load these files into a software application that can directly control the hardware and will mange the entire process for you.

![Screenshot from Cel Robox printer showing the imported Flight Unit base on the virtual printer bed](images/automaker.png)

Or if you use a web interface or other client software such as [Octoprint](https://octoprint.org/) to control a [FDM/FFF printer](https://en.wikipedia.org/wiki/Fused_filament_fabrication#Fused_deposition_modeling), you may need to use separate slicing software like [Cura](https://github.com/Ultimaker/Cura) which will convert the model into a series of thin layers to produce a G-code file containing instructions. 

![Screenshot showing an example of the Cura slicing software with a front part standing upright ](images/cura_upright.png)

Make sure you adjust the orientation of the parts in the virtual printer bed so that they are laying flat as shown below. This will minimise scaffolding and rafting.

![Screenshot showing an example of the Cura slicing software with a front part laying flat and face down ](images/cura_top_flat.png)

![Screenshot showing an example of the Cura slicing software with a base part laying flat and face down ](images/cura_base_flat.png)

![Screenshot showing an example of the Cura slicing software with the camera mount part laying flat and face down ](images/cura_camera.png)

This G-code file can then be printed via the client software, which will load the G-code and use it to instruct the printer during the 3D printing process.

![Screenshot showing an example of the Octoprint web-interface which is displaying the imported Flight Unit base in the gcode viewer](images/octoprint.png)

In order to get a nice finish we recommend you print on a high detail setting; this is usually a number specified in [microns](https://en.wikipedia.org/wiki/Micrometre){:target="_blank"} in the 3D printer software. The lower this number is, the more precise the model will be. Please also be aware that precise prints take longer and, for the models you're going to make, each piece can take up to **eight** hours to complete. Make sure you have enough filament.

Having said that, our test cases were also printed using the default "medium quality" settings for the printers and they look fine. 


--- /task ---

