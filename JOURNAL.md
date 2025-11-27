# AutoDrift Journal

## Journal entry 1: Making the Schematic - Part 1

Making a custom dev board is so tedious! For every component, you have to read and understand the datasheet for it so you know how to wire everything. It's not connecting some pins to get it to work anymore. I choose some basic components for the flight controller, and started wiring the power module.

Parts I chose (So far):
- MCU: STM32F765IIT6
- IMU: ICM-42688-P (Only got 6-axis, as apparently magnetometers are easy to mess up due to large influences from other components)
- Barometer: DPS368
- Bluetooth/WiFi interface: ESP32-WROOM-32E
- Blackbox: W25Q128JVSIQ
- Main Voltage Regulator 5V: TPS54140DGQ
- LDO Voltage Regulator 3.3V: LT3065HMSEPBF
- Current Sense Amplifier: INA240A3D

The biggest problem I have right now is that there is no one to check my work, and as I'm new to this, I'm prone to make mistakes. I'm hoping to find a program or app that can check my schematic in the future, but for now, I can just pray.

**Schematic**
<img width="977" height="845" alt="2025-11-27-185147_977x845_scrot" src="https://github.com/user-attachments/assets/69aff9b8-e087-4f6f-b6bd-4ed08399f714" />

### Hours spent: 5.0h
