# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

El desafio consiste en maquetar una tarjeta centrada, la tarjeta no tiene diferencias en el diseño al cambiar el dispositivo (desktop o mobile).

### Screenshot

![Captura de la solución](/images/captura.png)

### Links

- Solution URL: [Repositorio](https://github.com/JoseFGuzman/Frontend-Mentor-1.git)
- Live Site URL: [GitHub Page](https://JoseFGuzman.github.io/Frontend-Mentor-1/)

## My process

Paso 1: Dividimos el diseño en cajas o contenedores.
![Paso 1](/images/paso-1.png)

Paso 2: Estructura HTML.
![Paso 2](/images/paso-2.png)

Paso 3: CSS.
Una vez que tenemos el html lo siguiente es el CSS pero antes de empezar a escribir codigo definimos especificaciones a tener en cuenta para cada caja o contenedor.
![Paso 3 - a](/images/paso-3a.png)
En este desafio la tarjeta debia tener un ancho especifico de 320px, por que se decidio trabajar con box-sizing: border-box para que el padding estuviera contemplado en esa medida. Eso dejaria el ancho del contenido de la tarjeta en (320px - padding), ancho que seria el width de la imagen QR (width: 100%).
![Paso 3 - a](/images/paso-3b.png)

En este caso se decidio trabajar con la metodoligía BEM.

### Built with

- Semantic HTML5 markup
- Flexbox
- Metodología BEM

## Author

- Website - [Perfil GitHub](https://github.com/JoseFGuzman)
- Frontend Mentor - [@JoseFGuzman](https://www.frontendmentor.io/profile/JoseFGuzman)
