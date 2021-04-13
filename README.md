# SolarHeater
Solar Heating

## Controller

Include test buttons
Reset button for bootloader

### Safety Hardware
Activate 40A isolator from
1. If element > 5 V for 50 ms
2. If tank low level input active
3. If tank temperature > 60 C

### Digital Outputs
1. Open collector / drain 100 V / 2A
2. Relay drive with free wheel diode
3. 5 V / 12 V SSR drive
4. Isolated DRED output

### Inputs
1. Temperature sensors (5)
2. Bus voltage sensor (1)
4. Element voltage present (1)
5. Tank level (1)
6. Flow sensor (1)


### Communications
1. Serial bus (isolated onewire) (2)


## Universal Hardware

Design PCB for maximum utility.

Supply 10 to 100 V





