# AutoDrift Journal

## Total Hours: 16.0h

## Journal entry 1: Making the Schematic - Part 1

Making a custom dev board is so tedious! For every component, you have to read and understand the datasheet for it so you know how to wire everything. It's not connecting some pins to get it to work anymore. I chose some basic components for the flight controller and started wiring the power module.

Parts I chose (So far):
- MCU: STM32F765IIT6
- IMU: ICM-42688-P (Only got 6-axis, as apparently magnetometers are easy to mess up due to large influences from other components)
- Barometer: DPS368
- Bluetooth/WiFi interface: ESP32-WROOM-32E
- Blackbox: W25Q128JVSIQ
- Main Voltage Regulator 5V: TPS54140DGQ
- LDO Voltage Regulator 3.3V: LT3065HMSEPBF
- Current Sense Amplifier: INA240A3D

The biggest problem I have right now is that there is no one to check my work, and as I'm new to this, I'm prone to making mistakes. I'm hoping to find a program or app that can check my schematic in the future, but for now, I can just pray.

**Schematic**
<img width="977" height="845" alt="2025-11-27-185147_977x845_scrot" src="https://github.com/user-attachments/assets/69aff9b8-e087-4f6f-b6bd-4ed08399f714" />

### Hours spent: 4.0h


## Journal entry 2: Making the Schematic - Part 2

Who knows, datasheets do what they are supposed to: tell you about the component! It's gotten much easier to understand and read datasheets, and to connect the right components in the right place. I've finished setting up the battery module, main buck converter, LDO, and the IMU. To be honest, I've never used so many capacitors and resistors! I also had to create my own symbols for the parts based on the datasheet. There were also so many equations on the datasheets for calculating capacitors and resistors that it was very confusing. For now, I think I will continue and keep connecting all the parts.

**Schematic**
<img width="954" height="837" alt="2025-11-28-151457_954x837_scrot" src="https://github.com/user-attachments/assets/de025f3e-b601-4d7e-87a5-95ee4ae4642a" />

### Hours spent: 6.0h

## Journal entry 3: Making the Schematic - Part 3

Lots of changes! First, I finished the first draft of my schematic. It was my first time making such a complex schematic; it was very messy, and things weren't properly labelled. I then asked around on Slack and got lots of feedback. One of the biggest points was that my schematic was extremely disorganized, and they encouraged me to use hierarchical formatting for my schematic. I watched a few YouTube videos and started implementing the changes. After these changes are made, I will make a more detailed journal entry about finishing the schematic and the entire process.

**Old schematic**
<img width="4960" height="3507" alt="image" src="https://github.com/user-attachments/assets/0d05c451-b3ba-4902-8a76-99fe48d3d11b" />

### Hours spent: 6.0h
