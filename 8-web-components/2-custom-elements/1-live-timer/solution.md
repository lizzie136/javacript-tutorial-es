
Por favor ten en cuenta:
1. Borramos el temporizador `setInterval` cuando el elemento es quitado del documento. Esto es importante, de otro modo continuará ejecutando aunque no se lo necesite más. Y el navegador no puede liberar la memoria asignada a este elemento.
2. Podemos acceder a la fecha actual con una propiedad `elem.date`. Todos los métodos de clase y propiedades son naturalmente métodos y propiedades del elemento.
