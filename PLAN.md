# Plan semanal (26 nov 2026 → 19 ene 2027)

Entrega: martes 19 de enero de 2027, 12:00 (Reino Unido). Objetivo: tener todo listo el viernes 15 de enero para entregar con margen.

| Semana | Fechas | Objetivo | Entregable en el repo |
|---|---|---|---|
| 0 | 26–29 nov | Arrancar: repo creado, idea elegida, leer el informe de ejemplo (pet tracker) y ver el vídeo del brief | `ideas/IDEAS.md` con la idea final |
| 1 | 30 nov–6 dic | Requisitos y diseño: componentes, arquitectura (nodo → M2M → gateway → nube), circuito simulado (Wokwi o Tinkercad). Validar la idea con el Dr Usman | `hardware/componentes.md`, diagrama de arquitectura, captura de la simulación |
| 2 | 7–13 dic | Prototipo básico: sensor DHT20 + ventilador por relé/transistor con umbral fijo e histéresis; envío a ThingSpeak | `firmware/sensor-node/` funcionando, canal de ThingSpeak |
| 3 | 14–20 dic | Comunicación M2M: LoRa (lab semana 5) o Bluetooth (lab semana 6) entre nodo y gateway; dashboard en la nube. Empezar a guardar datos para entrenar | `firmware/gateway/`, dashboard, primeros CSV en `data/` |
| 4 | 21–27 dic | Navidad, semana ligera: dejar el sistema registrando datos; leer bibliografía (5–10 fuentes) y anotar referencias | `report/referencias.md` |
| 5 | 28 dic–3 ene | Edge AI: entrenar un modelo (predicción de temperatura o detección de anomalías) y desplegarlo en el dispositivo (VENTUNO Q como en los labs 8–9, o TinyML). La ventilación se activa según la predicción, no solo el umbral | `edge-ai/` con modelo, script y resultados |
| 6 | 4–10 ene | Pruebas y analítica: casos de prueba, latencia, precisión del modelo, gráficas; fotos del montaje; grabar el vídeo de demo | `data/analisis`, fotos, enlace al vídeo |
| 7 | 11–17 ene | Informe de 2000 palabras: ética, legal, comercial, sostenibilidad, EDI, referencias, declaración de uso de IA. Revisión final el 15 de enero | Informe terminado + cover sheet |
| — | 18–19 ene | Entrega en Moodle con margen | ✓ |

## Hitos de control
- 6 dic: idea validada con el profesor y circuito simulado.
- 20 dic: sistema completo sin IA (sensor → M2M → nube → ventilador).
- 3 ene: Edge AI funcionando en el dispositivo.
- 15 ene: todo terminado.

## Cómo encaja con la nota
- 1a Problema resuelto (25): el sistema funciona de forma fiable → semanas 2–3 y 6.
- 1b Originalidad (10) y Edge AI visible → semana 5.
- 1c Nube (5) → semanas 2–3.
- 1d Demo (10) → semana 6.
- 2a–2d Informe (50) → semanas 4 y 7, con notas a lo largo del proyecto.

> Recordatorio: el informe lo escribes tú (política de IA Tier 2). Claude puede ayudar con ideas, código, revisión y feedback, y hay que declararlo en el AI Use Statement.
