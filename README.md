# ESPTemp

A small ambient sensor PCB powered by an ESP32-C3 an BME280 or BME680

## Parts

| **Part** |  **Description** |
| -------- | ---------------- |
| U1       | ESP32-C3-WROOM   |
| U2       | TLV1117-3.3V     |
| U3       | BME280           |
| U4       | BME680           |
| D1       | WS2812B LED      |
| R1,R2    | 5.1k Resistor    |
| R3,R5,R6 | 10k Resistor     |
| R4       | 1k Resistor      |
| C1,C4    | 100 uF Capacitor |
| C2       | 1 uF Capacitor   |
| C4       | 10 uF Capacitor  |
| J1       | USB_C_Receptable |
| J2       | 3-Pin-Connector  |

## Software

As [ESPHome](https://esphome.io/) does support the BME280/BME680 it is recommended to use ESPHome.
