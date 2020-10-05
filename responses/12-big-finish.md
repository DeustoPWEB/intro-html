### Enseña al mundo tu página terminada

Bien hecho @{{ user.username }}, aquí tienes el resultado terminado: {{ pagesUrl }}

Has aprendido lo más básico de HTML, y lo has usado para generar una página web sencilla. 

Aunque esto funciona, hay mucho más que puedes hacer para asegurarte de estar al día con los estándares de desarrollo web, como usar un validador de HTML.

{% if GHE_HOST %}
<h3 align="center"><a href="https://validator.w3.org/nu/?showsource=yes&doc=https://pages.{{ GHE_HOST }}/{{ user.login }}/{{ repo }}/">Ver validación</a></h3>
{% else %}
<h3 align="center"><a href="https://validator.w3.org/nu/?showsource=yes&doc=https://{{ user.login }}.github.io/{{ repo }}">Ver validación</a></h3>
{% endif %}


Si quieres, puedes convertir tu flamante nueva página en la página de inicio por defecto de tu navegador. Simplemente sigue los enlaces de aquí abajo para más información:

- [Google Chrome](https://support.google.com/chrome/answer/95314?hl=en)
- [Safari](https://support.apple.com/guide/safari/set-your-homepage-ibrw1020/mac)
- [Firefox](https://support.mozilla.org/en-US/kb/how-to-set-the-home-page)
- [Microsoft Edge](https://support.microsoft.com/en-us/help/4027577/windows-change-your-home-page)
