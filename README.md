# Entrega 2 — Telemática

Repositorio de entrega del diseño e implementación de una red multisistema autónomo en Cisco Packet Tracer.

## Archivos para entregar

- `Entrega2_AS1_AS2_AS99.pkt`: topología completamente configurada en Cisco Packet Tracer.
- `Informe_Entrega2_Redes.pdf`: informe técnico con diseño, direccionamiento, configuración y pruebas.

## Contenido de la solución

- AS1 con RIP versión 2.
- AS2 con OSPF.
- AS99 con servicios DNS y WEB.
- VLAN 10 y VLAN 20.
- DHCP centralizado mediante DHCP Relay.
- NAT/PAT para resolver el solapamiento de las redes privadas.
- Registro DNS `www.entrega2.local` hacia el servidor WEB.

## Verificación

Los cuatro equipos cliente obtienen su configuración mediante DHCP. Se verificó conectividad desde AS2 hacia los servidores DNS (`203.0.114.53`) y WEB (`203.0.114.80`), además de la resolución de `www.entrega2.local`.

## Apertura

Abra `Entrega2_AS1_AS2_AS99.pkt` con Cisco Packet Tracer 9.0.1 o una versión compatible.
