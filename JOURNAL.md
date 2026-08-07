# 8/6/2026
**Total time spent: 4 hours**  [LAPSE](https://lapse.hackclub.com/timelapse/iRWs18JDHpQW)  [LAPSE](https://lapse.hackclub.com/timelapse/W2zX3hPzNi-D)

I forgot to resume the first lapse after pausing it 💔 1:30 just wasted. Anyways I finished power sequencing in the schematic. I used AI to help me choose components and I spent a lot of time cross-checking my intended design with a few other existing laptop coolers. I made sure to organize net labels where it'd be most convenient so I dont make the same mistakes as I did previously in FREEBOARD and my failed flight controller but here's how it looks right now:

<img width="976" height="676" alt="image" src="https://github.com/user-attachments/assets/ab458d90-9292-4d28-be51-9d31d749dda2" />

I just finished the second lapse just now and I have a good idea of everything that I'm going to do. I thought about the form factor and function my cooler would have and I decided to make multiple connectors and terminal updates to accommodate these newfound ideas.

1. I added a 1x2 screw terminal to attach a permanent-ish USB-A male cord so voltage and amperage would be able to transfer smoothly. Because I learned that a female-female connector or male-male connector just isnt as practical and results in a major loss of efficiency. So I for the terminals, 1 will house the +5V wire and the other will house the GND wire. The D+ and D- wires will be cut short and insulated because they aren't really necessary.

2. I decided the entire build will be operable at ~500 mA or less because most USB 2.0 ports can't go too much above this and this is basically the absolute maximum for a lot of low-level NAS and Mini-PC USB-A outputs. This is mainly for accessibility.

3. I decided to have 4-pin connectors for 4-wire fans to make data transfer and monitoring the system to be a lot more easy to the user.

4. And the ISP 2x3 connector is how firmware will be flashed onto the system. So this utility will have a polished software and interact-ability to anyone wanting to use it. Further lengthening the accessibility of it.

Later on I plan to have UI Buttons, an OLED display, RGB, and other miscellaneous items. And I'll be setting the BOM up soon to ensure this runs closer to 400-500 mA so older models can be used with it. Here's how it looks right now:

<img width="984" height="656" alt="image" src="https://github.com/user-attachments/assets/f5bc868b-4560-487e-bd64-160a245eebe7" />

