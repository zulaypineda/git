# Cabeceras
# cabecera H1
## cabecera H2
### cabecera H3
#### cabecera H4
##### cabecera H5
###### cabecera H6

# Underlines
Underline1
----------

Underline1
==========

# Formatos de enfasis
- formato *italica* de la primer forma
- formato _italica_ de la segunda forma
- formato **bold** o __strong__
- formato ~~tachado~~, formato normal
- aqui podemos usar formato *italico*, pero tambien **bold** y ~~tachado~~

# Listas
### Listas ordenadas
1. Esto es un item
1. Esto es un item
1. Esto es un item

### Listas no ordenadas
- Esto es un item
- Esto es un item
- Esto es un item

# Links
- <a href="http://www.google.com"> esto es un link html</a>
- [esto es un link en markdown](http://www.google.com)
- [esto es un link al index ](index.html)

# Imagenes
![Logo Github](https://1000marcas.net/wp-content/uploads/2020/02/GitHub-logo-1.jpg)

# Code Snippets
### Highlight.js
Codigo en Json
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```

Codigo en Javascript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas
| Nombre | Apellido | Documento |
|--------|----------|-----------|
| zuly | pineda | 19267152 |
| marvin | bernal | 18154154 |