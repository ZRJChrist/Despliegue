# Actividad 2 - Configuracion Apache

## Añadir un puerto

1. Para agregar o cambiar el puerto de apache nos dirigimos a:
```shell 
nano /etc/apache2/ports.conf
```
2. Agegamos el puerto nuevo añadiendo el siguiente texto _"Listen 81_". _CTRL+X_ para cerrar y aceptamos el sobreescribir

3. Reiniciamos apache para que la configuracion se aplique
```shell
sudo service apache2 restart
```

## Añadir al servidor un dominio
1. Abre el archivo /etc/hosts con un editor de texto. 
```shell 
sudo nano /etc/hosts
```
2. Desplázate hacia la parte inferior del archivo y añadimos una nueva línea con la dirección IP que deseamos asignar y el nombre de dominio.
```shell
192.0.0.1    marisma.intranet
```
3. Reiniciamos apache para que la configuracion se aplique
```shell
sudo service apache2 restart
```
## Cambia la directiva “ServerTokens” 

1. Simplemente no dirigimos al archivo apache2.conf donde agrgaremos la linea _"ServerTokens ProductOnly"_
```shell
sudo nano /etc/apache2/apache2.conf
```
2. En ese archivo añadirmos la linea mencionada y reiniciamos apache para que se aplique la configuracion.

## Haz que se visualice el pie de página de Apache en tu navegador

1. En el archivo apache2.conf agregamos la linea _"ServerSignature On"_.Por defecto sera _"On"_, si queremos quitar dicha informacion del navegador el valor tedra que ser _"Off"_ 
```shell
sudo nano /etc/apache2/apache2.conf
```
2. Reiniciamos para que se aplique la configuracion.

## Crea un directorio “prueba” y otro directorio “prueba2”

1. Nos situamos en la direccion _/var/www/html_ y creamos 2 capetas _prueba1_ y _prueba2_, a cada carpeta le creamos un index html.

```shell
cd /var/www/html
mkdir prueba1
mkdir prueba2
# Creamos el archivo en cada carpeta
cd prueba1
nano index.html
cd ../prueba2
nano index.html
```