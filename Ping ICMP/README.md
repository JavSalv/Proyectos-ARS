# Programa de Ping Sencillo

Práctica del Tema 8 de la asignatura Arquitectura de Redes y Servicios.

Ping ICMP similar a la utilidad ping de UNIX.

## Compliar

```bash
make all
```

## Cliente

```bash
./miping direccion_ip [-v]
```
- dirección_ip: dirección a la que enviamos el ping.
- v: Activa el modo verbose, informa de los pasos que realiza así como del contenido de los campos del paquete ICMP.

