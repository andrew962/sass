# Partials

Al crear archivos **partials** se puede tener la opcion de crearlos como modulos esto nos da la opcion de poder cambiar los estilos, para esto debemos agregar a la variable la propiedad de ```!default``` para decir que tiene un valor por defecto por lo que puede ser personalizada. Al poner ```!default``` le decimos que esta esa variable esta destinada a cambiar.

*Ejemplo:*

```
style.scss

@use 'variables' with (
    $primary: red;
); 

body{
    background-color: variables.$primary;
}
```

```
_variables_.scss

$primary:#000 !default;

```