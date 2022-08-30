### KOFFE SHOP ###

El primer paso para abrir el aplicativo es abrir el gestor de bases de datos local, en este caso, yo utilicé XAMPP, Con PHPMYADMIN, Tenemos 2 formas de ejecutar la base de datos, se encuentra en la carpeta DATABASE el archivo Koffe.sql este archivo lo podemos importar directamente en el gestor de base de datos

o podemos crear la base de datos llamada Koffe, y desde la consola ejecutar el comando php artisan migrate esto migrará solamente las tablas más no la informacion ya almacenada

despues de haber instalado la base de datos, ejecutamos nuestro IDE o editor de codigo favorito, copiamos nuestro repositorio con Git clone

posteriormente ejecutamos el comando npm install para instalar todas las dependencias y librerias de Node y así poder inicializar la app, despues de terminar la instalacion de NPM

debemos ejecutar el comando Php artisan serve, esto ejecutará la aplicacion en localhost, especificamente en el puerto 8000

es decir: 127.0.0.1:8000

### NOTA ###

Debido a la ultima actualizacion de Laravel, este ya utiliza Vite como motor de procesado, esto lo hace un poco más eficiente a la hora de cargar nuestras aplicaciones, pero esto añade un paso, solo si es necesario y se lanza un error apenas entrar al aplicativo, la solucion es en la terminal dentro de la carpeta raiz, debemos ejecuar el comando "Npm run dev" Esto solucionará el error y te permitirá navegar sin problemas


## FIn ###

Posteriormente procedo a informar que contiene este aplicativo

-Modulo de usuarios
-Modulo de productos
-Modulo de ventas y detalles de ventas
-Modulo de carrito de compras
-APIRestFull de MercadoPago en modo sambox para realizar pruebas de compra utilizando el metodo de pago mencionado
-Diseño y estructura totalmete CSS no se utilizó ningun tipo de plantilla, unicamente en el dashboard admin Utilizando ADMINLTE3


### Disfruta de este repo es totalmente libre de modificaciones ### 

La idea es seguir aprendiendo cada diá más! Just Be Fun :)

Visita mi portafolio www.sebasportafolio.com