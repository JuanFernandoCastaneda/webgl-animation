# webgl-animation

Hola profesor (o monitore), buen día.

El método de envío que elegí para este proyecto fue dictado por la falta de tiempo que tenía para realizarlo antes de la fecha límite. Enviar un link de Github me permitía modificarlo incluso después de entregado. Espero que esto no sea un inconveniente muy grande :)

De todas maneras, aquí encuentra el Fiddle más actualizado del proyecto para su despliegue real (antes de las 12) 
https://jsfiddle.net/MightopitaGuy/gu50tbna/1/ 

ACTUALIZACIÓN: este es el link final, después de las 12 (específicamente 12:41 a.m.), pero que espero sea calificado :)
https://jsfiddle.net/MightopitaGuy/gu50tbna/5/

## Lógica

La forma en que funciona el programa es que se cargan los datos del archivo de caminar desde el link de Github. Luego de estar cargado, se convierte el archivo en un arreglo, en que cada 67 posiciones representan una fila de una matriz. Como eventualmente me di cuenta de que cada 3 columnas era un punto X-Y-Z, pinté todas las articulaciones en cada segundo con un único objeto Person que trasladaba de un lado a otro.

Si se quiere modificar la cantidad de tiempo a mostrar de la animación, se debe modificar la variable "tiempo_máximo", que en este momento por defecto está puesta en 200.

## Resultado
<img width="443" alt="image" src="https://user-images.githubusercontent.com/26715082/190842222-25fb165b-6ae8-4b38-933f-767c22df5685.png">
<img width="447" alt="image" src="https://user-images.githubusercontent.com/26715082/190842230-2b987e95-efac-466c-aebb-7f60fb71ee17.png">
<img width="445" alt="image" src="https://user-images.githubusercontent.com/26715082/190842226-d9adeee2-995b-43fe-8e65-24dfe2f451a7.png">
