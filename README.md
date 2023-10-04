# snatreal.github.io
SNATREAL 
<!DOCTYPE html> <!--version de HTML-->
<html lang="en"><!--Idioma-->
<head>
    <meta charset="UTF-8"> <!--caracteres-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    
<!--enlace para estilo texto--> 
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Black+Han+Sans&family=Lilita+One&family=Permanent+Marker&display=swap" rel="stylesheet">
<!--enlace para hoja de estilos-->  
    <link rel="preload" href="estilos.css" as="style"><!--cargar más rapido -->
    <link href="estilos.css" rel="stylesheet" > <!--cargar la hoja de estilos -->
</head>
<body>
    <!--cabeza de la página-->
    <header>
        <h1 class="titulo">Real Madrid</h1>
       
    </header>
 <!--Navegación de la pagina-->
<nav class="navegacion">
    <a >Historia</a>
    <a>Leyendas</a>
    <a>Campeonatos</a>
    <a>Jugadores</a>
</nav>


    <!--Sección principal de la pagina-->
    <main>
<!--grid principal de la pagina -->
<div class="principal">
<!--Secciones de nuestra pagina serán 3-->
        <section>
            <h3>CAMPEONATOS</h3>
            <p>El Real Madrid fue fundado en 1902. Julián Palacios es el primer presidente, pero fue Juan Padrós, catalán y de Barcelona, quien formalmente constituyó la institución ese año.</p>
            <img src="C:\Users\804\Downloads\OCTAVO\OCTAVO\img\15874616058693.jpg" width="200px" height="200px">
            <img src="C:\Users\804\Downloads\OCTAVO\OCTAVO\img\InicioM.jpg" width="200px" height="200px">
        </section>
   <!--Seccion dos de la pagina-->     
        <section >
            <h3>JUGADORES</h3>
            <p>Los 100 títulos del Madrid se desglosan de la siguiente manera: 14 Copa de Europa/Champions, 35 Ligas, 20 Copas del Rey, 8 Intercontinentales/Mundial de Clubes, 5 Supercopas de Europa, 2 Copas de la UEFA, 12 Supercopas de España, 2 Copas Latinas, 1 Copa de Liga y 1 Copa Eva Duarte.</p>
            <img src="C:\Users\804\Downloads\OCTAVO\OCTAVO\img\01gzspm56sy8czcxrq42.webp" width="200px" height="200px">
            <img src="C:\Users\804\Downloads\OCTAVO\OCTAVO\img\stones.jpeg" width="200px" height="200px">
        </section>
<!--Seccion tres de la pagina-->  
        <section>
            <h3>LEYENDAS</h3>
            <p>
                Cristiano Ronaldo

                Cristiano Ronaldo es el jugador número 1 indiscutible de esta lista. Es la mayor leyenda del Real Madrid. Ronaldo ya tenía una carrera sensacional en el Manchester United, pero fue durante sus años en el Real Madrid cuando se convirtió en el mejor jugador del mundo.
            </p>
            <img src="C:\Users\804\Downloads\OCTAVO\OCTAVO\img\15873967947516.jpg" width="200px" height="200px">
            <img src="C:\Users\804\Downloads\OCTAVO\OCTAVO\img\SLIDE+1+-+Di+Stéfano,3.jpg">
        </section>
    </main>
</div>
<!--Parte inferior de la pagina-->  
<footer> contactos y derechos de autor </footer>
<footer> Santiago Bustos Valbuena </footer>
<img src="C:\Users\804\Downloads\OCTAVO\OCTAVO\img\fotos.png">
</body>
</html>

body {
    background-image: url("https://i.pinimg.com/736x/ea/7c/c1/ea7cc1f1bd64978a150dfcbb13bd8249.jpg");
    /*background-attachment: fixed;/*toda la hoja*/
}


h1 {
    text-align: center;
    color: black;
    font-family: Arial, Helvetica, sans-serif;
}


p {
    background-color: black;
    color: yellow;
    margin: 10px;
}

/* clase para título*/
.titulo {
    font-family: 'Lilita One', cursive;
    font-size: 50px;
    letter-spacing: 2px;
    text-align: center;
    font-weight: 400; /*grosor del texto*/
    /*background-color:green*/
}

.navegacion {
    font-family: 'Edu SA Beginner', cursive;
    color: white;
    text-decoration: none;
    /*width: auto;*/
    margin: 0px auto; /*distancia entre la barra de navegación y titulo*/
    background-color: #1C79A7;
    padding: 8px;
    text-decoration: none;
    /*distribuye la barra de menú*/
    display: flex;
    justify-content: space-around;
}
/*clase para distribuir los parrafos*/
.principal {
    display: flex;
}

