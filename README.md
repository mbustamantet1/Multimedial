# Multimedial

## Taller Multimedia

Ejercicio 1, semana 1 

```
<!DOCTYPE html>
<!-- Indica al navegador que este documento usa HTML5 -->

<html>
<!-- Inicio del documento HTML -->

<head>
<!-- Sección donde van metadatos, título y estilos -->

<meta charset="UTF-8">
<!-- Define la codificación de caracteres para que se vean bien tildes y símbolos -->

<title>Multimedial</title>
<!-- Título de la página que aparece en la pestaña del navegador -->

<style>
/* Aquí comienza la sección de estilos CSS que define la apariencia visual */

body{
/* "body" se refiere a todo el contenido visible de la página */

  background-color: white;
  /* Define que el fondo de toda la página sea blanco */

  color: black;
  /* Define que el color del texto sea negro */

  margin: 0;
  /* Elimina los márgenes que los navegadores agregan por defecto */

  height: 100vh;
  /* Hace que el alto del cuerpo sea igual al 100% de la altura de la pantalla */

  display: flex;
  /* Activa el sistema Flexbox para organizar y centrar elementos */

  justify-content: center;
  /* Centra el contenido horizontalmente */

  align-items: center;
  /* Centra el contenido verticalmente */

  font-family: Arial, sans-serif;
  /* Define la tipografía del texto */

  font-size: 60px;
  /* Define el tamaño grande del texto */

}
/* Fin de las reglas de estilo del body */

</style>
<!-- Fin de la sección de estilos -->

</head>
<!-- Fin de la sección head -->

<body>
<!-- Inicio del contenido visible de la página -->

MULTIMEDIAL
<!-- Texto que aparece en el centro de la pantalla -->

</body>
<!-- Fin del contenido visible -->

</html>
<!-- Fin del documento HTML -->
```

Ejercicio 2, Semana 2
index.html
```
<!DOCTYPE html>
<html>
<head>
<title>Mi sitio</title>
</head>

<body>

<h1>Página principal</h1>

<a href="pagina2.html">Ir a la segunda página</a>

</body>
</html>
```
## Códigos página web.


