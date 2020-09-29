## Paso 12: Make it beautiful

You may be wondering why your page hasn't looked exactly the same as the sample I showed in the beginning. That's because HTML gives your webpage structure, but the simple tags you have learned so far don't tell the web browser how you want each page element to appear. 

The appearance of each page element is defined through styles and is the subject of another course. For now, I have added [a stylesheet]({{ repoUrl }}/blob/add-style/style.css) for you. 

For your webpage to use your new stylesheet, you just need to link it within the `<head>` of your `index.html` file. If you include the following link in your `index.html` file, your webpage will begin using the css file to make your website look awesome!

```html
  <link rel="stylesheet" href="style.css">
```

As an example, your `index.html` file might look like this:

```html
    <head>
        <title>I am a title!</title>
        <link rel="stylesheet" href="style.css">
    </head>
```

### :keyboard: Actividad: Create a style to your site

1. Edit the `index.html` file in the `add-style` branch by [usando este enlace directo]({{ repoUrl }}/edit/add-style/index.html) o yendo a la pestaña **Code**, selecting the `add-style` branch, clicking on the `index.html` file, and clicking the pencil :pencil: to edit.
1. Between the `<head>` tags, add the following `<link rel="stylesheet" href="style.css">`.
1. En la sección _Commit changes_, introduce un mensaje de confirmación que describa lo que has hecho.
1. Haz clic en **Commit changes**.

<hr>
<h3 align="center">Responderé cuando haya detectado que has confirmado cambios en esta solicitud de extracción.</h3>