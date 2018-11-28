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
            background:#FFFFFF;
        }
    </style>
</head>
...
```
css embebido
```html
<p>¡Hola <span style="color:#FF0000">amigo lector</span>!</p>
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
### ¿Que diferencia hay entre una clase y una ID
### código para hacer un enlace a otra página y que esta se abra en una nueva ventana
### ¿Qué son las pseudoclases?, pon ejemplos.
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
