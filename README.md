# Hardening de Infraestructura de Red (ISO/IEC 27001)

Este proyecto consiste en el diseño y aseguramiento lógico de una red institucional, aplicando controles de seguridad en Capa 2 y Capa 3 bajo los lineamientos y mejores prácticas de la norma internacional ISO/IEC 27001. 

El objetivo principal es mitigar vulnerabilidades operativas, segmentar el tráfico y prevenir ataques comunes a nivel de red de área local (LAN).

## Topología de la Red

<img width="707" height="331" alt="Hardening" src="https://github.com/user-attachments/assets/d54080b0-41b0-4735-b860-dcdc8f57ea60" />


## Controles de Seguridad Implementados

**Seguridad en Capa 2 (Switching):**
* **VLANs:** Segmentación lógica de departamentos para aislar dominios de broadcast.
* **Port Security:** Restricción de direcciones MAC por puerto para prevenir ataques de suplantación y conexión de dispositivos no autorizados.
* **DHCP Snooping:** Mitigación de ataques de servidores DHCP falsos (*Rogue DHCP*).
* **Dynamic ARP Inspection (DAI):** Prevención de envenenamiento ARP.
* **STP Security:** Implementación de BPDU Guard para proteger la topología de Spanning Tree.

**Seguridad en Capa 3 (Routing) y Administración:**
* **Access Control Lists (ACLs):** Listas de control de acceso para filtrar el tráfico entre VLANs según políticas institucionales.
* **SSHv2:** Configuración de acceso remoto cifrado para la administración de equipos, reemplazando protocolos inseguros.

## Contenido del Repositorio

* `Proyecto Final Propuesta De Hardening.pkt`: Archivo de simulación. Requiere **Cisco Packet Tracer** para interactuar con la configuración de los equipos y la CLI.
* `Reporte Proyecto Final.pdf`: Documentación técnica detallada del proyecto, incluyendo el esquema de direccionamiento IP y la justificación de los controles.


## Autor
**Carlos Mauricio Valadez Espinoza**
* [GitHub - Mau22v](https://github.com/Mau22v)
