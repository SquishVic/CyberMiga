# CyberMiga
Laptop meets Amiga, Meets Commodore.
I'm documenting how I've turned an old gaming laptop collecting dust in my closet into a Cyberdeck. I needed a computer that I could take with me to college, so this turned out to be a wonderful way to recycle something that would have gone to waste otherwise. Be environmentally considerate!

—

Where I'm at:

Fully Functional

—

Most Current Update:

• Case re-re-design to look more like the PS Vita. Rounded edges and a curved bottom shell for better ergonomics.

![name](https://github.com/SquishVic/PCVita/blob/main/Screen%20Shot%202022-09-10%20at%201.00.36%20PM.png?raw=true)

—

Sequential Updates:

• (Original design reflected that of the Steam Deck or a large Playstation Vita)

• Harvesting the vitals! Removed all components from laptop case.

• Once everything was out, I disconnected daughterboards, hard drive, battery, and ribbon cables from motherboard.

![name](https://raw.githubusercontent.com/SquishVic/PCVita/main/mobo%20w%3Ao%20daughterboards.jpg)

• Desoldered ribbon cable connector on the motherboard which lead to USB and Power Button Daughterboard.

• Soldered magnet wire to (+) and (-) terminals of on/off switch.

![name](https://raw.githubusercontent.com/SquishVic/PCVita/main/magnetwireattached.jpg)

• Added NVMe M.2 SSD to replace bulky hard drive

• Removed Heatpipes from heatsink shrowd. They extended the form factor of the motherboard too much for my liking. Using thermally conductive adhesive, I added copper fin heatsinks(rated at 401 W) to the shrowd.

• Tested display output and installed Windows 11 + HP drivers needed to improve preformance.

• 3D modeled motherboard into Fusion 360.

![name](https://github.com/SquishVic/PCVita/blob/main/motherboard.png?raw=true)

• 3D modeled exhaust channel for the new heatsinks.

• Edited exhaust model to include more effective turning vanes to minimise heat that cannot escape.

• 3D modeled portable monitor into project

• 3D modeled laptop li-po battery into project

• Designed wedge 2DS-like case and moved components around to fit.

• Re-designed layout to fit Wii U Gamepad model from GrabCAD

• Case re-re-design to look more like the PS Vita. Rounded edges and a curved bottom shell for better ergonomics.

![name](https://github.com/SquishVic/PCVita/blob/main/Screen%20Shot%202022-09-10%20at%201.00.36%20PM.png?raw=true)
![name](https://github.com/SquishVic/PCVita/blob/main/Screen%20Shot%202022-09-10%20at%2012.15.30%20PM.png?raw=true)

• Figured out that a single USB port would not be enough to power the external monitor, USB wifi/bt adapter, and the microcontroller for the gamepad simultaneously. This meant that I needed to receive power from a different source. My plan is to use the 12v power output for the monitor backlight and use a buck converter to step down 12v to 5v. This way, the low-power components like the USB wifi/bt adapter and the microcontroller can share the USB port via a USB hub.

• Major design pivot: After considering the production of heat and the size of the handheld, I decided to pivot and make a Cyberdeck instead. This loops back to the original purpose of this project, to take my overheating laptop and make it fully functional for editing, 3D modeling, and gaming.

• My reimagining of the design followed many of the principles that I outlined before, however with a greater attention to the amount of airflow. I wanted to make sure all the components had adequate breathing room for optimal performance.

• The first design for the case followed an angular wedge design. However, after making a miniature test print I thought that the design was a little too angular. After doing some research online, I decided that I wanted to mimic the triangular side profile of the Amiga and the Commodore. 

![name](https://github.com/SquishVic/PCVita/blob/main/Screenshot%202023-03-23%20at%201.08.40%20PM.png)

• Added fan cutouts

• Changed fan cutouts to have a slant, they looked more stylish and fit the aesthetic I was going for.

• 
