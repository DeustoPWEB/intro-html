## Paso 10: Añade enlaces a tu lista

✅ Marca 
✅ eso como
✅ completado en tu lista!

Buen trabajo con la lista. Vamos a añadir algunos enlaces, ¿te parece?

### Sobre los hipervínculos

Los hipervínculos permiten a las personas navegar a través de las páginas de la web. Los enlaces se consiguen con la etiqueta ancla, `<a>`, y tienen dos componentes principales: la ubicación a la que enlazan, y el contenido que debería enlazarse. La ubicación del enlace se especifica en un atributo `href`, y el contenido que debería enlazarse se ubica entre las etiquetas de apertura y cierre, así:

{% if GHE_HOST %}
  https://pages.{{ GHE_HOST }}/{{ user.login }}/{{ repo }}
        ```
      <li><a href="https://{{ GHE_HOST }}">Esto es un enlace a GitHub</a></li>
      ```
{% else %}
      ```
      <li><a href="https://github.com">Esto es un enlace a GitHub</a></li>
      ```
{% endif %}

### :keyboard: Actividad: Crea enlaces a tus sitios favoritos

Aplica esta sugerencia de cambio, o sigue las instrucciones de abajo si prefieres teclear el código manualmente. Ten en cuenta que el cambio sugerido puede no estar en el lugar correcto de tu lista, así que asegúrate de que está dentro de un conjunto de etiquetas `<ol>` o `<ul>`.

```suggestion
      <li>Mi sitio favorito es <a href="https://github.com">GitHub</a></li>
```

1. Haz clic en **Files Changed**.
1. Haz clic en los puntos suspensivos (...) y selecciona **Edit file**.
1. En la lista que acabas de crear, añade un enlace a cada uno de tus sitios favoritos hacia sus respectivas URLs. Puedes hacer esto añadiendo una etiqueta de apertura `<a>` con un atributo `href` con la URL de tu sitio favorito, el nombre del sitio dentro de la etiqueta de ancla, y una etiqueta `</a>` de cierre. Aquí tienes un ejemplo de un elemento de lista con un enlace:

{% if GHE_HOST %}
        ```
      <li><a href="https://{{ GHE_HOST }}">Esto es un enlace a GitHub</a></li>
      ```
{% else %}
      ```
      <li><a href="https://github.com">Esto es un enlace a GitHub</a></li>
      ```
{% endif %}

1. En la sección _Commit changes_, introduce un mensaje de confirmación que describa lo que has hecho.
2. Haz clic en **Commit changes**.

<hr>
<h3 align="center">Responderé cuando haya detectado que has confirmado cambios en esta solicitud de extracción.</h3>
