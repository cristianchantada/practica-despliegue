# practica-despliegue
Práctica del módulo de configuración de servidores y despliegue de aplicaciones KC Web 14 Cristian Varela Casas

## URLs:

  * https://backend.nodepop.duckdns.org/
  * https://react.nodepop.duckdns.org/login

## Notas.

# Requisitos obligatorios APP Node:

  * Se utiliza gestor de procesos para mantener en pie APP ante caídas del servidor.
  * Se utiliza proxy inverso en el servidor web.
  * Los ficheros estáticos pasan a ser servidos por el servidor web utilizado.

# Requisitos obligatorios APP React con Router:

  * La navegación se habilita para APP utilizando React Router.

# Además de los requisitos para la superaciónd de la práctica decido realizar de motu proprio:
  
  * Se securiza la base de datos.
  * Se asigna una ip fija al servidor.
  * Se asignan dominios propios.
  * Se obtiene certificado SSL y se cambia protocolo a HTTP.
  * Se habilita el servicio fail2ban de protección.
  * Se habilita el ocultar nº de versión del servidor web que estamos utilizando.
  * Se cambia el puerto SSH por defecto.

Cristian Varela Casas.
En Chantada, a 12 de julio de 2023. 
