# Datasheets

This directory contains datasheets for all components used in the Fixed Wing Flight Control Unit (FCU).

## Directory Structure

### `/microcontrollers`
Microcontroller and processor datasheets including:
- Main MCU datasheets
- Coprocessor datasheets
- Reference manuals
- Errata documents
- Application notes

### `/sensors`
Sensor datasheets including:
- IMU (Inertial Measurement Unit) sensors
- GPS modules
- Barometric pressure sensors
- Airspeed sensors
- Magnetometers
- Temperature sensors

### `/communication`
Communication module datasheets including:
- Radio transceivers
- Telemetry modules
- UART/I2C/SPI interface chips
- USB interfaces
- CAN transceivers

### `/power`
Power management datasheets including:
- Voltage regulators
- Power distribution components
- Battery management ICs
- DC-DC converters
- Protection circuits

### `/connectors`
Connector datasheets including:
- Board-to-board connectors
- Wire-to-board connectors
- Servo connectors
- Programming interfaces
- Antenna connectors

### `/misc`
Miscellaneous component datasheets including:
- LEDs and indicators
- Crystal oscillators
- Passive components (when specs are critical)
- ESD protection devices
- Any other components

## File Naming Convention

Please use the following naming convention for datasheets:
```
<manufacturer>_<part-number>_<description>.pdf
```

Examples:
- `STMicroelectronics_STM32F4_Datasheet.pdf`
- `Bosch_BMI088_IMU_Datasheet.pdf`
- `uBlox_NEO-M9N_GPS_Datasheet.pdf`

## Notes

- Always use official datasheets from manufacturers
- Include version/revision information in the filename if critical
- Keep datasheets up to date with component revisions
- Reference specific pages in BOM or design docs when needed
