# Servidor y Cliente TCP sencillos

Práctica del Tema 6 de la asignatura Arquitectura de Redes y Servicios.

Cliente y Servidor que se comunican por TCP. El servidor transforma la cadena recibida de mayúsculas a minúsculas y viceversa.

## Compliar


```bash
make all
```

## Cliente

```bash
./echo-tcp-client ip_servidor [-p puerto_servidor] cadena
```
La longitud de la cadena será truncada a 80 caracteres en el caso de ser más larga.

## Servidor

```bash
./echo-tcp-server [-p puerto_servidor]
```

Por defecto el servidor está escuchando en el puerto 5, se necesitan permisos de root para ejecutar servicios en puertos menores a 1024.
