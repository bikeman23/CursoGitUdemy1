@ Versión del curso
Version actual: V1.2.2

# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Cabecera underline 1
--------

Cabecera Underline 2
=====

# formatos de enfasis
- formato *itálica* de la primera forma.
- formato _itálica_ de la segunda forma.
- formato **bold** de la primera forma.
- formato __bold__ de la segunda forma.
- formato ~~tachado~~.

# Listas
1. Esto es un item
2. Esto es un item
3. Esto es un item

# Links
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link a index.html](index.html)

# Imágenes
![Logo Github](LogoGit)

 # Code Snippets
 Código en JSON
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

 código en JavaScripts
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

| Nombre | Apellido | Documento|
| ----- | ---- | ------ |
| Maxi | Burgos | 123154241|
| Tomas | Tompson | 12315421412 |

# Citas

Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.


Esto es otro texto que no se relaciona con la cita anterior:

>Esto es otra cita.

# Lineas divisoras
Esto es un texto que será dividido por guiones medios

---
Esto es otro texto dividido asteríscos

***
Esto es otro texto divido por guiones bajos

___

# Saltos de línea
Esto es nuestro primer parrafo. 

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
- Lista



