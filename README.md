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

#Imagen Parte 1

![](https://github.com/JCPB2000/A1.Paguay_Julio_PICW/blob/main/img/Supermaxi.jpg)

# Análisis

## Los elementos que se pueden identificar son los siguientes:

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

# La página está estructurada de la siguiente forma:
 Encabezado (Header):
Incluye el logo de Supermaxi (el placer de comprar).
Una barra de búsqueda que dice: “Busca productos, locales, recetas…”.
Botones destacados:
Comprar por Tipti (botón naranja).
Consulta por WhatsApp (botón verde).
Información sobre la tienda local: “Supermaxi San Gabriel, a 5.67 KMS.: Cambiar”.
La barra de navegación justo debajo incluye las siguientes categorías:
SÚPER OFERTAS
AFILIACIÓN
BENEFICIOS
CATÁLOGOS
EMPRESA
LOCALES
MÁS
Contenido principal:
Un área destacada con un banner principal donde aparece Carolina Sánchez (Chef ecuatoriana), con el mensaje:
“ORGULLO ECUATORIANO”
“Conoce las recetas más representativas”.
Botón rojo: “Descubre el Ecuador en Recetas”.
Encima hay un aviso promocional:
 “OBTÉN EL 20% DE DTO. EN FLORES, FRUTAS Y VERDURAS, TODOS LOS MIÉRCOLES.”
Modales y pop-ups:
Ventanas emergentes configuradas en <div> con IDs como:
promo-bugatti
nollas-bugatti
shareRecipeModal
Estas aparecen para mostrar promociones especiales o para compartir recetas y otros contenidos de interés.
Pie de página (Footer):
Dividido en varias columnas visibles:
▪️ LA EMPRESA:
Trabaje con Nosotros
Acerca de Supermaxi
Responsabilidad Social
Preguntas Frecuentes
▪️ PROVEEDORES Y CONSUMIDORES:
Quieres ser proveedor de Corporación Favorita
Facturación Electrónica
Proveedores
▪️ INFORMACIÓN DE INTERÉS:
Términos y Condiciones
Políticas de privacidad
Convenio de afiliación
Términos y Condiciones Renueve su Afiliación
Derechos sobre datos personales
▪️ Redes Sociales:
Íconos para:
TikTok
Facebook
X (Twitter)
Instagram
YouTube
▪️ Información destacada:
Imagen de Crédito Favorito (servicio financiero).
Franja inferior:
Texto legal:
“Todos los derechos reservados® Corporación Favorita. 2025”

