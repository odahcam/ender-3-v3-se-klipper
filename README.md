# Ender 3 v3 SE Klipper

This is my repository of configurations that work with my Ender 3D printer. Mine is the first version motherboard, so keep that in mind.

I learnt how to install Klipper by following this:
- How-to install article: https://athemis.me/projects/klipper_guide 
- YouTube video for custom Klipper builds, necessary for things like Auto Z Offset: https://youtu.be/2bOx0buOJaM?si=oqvXlv7VKYWRy902

I'm new to Klipper but I've already made a few improvements to my configuration and I will keep updating this in the future so I can come back here in case anything happens with my configuration or anyone else wants to leverage these files (at your own responsibility and risk) for their printer.

I've invested many hours into making the printer work and I will probably invest many more with the upgrades I have planned, so I hope this becomes a place where I can always rely on a working config in case I need one.

## Mods

3D models for the mods I add to my print will also be available here as well as links to buy parts and also instructions when plausible.

## Extra Tips

Based on my experience with Ender 3 in Marlin and a Bambu Lab A1, I have some idea of what makes a good difference and what's not.

- **Auto Z Offset**: it is a must, you have to setup this if you want to use the full potential of the Ender 3 v3. Otherwise you're just loosing an awesome feature and waisting your time with confusing manual probe calibration using paper.
- **Original LCD screen with Klipper**: I think this is useless and I intend to use Creality's cable for the Nebula display to connect my Raspberry and do the infamous LCD delete.
- **Extra sensosrs**: XYZ sensor for input shaping and Filament runout sensor are a really worth upgrade.
- **Bed mashing/levelling**: Ender 3's have a scewed X axis and you shall be able to fix it searching online. It will not prevent you from printing though, and is my lowest priority in the list of items to fix. I rather prefer upgrading the axis with rails first.

## Firmware builds

I'm adding `.bin` files that works in my printer to the repo so I don't have to build them again. They can be helpful in case it is not possible to build them in the future anymore.

## Roadmap

- [X] Add webcam (Logitech C170).
- [X] Side mounted spool (for stability) with bowden tubes and guides.
- [X] Printer enclosure (using Sunlu).
- [X] Install Klipper.
- [ ] Add XYZ sensor.
- [ ] Add Filament runout sensor.
- [ ] Add Creality LED light bar.
- [ ] LCD delete.
- [ ] Rails upgrade.
