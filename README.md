# Halflife: Starbie

## Why Starbie?
As an aspiring engineer, I have had no experience with PCB design, so I chose to follow the provided guide for my first taste of PCB design. If I'm being honest, the Starbie itself doesn't hold much meaning to me, but what I takeaway from it does. Electronics have always fascinated me, and PCBs are such an integral part of that wonder. Learning PCB design opens up a whole different aspect of electronics that I previously hadn't seen.

<img width="1037" height="691" alt="Screenshot 2026-10-06 213134" src="https://github.com/user-attachments/assets/4b46310c-a368-45bb-8e8a-564744696dd7" />
## PCB Design
Frankly, I followed the guide, but I did have some trouble (as documented in my journal) with certain parts. To design it, I used KiCAD, which is something I hadn't used before. First you have to make a schematic of your PCB, which shows what is routed to what. Then, using that schematic, KiCAD helps you design the PCB itself. Something that I struggled with was making the ground plane, but that was just because of a silly mistake that I made.
<img width="730" height="684" alt="Screenshot 2026-10-06 222959" src="https://github.com/user-attachments/assets/bb1e221f-19f0-4aac-a5b8-7ae91db876fa" />

## How to Build Starbie
*I'm going to assume this means the build process after designing it.*
### Assembly
Since the Starbie uses mainly SMD components, assembly should be pretty simple. With a soldering iron, solder each component into places on the PCB. Use flux if necessary to make your soldering easier. If all goes well, you should be able to complete assembly of the PCB in a short time.

### Flashing
Flashing should be pretty simple. While holding down the "boot" button, plug the ESP32 into your computer. You can then select the ESP32 in Arduino IDE, make sure you have your code loaded, and then press upload to flash the ESP32. 

## BOM
## Bill of Materials (BOM)

| Item | Qty | Supplier | Cost/Item | Total Cost | Link |
|---|---:|---|---:|---:|---|
| Display | 1 | Amazon | $6.99 | $6.99 | [Amazon](https://www.amazon.com/UCTRONICS-SSD1306-Self-Luminous-Display-Raspberry/dp/B072Q2X2LL?sr=8-8) |
| 10k Resistor | 1 | Amazon | $3.99 | $3.99 | [Amazon](https://www.amazon.com/California-JOS-Carbon-Resistor-Tolerance/dp/B0BR68QQPF?sr=8-3) |
| DHT11 | 1 | Amazon | $5.99 | $5.99 | [Amazon](https://www.amazon.com/gp/product/B07WT2HJ4F?smid=A2Z10KY0342329&psc=1) |
| XIAO-ESP32-C3-SMD | 1 | Amazon | $9.90 | $9.90 | [Amazon](https://www.amazon.com/gp/product/B0B94JZ2YF?smid=A1YP59NGBNBZUR) |
| PCB | 1 | JLCPCB | $4.00 | $4.00 | [JLCPCB](https://cart.jlcpcb.com/quote?stencilLayer=2&stencilWidth=100&stencilLength=100&stencilCounts=5&plateType=1&spm=Jlcpcb.Homepage.1010) |
| Estimated Shipping | 1 | — | $10.97 | $10.97 | — |
| **Grand Total** | | | | **$41.84** | |
