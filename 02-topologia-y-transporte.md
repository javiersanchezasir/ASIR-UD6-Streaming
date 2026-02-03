## Topología de red

### Unicast
- Conexión 1 a 1
- Si hay N usuarios, el servidor envía el stream N veces
- Fórmula:
BW total = BW stream × nº usuarios
- Desventaja: poco escalable

### Multicast
- El servidor envía a una dirección multicast
- Rango: 224.0.0.0 – 239.255.255.255
- Los routers replican paquetes solo si hay suscriptores
- Solo viable en redes internas



## TCP vs UDP

### TCP
- Fiable (retransmisión de paquetes)
- Más latencia
- Pasa bien firewalls, NAT y proxy
- Usado por: Netflix, Spotify, YouTube, Icecast

### UDP
- No fiable
- Latencia mínima
- Usado cuando el retraso no es admisible (videollamadas, juegos)
