**COMPRIMIR A TAR.GZ** 

> tar -zcvf resultado.tar.gz carpeta-o-archivo

**DESCOMPRIMIR DE TAR.GZ** 

> tar -xvzf archivo-comprimido.tar.gz

**ARCHIVO LOCAL A REMOTO Y VICEVERSA**

> scp <RUTA-DE-FICHERO-A-MOVER> estefania@34.76.205.238:/<RUTA-A-DONDE-SE-QUIERE-MOVER>

**COGER ARCHIVOS DE UNA URL**

> wget <url>

**DESCARGAR FICHEROS ELASTICSEARCH** 

> curl -O url.zip
  
**DESCOMPRIMIR** 
  
> unzip name.zip  
  
**VER CONTENEDORES EN MARCHA**

> sudo docker ps
  
**Ver contenedores creados** 
  
> sudo docker ps -a
  
**Ver imágenes creadas** 

> sudo docker images
  
**Borrar contenedor** 
  
> sudo docker rm ID
  
**Borrar imágen**
  
> sudo docker rmi ID

**Borrar todos los contenedores e imágenes creadas** 

> sudo docker prune
