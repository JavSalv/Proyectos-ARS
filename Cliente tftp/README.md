# Cliente TFTP sencillo

Práctica del Tema 7 de la asignatura Arquitectura de Redes y Servicios.

Cliente tftp que envía y recibe archivos sobre el protocolo TFTP(Trivial File Transfer Protocol) sobre UDP.

## Compliar


```bash
make all
```

## Ejecutar

```bash
./tftpclient.out ip_servidor {-r|-w} archivo [-v]
```
- ip_servidor: dirección IP del servidor TFTP.
- {-r|-w}: Lectura o escritura, respectivamente.
- archivo: Nombre del fichero a enviar o recibir.
- v (opcional): Activa el modo verbose, el cliente informa por salida estándar de los paquetes enviados/recibidos.