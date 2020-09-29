## Paso 7: Añadir una imagen

¡Fantástico! Los encabezados te permiten resaltar algunos segmentos de tu página web. 

Hasta ahora, hemos visto etiquetas que se valen por sí solas. Sin embargo, a veces necesitamos especificar algún atributo, que es información que la etiqueta necesita para funcionar. Por ejemplo, para mostrar una imagen, necesitamos una etiqueta `<img>`, pero también necesitamos un atributo para la fuente (o _source_) de manera que el navegador sepa la ubicación de la imagen. Podemos añadir un atributo así:

```html
<img src="https://octodex.github.com/images/vinyltocat.png">
```

Te darás cuenta también de que la etiqueta de imagen no necesita cerrarse, dado que se considera una etiqueta [vacía](https://www.w3schools.com/html/html_elements.asp).

### :keyboard: Actividad: Añade una imagen a tu página web

Sigue las instrucciones para añadir una imagen. Puedes usar tu avatar de GitHub (sugerido abajo) o enlazar cualquier imagen de tu elección.

```suggestion
<img src="{{ user.avatarUrl }}">

```

1. Haz clic en **Files Changed**.
1. Haz clic en los puntos suspensivos (...) y selecciona **Edit file**.
2. Coloca una etiqueta `<img>` de apertura entre las etiquetas body. Recordatorio: ¡no necesitas cerrar una etiqueta `<img>`!
3. Establece el atributo `src` con la URL de la imagen que te gustaría mostrar. Puedes usar tu imagen de perfil de GitHub: `{{ user.avatarUrl }}`
4. En la sección _Commit changes_, introduce un mensaje de confirmación que describa lo que has hecho.
5. Haz clic en **Commit changes**.

<hr>
<h3 align="center">Responderé cuando haya detectado que has confirmado cambios en esta solicitud de extracción.</h3>
