# Ideas

## Main idea
A temperature sensor that automatically switches on ventilation when a threshold is crossed.

### Open questions
- Should ventilation start when the temperature **rises** above the threshold (usual case) or when it **drops** below it?
- Where will it be used? (classroom, greenhouse, server room, an elderly person's room, farm…) A concrete context strengthens the "real-world problem" criterion.
- Which actuator? 5 V fan with transistor/relay, or the kit's motor.

### How to reach a first-class mark
- M2M: sensor node → LoRa or Bluetooth → gateway (mandatory requirement).
- Cloud: ThingSpeak with charts and alerts.
- Edge AI: forecast the temperature for the next few minutes and switch on before reaching the threshold, or detect anomalies (open door, fan failure).
- Extras: hysteresis to avoid rapid on/off cycling, remote manual override, energy consumption tracking.

## Other ideas
- (add here)
