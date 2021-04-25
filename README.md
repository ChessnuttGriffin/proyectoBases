
# Base de Datos
---

## Herramientas utilizadas
* Python 3
* MariaDB 10.3 o
* MySQL 5.7
* TKinter
--------------------------------
## Forma de Trabajo
* Se identifica que el proyecto consta de partes fundamentales las cuales definen la forma en la que se comienza a trabajar, las cuales son:

    * **Desarrollo en python**
    * **Desarrollo de las bases de datos** 

    se acordo que ambos integrantes del proyecto tabajarian en ambas partes a la vez que se avanzara en el.

    **Planificado:**

    * Como parte de la planificacion, dividimos y definimos por partes las diferentes funcionalidades a realizar.
    * Se analizo el proyecto de forma exhaustiva, y se dio a conocer las partes que se trabajarian primero, asi como los encargados.
    * Con el planteamiento en marcha, se dio la tarea de crear las tablas  de Entidad-Relacion y Relacionales que prueben la funcionalidad de nuestro analisis.
    * Seguidamente, se dio inicio a la creacion de codigo para SQL asi como para Python.
    * Se utilizo los recursos, manuales y documentacion que proporcionan estos lenguajes respectivamente.
    * Se dividio en grupos la totalidad del trabajo, comenzando por la distribucion de:
            * La creacion de ventanas para GUI en la parte del usuario.
            * La creacion de la Base de Datos del sudoku.
            * Creacion de metodos, clases y funcionalidades para cada ventana y para retorno y extraccion de datos. 

## Analisis de Diseño
---

- La base de datos surge de la necesidad de generar el sistema de almacenamiento, para la autenticacion y el retorno de datos de usuario para un juego de Sudoku. Se empezó por crear cada una de las tablas, pero esto sin antes analizar la naturaleza de la aplicación y de sus posibles escenarios, todas la tablas creadas fueron analizadas y pensadas de tal forma, que así se llevarán acabo todas las consultas de las peticiones realizadas por el usuario en la aplicacíon y por su puesto un registro total de todo lo que hagan los usuarios, ademas cumpliendo con los items de la definción del proyecto. 
    
- La tabla Rol tiene como funcionalidad la identificacion de aquellos usarios considerados como "Administrador", y el usuario normal, estos tienen como valores predefinidos los roles anteriormente mencionados, lo que hace a la tabla una parte fucndamental al momento de su utilizacion, ya que el administrador gestiona la parte de la creacion de nuevos usuarios.

- La tabla Cuenta esta definida de tal manera que se guardaran los datos de los usuarios, estos tienen como atributos un nombre, una contraseña (password) y el rol especifico.

- La tabla de Tableros tiene como atributos un nombre de archivo y un archivo de tipo json que almacena los tableros en formato json.

- La tabla Puntuaciones tiene la tarea especifica de almacenar y retornar datos para una interfaz especifica que muestra los mejores puntajes de los usuarios que jugaron anteriormente, demostrando los mejores tiempos.

- La tabla PartidaEspera se define de tal manera que al iniciar un juego nuevo esta quede registrada con los valores que se dejaron anteriormente, y en caso de que el usuario lo desee este tendra la oportunidad de continuar el juego actual o iniciar un nuevo juego.

- La tabla Bitacora es un modulo con la finalidad de establecer un registro de acciones, en este caso, se realizo la creacion de una tabla que contenga los valores para la funcionalidad de este registro, como ser una cuenta, una accion y una fecha.

- Creamos procedimientos almacenados y triggers esto para poder obtener información de manera dinámica y definiendo eventos automáticos para la inserción de datos.

--------------------------------
## Forma de Trabajo
* Se identifica que el proyecto consta de partes fundamentales las cuales definen la forma en la que se comienza a trabajar, las cuales son:

    * **Desarrollo en python**
    * **Desarrollo de las bases de datos** 

    se acordo que ambos integrantes del proyecto tabajarian en ambas partes a la vez que se avanzara en el.

    **Planificado:**

    * Inicialmente para la elaboracion del proyecto se cuenta con mas integrantes.
    * Se divide en parejas para realizar las 2 partes fundamentales encontradas.
    * La pareja que se encarga del desarrollo en python se dividen el trabajo que tambien constaba de 2 partes que son:
        * Desarrllo de la parte grafica del proyecto, junto a ventanas emergentes, ventanas de errores y botones.
        * Desarrollo de la funcionalidas que acompañan la parte grafica y la conexión con la base de datos.
    * Igualmente la otra pareja se encarga del desarrollo de las bases de datos las cuales son 2 asi que se dividen en 2 partes.
        * Desarrolo de la Base de Datos principal.
        * Desarrollo de la Base de Datos de Respaldo.


