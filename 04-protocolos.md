## Modelos de streaming

### HTTP Legacy (Icecast)
- Protocolo: ICY
- Basado en TCP
- Flujo continuo de datos
- Puertos: 80, 443, 8000
- Usado en radio online


### HTTP Adaptativo
- Protocolos: HLS, MPEG-DASH
- Usa TCP
- Divide el contenido en chunks (2–10 segundos)
- Permite calidad adaptativa
- Usado por Netflix, YouTube


### Real-Time
- RTMP: TCP, ingestión (OBS → servidor)
- RTSP: UDP datos + TCP control (cámaras IP)
- WebRTC: UDP, P2P, videoconferencia (<0.5s)


## Resumen rápido
- Netflix / Spotify → TCP
- Twitch (viewer) → TCP
- Videollamadas → UDP
