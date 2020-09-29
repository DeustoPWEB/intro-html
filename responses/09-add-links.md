## Paso 10: Add links to your list

✅ Check
✅ That
✅ Off your list!

Great job with lists. Let's try adding some links, shall we?

### About hyperlinks

Hyperlinks allow people to navigate through pages on the web. Links are achieved with the anchor tag, `<a>`, and have two major components: the location they link to, and the content that should be linked. The location of the link is specified as a `href` attribute, and the content that should be linked can be specified between the opening and closing tags, like this:

{% if GHE_HOST %}
  https://pages.{{ GHE_HOST }}/{{ user.login }}/{{ repo }}
        ```
      <li><a href="https://{{ GHE_HOST }}">This is a link to GitHub!</a></li>
      ```
{% else %}
      ```
      <li><a href="https://github.com">This is a link to GitHub!</a></li>
      ```
{% endif %}

### :keyboard: Actividad: Create links to your favorite sites

Aplica esta sugerencia de cambio, o sigue las instrucciones de abajo si prefieres teclear el código manualmente. Please note that the suggested change may not be in the proper place for your list, so make sure it is inside of a set of `<ol>` or `<ul>` tags.

```suggestion
      <li>My favorite site is <a href="https://github.com">GitHub</a>!</li>
```

1. Haz clic en **Files Changed**.
1. Haz clic en los puntos suspensivos (...) y selecciona **Edit file**.
1. In the list you just created, add a link to each of your favorite sites to their respective URLs. You can do this by adding an opening anchor tag `<a>` tag with `href` attribute with your favorite site's URL, the name of the site inside the anchor tag, and a closing anchor `</a>` tag. Here is an example of a list item with a link:

{% if GHE_HOST %}
        ```
      <li><a href="https://{{ GHE_HOST }}">This is a link to GitHub!</a></li>
      ```
{% else %}
      ```
      <li><a href="https://github.com">This is a link to GitHub!</a></li>
      ```
{% endif %}

1. En la sección _Commit changes_, introduce un mensaje de confirmación que describa lo que has hecho.
2. Haz clic en **Commit changes**.

<hr>
<h3 align="center">Responderé cuando haya detectado que has confirmado cambios en esta solicitud de extracción.</h3>
