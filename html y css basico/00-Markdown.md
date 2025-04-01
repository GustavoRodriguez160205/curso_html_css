# Curso de HTML - Resumen

## Estructura de una Etiqueta (45:48)
- Una etiqueta HTML se compone de:
  - Etiqueta de apertura (`<etiqueta>`)
  - Contenido
  - Etiqueta de cierre (`</etiqueta>`)
- Algunas etiquetas no requieren cierre (`<img>`, `<br>`, `<input>`).

## Estructura de una Página Web (51:58)
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Web</title>
</head>
<body>
    <h1>Bienvenidos a mi página</h1>
</body>
</html>
```

## Párrafos y Encabezados (1:00:09)
- Encabezados: `<h1>` a `<h6>` (de mayor a menor importancia).
- Párrafos: `<p>` para textos.

```html
<h1>Título Principal</h1>
<h2>Subtítulo</h2>
<p>Este es un párrafo con contenido.</p>
```

## Listas (1:10:45)
- Listas ordenadas (`<ol>`) y no ordenadas (`<ul>`).
- Elementos de lista: `<li>`.

```html
<ul>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
</ul>

<ol>
    <li>Primer ítem</li>
    <li>Segundo ítem</li>
</ol>
```

## Enlaces (Básico) (1:26:09)
- Se usa `<a>` con el atributo `href` para definir un enlace.

```html
<a href="https://www.google.com" target="_blank">Ir a Google</a>
```

## Imágenes y Rutas (1:41:40)
- Se usa `<img>` con los atributos `src` y `alt`.
- Rutas absolutas y relativas.

```html
<img src="imagen.jpg" alt="Descripción de la imagen">
```

## Formularios (1:50:00)
- Se usa `<form>` para recopilar información del usuario.
- Controles básicos: `<input>`, `<textarea>`, `<button>`.

```html
<form action="/procesar" method="post">
    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="nombre" required>
    <button type="submit">Enviar</button>
</form>