# Dreams-Desing
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dreams Desing</title>
    <link rel="stylesheet" href="css/normalize.css">
    <link rel="stylesheet" href="css/skeleton.css">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

    <header class="header">
        <div class="container">
            <div class="row">
                <div class="four columns">
                    <h1><img src="img/logo.png" alt="">Dreams Desing</h1>
                </div>
                <div class="two columns u-pull-rigth">
                    <ul>                       
                        <li class="submenu">
                            <img src="img/cart.png" alt="">
                            <div id="carrito">
                                <p class="vacio">carrito vacio</p>
                                <table class="u-full-width">
                                    <thead>
                                        <tr>
                                            <th>Imagen</th>
                                            <th>Productos</th>
                                            <th>Precio</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td>
                                                <img src="img/camisetas personalizables.JPG" width="100">
                                            </td>
                                            <td>camisetas personalizables</td>
                                            <td>20€</td>
                                            <td><a href="#" class="borrar-producto" ></a></td>
                                        </tr>
                                        <tr>
                                            <td>
                                                <img src="img/mascarillas personalizables.JPG" width="100">
                                            </td>
                                            <td>Mascarillas personalizables</td>
                                            <td>8€</td>
                                            <td><a href="#" class="borrar-producto" ></a></td>
                                        </tr>
                                    </tbody>
                                </table>
                                <a href="#" class="button u-full-width">vaciar carrito</a>
                            </div>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </header>

    <div class="hero">
        <div class="container">
            <div class="row">
                <div class="six columns">
                    <div class="contenido-hero">
                        <h2>PERSONALIZA: CAMISETAS, MASCARILLAS,TAZAS,ETC.</h2>
                        <p>Personaliza tus propios productos de forma telematica, para decirme lo que quereis contactarme al gmail: dreamsdesing12345@gmail.com
                        </p>
                        <form>
                            <input class="u-full-width" type="text" placeholder="¿que te gustaria personalizar?" id="buscador">
                            <input style="color:rgb(0, 86, 161);" type="submit" class="submit-buscador">
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
    
    <div class="barra">
        <div class="container">
            <div class="row">
                <div class="four columns icono icono1">
                    <p>las puede personalizar como a ti mas te guste</br>
                    explora nuestros productos</p>
                </div>
                <div class="four columns icono icono2">
                    <p>mascarillas de muy buena calidad 40 lavados</br>
                    explora nuestros productos</p>
                </div>
                <div class="four columns icono icono3">
                    <p>ten tu propia taza con el diseño que quieras</br>
                    explora nuestros productos</p>
                </div>
            </div>
        </div>
    </div>



    <div class="lista de productos" class="container">
        <h1 class="encabezado">pedidos en linea</h1>

        <div class="row">

            <div class="four columns">
                <div class="card">
                    <img src="img/camisetas personalizables.JPG" class="imagen camisetas u-full-width">
                    <div class="info card">
                        <h1>Camisetas personalizables</h1>
                        <p style="color: aliceblue;" >las puede personalizar como a ti mas te guste, diseños ilimitados</p>
                        <img src="img/estrellas.png">
                        <p style="color: aliceblue;" class="precio">20€<span class="u-pull-right">20€</span> </p>
                        <a href="#" class="u-full-width button-primary button input agregar-carrito" data-id="1">agregar al carrito</a>
                    </div>
                </div>
            </div>
            <div class="four columns">
                <div class="card">
                    <img src="img/mascarillas personalizables.JPG" class="imagen camisetas u-full-width">
                    <div class="info card">
                        <h1>Mascarillas personalizables</h1>
                        <p style="color: aliceblue;" >mascarillas de muy buena calidad 40 lavados, diseños ilimitados</p>
                        <img src="img/estrellas.png">
                        <p style="color: aliceblue;" class="precio">8€<span class="u-pull-right">8€</span> </p>
                        <a href="#" class="u-full-width button-primary button input agregar-carrito" data-id="1">agregar al carrito</a>
                    </div>
                </div>
            </div>
            <div class="four columns">
                <div class="card">
                    <img src="img/tazas personalizables.JPG" class="imagen camisetas u-full-width">
                    <div class="info card">
                        <h1>Tazas personalizables</h1>
                        <p style="color: aliceblue;" >ten tu propia taza exclusiva con el diseño que quieras, diseños ilimitados</p>
                        <img src="img/estrellas.png">
                        <p style="color: aliceblue;" class="precio">8€<span class="u-pull-right">8€</span> </p>
                        <a href="#" class="u-full-width button-primary button input agregar-carrito" data-id="1">agregar al carrito</a>
                    </div>
                </div>
            </div>
            <div class="four columns">
                <div class="card">
                    <img src="img/logo generacion actual.JPG" class="imagen camisetas u-full-width">
                    <div class="info card">
                        <h1>logos</h1>
                        <p style="color: aliceblue;"> diseños ilimitados</p>
                        <img src="img/estrellas.png">
                        <p style="color: aliceblue;" class="precio">50€<span class="u-pull-right">50€</span> </p>
                        <a href="#" class="u-full-width button-primary button input agregar-carrito" data-id="1">agregar al carrito</a>
                    </div>
                </div>
            </div>
            <div class="four columns">
                <div class="card">
                    <img src="img/banner.JPG" class="imagen camisetas u-full-width">
                    <div class="info card">
                        <h1>banners</h1>
                        <p style="color: aliceblue;" >diseños ilimitados</p>
                        <img src="img/estrellas.png">
                        <p style="color: aliceblue;" class="precio">50€<span class="u-pull-right">50€</span> </p>
                        <a href="#" class="u-full-width button-primary button input agregar-carrito" data-id="1">agregar al carrito</a>
                    </div>
                </div>
            </div>  
         </div>
      </div>
   </div>

</div>



<footer class="footer">
    <div class="container">
        <div class="row">
            <div class="four columns">
                <nav class="menu">
                    <a class="enlace" href="#">pedidos en linea</a>
                    <a class="enlace" href="#">pedidos por telefono</a>
                    <a class="enlace" href="#">pedidos por correo</a>
                    <a class="enlace" href="#">Menu</a>
                    <a class="enlace" href="#">camisetas</a>
                </nav>
            </div>
            <div class="four columns">
                <nav class="menu">
                    <a class="enlace" href="#">Correo electronico</a>
                    <a class="enlace" href="#">Telefono</a>
                    <a class="enlace" href="#">mascarillas</a>
                    <a class="enlace" href="#">tazas</a>
                    <a class="enlace" href="#">logos</a>
                </nav>
            </div>
        </div>
    </div>
</footer>






</body>
</html>
