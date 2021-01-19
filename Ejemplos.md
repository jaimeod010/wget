#Ejemplos 

##-¿Cómo descargar una pagina web?

Para descargarnos recomiendo usar este comando
```
wget -m -F -p -np -k -erobots=off -U mozilla --limit-rate=50K --wait=2 --html-extension elsitiowebparadesc
```
Usamos * `-m` porque es similar a la descarga recursiva, pero en este caso no existe limite en lo absoluto

Usamos * `-f` para  para que fuerce a descargar la web aunque encuentre algún problema

Usamos * `-p` porque permite especificar donde se almacenarán los archivos descargados, si la carpeta no existe wget la creará.

Usamos * `-k` porque al finalizar la descarga re-escribe los links que existan en la página para que apunten a los archivos descargados si fuera necesario, para asegurar su funcionamiento offline.

Usamos * `-U` para especificar con que navegador quiere que se haga la descarga

Usamos * `-limit-rate` para limitar la velocidad al realizar la descarga.


##Enlaces de interes

https://norfipc.com/internet/ejemplos-wget.html

En este enlace nos explica opciones de wget y ademas nos proporciona tips
