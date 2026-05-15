# Solemne-II
Sistema interactivo óptico

Autor: Elena Fonseca
Curso: Pensamiento Computacional

## Descripción objetiva

El proyecto consiste en un sistema visual interactivo desarrollado en p5.js basado en patrones geométricos repetitivos.

En pantalla se observa una grilla de figuras (circulos y cuadrados) superpuestas en distintas capas de color que van cambiando dependiendo si el raton se se mueve al lado izquierdo o al derecho. Cada capa posee un leve desfase horizontal y un cambio de color, generando vibración óptica y mezcla cromática.

El sistema responde continuamente al movimiento horizontal y vertical del mouse:
- el eje X cambio de figura, modifica el tamaño y reorganización cromática
- el eje Y modifica la separación entre módulos

## Composición
La composición cambia en tiempo real generando ilusiones visuales dinámicas.

El proyecto explora principios del Op Art y del diseño generativo mediante sistemas computacionales reactivos.
Aquí los referentes de color y referentes visuales:

![COLOR](<img width="768" height="534" alt="ilusion-optica-768x534" src="https://github.com/user-attachments/assets/d9074da8-aea4-47d5-a6bd-a82d452a8e10" />)
https://es.pinterest.com/pin/800514902486425261/
![PROCESO DE COLOR](<img width="897" height="817" alt="proceso de color" src="https://github.com/user-attachments/assets/885e7bb4-b90c-4f5d-8c38-b8d6aba3f1d8" />)


![EFECTOS VISUALES1](<img width="280" height="180" alt="images" src="https://github.com/user-attachments/assets/b25d428b-c590-41e9-8ddc-265339e56e56" />)
https://www.oftalvist.es/blog/ilusiones-opticas
![EFECTOS VISUALES2](<img width="225" height="225" alt="download" src="https://github.com/user-attachments/assets/9ffd6740-167b-47a1-980e-a8912de2e601" />)
https://depositphotos.com/es/vector/illustration-of-black-and-white-phenomenal-optical-illusion-3d-effect-moving-circle-vector-illustration-121384622.html


La obra toma como referencia la repetición geométrica, el contraste cromático y las ilusiones ópticas presentes en artistas como Victor Vasarely y Bridget Riley.

En lugar de reproducir una imagen estática, el proyecto traduce estas lógicas visuales a un sistema dinámico basado en reglas, variaciones y respuesta al input del usuario.

El desfase entre capas de color produce vibración visual y percepción de movimiento.

### Inputs

- MouseX:
  Cambia las figuras dependiendo de su posición, controla el tamaño de las figuras y cambia el orden cromático del sistema.

- MouseY:
  Controla la distancia entre elementos de la grilla.
  
### Outputs

El resultado visual es una composición dinámica que genera:
- vibración óptica
- mezcla cromática
- sensación de movimiento
- transformación constante del patrón geométrico

### Procesos

El sistema utiliza bucles para generar múltiples capas geométricas repetidas.

Cada capa de color se desplaza horizontalmente 5 pixeles, empezando desde el 0, para crear un desfase óptico.
![DESFACE DE CAPAS](<img width="513" height="811" alt="desface de capas" src="https://github.com/user-attachments/assets/f9194444-5a8f-448d-b25d-669600ef8c4d" />)

La función map() transforma la posición del mouse en cambios de tamaño y separación.
![MAP](<img width="415" height="62" alt="ESPACIO" src="https://github.com/user-attachments/assets/932d2c70-0db7-4129-927d-b4101246c21b" />)

Condicionales permiten alterar el orden de los colores dependiendo de la posición horizontal del cursor.
![PROCESO DE CLASE ANTERIOR(CAMBIO CROMÁTICO)](<img width="1228" height="463" alt="cambio de color eje x" src="https://github.com/user-attachments/assets/bfbfda55-ac26-4351-9e9f-8ed1c72a3250" />)

Cambio de forma dependiendo de la posición del mouse.
![Cambio de forma](<img width="805" height="671" alt="cambio de forma" src="https://github.com/user-attachments/assets/3fcd4b6b-a526-482b-a0e2-4aa11783ed9a" />)

![Forma Cuadrada](<img width="352" height="111" alt="FORMA CUADRADA" src="https://github.com/user-attachments/assets/970cc293-6e0c-48d8-9c90-d0e7ebaeb7eb" />)

![Forma Circular](<img width="354" height="105" alt="FORMA CIRCULAR" src="https://github.com/user-attachments/assets/2f84b686-8167-4cea-af4b-93f9663af067" />)
