# AW
## HTML y CSS
### estructura mínima de una web

```html
<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>

</body>
</html>
```
### explica las 3 formas de usar CSS en HTML
css externo 
```html
<link rel="stylesheet" type="text/css" href="index.css" />
```
css interno
```html
<!DOCTYPE html>
<html>
<head>
    <title>Título de la página</title>
    <style type="text/css">
        div {
            background:#FFFF00;
        }
    </style>
</head>
...
```
css embebido
```html
<p>¡Hola <span style="color:#FF0305">amigo </span>!</p>
```
### crea una lista sin ordenar con 5 ingredientes de una receta de cocina
```html
<ul>

<li aceite /li>

<li atun /li>

<li tomate /li>
	
<li lechuga /li>
	
<li huevo /li>	
</ul>
```
### como se puede incluir javascript en HTML
Se puede agregar mediante la etiqueta "script" entre las etiquetas del "head" o del "body:
```html
<html lang="en-US">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<script>JAVASCRIPT ESTA SITUADO AQUÍ</script>
<title></title>
</head>
<body>
<script>JAVASCRIPT TAMBIÉN PUEDE IR AQUÍ</script>
</body>
```

### ¿Que diferencia hay entre una clase y una ID
El elemento "ID" es único y por tanto no se podrá repetir dentro del documento HTML. El elemento "clase" se puede repetir, eso es muy beneficioso cuando aplicamos los mismos estilos a diferentes elementos, puesto que permite reducir las líneas de código.

### código para hacer un enlace a otra página y que esta se abra en una nueva ventana
```html
<head>
</head>
<body>
	<a href="https://www.sport.es/">Sport</a>
</body>
```
### ¿Qué son las pseudoclases?, pon ejemplos.
Una pseudoclase es una palabra clave que se añade a los selectores y que especifica un estado especial del elemento seleccionado. Ejemplos:

:valid Esta pseudoclase ayuda al usuario a resaltar los campos correctos.
:fullscreen  se muestra cuando la pantalla está completa.
:disabled Representa a cualquier elemento que no está activado.
:focus Representa un elemento que ha sido enfocado, que se ha centrado en él y se activa cuando el usuario hace clic o toca un elemento.


### Explica el modelo de caja de CSS (margin, border y padding)
### Explica que son los selectores de CSS y pon ejemplos
### Di a quien afectan:
p a { color: red;
p > a { color: red; }
h1 + h2 { color: red }
a[class] { color: blue; }
a[class="externo"] { color: blue; }
a[href="http://www.ejemplo.com"] { color: blue; }
```html