index.html
```
<!DOCTYPE html>
<!-- Indica al navegador que este documento usa HTML5 -->

<html>
<!-- Inicio del documento HTML -->

<head>
<!-- Sección donde van metadatos, título y estilos -->

<meta charset="UTF-8">
<!-- Define la codificación de caracteres para que se vean bien tildes y símbolos -->

<title>Multimedial Marina</title>
<!-- Título de la página que aparece en la pestaña del navegador -->

<style>
/* Aquí comienza la sección de estilos CSS que define la apariencia visual */

body{
/* "body" se refiere a todo el contenido visible de la página */

  background-color: #ddd4b5;
  /* Define que el fondo de toda la página sea blanco */

  color: rgb(206, 19, 19);
  /* Define que el color del texto sea negro */

  margin: 1000;
  /* Elimina los márgenes que los navegadores agregan por defecto */

  height: 100vh;
  /* Hace que el alto del cuerpo sea igual al 100% de la altura de la pantalla */

  display: flex;
  /* Activa el sistema Flexbox para organizar y centrar elementos */

  justify-content: center;
  /* Centra el contenido horizontalmente */

  align-items: center;
  /* Centra el contenido verticalmente */

  font-family: Times New Roman, sans-serif;
  /* Define la tipografía del texto */

  font-size: 50px;
  /* Define el tamaño grande del texto */

}
/* Fin de las reglas de estilo del body */

        /* Contenedor principal */
        .contenedor {
            width: 35%;
            margin: auto;
        }

        /* Sección o bloque */
        .bloque {
            background-color: white;
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
        }

        /* Imagen */
        .bloque img {
            width: 100%;
            height: auto;
        }

        /* Encabezado */
        .bloque h2 {
            margin-top: 10px;
        }

        /* Texto */
        .bloque p {
            line-height: 1.5;
        }

        /* Estilo para los links como botones */
.bloque a {
    display: inline-block;       /* Permite dar tamaño tipo caja */
    background-color: #ce1313;   /* Color de fondo */
    color: white;                /* Color del texto */
    padding: 10px 20px;          /* Espacio interno */
    margin: 10px 5px 0 0;        /* Separación entre botones */
    text-decoration: none;       /* Quita el subrayado */
    border-radius: 8px;          /* Bordes redondeados */
    font-size: 20px;             /* Tamaño del texto */
    transition: 0.3s;            /* Animación suave */
}

/* Efecto cuando pasas el mouse */
.bloque a:hover {
    background-color: #a10f0f;
}

</style>
<!-- Fin de la sección de estilos -->

</head>
<!-- Fin de la sección head -->

<body>

    <!-- Contenedor principal -->
    <div class="contenedor">

        <!-- BLOQUE 1 -->
        <div class="bloque">
            <img src="img/IMG_1.jpeg" alt="imagen con pájaro">
            <h2>Marina B. Bustamante Tupper</h2>
            <p>
                Serie de grabados de flora y fauna nativa, mezclando la técnica de barniz blando y linografía. 
            </p>
            <a href="obra.html">Obra</a><br>


<a href="contacto.html">Contacto</a>

        </div>
<!-- Inicio del contenido visible de la página -->
 
  
<!-- Texto que aparece en el centro de la pantalla -->





</body>
<!-- Fin del contenido visible -->

</html>
<!-- Fin del documento HTML -->
```
obra.html
```
<!DOCTYPE html>
<!-- Indica al navegador que este documento usa HTML5 -->

<html>
<!-- Inicio del documento HTML -->

<head>
<!-- Sección donde van metadatos, título y estilos -->
   <meta charset="UTF-8">
    <title>Mi obra</title>

    <style>
        /* Estilo general del cuerpo */
        body {
            font-family: 'Times New Roman', Times, serif, sans-serif;
            background-color: #ddd4b5;
             color: rgb(206, 19, 19);
            margin: 0;
        }

        /* Contenedor principal */
        .contenedor {
            width: 35%;
            margin: auto;
        }

        /* Sección o bloque */
        .bloque {
            background-color: rgb(247, 247, 232);
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
        }

        /* Imagen */
        .bloque img {
            width: 100%;
            height: auto;
        }

        /* Encabezado */
        .bloque h2 {
            margin-top: 10px;
        }

        /* Texto */
        .bloque p {
            line-height: 1.5;
        }

        /* Botones (links) */
a {
    display: inline-block;
    background-color: #ce1313;
    color: white;
    padding: 10px 20px;
    margin: 10px 5px 0 0;
    text-decoration: none;
    border-radius: 8px;
    font-size: 18px;
    transition: 0.3s;
}

a:hover {
    background-color: #a10f0f;
}
    </style>
</head>

<body>

    <!-- Contenedor principal -->
    <div class="contenedor">

        <!-- BLOQUE 1 -->
        <div class="bloque">
            <img src="img/IMG_1.jpeg" alt="Descripción de la imagen" width="50">
            <h2>Tenca y Maitén</h2>
            <p>
                Barniz blando y linografía sobre papel de grabado, 2025.
            </p>
        </div>

        <!-- BLOQUE 2 -->
        <div class="bloque">
            <img src="img/IMG_2.jpeg" alt="Descripción de la imagen">
            <h2>Zorzal y Patagua</h2>
            <p>
               Barniz blando y linografía sobre papel de grabado, 2025.
            </p>
        </div>

        <!-- BLOQUE 3 -->
        <div class="bloque">
            <img src="img/IMG_3.jpeg" alt="Descripción de la imagen">
            <h2>Carancho y Canelo</h2>
            <p>
               Barniz blando y linografía sobre papel de grabado, 2025.
            </p>
        </div>

    </div>

</body>
    </div>

    <h1>Mi obra</h1>

    <p>Serie de grabados con técnica mixta, barniz blando y linografía, sobre papel de grabado.</p>

    <p>Mi enfoque es hacia la flora y fauna, principalmente nativa.</p>

    <p>
        <a href="index.html">Inicio</a>
        <a href="contacto.html">Contacto</a>
    </p>

</body>
</html>
```

contacto.html
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Contacto</title>

    <style>

    

        body {
            font-family: 'Times New Roman', Times, serif;
            background-color: #ddd4b5;
            color: rgb(206, 19, 19);

            margin: 0;
            height: 100vh;

            display: flex;
            justify-content: center;
            align-items: center;
        }

        /* Contenedor principal */
        .contenedor {
   
    bottom: 0;
    left: 0;
    width: 100%;
    padding: 10px;

        }

        /* Bloque */
        .bloque {
            background-color: white;
            margin: 20px auto;
            padding: 20px;
            border-radius: 20px;

            width: 700px; 
        }

        /* Títulos */
        .bloque h2 {
            font-size: 20px;
            margin-bottom: 10px;
        }

        .bloque h3 {
            font-size: 16px;
            margin-bottom: 10px;
        }

        /* Texto */
        .bloque p {
            margin: 5px 0;
            line-height: 1.5;
        }

        /* Links como botones */
a {
    display: inline-block;
    background-color: #ce1313;
    color: white;
    padding: 10px 20px;
    margin: 10px 5px 0 0;
    text-decoration: none;
    border-radius: 8px;
    font-size: 18px;
    transition: 0.3s;
}

a:hover {
    background-color: #a10f0f;
}

        .foto {
    width: 600px;
    height: auto;
    display: block;
    margin: 10px auto;
}

    </style>
</head>

<body>

    <div class="contenedor">
        <div class="bloque">
            <h2>Contacto</h2>

            <img src="img/IMG_1.jpeg" alt="imagen con pájaro" class="foto">

            <h3>Marina B. Bustamante T.</h3>

            <p>Mail: mbustamantet@uft.edu</p>
            <p>Teléfono: +56942529496</p>

            <a href="index.html">Inicio</a>
            <a href="obra.html">Obra</a>
        </div>
    </div>

</body>
</html>
```
