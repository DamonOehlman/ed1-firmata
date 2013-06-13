

## Inputs

- D14: Push Button
- D15: Push Button
- D16: IR Rx (SFH5110)

- A3: Potentiometer
- A6: Temperature Sensor [MCP9701A-E/TT](http://www.microchip.com/wwwproducts/Devices.aspx?dDocName=en027104)
- A7: Light Sensor [APDS-9002](http://www.avagotech.com/pages/en/optical_sensors/ambient_light_photo_sensors/apds-9002/)

- I2C (0x1D) Accelerometer 

## Outputs

- D9: Piezo Buzzer
- D13: IR Tx (NC7SZ125M5X)

### LCD (16x2)

```
rs		D6
rw		D7
enable  D8
d4      D2
d5      D3
d6      D4
d7      D5
```

### LED Shift Register

- D10: Clock
- D11: Latch
- D12: Data

## Other

- I2C (0x51) Eeprom