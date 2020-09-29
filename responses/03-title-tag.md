## Paso 4: Añade un título a la página

¡Tu página web empieza a tomar forma! Las etiquetas HTML y body son importantes, pero su efecto no es muy visible. A continuación haremos un cambio visible, dándole un título a tu página. El título de tu página se mostrará en la barra de título de tu navegador, o como título de la pestaña que tengas abierta. ¡El título se utiliza en todo tipo de sitios!

![a screenshot of the title on a browser tab](https://user-images.githubusercontent.com/16547949/41006294-e990b476-68ee-11e8-8cfa-67c72c132095.png)

La etiqueta de título tiene este aspecto:

```html
<title>Soy un título</title>
```

Pero la etiqueta de título debe estar dentro de una etiqueta head. Por ahora, te habrás dado cuenta de que las etiquetas tienen una estructura jerárquica. En nuestro ejemplo anterior, la etiqueta `html` era padre de la etiqueta `body`. Similarmente, la etiqueta `head` será padre de la etiqueta `title` así:

```html
<head>
    <title>Soy un título</title>
</head>
```

Finalmente, las etiquetas `head` y `title` son hijas de la etiqueta `html`, pero hermanas de la etiqueta `body`.

```html
<html>
    <head>
        <title>Soy un título</title>
    </head>

    <body>
        Un contenido.
    </body>
</html>
```

### :keyboard: Actividad: Titula tu página

Aplica esta sugerencia de cambio, o sigue las instrucciones de abajo si prefieres teclear el código manualmente.

```suggestion
    <head>
        <title>Mi estupenda página web</title>
    </head>

```

1. Haz clic en **Files Changed**.
1. Haz clic en los puntos suspensivos (...) y selecciona **Edit file**.
2. Coloca una etiqueta `<head>` de apertura y una etiqueta `<title>` de apertura después de la primera etiqueta `html` de apertura, pero antes de la etiqueta `body` .
3. Escribe tu título después de la etiqueta `title` de apertura.
4. Coloca una etiqueta `</title>` de cierre y una etiqueta `</head>` de cierre después de tu nuevo título, pero antes de la etiqueta `body`. 
5. En la sección _Commit changes_, introduce un mensaje de confirmación que describa lo que has hecho.
6. Asegúrate de que has seleccionado _Commit directly to the `add-index` branch_.
7. Haz clic en **Commit changes**.

<hr>
<h3 align="center">Responderé cuando haya detectado que has confirmado cambios en esta solicitud de extracción.</h3>