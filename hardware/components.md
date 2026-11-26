# Components

## Already available
- **Arduino UNO R4 WiFi** – gateway: WiFi to ThingSpeak, built-in BLE (ESP32-S3) for M2M.

## Needed
| Component | Purpose | Notes |
|---|---|---|
| Temperature (and humidity) sensor: DHT20 (Grove kit, I2C) or DHT22/AM2302 | Measure temperature | DHT20 is in the lab Grove kit; DS18B20 if only temperature is needed |
| Second microcontroller (another UNO R4 WiFi, ESP32 or Grove Beginner Kit) | Sensor node that sends data over M2M | Required so there is real machine-to-machine communication |
| M2M link: BLE (built into the R4 WiFi) **or** 2× RFM9x LoRa 433 MHz modules | Node → gateway communication | LoRa covers longer range (week 5 lab); BLE needs no extra hardware |
| 5 V DC fan | Ventilation actuator | A small PC-style fan is enough for the prototype |
| Logic-level N-channel MOSFET (e.g. IRLZ44N) or NPN transistor (TIP120 / 2N2222), or a 5 V relay module | Switch the fan from an Arduino pin | Arduino pins cannot power a fan directly |
| 1N4007 flyback diode | Protect the circuit from the motor's back-EMF | Not needed with most relay modules |
| 220 Ω–1 kΩ resistor (gate/base) + 10 kΩ pull-down | Transistor/MOSFET drive | |
| External 5 V supply (USB power bank or 5 V adapter) | Power the fan separately | Share GND with the Arduino |
| Breadboard and jumper wires | Prototyping | |
| Optional: Grove OLED display, LED, push button | Local status display and manual override | |
| Edge AI device: Arduino VENTUNO Q (labs 8–9) or TinyML on the UNO R4 | On-device prediction / anomaly detection | Needed for a first-class mark; ask whether the lab board can be borrowed |

## Software / cloud
- Arduino IDE, ThingSpeak (free account), Wokwi or Tinkercad for circuit simulation, Edge Impulse or TensorFlow Lite Micro for the model.
