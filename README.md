# 100LMSGIUnidad3
Unidad 3 Manipulación de documentos web

## TEORÍA
## Seleccionar elementos en el DOM
1. Método tradicional

| **Método de Búsqueda**              | **Descripción**                                   | **Si no lo encuentra...**              |
|--------------------------------------|--------------------------------------------------|-----------------------------------------|
| `.getElementById(id)`               | Busca un elemento HTML por su **id**.           | Devuelve **uno** o `null`.             |
| `.getElementsByClassName(class)`    | Busca elementos con la **clase** `class`.       | Devuelve una **lista de nodos `[]`**.  |
| `.getElementsByName(value)`         | Busca elementos con el **atributo `name`**.     | Devuelve una **lista de nodos `[]`**.  |
| `.getElementsByTagName(tag)`        | Busca elementos por su **etiqueta HTML**.       | Devuelve una **lista de nodos `[]`**.  |

2. Metodos modernos de búsqueda
   
| **Método de Búsqueda**       | **Descripción**                                                 | **Si no lo encuentra...** |
|------------------------------|-----------------------------------------------------------------|---------------------------|
| `.querySelector(sel)`        | Busca el **primer** elemento que coincide con el selector CSS `sel`. | Devuelve `null`.          |
| `.querySelectorAll(sel)`     | Busca **todos** los elementos que coinciden con el selector CSS `sel`. | Devuelve `[]`.            |


### Modificar el contenido DOM

| **Propiedad**       | **Descripción**                                                                          |
|---------------------|----------------------------------------------------------------------------------------|
| `STRING .nodeName`  | Devuelve el nombre del nodo. **Sólo lectura**.                                         |
| `STRING .textContent` | Devuelve (o cambia) el contenido de texto del elemento.                              |
| `STRING .innerText`  | Devuelve (o cambia) el contenido de texto renderizado (tiene en cuenta los estilos CSS). |
| `STRING .outerText`  | Igual a `.innerText`, pero al reemplazar también reemplaza la etiqueta contenedora.   |
