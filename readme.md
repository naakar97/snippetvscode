# Documentación del Proyecto

Este proyecto contiene configuraciones JSON que pueden ser utilizadas en aplicaciones web para generar contenido HTML y manejar un slider de imágenes en JavaScript.

## JSON de HTML

El JSON para HTML incluye snippets para generar contenido en la sección `<head>` de mi página web, asi como las metas que creo minimamente necesarias.
Tambien he incluido un pie de página (footer) con las redes sociales de la pagina web que cree. 

Aquí está la estructura:

{
    "Metas": {
        "prefix": "metas",
        "body": [
            "<meta charset=\"UTF-8\">",
            "<meta name=\"viewport\" content=\"width=device-width, initial-scale=1.0\">",
            "<meta name=\"description\" content=\"Descripción breve de tu página que incluye palabras clave relevantes.\">",
            "<meta name=\"keywords\" content=\"palabra1, palabra2, palabra3\">",
            "<meta name=\"author\" content=\"Tu Nombre o Tu Empresa\">",
            "<meta name=\"robots\" content=\"index, follow\">",
            "<title>Título de tu página - Palabra Clave Principal</title>",
            "<link rel=\"canonical\" href=\"https://www.tusitio.com/\">",
            "<meta name=\"robots\" content=\"noimageindex, noindex, nofollow, noarchive, nosnippet\">"
        ],
        "description": "Los metas para mi página web"
    },
    "Footer RRSS": {
        "prefix": "forrss",
        "body": [
            "<footer>",
            "<p>&copy; 2024 Urban Rolling. Todos los derechos reservados.</p>",
            "<div class=\"social-media\">",
            "<a href=\"https://www.facebook.com\" target=\"_blank\" aria-label=\"Facebook\"><i class=\"fab fa-facebook\"></i></a>",
            "<a href=\"https://www.twitter.com\" target=\"_blank\" aria-label=\"Twitter\"><i class=\"fab fa-twitter\"></i></a>",
            "<a href=\"https://www.instagram.com\" target=\"_blank\" aria-label=\"Instagram\"><i class=\"fab fa-instagram\"></i></a>",
            "<a href=\"https://www.youtube.com\" target=\"_blank\" aria-label=\"YouTube\"><i class=\"fab fa-youtube\"></i></a>",
            "</div>",
            "</footer>"
        ],
        "description": "Footer con RRSS"
    },
    "Enlaces head": {
        "prefix": "enhead",
        "body": [
            "<link rel=\"stylesheet\" href=\"https://necolas.github.io/normalize.css/latest/normalize.css\">",
            "<link rel=\"icon\" href=\"imagen/icono.ico\" type=\"image/x-icon\">",
            "<link rel=\"stylesheet\" href=\"style.css\">",
            "<link rel=\"stylesheet\" href=\"https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css\">"
        ],
        "description": "Enlaces para mi header"
    }
}


## JSON de JavaScript

El JSON que creé para mi JS es un slider para que dentro de mi pagina web puedan aparecer mis objetos y el cliente puede mover cada producto para elegir el que necesite.

La estructura es la siguiente:

{
    "slider": {
        "imagenes": [
            {
                "src": "https://example.com/images/image1.jpg",
                "alt": "Descripción de la imagen 1",
                "caption": "Esta es la imagen 1"
            },
            {
                "src": "https://example.com/images/image2.jpg",
                "alt": "Descripción de la imagen 2",
                "caption": "Esta es la imagen 2"
            },
            {
                "src": "https://example.com/images/image3.jpg",
                "alt": "Descripción de la imagen 3",
                "caption": "Esta es la imagen 3"
            },
            {
                "src": "https://example.com/images/image4.jpg",
                "alt": "Descripción de la imagen 4",
                "caption": "Esta es la imagen 4"
            }
        ],
        "settings": {
            "autoplay": true,
            "duration": 3000,
            "transitionEffect": "fade"
        }
    }
}