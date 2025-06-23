# Ricomida

Ricomida es una página web de recetas de cocina que presenta una receta destacada (Pizza al estilo Chicago con espinacas y champiñones), secciones para ingredientes, preparación, recetas relacionadas, un formulario de suscripción a un newsletter y un pie de página. El proyecto está construido con HTML, CSS, Bootstrap, JavaScript, jQuery y la librería ScrollReveal para animaciones.

## Características

* **Header Fijo:** Navegación superior (`.navbar`) que permanece visible al hacer scroll.
* **Sección Principal de Receta:**
    * Imagen destacada de la receta.
    * Título de la receta con tiempo de preparación y porciones.
    * Botones interactivos para "Enviar por correo" (con alerta JavaScript) y "Añadir a favoritos" (con tooltip de Bootstrap).
* **Carrusel de Imágenes:** Un carrusel (`.carruzzel`) que muestra imágenes relacionadas con la receta, visible solo en pantallas medianas y grandes.
* **Secciones de Ingredientes y Preparación:**
    * Listado detallado de ingredientes.
    * Pasos de preparación numerados.
    * Interacción JavaScript: Los títulos "INGREDIENTES" y "PREPARACIÓN" cambian de color al hacer doble clic.
* **Recetas Relacionadas:**
    * Sección con tarjetas (`.card`) que muestran otras recetas.
    * Interacción JavaScript: Al hacer clic en el título de cada tarjeta, se oculta/muestra el texto de descripción (`.card-text`).
* **Sección Newsletter:**
    * Formulario de suscripción estilizado.
    * Botón "Empezar".
* **Footer:** Pie de página con el logo "Ricomida".
* **Diseño Responsivo:** Adaptabilidad a diferentes tamaños de pantalla (`@media queries`).
* **Animaciones:** Uso de ScrollReveal para animaciones al desplazar la página en secciones clave.
* **Tooltips de Bootstrap:** Información emergente al pasar el cursor sobre ciertos elementos.

## Tecnologías Utilizadas

* **HTML5:** Estructura de la página web.
* **CSS3:** Estilos personalizados (`style.css`).
* **Bootstrap 5.3.3:** Framework CSS para el diseño responsivo y componentes.
* **JavaScript (ES6+):** Lógica interactiva de la página (`script.js`).
* **jQuery 3.7.1:** Librería JavaScript para manipulación del DOM y manejo de eventos.
* **ScrollReveal:** Librería para animaciones de elementos al hacer scroll.
* **Google Fonts:** Fuentes "Cabin" y "Lobster" para el texto y el logo.

## Estructura del Proyecto

ricomida/
├── assets/
│   ├── css/
│   │   └── style.css
│   └── img/
│       ├── principal.jpg
│       ├── recipe-card-1.png
│       ├── recipe-card-2.png
│       ├── recipe-card-3.png
│       ├── slider-1.png
│       ├── slider-2.png
│       ├── slider-3.png
│       ├── slider-4.png
│       ├── slider-5.png
│       ├── slider-6.png
│       ├── slider-7.png
│       └── slider-8.png
├── index.html
└── script.js
└── README.md

## Cómo Usar

Para visualizar este proyecto, simplemente abre el archivo `index.html` en tu navegador web. No se requiere ninguna configuración de servidor adicional.

### Requisitos

* Un navegador web moderno (Chrome, Firefox, Safari, Edge, etc.).

## Instalación (Opcional - Para desarrollo)

Si deseas modificar el proyecto o trabajar en él localmente:

1.  Clona este repositorio:
    ```bash
    git clone [https://github.com/tu-usuario/ricomida.git](https://github.com/tu-usuario/ricomida.git)
    ```
    (Reemplaza `tu-usuario/ricomida.git` con la URL real de tu repositorio si ya lo tienes en GitHub).
2.  Navega al directorio del proyecto:
    ```bash
    cd ricomida
    ```
3.  Abre el archivo `index.html` en tu navegador.

## Contribución

Si deseas contribuir a este proyecto, por favor sigue los siguientes pasos:

1.  Haz un "fork" de este repositorio.
2.  Crea una nueva rama (`git checkout -b feature/nombre-de-la-caracteristica`).
3.  Realiza tus cambios y haz "commit" de ellos (`git commit -m 'Agrega nueva característica'`).
4.  Empuja tus cambios a la rama (`git push origin feature/nombre-de-la-caracteristica`).
5.  Abre un "Pull Request".

## Contacto

Si tienes alguna pregunta o sugerencia, no dudes en contactarme.

---
**Desarrollado por:** Jairo Muñoz Muñoz

**Fecha:** Agosto 2024
