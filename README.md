# Sass

Pequeño curso de sass

La buena practica de sass es crear un archivo ```scss``` principal y crear archivos que separen la logica, estos archivos deben tener una barra baja ```_``` al incio para que sas entienda que no es un archivo compilable.

*Ejemplo:* ```style.scss _variables.scss```

De tener los archivos con esta estructura solo queda ir al archivos principal y usar la palabra reservada de sass ```@use``` para importar el archivo, no es necesario agregar la extencion.

*Ejemplo:*
***style.scss***
```@use 'variables';```
