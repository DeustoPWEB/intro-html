## Paso 3: Añade estructura HTML al documento

¡Buen trabajo abriendo una solicitud de extracción, @{{ user.username }}! Me he adelantado y he cerrado tu [anterior incidencia]({{ welcomeLink }}). 

Esta solicitud de extracción contiene algo de contenido, pero no tiene nada de la estructura HTML que le dice al navegador cómo estructurar el contenido. Todas las páginas creadas con HTML deben contener ciertas etiquetas que las identifican como tales. Las etiquetas tienen este aspecto:

```html
<html>
    <body>
        El contenido HTML va aquí.
    </body>
</html>
```

Puede que veas que hay dos copias de la etiqueta HTML, y otras dos copias de la etiqueta body. Llamamos a éstas etiquetas de _apertura_ y de _cierre_. Vamos a ver el mismo código, pero añadiendo una pequeña explicación.

- `<html>` es la etiqueta HTML de apertura
- `<body>` es la etiqueta body de apertura
- `</body>` es la etiqueta body de cierre
- `</html>` es la etiqueta HTML de cierre

En HTML, el espaciado realmente no importa. Hemos añadido algunas tabulaciones para que el código sea más fácil de leer, pero el navegador ignorará el espaciado adicional. Ahora que entiendes las piezas principales de HTML, vamos a añadir HTML al archivo `index.html` de tu proyecto.

### :keyboard: Actividad: Añade las etiquetas `html` y `body` al archivo `index.html`

Aplica esta sugerencia de cambio, o sigue las instrucciones de abajo si prefieres teclear el código manualmente.

```suggestion
<html>

  <body>
    ¡Hola, persona estupenda! 
  </body>

</html>
```

1. Haz clic en **Files Changed** para ver el archivo `index.html` recién añadido.
2. Haz clic en los puntos suspensivos (...) y selecciona **Edit file**.
3. Antes del contenido existente, añade una etiqueta `<html>` de apertura, y una etiqueta `<body>` de apertura.
4. Después del contenido existente, añade una etiqueta `</body>` de cierre, y una etiqueta `</html>` de cierre.
5. En la sección _Commit changes_, introduce un mensaje de confirmación que describa lo que has hecho.
6. Asegúrate de que has seleccionado _Commit directly to the `add-index` branch_.
7. Haz clic en **Commit changes**.

<hr>
<h3 align="center">Responderé cuando haya detectado que has confirmado cambios en esta solicitud de extracción.</h3>