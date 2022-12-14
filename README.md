# Frontend Mentor

### Desafio - Todo app

![Todo app](./public/desktop-preview.jpg)

Esta es la solucion para [Todo app](https://www.frontendmentor.io/challenges/todo-app-Su1_KokOW). Frontend Mentor challenges te ayuda a mejorar tus habilidades en el Frontend.

## Table of contents β¨

- [Vision General](#vision-general-π)

- [Desafio](#desafio-π)

- [Links](#links-π)

- [Proceso](#proceso-π¨)

- [Proyecto](#proyecto-π)

- [Que aprendi](#que-aprendi-π‘)

- [Recursos utiles](#recursos-utiles-π)

- [Autor](#autor-π)

## Vision General π

### Desafio π

El Usuario deberia ser capaz de:

- Ver el diseΓ±o de manera optioma en ambas pantallas, escritorio y mobil.

- Ver todos los movimientos interactivos sobre los botones

- Cambios de temas

- Poder arrastrar los items y reordenarlos

- Guardar en local storage los datos cargados

### Links π

- URL de la solucion: [Github](https://github.com/gabrielteresczuk/todo-app) π

- URL del Sitio en Vivo: [Demo](https://gabrielteresczuk.github.io/todo-app/) π

## Proceso π¨

### Proyecto π

- Etiquetas semanticas de HTML 5

- Propiedades CSS propias

- Flexbox

- CSS Grid

- React Js

### Que aprendi π‘

Uso de Linear Gradient

```css
background: linear-gradient(135deg, #57ddff 0%, #c058f3 100%);
```

Linear gradient en TEXTOS

```css
.filters__color{
    background: -webkit-linear-gradient(45deg,#57ddff, #c058f3);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

```

Editar otros elemntos al hacer hover

```css
.item__cont:hover .item__cross{
    display:block;
}
```

comentar mejor el codigo con

```css
/*------------- COMENT --------------*/
```

Uso de Drag and Drop con

```js
<div className='item__cont' 
draggable 
onDragStart={()=>handleDragStart(index)} 
onDragEnter={()=>handleDragEnter(index)} 
onDragEnd={handleDragEnd}>
```

### Recursos Utiles π

- [w3schools](https://www.w3schools.com/css/) - Esta pagina es escencial para aprender lo basico de CSS.

- [Mdn Mozilla developer Network](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Grid_Layout) - MDN es el sitio de documentacion STANDART.

## Autor π

- Portfolio - [Portfolio](https://gabrielteresczuk.github.io/portfolio2/)

- Frontend Mentor - [@gabrielteresczuk](https://www.frontendmentor.io/profile/gabrielteresczuk)

- Linkedin - [in/gabriel-teresczuk](https://www.linkedin.com/in/gabriel-teresczuk/)