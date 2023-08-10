# Versión
Verisón Actual: v1.2.0

# Cabezaceras
# Cabezacera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6


# Underlines
Cabecera H2 con Underline 1
---

Cabera H1 con Underline 2
===

# Formatos de ensafasis
- Formato de Letra *Italica* forma 1.
- Formato de letra _Italica_ forma 2.

- Formato de letra **bold o strong** forma 1.
- Formato de letra __bold o strong__ forma 1.

- Formato tachado

# Listas
## Lista ordenada
1. Esto es el primer item.
2. Esto es el segundo item.
3. Esto es el tercer item.
4. Esto es el cuarto item.
## Lista desordenada
- Esto es un item.
- Esto es un item.
- Esto es un item.
- Esto es un item.
- Esto es un item.

# Links
- <a href=http://google.com>Esto es un link formato HTML</a>
 - [Esto es un link en formato MARKDOWN](http://google.com)
 - [Esto es un link en formato codigo de prueba](prueba.cpp)

 # Imagenes
 ![Logo github](https://1000logos.net/wp-content/uploads/2021/05/GitHub-logo.png)

# CODE SNIPPETS
- Esto usa highlights.js 
- Codigo en JSON
``` JSON
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
- Código JavaScript
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
```

# Tablas
| Nombre | Primer Apellido | Edad | DNI |
| ------ | --------------- | ---- | --- |
| Alberto | Martínez | 24 | 1423423B |
| Gonzalo | Gómez | 24 | 22342343I |

# Citas
Esto es un texto referente a una cita que se añade debajo
> Esto es una cita. 

Esto es otro texto no relacionado con la cita anterior.

> Esto es una nueva cita.

# Líneas horizontales divisoras

Esto es un texto que se quiere seperar de los siguiente por una línea. Con ---

----
Esto es el siguiente texto que se quería separar. El siguiente se separa con ***

*** 
Esto es un tercer texto serparado. El siguiente con ___

___

# Saltos de línea entre parrafos simples
Parrafo 1.

Parrafo 2.

Parrafo 3.
