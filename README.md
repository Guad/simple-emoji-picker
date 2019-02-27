# simple-emoji-picker

This is just a simple emoji picker for `input` and `textarea` elements.

## Usage

Just reference the CSS and the javascript file at the end of the document. Then wrap any input you want to add a picker to with `<div class="emojipicker-container">`. That's it! 

````
<html>
  <head>
    <link rel="stylesheet" type="text/css" href="/css/emoji.css"/>
  </head>
  <body>
    ...
    <script src="/js/emoji.js"></script>
  </body>
</html>
````


If you dynamically generate elements, call `emojipicker(options)` where `options` is a dictionary.

````
emojipicker({
    'el': document.getElementById('my-input'),
    'categories': ['Personas', 'Naturaleza', 'Comida', 'Actividades', 'Lugares', 'Objetos', 'Símbolos', 'Banderas'] // Optional, for translation
});
````
