# PCVita
Laptop meets PS Vita. 
I'm documenting how I've turned an old gaming laptop collecting dust in my closet into a DIY Steam Deck for on-the-go gaming. To be clear, this is not cheaper than a steam deck by any meaningful amount, but this was a wonderful way to recycle something that would have gone to waste otherwise. Be enviromentally considerate!

—

Where I'm at:

Design phase! 🤍

—

Most Current Update:

• Case re-re-design to look more like the PS Vita. Rounded edges and a curved bottom shell for better ergonomics.

![name](https://github.com/SquishVic/PCVita/blob/main/Screen%20Shot%202022-09-10%20at%201.00.36%20PM.png?raw=true)

—

Sequential Updates:

• Harvesting the vitals! Removed all components from laptop case.

• Once everything was out, I disconnected daughterboards, hard drive, battery, and ribbon cables from motherboard.

• Desoldered ribbon cable connector on the motherboard which lead to USB and Power Button Daughterboard.

• Soldered magnet wire to (+) and (-) terminals of on/off switch.

![name](https://raw.githubusercontent.com/SquishVic/PCVita/main/20220817_183913.jpg)
![name](https://raw.githubusercontent.com/SquishVic/PCVita/main/20220817_183937.jpg)

• Added NVMe M.2 SSD to replace bulky hard drive

• Removed Heatpipes from heatsink shrowd. They extended the form factor of the motherboard too much for my liking. Using thermally conductive adhesive, I added copper fin heatsinks(rated at 401 W) to the shrowd.

• Tested display output and installed Windows 11 + HP drivers needed to improve preformance.

![name](https://raw.githubusercontent.com/SquishVic/PCVita/main/runningwin11.jpg)
![name](https://github.com/SquishVic/PCVita/blob/main/motherboard.png?raw=true)

• 3D modeled motherboard into Fusion 360.

• 3D modeled exhaust channel for the new heatsinks.

• Edited exhaust model to include more effective turning vanes to minimise heat that cannot escape.

• 3D modeled portable monitor into project

• 3D modeled laptop li-po battery into project

• Designed wedge 2DS-like case and moved components around to fit.

• Re-designed layout to fit Wii U Gamepad model from GrabCAD

• Case re-re-design to look more like the PS Vita. Rounded edges and a curved bottom shell for better ergonomics.

![name](https://github.com/SquishVic/PCVita/blob/main/Screen%20Shot%202022-09-10%20at%201.00.36%20PM.png?raw=true)
![name](https://github.com/SquishVic/PCVita/blob/main/Screen%20Shot%202022-09-10%20at%2012.15.30%20PM.png?raw=true)

• Figured out that the single USB port would not be enough to power the external monitor, USB wifi/bt adapter, and the microcontroller for the gamepad. This meant that I needed to receive power from a different source. My plan is to use the power output from the monitor backlight and use a buck converter to step the 12v down to the 5v which the external monitor requires. This way, the low power components like the USB wifi/bt adapter and the microcontroller can utilize the USB port on the mobo.
