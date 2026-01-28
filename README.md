# Media Center

## Summary
The purpose of this project is to create an interactive media center using the Keil MCB1700 Evaluation Board (ARM Cortex-M3) and the µVision software. This media center features:
1. A photo gallery that displays 4 of my favourite hip-hop albums/mixtapes
2. A Spotify-themed MP3 player that streams audio from the PC via USB
3. A fan-made Mario Kart game

These features can all be located via the main menu. The media center's interface is implemented on the LCD and users can navigate through the system using the MCB1700’s joystick. Creating this media center requires converting the BMP files into C-source arrays to display the images, implementing a USB-based MP3 player with volume control by using the board’s potentiometer, and creating a game environment that uses the LCD and joystick.

## Features
### 1. Photo Gallery
- Displays 4 hip-hop album/mixtape covers (converting BMP files into C-source arrays)
    - Photo #1: good kid, m.A.A.d city
    - Photo #2: 1999
    - Photo #3: Madvillainy 
    - Photo #4: The Marshall Mathers LP
- Joystick navigation with highlighted selection
    - Up/Down: Toggle through options
    - Push: Select the highlighted option
    - Left: Go back

<p align="center">
  <img src="Results/Photo Gallery.jpeg" width="350">
</p>

<p align="center">
  <img src="Results/Photo 1.jpeg" width="350">
</p>

<p align="center">
  <img src="Results/Photo 2.jpeg" width="350">
</p>

<p align="center">
  <img src="Results/Photo 3.jpeg" width="350">
</p>

<p align="center">
  <img src="Results/Photo 4.jpeg" width="350">
</p>

### 2. MP3 Player
- Streams PC audio over USB to the board
- Disconnects audio when exiting
- Potentiometer volume control
    - Clockwise: Raise volume
    - Counter-clockwise: Lower volume

<p align="center">
  <img src="Results/MP3 Player.jpeg" width="350">
</p>

<!--
## Tools
- GIMP-->