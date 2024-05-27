# Proyecto de Carrusel de Reseñas

## Descripción del Proyecto

Este proyecto es un carrusel de reseñas que permite a los usuarios navegar a través de un conjunto de reseñas y ver la información de cada una, incluyendo el nombre, el trabajo, la imagen y el texto de la reseña.

## Lógica del Código

El proyecto utiliza JavaScript para manipular el DOM y mostrar diferentes reseñas basadas en la interacción del usuario. Al cargar la página, se muestra la primera reseña en el conjunto de datos. Los usuarios pueden navegar a través de las reseñas utilizando los botones "next" y "prev". También pueden ver una reseña aleatoria al hacer clic en el botón "random".

## Navegación a través de las Reseñas

Los usuarios pueden navegar a través de las reseñas utilizando los botones "next" y "prev". Al hacer clic en "next", se muestra la siguiente reseña en el conjunto de datos. Si ya se está mostrando la última reseña, se vuelve a la primera. De manera similar, al hacer clic en "prev", se muestra la reseña anterior, y si ya se está mostrando la primera reseña, se va a la última.

## Generación de Reseñas Aleatorias

Al hacer clic en el botón "random", se selecciona una reseña aleatoria del conjunto de datos y se muestra al usuario.

## Agregar o Modificar Reseñas

Las reseñas se almacenan en una matriz de objetos en el código JavaScript. Para agregar una nueva reseña, puedes agregar un nuevo objeto a esta matriz con las propiedades `id`, `name`, `job`, `img` y `text`. Para modificar una reseña existente, puedes buscar el objeto correspondiente en la matriz y cambiar sus propiedades.
