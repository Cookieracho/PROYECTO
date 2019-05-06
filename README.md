# PROYECTO DE PAGINA WEB DE EDIFICIO DE APARTAMENTOS
El proyecto debe de tener lo siguiente: Se debe de ver bien,  debe de poder adecuarse a cada dispositivo móvil, pantalla, computadora, etc.) y debe de poder modificarse el contenido mediante una base de datos.
La página debe de hacer lo siguiente:
    •	Debe de decir su misión y visión
    •	Debe de tener fotos de las habitaciones
    •	Debe de decir qué características tiene cada habitación, esto para poder realizar filtros.
    •	Debe de tener una sección de comentarios para que se opine acerca de los edificios
    •	Debe de tener un contacto
    
(Esto es solo general)
Entonces, habrá diferentes archivos, los cuales se conectarán uno con otro.

# PÁGINA PRINCIPAL

La página principal mostrará lo siguiente: 
    •	Una barra en donde se puede ir a las demás páginas
    •	La sección en donde se mostrarán las imágenes de los cuartos novedosos.
    •	Una imagen de un cuarto al azar, con descripción
    •	La sección donde diga contáctanos
    
Esto se hará de la siguiente manera: La barra estará estática, por lo que no debemos de ponerle base de datos.

-----------------------------------------FALTA MENCIONAR QUE LLEVA LA BARRA

Para las imágenes de los cuartos novedosos, hay dos opciones:
    •	Estático, que solo muestre las recámaras más llamativas (es lo que tiene más sentido)
    •	Versátil, que el admón. pueda elegir cuales se pone. Es más difícil, y no tiene mucho caso, debido a que obviamente el admón.     elegirá las recámaras que se vean mejor, y en un edificio de este tipo, TODAS SON IGUALES.
# P.D. ESTATICO ES QUE EL ADMON NO LO PUEDE MODIFICAR Y VERSÁTIL SÍ, MEDIANTE UNA B.D. Hay que usar  esto para ahorrar saliva y no escribir mucho.

Para poner el cuarto al azar, podemos hacerlo de la siguiente manera: Con un numero aleatorio escogemos el código de la habitación y así ponemos su info y todo eso.
Tenemos que tener en cuenta que para hacer esto hace falta una base de datos. Esta base de datos de Mysql tenemos que planearla bien, porque si no tendríamos que adaptar todo a una nueva base ya corregida.
Mi propuesta de base de datos para las habitaciones es lo siguiente:

ID	Llave primaria
PISO	El número de piso en el que se encuentran
IMAGEN	Imagen del cuarto	
PRECIO	Cuanto cuesta
FILTRO1	Carac. No. 1 del cuarto (amueblado o no)
FILTRO2	Carac. No. 2 (Terraza)
FILTRO3	Carac. No. 3 (Tiene Boiler)
Descripcion (tiene 3 camas, 1 tele, etc.)

Con esto podemos hacer lo que antes mencionamos de la llave primaria al azar, la imagen y podemos hacer varios filtros.
Siguiendo con lo que debe llevar la página, tenemos la sección de contáctanos, la cual tendrá un lugar que dice el teléfono y celular, esto debe de estar conectado a otra base de datos.

