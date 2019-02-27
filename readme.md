# Criptobook

Notas a como se ha realizado la solución.

1.- Se ha incluido un pequeño fichero `criptobook.css` para mejorar el aspecto. Básicamente un clear: both para poder poner los botones a la derecha

2. El ciclo de petición respuesta es el siguiente:
    - GET nuevacompra con btnselected = 'Borrar'
    - Devuelve formulario de confirmación `confirmdelete``
    - POST `deletecompra` con `registroseleccionado``

3. He modificado views para refactorizar la lectura y modificación/delete del fichero. A estas alturas ya sabemos utilizar funciones de nivel superior. Es interesante revisar este código (sencillo y muy mejorable pero, al menos, evitamos repetir el bucle de lectura hasta encontrar el registro a borrar/modificar)


