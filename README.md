# Ventilación inteligente con IoT y Edge AI

Proyecto final del módulo COM6017M The Internet of Things (York St John University, 2026-27).

**Idea:** un nodo con sensor de temperatura (y humedad) que activa automáticamente un sistema de ventilación cuando la temperatura cruza un umbral. Los datos viajan por M2M (LoRa o Bluetooth) a un gateway con WiFi, se guardan y analizan en la nube (ThingSpeak), y un modelo de Edge AI en el propio dispositivo anticipa cuándo activar la ventilación.

**Entrega:** martes 19 de enero de 2027, 12:00 hora de Reino Unido.

## Estructura
| Carpeta | Contenido |
|---|---|
| `docs/` | Contexto del curso y plan semanal |
| `ideas/` | Ideas, decisiones y dudas para el profesor |
| `hardware/` | Lista de componentes, esquemas y simulación del circuito |
| `firmware/sensor-node/` | Código del nodo sensor (sensor + actuador + emisor M2M) |
| `firmware/gateway/` | Código del gateway (receptor M2M + WiFi + nube) |
| `edge-ai/` | Datos de entrenamiento, modelo y despliegue en el dispositivo |
| `data/` | Exportaciones de datos y análisis |
| `report/` | Notas, figuras y referencias para el informe |

## Enlaces
- Plan: [docs/PLAN.md](docs/PLAN.md)
- Requisitos del curso: [docs/contexto-curso.md](docs/contexto-curso.md)
- Ideas: [ideas/IDEAS.md](ideas/IDEAS.md)
