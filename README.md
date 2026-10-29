# Portafolio Interactivo

Página desarrollada para mi Práctica Calificada 3 del curso **Hojas de Estilo en Cascada Avanzado**.

Utilicé **Bootstrap 5** para organizar la navegación, las columnas y el formulario de contacto. La página presenta tres proyectos de Chilete DevPath y se adapta a escritorio, tablet y celular.

## Efectos CSS

- **Rotación 2D:** la primera tarjeta gira con `rotate(3deg)`.
- **Escalado 2D:** la segunda tarjeta aumenta de tamaño con `scale(1.055)`.
- **Traslación 2D:** la tercera tarjeta sube con `translateY(-14px)`.
- **Transiciones:** las tres tarjetas usan `transition` para suavizar los cambios al pasar el cursor.
- **Transformación 3D:** la imagen del inicio gira con `rotateX(8deg)` y `rotateY(180deg)`. El contenedor usa `perspective` y la tarjeta `transform-style: preserve-3d`.
- **Animación personalizada:** `@keyframes entrada-suave` hace aparecer el contenido principal desplazándolo hacia arriba.
- **Loader:** `@keyframes giro-carga` mantiene en movimiento el indicador circular del inicio.

## Estructura

- `index.html`: estructura de la página y componentes Bootstrap.
- `css/estilos.css`: estilos, transformaciones, transiciones y animaciones.
- `js/main.js`: comportamiento del formulario de prueba y cierre del menú móvil.
- `img/`: fotografías y logotipo de Chilete DevPath.
- `vendor/`: copia local de Bootstrap 5 como respaldo del CDN.

## Cómo abrir el proyecto

Abrir `index.html` en el navegador o ejecutarlo con **Live Server** desde Visual Studio Code. Los archivos de Bootstrap también están incluidos para que la página pueda abrirse sin conexión.

El formulario verifica los campos, pero **no envía mensajes** porque el proyecto no incluye un servidor de correo.

**Autor:** Chilete DevPath by Adrian Pisco **Sitio:** https://chiletedevpath.com/
