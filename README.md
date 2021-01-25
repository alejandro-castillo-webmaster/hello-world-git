# CABECERAS

# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
#### Cabecera H6

# Underline

UNDERLINE 1
---------------

UNDERLINE 2
==============

# Formato de enfasis
- Formato *italica* de la primera forma
- Formato _italica_ de la segunda forma
- Formato **bold o strong** de la primera forma
- Formato __bold o strong__ de la primera forma
- Formato ~~tachado~~


# Listas

1. Este es un item de una lista ordenada
2. Este es un item de una lista ordenada
3. Este es un item de una lista ordenada
4. Este es un item de una lista ordenada
5. Este es un item de una lista ordenada


# Listas desordenadas

- Este es un item de una lista desordenada
- Este es un item de una lista desordenada
- Este es un item de una lista desordenada
- Este es un item de una lista desordenada
- Este es un item de una lista desordenada


# Links

- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link de MarkDown](http://www.google.com)
- [Esto es un link al Index con MarkDown](index.html)


# Imágenes

![LogodeGitHub](https://1000logos.net/wp-content/uploads/2018/11/GitHub-logo.png)


# Code Snippets
### json
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

### html
```HTML
<!DOCTYPE html>
<title>Title</title>

<style>body {width: 500px;}</style>

<script type="application/javascript">
  function $init() {return true;}
</script>

<body>
  <p checked class="title" id='title'>Title</p>
  <!-- here goes the rest of the page -->
</body>
```

### JavScript
```JavaScript
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
| nombre | Apellido | Documento |
|--------|----------|-----------|
| Nombre Prueba | Apellido Prueba| Documento de prueba|
| Nombre Prueba | Apellido Prueba| Documento de prueba|
| Nombre Prueba | Apellido Prueba| Documento de prueba|
| Nombre Prueba | Apellido Prueba| Documento de prueba|



# Citas

Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita

Esto es otro texto, que no tiene nada que ver con la cita anterior
> Esto es otra cita



# Lineas horizontales o divisorias

Esto es un texto de prueba dividido por ---

---

Esto es un texto de prueba dividido por ***

******

Fin de los textos de prueba dividido por ___

___


# Saltos de línea

Esto es nuestro primer parrafo

Esto es nuestro segundo parrafo

Este es nuestro tercer parrafo
- Item 1
- Item 2
- Item 3
- Item 4








