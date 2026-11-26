# Module Brief Summary: COM6017M The Internet of Things (2026-27, Sem 1, Group A)

Source: York St John University Moodle course page and Assignment Brief, read on 26/11/2026.

## Module details
- Code: COM6017M · Level 6 · 20 credits
- Module Leader: Dr Aminu Usman
- Technical Demonstrators: Norbert Dajnowski, Slav Shkratsky, Adel Rahuma
- Single assessment: 1 component = 100% of the module grade. Format: Portfolio, submitted via Moodle.
- Limit: 2000 words (the AI Use Statement does not count).

## Key dates
- Submission: Tuesday 19 January 2027, 12:00 noon UK time. (The brief says "2026" by mistake; Moodle shows the 2027 date.)
- 2-week extension (approved LAP or Exceptional Circumstances only): 2 February 2027.
- Feedback: 9 February 2027.
- Resits/deferrals: 6 April 2027 (resit period 5–9 April 2027; also August and October 2027).
- In-person demo timetable is released one week before demo week.

## Task
Design, develop, evaluate and communicate an IoT project that solves a real-world problem of your choice, ideally combining IoT with Edge AI. Suggested areas: health, environment, agriculture, transportation, security, smart homes, industry.

### Task 1: IoT + Edge AI artefact (50%)
The artefact must:
- Work reliably and solve a specific real-world problem (big or small).
- Use M2M communication: LoRa/LoRaWAN, ZigBee, Sigfox, 6LoWPAN, GSM, RFID, Bluetooth/BLE or NFC.
- Include internet connectivity (WiFi, LTE, etc.).
- Use data storage and analytics: cloud (AWS IoT, ThingSpeak, Azure IoT Hub, Google Cloud IoT) or a custom web server and database.
- For a distinction: integrate Edge AI, e.g. on-device ML inference (Arduino + TinyML, Raspberry Pi + TensorFlow Lite, Jetson Nano), local anomaly detection, activity recognition, voice/image/sensor classification. Training can happen in the cloud, but inference must run locally.

### Task 2: Written report (50%)
Suggested structure (can be adapted):
1. Introduction and problem definition
2. Project requirements (hardware, software, cloud services) with brief descriptions
3. Circuit design (using a simulator)
4. Testing phase
5. Data analytics (analysis, visualisation, presentation)
6. Legal and ethical evaluation
7. Conclusion
8. Source code on GitHub/GitLab (link)
9. References
10. Appendix (project photos)

It must also cover the legal, ethical, commercial and economic context, sustainability and EDI; explain design, development, testing and implementation with underlying theory; include diagrams, pictures and the artefact's schema; and show research through related work and references.

### Demonstration (mandatory)
- In person: up to 15 minutes in class, or
- Video: on an accessible platform (YouTube, etc.) with the link in the report, or uploaded to Moodle (max 400 MB). An in-person demo may be requested if unclear.

## Marking criteria (100 marks)
Artefact (50):
- 1a Problem solved / artefact works: 25
- 1b Originality and contribution: 10
- 1c Use of internet/cloud platforms: 5
- 1d Demonstration/presentation: 10

Report (50):
- 2a Report structure: 5
- 2b Body of report (processes, theory, design, development, testing, implementation): 20
- 2c Legal, ethical, commercial, economic context + sustainability and EDI (and quality of diagrams/architecture): 10
- 2d Research and references: 15

The 1st band of almost every criterion requires Edge AI to be "visible and practical". Bands: 1st, 2:1, 2:2, 3rd; pass from 40, and learning outcomes must be met.

## AI policy (Tier 2: some AI use permitted)
- Permitted: brainstorming, grammar/spelling proofreading, checking reference formatting, exploring theoretical frameworks, finding papers to read yourself, practice Q&A questions, general feedback on your own work.
- Not permitted: generating full paragraphs or answers, paraphrasing sources with AI, submitting AI-generated content as your own.
- Required: an AI Use Statement at the end stating which tools were used and how (not counted in the word limit).

## Learning outcomes (summary)
Academic research and critique; using tools to build and document applications; defining a problem with its social context, constraints and cost drivers; specifying, designing, deploying, verifying and maintaining systems; ethical and secure data management; project management; information security in system design and use.

## Weekly lab content
- Week 1: Arduino Uno, getting started with the IDE.
- Week 2: Arduino UNO R4 WiFi, multiple sensors, WiFi (WiFiS3), sending data to ThingSpeak.
- Week 3: Circuit design with Arduino.
- Week 4: Seeed Grove Beginner Kit (DHT20) + UNO R4 WiFi + UART + OLED + ThingSpeak; five IoT systems.
- Week 5: LoRa at 433 MHz (RFM9x + DHT11, sender/receiver), plus Dragino lab.
- Week 6: Multi-sensor environmental monitor (Grove) to ThingSpeak with two Arduinos; Part 3: Bluetooth (HC-05/06) to a gateway and the cloud.
- Week 7: lecture and lab (file not machine-readable).
- Week 8: Edge AI on Arduino VENTUNO Q: local detection of unusual environmental conditions (group).
- Week 9: Python-based Edge AI on VENTUNO Q (continuation).

## Useful Moodle resources
- Assignment Brief (DOCX) and brief explanation video (Teams recording).
- Sample previous reports: 3 PDFs plus "Sample of IoT project" (a pet tracker following the same structure as the brief).
- University cover sheet (DOCX), preparation and final submission checklists.
- Module reading list, referencing and study skills guides.
