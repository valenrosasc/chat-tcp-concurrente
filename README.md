# Chat TCP concurrente

Proyecto final: aplicación de chat cliente-servidor para varias personas, con salas y una interfaz gráfica.

## Objetivo

Construir un servidor TCP que acepte varias conexiones simultáneas, distribuya mensajes a los usuarios de cada sala y gestione correctamente las desconexiones.

## Alcance inicial

- Conexión de varios clientes al servidor.
- Ingreso a salas y envío de mensajes.
- Avisos de usuarios que entran y salen.
- Interfaz gráfica para conectarse y chatear.
- Manejo de errores y cierre limpio de conexiones.
- Pruebas con varios clientes, incluyendo conexiones simuladas.

## Tecnologías previstas

- Python
- TCP sockets
- `asyncio` para atender múltiples conexiones
- Tkinter para la interfaz gráfica inicial

La implementación y las decisiones técnicas se documentarán a medida que avance el proyecto.
