# MarcelHackPad
This is the repository for my HackPad Project, which is aptly named "Marcel Hack Pad"
It is a useful hackpad with a rotary encoder, allowing for some extra buttons and functionality when working on my computer.

<img width="889" height="602" alt="Screenshot 2026-06-23 at 11 19 56 AM" src="https://github.com/user-attachments/assets/57b7af1d-de8e-427e-88ed-002a4a95e0db" />

The design is inspired by the Apollo mission control desks at NASA, I have used several images as inspiration and reference for design choices. This includes: 

1. The color palette (cream and turqouise)
1. The keycap colors 
1. The triangular name plate _"Flight Director"_ (inspired by a real photo!)
1. The NASA logo on a panel on the side

<img width="1350" height="1810" alt="Z3C75315-scaled" src="https://github.com/user-attachments/assets/15d373fc-83b8-4bc1-8a7c-6d3b7abe19af" />
(this is one of the inspirations!)

See it the project here On KiCanvas: 

[![Try it](https://img.shields.io/badge/Try%20it-Live%20Demo-blue?style=for-the-badge)](https://kicanvas.org) 

## Features of the Project:

1. **Six** customizable key switches
2. A Rotary Encoder Switch
3. An opening for a USB-C cable to plug into the microcontroller

### How it works:

I used a Matrix style connection for the key switches, this was because I used 6 or more individual keys and had never designed a matrix-system before. Additionally, the Rotary Encoder Switch is plugged into the microcontroller directly, seperately to the matrix. Finally, I used QMK through HomeBrew to create the firmware of the Keys, which was slightly challenging.

