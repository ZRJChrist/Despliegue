# Actividad 0.2 - Comparación de los Protocolos de Transporte UDP y TCP

## Diferencias entre UDP y TCP
- UDP es un protocolo sin conexión, no garantiza la entrega ni el orden de los datos.
- TCP es un protocolo orientado a la conexión, garantiza la entrega y el orden de los datos.

## Aplicaciones que usan TCP
- HTTP (Protocolo de Transferencia de Hipertexto)
- SMTP (Protocolo Simple de Transferencia de Correo)
- POP (Protocolo de Oficina de Correo)
- IMAP (Protocolo de Acceso a Mensajes de Internet)
- SSH (Secure Shell)

## Aplicaciones que usan UDP
- DNS (Sistema de Nombres de Dominio)
- VoIP (Voz sobre IP)
- Videoconferencia
- Juegos en línea (por ejemplo, para transmisión de datos en tiempo real)

## Capa que almacena el puerto
La capa de transporte almacena el puerto. En el caso de TCP y UDP, se utilizan puertos para dirigir los datos a aplicaciones específicas en un dispositivo.

## Capa que almacena la dirección IP
La capa de red almacena la dirección IP. La dirección IP se utiliza para enrutar los datos a través de la red hasta su destino.

## ¿Qué es el "Three-Way Handshake"?
El "Three-Way Handshake" es un proceso de establecimiento de conexión en TCP. Implica tres pasos: SYN (sincronización), SYN-ACK (sincronización-acknowledgment) y ACK (acknowledgment). Este proceso se utiliza para establecer una conexión TCP de manera segura y bidireccional entre un cliente y un servidor, asegurando que ambas partes estén listas para la comunicación antes de enviar datos.
