# DocumentacionFNACuel


Lo primero que tienes que tener instalado es java, por si no lo tuvieses instalado
dejo un enlace directo para que lo instales 

https://www.filehorse.com/download/file/DyeXiKabQNFen5HV6tsDBrz0RtNWMpF3w3r8_O17VcIDUMz3sMOE8N9-3mdrukca1LyP2BiitgphwjAtbFGwnkOeEVEuAjD4kUU4BUz4aM4/

Una vez tengas instalado java es necesario desplegar el docker-compose up -d en la carpeta donde este el .yml, luego en la consola pondrias
```
docker-compose up -d
```

cuando se haya desplegado el docker compose y veamos que esta en verde en la aplicacion de docker, en el mismo directorio donde se encontraba el **docker compose**
pondremos:
```
java -jar ProyectoFinalDeSpring-0.0.1-SNAPSHOT.jar
```

Por ultimo cuando se haya desplegado el Spring, pondremos **localhost:9001** y acabariamos
