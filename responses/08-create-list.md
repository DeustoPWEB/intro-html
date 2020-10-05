## Paso 9: Crea una lista

Puedes ver tu sitio con la nueva foto en: {{ pagesUrl }}

> Nota: A veces puede llevar unos minutos a GitHub Pages recargar un sitio. Si tus cambios todavía no se visualizan pasados unos minutos, puedes intentar borrar la caché de tu navegador y actualizar la página.

### Listas ordenadas y desordenadas

Las listas se usan por todo internet. Las hay de dos tipos: ordenadas y desordenadas.

1. Esto
2. Es una
3. Lista ordenada

Y...

- Esto
- Es una
- Lista desordenada

Puedes crear listas usando la etiqueta `<ol>` para listas ordenadas, y la etiqueta `<ul>` para listas desordenadas. Después, cada elemento de la lista debe rodearse de etiquetas `<li>`, o _list item_. Aquí tienes el código que genera la lista que te he enseñado más arriba:

```html
<ol>
    <li>Esto</li>
    <li>Es una</li>
    <li>Lista ordenada</li>
</ol>
```

And...

```html
<ul>
    <li>Esto</li>
    <li>Es una</li>
    <li>Lista desordenada</li>
</ul>
```

Para el siguiente ejercicio vas a crear una lista de tus sitios web favoritos. Después añadiremos enlaces, de forma que puedas acceder a esos sitios rápidamente. Por ahora, céntrate en crear los elementos de la lista.

### :keyboard: Actividad: Crea una lista de tus sitios favoritos

1. Edita el archivo `index.html` en tu rama master [usando este enlace directo]({{ repoUrl }}/edit/master/index.html) o yendo a la pestaña **Code**, haciendo clic en el archivo `index.html` y haciendo clic en el lápiz :pencil: para editar el HTML.
1. Dentro de la etiqueta body, crea una lista, ordenada o desordenada, de tus sitios favoritos en internet.
1. En la sección _Commit changes_, introduce un mensaje de confirmación que describa lo que has hecho.
1. Asegúrate de que has seleccionado _Create a new branch for this commit and start a pull request_.
1. Pon un nombre descriptivo a tu rama, como `add-links-and-lists`.
1. Haz clic en **Commit changes**.
1. Pon un título a tu solicitud de extracción, y un mensaje descriptivo.
1. Haz clic en **Create pull request.**

<hr>
<h3 align="center">Busca mi respuesta en tu nueva solicitud de extracción</h3>
