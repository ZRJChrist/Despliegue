## Ejemplo del uso del comando Telnet

**Telnet** es un protocolo de red que se utiliza para acceder a dispositivos y servidores de forma remota a través de una conexión de texto sin formato. A continuación, se muestra un ejemplo de cómo utilizar Telnet para conectarse a un servidor y realizar una solicitud HTTP manualmente:

1. Abre una ventana de terminal o línea de comandos en tu sistema operativo.

2. Utiliza el comando `telnet` seguido de la dirección IP o el nombre de dominio del servidor web y el puerto 80 (el puerto predeterminado para HTTP). Por ejemplo:

```shell
   telnet ejemplo.com 80
```
Deberías ver una respuesta del servidor que indica que has establecido una conexión. Esto se verá así:

```shell
Trying 192.168.1.1...
Connected to ejemplo.com.
Escape character is '^]'.
```

Ahora puedes enviar una solicitud HTTP manualmente. Por ejemplo, para solicitar la página de inicio, puedes escribir:

```shell
GET / HTTP/1.1
Host: ejemplo.com
```

