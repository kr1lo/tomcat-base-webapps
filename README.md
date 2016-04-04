# tomcat-base-webapps

Configuración de tomcat para servir multiples aplicaciones Java

## Anotaciones

Para hacer que funcione esta configuración se debe tener el WAR de la aplicación
construido ya sea con maven o con el compilador que más les agrade.

El o los archivos WAR se deben colocar en el directorio `webapps`. Una vez que se
tienen los archivos WAR en este directorio se puede proceder a inicializar el
servidor.

```bash
./bin/startup.sh
```

Esto inicializará el servidor y lanzará todas las aplicaciones WAR que se tengan
en el directorio `webapp`.
