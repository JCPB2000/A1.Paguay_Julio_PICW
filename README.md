# Parte 1: Crea tu primera página HTML

## HTML

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Actividad 1</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Universidad de las Fuerzas Armadas ESPE</h1>
    <img src="espe.png" alt="Imagen de mi actividad">
   
    <section>
        <h2>Datos de la actividad</h2>
        <p><strong>Modalidad:</strong> En línea</p>
        <p><strong>Grado:</strong> Ingeniería en Tecnologías de la Información</p>
        <p><strong>Asignatura:</strong> Programación Integrativa de Componentes Web</p>
        <p><strong>Actividad:</strong>  Primer Parcial</p>
        <p><strong>Estudiante:</strong> Julio Paguay</p>
        <p><strong>Tutor:</strong> Ing. Criollo Chanchicocha Vilmer David</p>
        <p><strong>NRC:</strong> 23407</p>
        <p><strong>Fecha:</strong> 07/05/2025</p>
        Enlace: <a href="https://youtu.be/q8fK4La_jmM?si=kNa78kXA6yhRAxfo" target="_blank"> Youtube </a>
    </section>
</body>
</html>
```

#CSS
```css
body {
    text-align: center;
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;


img {
    max-width: 300px;
    margin: 20px 0;
}


a {
    display: inline-block;
    margin-top: 10px;
    text-decoration: none;
    color: #0077cc;
    font-weight: bold;
}
}
```

La imagen diseñada está estructurada con un encabezado principal que presenta el nombre completo de la Universidad de las Fuerzas Armadas ESPE, seguido de una imagen institucional (logo oficial). Debajo, se encuentra una sección bien definida con el título “Datos de la actividad”, donde se organizan en formato de lista los detalles clave: modalidad, grado académico, asignatura, actividad, nombre del estudiante, tutor, NRC, fecha y un enlace externo a YouTube. 

#Imagen Parte 1

![](https://github.com/JCPB2000/A1.Paguay_Julio_PICW/blob/main/img/Pagina.jpg)

> Primera parte.


# Parte 2: Analiza una página web existente

#Imagen Parte 2

![](https://github.com/JCPB2000/A1.Paguay_Julio_PICW/blob/main/img/Supermaxi.jpg)

# Análisis

## Los elementos que se pueden identificar son los siguientes:

```
<html>: Elemento raíz del documento.
<head>: Contiene metadatos, enlaces a hojas de estilo y scripts.
<body>: Alberga todo el contenido visible de la página.
<div>: Elemento contenedor usado en muchas partes.
<section>: Divide el contenido en secciones (como encuestas, derechos de autor).
<nav>: Barra de navegación para los menús.
<header>: Encabezado principal del sitio.
<footer>: Pie de página con enlaces e información legal.
<style>, <script>, <noscript>: Para estilos y scripts.
<link>: Cargar hojas de estilo externas.
<img>: Inserción de imágenes (como el logo y banners).
<a>: Enlaces de navegación y llamados a la acción.
<button>, <input>: Para la búsqueda y acciones de usuario.
Modales: <div> con clases especiales para ventanas emergentes (ej. shareRecipeModal)
```

# La página está estructurada de la siguiente forma:
#### Encabezado (Header):
- Incluye el logo de Supermaxi (el placer de comprar).
- Una barra de búsqueda que dice: “Busca productos, locales, recetas…”.
+ Botones destacados:
  + Comprar por Tipti (botón naranja). 
  + Consulta por WhatsApp (botón verde).
+ Información sobre la tienda local: “Supermaxi San Gabriel, a 5.67 KMS.: Cambiar”.
+ La barra de navegación justo debajo incluye las siguientes categorías:
- SÚPER OFERTAS
- AFILIACIÓN
- BENEFICIOS
- CATÁLOGOS
- EMPRESA
- LOCALES
- MÁS
#### Contenido principal:
Un área destacada con un banner principal donde aparece Carolina Sánchez (Chef ecuatoriana), con el mensaje:
- “ORGULLO ECUATORIANO”
- “Conoce las recetas más representativas”.
- Botón rojo: “Descubre el Ecuador en Recetas”.
- Encima hay un aviso promocional:
 “OBTÉN EL 20% DE DTO. EN FLORES, FRUTAS Y VERDURAS, TODOS LOS MIÉRCOLES.”
#### Modales y pop-ups:
+ Ventanas emergentes configuradas en <div> con IDs como:
  + promo-bugatti
  + nollas-bugatti
  + shareRecipeModal
Estas aparecen para mostrar promociones especiales o para compartir recetas y otros contenidos de interés.
#### Pie de página (Footer):
Dividido en varias columnas visibles:
- LA EMPRESA:
Trabaje con Nosotros
Acerca de Supermaxi
Responsabilidad Social
Preguntas Frecuentes
- PROVEEDORES Y CONSUMIDORES:
Quieres ser proveedor de Corporación Favorita
Facturación Electrónica
Proveedores
- INFORMACIÓN DE INTERÉS:
Términos y Condiciones
Políticas de privacidad
Convenio de afiliación
Términos y Condiciones Renueve su Afiliación
Derechos sobre datos personales
- Redes Sociales:
Íconos para:
-TikTok
-Facebook
-X (Twitter)
-Instagram
-YouTube
#### Información destacada:
Imagen de Crédito Favorito (servicio financiero).
#### Franja inferior:
Texto legal:
“Todos los derechos reservados® Corporación Favorita. 2025”

# Parte 3: Investigación
## Visita  de 3 sitios Web
#Imagen VISITA 1 Youtube

![](https://github.com/JCPB2000/A1.Paguay_Julio_PICW/blob/main/img/youtube.jpg)
## Elementos HTML identificados
```
<html> y <head>: Estructura base del documento.
<body>: Contiene todo el contenido visible.
<script>: Muchos scripts para cargar funciones y rastrear eventos (YouTube usa intensivamente JavaScript).
<ytd-app>: Etiqueta personalizada (Web Component) usada por YouTube para su estructura principal.
<iron-iconset-svg> y <iron-iconset-svg name="...">: Iconos SVG (parte de Polymer, un framework que usa YouTube).
<link>: Para cargar hojas de estilo externas.
<iframe>: Inserta contenido externo (como el módulo de autenticación de Google).
```

# La información se encuentra organizada de la siguiente forma.
 ## Encabezado (Header):
La parte superior contiene el logo de YouTube, barra de búsqueda y accesos rápidos (subir videos, notificaciones, perfil).


 ## Menú de navegación (Sidebar):
A la izquierda (no siempre visible en las capturas) suele haber enlaces a secciones como “Inicio”, “Tendencias”, “Suscripciones”.


## Contenido principal:
Compuesto por filas de videos (miniaturas + títulos + vistas). Cada video está dentro de un bloque que se repite, probablemente gestionado por Web Components como <ytd-rich-item-renderer> (no se muestra en las capturas pero es típico en YouTube).


## Scripts y recursos:
Hay muchas etiquetas <script> que cargan funciones internas para manejar dinámicamente todo el sitio (eventos de usuario, carga de videos, etc.).


## Pie de página (Footer):
No está visible en estas capturas, pero usualmente YouTube incluye allí enlaces a políticas, ayuda, etc.


#Imagen VISITA 2 Wikipedia

![](https://github.com/JCPB2000/A1.Paguay_Julio_PICW/blob/main/img/Wikipedia.jpg)
## Elementos HTML identificados


# Elementos HTML identificados

```
<html>: El elemento raíz de la página.
<head> y <body>: Estructura principal del documento.
<div>: Contenedores clave como main-wrapper, main-box, vector-header-container, etc.
<header>: Encabezado principal de la página.
<main>: Contenido principal (donde está el artículo).
<p>, <h2>: Texto y encabezados.
<a>: Enlaces de navegación.
<script>: Scripts para funcionalidades dinámicas.
<link>: Carga de estilos.
<noscript>: Contenido alternativo si JavaScript está desactivado.
<div class="mw-footer-container">: Contenedor para el pie de página (footer).
<div class="main-footer">: Otra parte importante del pie de página.
<img>: (visto en la parte visual para mostrar imágenes como la portada del artículo).
```

# La información se encuentra organizada de la siguiente forma.
## Encabezado (Header):
Incluye el logo de Wikipedia, barra de búsqueda y enlaces para iniciar sesión, crear cuenta y otras herramientas.


## Navegación:
Menú superior con enlaces como:


-Portada
-Discusión
-Leer
-Ver código fuente
-Ver historial


También tiene una barra lateral (no se ve completa aquí) donde usualmente está la navegación por categorías, idioma, etc.


## Contenido principal:
Incluye:


-Un bloque destacado de bienvenida (por ejemplo: “Bienvenidos a Wikipedia”).
-Artículos destacados (ejemplo: Don't Cry for Me Argentina).
-Texto con enlaces, imágenes y otros recursos enriquecidos.


##Todo está contenido dentro de elementos como:


-main-wrapper
-main-box
-main-box-content


## Pie de página (Footer):
Varios bloques:


-mw-footer-container y main-footer: donde aparecen enlaces a políticas, información sobre Wikipedia, y otros recursos legales o institucionales.
-Sección para mostrar el tiempo de carga y otros detalles técnicos al final del documento.

#Imagen VISITA 3 X Twitter

![](https://github.com/JCPB2000/A1.Paguay_Julio_PICW/blob/main/img/x.jpg)
## Elementos HTML identificados

```
<html> y <head>: Estructura base de la página.
<body>: Contenedor principal visible.
<noscript>: Para mostrar mensajes si JavaScript está deshabilitado.
<div>: Usado intensivamente para la estructura de la página (por ejemplo, id="react-root", capas flexibles y de diseño).
<script>: Muchos scripts para la carga dinámica y la funcionalidad.
<nav>: Aparece en el pie de página con el atributo aria-label="Pie de página" para navegación.
<main>: Contenedor principal para el contenido visual.
<button> (visible en la parte de registro) y enlaces (para términos y políticas).
```

# La información se encuentra organizada de la siguiente forma.
## Encabezado:
Muy simple: solo el logotipo de X en la parte superior izquierda. No hay menú clásico visible en esta página inicial.


## Contenido principal:
Un mensaje central destacado:
 “Lo que está pasando ahora”
 y el llamado a la acción: “Únete Hoy”.


## Opciones para registrarse:


-Registrarse con Google
-Registrarse con Apple
-Crear cuenta (botón azul).


Enlaces a Términos de servicio, Política de privacidad y Uso de Cookies justo debajo del formulario de registro.


## Pie de página (Footer):
Confirmamos que sí existe un pie de página mediante la etiqueta <nav> (visto en la última imagen), que contiene enlaces como:


- Información
- Descarga la app
- Centro de Ayuda
- Condiciones de Servicio
- Política de Privacidad
- Política de cookies
- Accesibilidad
- Información de anuncios
- Blog
- Empleos
- Recursos para marcas
- Publicidad
- Marketing
- X para empresas
- Desarrolladores
- Guía
- Configuración

También se muestra un aviso legal: © 2025 X Corp.


# Parte 4: Listas en HTML
## Se añade en el código anterior a las listas.
La sección diseñada presenta el título general "Mis Películas y Canciones Favoritas", seguido de dos bloques bien diferenciados. El primer bloque muestra la lista de películas favoritas, acompañada de una imagen destacada que recopila diversos pósters cinematográficos; a la derecha se encuentra la lista ordenada de las películas seleccionadas, lo que proporciona un equilibrio visual y facilita la identificación de cada elemento. El segundo bloque corresponde a las canciones favoritas, donde se incluye una imagen con portadas de álbumes representativos y, a su lado, una lista desordenada con los títulos y artistas. Toda la estructura está centrada y organizada utilizando un diseño flexible, lo que permite alinear de manera armoniosa las imágenes y las listas, ofreciendo una presentación clara y atractiva al usuario.

#Imagen Mis Películas y Canciones Favoritas

![](https://github.com/JCPB2000/A1.Paguay_Julio_PICW/blob/main/img/PeliculaCancion.jpg)

## HTNL
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Actividad 1</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Universidad de las Fuerzas Armadas ESPE</h1>
    <img src="espe.png" alt="Imagen de mi actividad">
   
    <section>
        <h2>Datos de la actividad</h2>
        <p><strong>Modalidad:</strong> En línea</p>
        <p><strong>Grado:</strong> Ingeniería en Tecnologías de la Información</p>
        <p><strong>Asignatura:</strong> Programación Integrativa de Componentes Web</p>
        <p><strong>Actividad:</strong> Primer Parcial</p>
        <p><strong>Estudiante:</strong> Julio Paguay</p>
        <p><strong>Tutor:</strong> Ing. Criollo Chanchicocha Vilmer David</p>
        <p><strong>NRC:</strong> 23407</p>
        <p><strong>Fecha:</strong> 07/05/2025</p>
        <p>Enlace: <a href="https://youtu.be/q8fK4La_jmM?si=kNa78kXA6yhRAxfo" target="_blank">Youtube</a></p>
    </section>


    <section>
        <h2>Mis Películas y Canciones Favoritas</h2>


        <h3>Películas favoritas</h3>
        <div class="media-list">
            <img src="https://ih1.redbubble.net/image.3120496015.9028/flat,750x,075,f-pad,750x1000,f8f8f8.jpg" alt="Posters de películas">
            <ol>
                <li>Titanic</li>
                <li>Sing</li>
                <li>Matrix</li>
                <li>Avatar</li>
                <li>Gladiador</li>
            </ol>
        </div>


        <h3>Canciones favoritas</h3>
        <div class="media-list">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSfJBpq-xZ5hH302X_9fSCKuxB7xavJsWMatg&s" alt="Portadas de discos">
            <ul>
                <li>Nuestro Juramento - Julio Jaramillo</li>
                <li>Hotel California - Eagles</li>
                <li>Imagine - John Lennon</li>
                <li>A Dios le Pido - Juanes</li>
                <li>Senderito de Amor - Paulina Tamayo</li>
            </ul>
        </div>
    </section>
</body>
</html>
```

## CSS
```css
body {
    text-align: center;
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
    margin: 20px;
}


img {
    max-width: 300px;
    margin: 20px 0;
}


a {
    display: inline-block;
    margin-top: 10px;
    text-decoration: none;
    color: #0077cc;
    font-weight: bold;
}


/* Alineación de imagen + lista */
.media-list {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 30px; /* espacio entre imagen y lista */
    margin: 20px 0;
}


.media-list img {
    max-width: 300px;
    height: auto;
    border: 2px solid #ccc;
    border-radius: 8px;
}


.media-list ol,
.media-list ul {
    text-align: left;
    padding-left: 20px;
    font-size: 16px;
}


li {
    margin: 5px 0;
}
```





