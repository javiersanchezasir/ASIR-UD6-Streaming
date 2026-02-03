## QoS

### Jitter
- Variación en el tiempo de llegada de los paquetes
- Si el jitter supera el tamaño del buffer → cortes de audio (buffer underrun)

### Buffer
- Memoria temporal en el cliente
- A mayor buffer:
  - Más estabilidad
  - Más latencia


## Burst-on-Connect
- Técnica usada por Icecast
- Al conectarse un cliente, el servidor envía datos a máxima velocidad
- Objetivo: llenar rápido el buffer y reducir el tiempo de espera
