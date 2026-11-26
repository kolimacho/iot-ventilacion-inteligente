# Smart Ventilation with IoT and Edge AI

Final project for the module COM6017M The Internet of Things (York St John University, 2026-27).

**Idea:** a sensor node measures temperature (and humidity) and automatically switches on a ventilation system when the temperature crosses a threshold. Data travels over M2M (LoRa or Bluetooth) to a WiFi gateway, is stored and analysed in the cloud (ThingSpeak), and an on-device Edge AI model predicts when ventilation will be needed so it can act ahead of time.

**Deadline:** Tuesday 19 January 2027, 12:00 noon (UK time).

## Repository structure
| Folder | Contents |
|---|---|
| `docs/` | Module requirements and weekly plan |
| `ideas/` | Ideas, decisions and questions for the lecturer |
| `hardware/` | Component list, schematics and circuit simulation |
| `firmware/sensor-node/` | Sensor node code (sensor + actuator + M2M transmitter) |
| `firmware/gateway/` | Gateway code (M2M receiver + WiFi + cloud) |
| `edge-ai/` | Training data, model and on-device deployment |
| `data/` | Data exports and analysis |
| `report/` | Notes, figures and references for the report |

## Links
- Plan: [docs/PLAN.md](docs/PLAN.md)
- Module requirements: [docs/module-brief-summary.md](docs/module-brief-summary.md)
- Ideas: [ideas/IDEAS.md](ideas/IDEAS.md)
