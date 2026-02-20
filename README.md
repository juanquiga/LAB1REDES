# LABORATORIO – NAVEGACIÓN POR LA RED (DISNEYPLUS)

## INTEGRANTES
- Juan David Quitian
- David Carvajal
- Tiffany Cardona

---

## DESCRIPCIÓN DEL PROYECTO

En este laboratorio se diseñó e implementó una red doméstica en Cisco Packet Tracer que permite a la familia Pérez navegar por el sitio web disneyplus.com desde su hogar.

La solución integra una red LAN (Red de Área Local) con una red WAN (Internet simulada) utilizando el dispositivo Cloud-PT, además de un servidor remoto que representa el servicio de Disney+.

El propósito principal para este laboratorio fue demostrar técnicamente que la comunicación de datos es exitosa utilizando herramientas como el comando ping y el navegador web.

---

## OBJETIVO

Nuestro objetivo para este lab es diseñar e implementar una topología de red que:

- Conecte dispositivos del hogar a Internet.
- Simule el acceso a un servidor en la nube.
- Permita validar la comunicación utilizando protocolos del modelo OSI y TCP/IP.
- Demuestre el flujo correcto de datos en Cisco Packet Tracer.

---

## TOPOLOGÍA IMPLEMENTADA

PC — Router — Cloud — Server

### Función de cada dispositivo

- PC: Dispositivo del usuario que realiza la navegación.
- Router: Conecta la red local con la red externa (Internet).
- Cloud-PT: Simula la red WAN (Internet).
- Server-PT: Representa el servidor donde está alojado el servicio de Disney+.

---

## TIPOS DE RED UTILIZADOS

- LAN: Red local dentro del hogar.
- WAN: Conexión hacia Internet simulada con Cloud-PT.

---

## SERVICIOS CONFIGURADOS

Durante la implementación se configuraron estos servicios:

- DHCP: Asignación automática de direcciones IP.
- HTTP: Servicio web habilitado en el servidor.
- DNS (si fue configurado): Resolución del nombre disneyplus.com a dirección IP.

---

## VALIDACIÓN DE LA COMUNICACIÓN

La comunicación fue validada mediante:

- Uso del comando ping desde la PC hacia el servidor.
- Acceso al navegador web ingresando la dirección del sitio.
- Observación del envío y recepción de paquetes en modo simulación.

Resultados obtenidos:

- Los paquetes ICMP respondieron correctamente.
- El navegador cargó el servicio web configurado.
- Se evidenció el funcionamiento del modelo OSI durante la transmisión.

---

## PROTOCOLOS UTILIZADOS

- HTTP (Capa de Aplicación)
- TCP (Capa de Transporte)
- IP (Capa de Red)
- Ethernet (Capa de Enlace)

Estos protocolos permiten la correcta transmisión de datos entre el cliente y el servidor.

---

## HERRAMIENTA UTILIZADA

- Cisco Packet Tracer

---

## CONTENIDO DEL REPOSITORIO

- Archivo .pkt con la topología implementada.
- Documentación detallada en la Wiki.
- Video explicativo del funcionamiento.

---

## CONCLUSIÓN

Se logró implementar correctamente una red doméstica funcional que simula el acceso a un servicio en la nube.

La práctica permitió comprender de manera aplicada cómo interactúan las redes LAN y WAN, así como el papel de los protocolos del modelo OSI en la comunicación de datos.

Este laboratorio fortaleció el entendimiento de conceptos básicos de redes mediante una implementación práctica en Cisco Packet Tracer.
