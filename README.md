The code in this repository is used by an ESP32 to control the chamber heater, which I will eventually post on printables.

This repository is under construction, so take everything here as preliminary.

Bill of materials:

- ESP32 Supermini Dev Board (https://aliexpress.com/item/1005010580012002.html)
- Short USB-C cable to power the ESP32 from the xBuddy board (https://aliexpress.com/item/1005011775608905.html)
- 2 x LR7843 Optocoupled MOSFET modules (https://aliexpress.com/item/1005006152963254.html)
- If you also have Buddy3D Camera: USB-C splitter (https://aliexpress.com/item/1005007045809081.html)
- 300W 24V DC power supply (https://aliexpress.com/item/1005008936305760.html)
- Bimetalic thermal switch, 16A, Normally closed, 75C (https://aliexpress.com/item/1005005556051317.html)
- 200W 24V DC PTC heater (https://aliexpress.com/item/1005004218891703.html)
- At least 1 meter of large-gauge wire suitable for up to 16A @ 24V. I suggest 2 meters of 14 AWG wire from here: (https://aliexpress.com/item/1005001876813940.html)
- At least 3 NTC 10K thermistors with 1m wire (https://aliexpress.com/item/1005009681281937.html)
- Backup thermal fuse, 75C and 15A, (https://aliexpress.com/item/1005009345938308.html)
- Screw block terminals. These I bought in the local hardware store, I but I believe they match the 12-piece 20A strip here: (https://aliexpress.com/item/1005006091337387.html). Unfortunately, I'm not apply to the confirm the size match right now.
- 3 x 10k resistors (https://aliexpress.com/item/1005007345052730.html)
- Small perfboard / protoboard to mount ESP32, thermistors, and resistors. I used the following, but you might have to source something similar yourself (https://futuranet.it/prodotto/protoboard-160-contatti-a-saldare-con-linee-di-alimentazione/)
- An AC power cable to power the PSU (you will have to cut off the head and then screw the wires directly into the PSU terminals). Example: (https://aliexpress.com/item/1005008168727108.html)
- Assorted M3 screws for assembly
- Jumper wires and solder kit
- At least 6 2.54mm male pins (https://aliexpress.com/item/1005007385580884.html)
