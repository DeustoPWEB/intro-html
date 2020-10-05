## Paso 12: Hazlo bonito

Puede que te estés preguntando por qué tu página no se ve exactamente como el modelo que te enseñé al principio. Es porque HTML aporta estructura a tus páginas web, pero las etiquetas simples que has aprendido hasta ahora no indican al navegador cómo quieres que se muestre cada elemento.

La apariencia de cada elemento en la página se define a través de estilos, y es objeto de otro curso. Por ahora, he añadido una [hoja de estilos]({{ repoUrl }}/blob/add-style/style.css) por ti. 

Para que tu página web utilice la nueva hoja de estilos, solamente necesitas enlazarla desde dentro de la etiqueta `<head>` en tu archivo `index.html`. Si incluyes el siguiente enlace en tu archivo `index.html`, tu página web empezará a usar el archivo css que hará que tu sitio se vea genial.

```html
  <link rel="stylesheet" href="style.css">
```

A modo de ejemplo, tu archivo `index.html` podría tener este aspecto:

```html
    <head>
        <title>Soy un título</title>
        <link rel="stylesheet" href="style.css">
    </head>
```

### :keyboard: Actividad: Crea un estilo para tu sitio

1. Edita el archivo `index.html` en la rama `add-style` [usando este enlace directo]({{ repoUrl }}/edit/add-style/index.html) o yendo a la pestaña **Code**, seleccionando la rama `add-style`, haciendo clic en el archiv `index.html`, y haciendo clic en el lápiz :pencil: para editar.
1. Entre las etiquetas `<head>`, añade lo siguiente: `<link rel="stylesheet" href="style.css">`.
1. En la sección _Commit changes_, introduce un mensaje de confirmación que describa lo que has hecho.
1. Haz clic en **Commit changes**.

<hr>
<h3 align="center">Responderé cuando haya detectado que has confirmado cambios en esta solicitud de extracción.</h3>