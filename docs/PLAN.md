# Weekly Plan (26 Nov 2026 → 19 Jan 2027)

Deadline: Tuesday 19 January 2027, 12:00 noon (UK). Target: everything finished by Friday 15 January to submit with time to spare.

| Week | Dates | Goal | Deliverable in the repo |
|---|---|---|---|
| 0 | 26–29 Nov | Kick-off: repo created, idea chosen, read the sample report (pet tracker) and watch the brief video | `ideas/IDEAS.md` with the final idea |
| 1 | 30 Nov–6 Dec | Requirements and design: components, architecture (node → M2M → gateway → cloud), simulated circuit (Wokwi or Tinkercad). Validate the idea with Dr Usman | `hardware/components.md`, architecture diagram, simulation screenshot |
| 2 | 7–13 Dec | Basic prototype: DHT20 sensor + fan via relay/transistor with a fixed threshold and hysteresis; send data to ThingSpeak | Working `firmware/sensor-node/`, ThingSpeak channel |
| 3 | 14–20 Dec | M2M communication: LoRa (week 5 lab) or Bluetooth (week 6 lab) between node and gateway; cloud dashboard. Start logging data for training | `firmware/gateway/`, dashboard, first CSVs in `data/` |
| 4 | 21–27 Dec | Christmas, light week: leave the system logging data; read literature (5–10 sources) and note references | `report/references.md` |
| 5 | 28 Dec–3 Jan | Edge AI: train a model (temperature forecasting or anomaly detection) and deploy it on the device (VENTUNO Q as in labs 8–9, or TinyML). Ventilation is triggered by the prediction, not just the threshold | `edge-ai/` with model, scripts and results |
| 6 | 4–10 Jan | Testing and analytics: test cases, latency, model accuracy, charts; photos of the build; record the demo video | `data/analysis`, photos, video link |
| 7 | 11–17 Jan | 2000-word report: legal, ethical, commercial, economic, sustainability and EDI evaluation, references, AI Use Statement. Final review on 15 January | Finished report + cover sheet |
| — | 18–19 Jan | Submit on Moodle with margin | ✓ |

## Checkpoints
- 6 Dec: idea approved by the lecturer and circuit simulated.
- 20 Dec: full system working without AI (sensor → M2M → cloud → fan).
- 3 Jan: Edge AI running on the device.
- 15 Jan: everything finished.

## Mapping to the marking criteria
- 1a Problem solved (25): reliable working system → weeks 2–3 and 6.
- 1b Originality (10) and visible Edge AI → week 5.
- 1c Cloud (5) → weeks 2–3.
- 1d Demonstration (10) → week 6.
- 2a–2d Report (50) → weeks 4 and 7, with notes kept throughout.

> Reminder: the report must be written by the student (Tier 2 AI policy). AI may help with ideas, code, proofreading and feedback, and this must be declared in the AI Use Statement.
