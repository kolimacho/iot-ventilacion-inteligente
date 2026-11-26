# Ideas

## Idea principal
Sensor de temperatura que activa automáticamente la ventilación cuando se cruza un umbral.

### Dudas por cerrar
- ¿La ventilación se activa cuando la temperatura **sube** por encima del umbral (lo habitual) o cuando **baja**?
- ¿Dónde se usa? (aula, invernadero, sala de servidores, habitación de una persona mayor, granja…) Un contexto concreto ayuda a la nota de "problema real".
- ¿Qué actuador? Ventilador de 5 V con transistor/relé, o el motor del kit.

### Cómo llevarla a la nota máxima
- M2M: nodo sensor → LoRa o Bluetooth → gateway (requisito obligatorio).
- Nube: ThingSpeak con gráficas y alertas.
- Edge AI: predecir la temperatura de los próximos minutos y encender antes de llegar al umbral, o detectar anomalías (puerta abierta, fallo del ventilador).
- Extras: histéresis para evitar encendidos continuos, control manual remoto, consumo energético.

## Otras ideas
- (añadir aquí)
