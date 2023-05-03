# Mainframe
 
Mainframe is a monospaced pixel font.
It prioritizes clarity and readability, and it pays homage to two classic typefaces:
- Fixedsys, the oldest typeface in Microsoft Windows.
- The default character set used in Commodore 64.

It was designed to be used in the on-screen display of first-person view drones running the Betaflight open-source flight controller firmware.

## Features

- Easily distinguishable characters (for example: 0 vs O, 8 vs B)
- A battery icon with easily discernible levels (like Digital)
- Less icons, more explicit text labels for understandability (for example: GPS satellites, flight distance, black box)
- A very light crosshair design that is noticeable, but does not block too much view
- Consistent spacing and outline rules for a harmonious look

## Example

![A mockup of a Betaflight OSD with tons of elements, showcasing the Mainframe font](https://github.com/dukeflipchart/mainframe-font/blob/main/mainframe-kitchen-sink-preview.png?raw=true)

## Installation

You can use Mainframe like any other custom font in Betaflight:
- Download [mainframe.mcm](https://raw.githubusercontent.com/dukeflipchart/mainframe-font/main/mainframe.mcm) from this repository and save it on your computer.
- Open Betaflight Configurator and connect to your drone.
- Go to the OSD tab and click the "Font Manager" button at the bottom right.
- Click "Open font file", and browse for the downloaded "mainframe.mcm".
- Click "Upload font" and wait for the upload to finish. Your drone will disconnect and reconnect.
- You're done! Note that you will not see the Mainframe font in Betaflight Configurator. Test the OSD with your drone and goggles instead.
