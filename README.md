
# MarcelHackPad
This is the repository for my HackPad Project, which is aptly named "Marcel Hack Pad"
It is a useful hackpad with a rotary encoder, allowing for some extra buttons and functionality when working on my computer.

<img width="889" height="602" alt="Screenshot 2026-06-23 at 11 19 56 AM" src="https://github.com/user-attachments/assets/57b7af1d-de8e-427e-88ed-002a4a95e0db" />

<img width="689" height="692" alt="Screenshot 2026-06-23 at 12 59 50 PM" src="https://github.com/user-attachments/assets/87543d9a-21a1-4913-be98-2b63e9e2f7c7" />

The design is inspired by the Apollo mission control desks at NASA, I have used several images as inspiration and reference for design choices. This includes: 

1. The color palette (cream and turqouise)
1. The keycap colors 
1. The triangular name plate _"Flight Director"_ (inspired by a real photo!)
1. The NASA logo on a panel on the side

<img width="1350" height="1810" alt="Z3C75315-scaled" src="https://github.com/user-attachments/assets/15d373fc-83b8-4bc1-8a7c-6d3b7abe19af" />
(this is one of the inspirations!)

See it the project here On KiCanvas: 

[![Try it](https://img.shields.io/badge/Try%20it-Live%20Demo-blue?style=for-the-badge)]([https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2F12-mrcel%2FMarcelHackPad)

## Features of the Project:

1. **Six** customizable key switches
2. A Rotary Encoder Switch
3. An opening for a USB-C cable to plug into the microcontroller

### How it works:

I used a Matrix style connection for the key switches, this was because I used 6 or more individual keys and had never designed a matrix-system before. Additionally, the Rotary Encoder Switch is plugged into the microcontroller directly, seperately to the matrix. Next, for the position of the keys and the board, I used the guide provided by HackClub on SandWhich mount keyboards. Finally, I used QMK through HomeBrew to create the firmware of the Keys, which was slightly challenging.

### Acknowledgements:

I used the 3D models provided from these links:

[Key Switches (Cherry MX)](https://github.com/hineybush/CherryMX)

[Rotary Encoder EC11](https://grabcad.com/library/rotary-encoder-17)

[General Resources and Links](https://hackpad.hackclub.com/resources)


Also, I used the HackPad manual:

[HackPad Manual Link](https://hackpad.hackclub.com/)

Finally, I must give credit to two Hackers who provided me with some inspiration and _very_ useful github repos!

[BajajPad by MrKillerShaunBa](https://github.com/MrKillerShaunBa/BajajPad/tree/main)

[HackPad by Ayushj-18](https://github.com/ayushj-18/hackpad/tree/main)
