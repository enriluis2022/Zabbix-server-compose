# ¿Cómo instalar Zabbix usando docker-compose?  

# 1. ¿Qué es Zabbix?  
Zabbix  es un Sistema de Monitorización de Redes que en tiempo real recoge miles de métricas de servidores, equipos virtuales, dispositivos de red y aplicaciones web.
El servidor Zabbix  almacena sus datos en una base de datos relacional alimentada con MySQL o PostgreSQL.

# 2. Instalación

	git clone https://github.com/jmlcas/zabbix-server

Ahora solo nos queda poner la aplicación en marcha con el comando habitual

	docker-compose up -d

Finalmente, digitamos en el navegador:

"Localhost:8080" o bien "IP:8080" para acceder desde otro PC en la misma red wifi. 

USER = Admin  
PASSWORD = zabbix
