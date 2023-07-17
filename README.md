# SpreadSheets con React. 

### Desplegada en Netlify. [Link here](https://googlesheetsdb.netlify.app/)

Utilizando Google Sheets como base de datos y empleando una petición Fetch para interactuar con ella, se pueden obtener los datos almacenados en la hoja de Google Sheets y mostrarlos en el *DOM* de manera dinámica con React.

![petición Fetch](https://github.com/oyham/SpreadSheets-con-React/assets/97111287/ed14a48d-9e09-4999-8709-22cf5d615a9d)

Cada dato que obtengo de Google Sheets se presenta en forma de tarjeta (card), lo cual facilita la visualización y el acceso a la información. Además, para mejorar la experiencia del usuario, se añade un carrusel utilizando la biblioteca Swiper, lo que permite desplazarse de manera fluida entre las diferentes tarjetas, ademas de un modal para añadir información extra si se es requerido. 

Esta integración entre ``Google Sheets, React y Swiper`` permite aprovechar la funcionalidad de hojas de cálculo de Google como una base de datos en *`tiempo real`* para la web. De esta manera, se puede mantener actualizada la información de forma sencilla y presentarla de manera atractiva a través de tarjetas y un carrusel interactivo.

![hoja de google](https://github.com/oyham/SpreadSheets-con-React/assets/97111287/0d829450-d9fd-431c-94d4-d1da25dac65c)

Para las imágenes que se muestran en las tarjetas, actualmente estoy utilizando imágenes de ejemplo que he extraído de Google mediante la copia de la URL de la imagen. Sin embargo, en un futuro cercano, planeo incorporar la ``API de Google Drive`` para mejorar aún más el proceso.

La finalidad de esta mini proyecto es crear una base de datos _``facil de leer y de modificar por el cliente final``_, o diferentes usuarios que tengan el acceso a la hoja de google, lo que permite gestionar de manera mas sencilla y en tiempo real los datos. 
