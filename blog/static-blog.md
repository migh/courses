# ¿Cómo hacer mi propio blog?

Este artículo está pensado para personas que no se dedican al desarrollo web, pero que no están dispuestos a ensuciarse un poco las manos haciendo su propio sitio, es decir, la clase de personas que disfrutan producir en lugar de consumir. No importa que no tengas ninguna experiencia en desarrollo web, los conocimientos que aprenderás te servirán para entender mejor como funciona el internet, son sencillos, prácticos y pueden tener muchas aplicaciones.

## ¿Qué es un sitio estático?

Tenemos que empezar por decir que en internet hay clientes y servidores, tú y yo en nuestros navegadores somos clientes, al acceder a un sitio web un servidor, es decir, una computadora que sirve archivos, nos regresa el contenido del sitio. La computadora puede hacer pequeños cambios en los archivos del sitio, como poner el nombre de usuario o la fecha, este tipo de sitios se conocen como dinámicos, por otro lado, cuando el servidor envía siempre exactamente el mismo archivo, se conoce como sitio estático.

Existen muchas ventajas para elegir un sitio estático, sólo hablaré de las dos principales. La más importante es la seguridad, cuando el sitio tiene información cambiante, existe la posibilidad de que alguien con malas intenciones la cambie, en los sitios estáticos esto es mucho más difícil porque la comunicación es solo en un sentido, del servidor hacia nosotros. La segunda es la sencillez, los sitios dinámicos generalmente involucran programar, es decir, aprender un lenguaje de programación y empezar a practicar; los sitios estáticos generalmente son mucho más sencillos y transparentes, lo que se escribe es lo que se va. 

## ¿Qué es un repositorio?

Para que la información sea enviada a los clientes, es necesario almacenarla en algún lado, los repositorios fueron creados para ese propósito, almacenar información y tener un registros claro de quién la edita, cuándo y exactamente qué es lo que modifica. En realidad fueron creados para programas de computadoras, porque esos detalles son bastante importantes, pero la gente notó que podían usarse para muchas otras cosas, bitácoras, archivos compartidos entre varias computadoras, libros, tutoriales e incluso blogs y sitios web. Existen muchos servicios de repositorios y varios sistemas, el sistema más común actualmente es git, muy utilizado para el desarrollo de software libre y bastante sencillo de utilizar, entre los principales servicios se encuentran Github, Bitbucket y GitLab.

## ¿Qué es markdown?

Markdown es un conjunto de acotaciones al texto que permiten desplegarlo con distintos estilos, por ejemplo, encabezados, letra cursiva, negritas, imágenes, citas, listas de numeradas y no numeradas, etcétera. Markdown es transformado automáticamente a HTML (Lenguaje en el que están hechos los sitios web) y es muy utilizado en los repositorios para archivos de descripción y wikis.

## Primeros pasos

1. Es necesario **descargar e instalar [git](https://git-scm.com/)**.
2. Obten **una cuenta en [Github](https://github.com/join?source=header-home)** (También puedes usar [GitLab](https://gitlab.com/) o [Bitbucket](https://bitbucket.org/)). Posiblemente estés leyendo este documento en Github.
3. Crea **un nuevo repositorio** o solicita acceso si ya tienes uno.
4. Sigue las indicaciones del servicio para agregar el contenido inicial al repositorio.

## ¿Cómo agregar información?

Para llevar un control preciso de los cambios los sistemas de versiones como git siguen un protocolo para introducir cambios al repositorio. En lugar de guardar el archivo como se haría normalmente es necesario llevar a cabo algunos sencillos pasos:

1. Modificar los archivos y guardar los cambios en la computadora.
2. Agregar los cambios al repositorio `git add .`.
3. Guardar los cambios en el repositorio y agregar un mensaje descriptivo. `git commit -m "Mensaje descriptivo"`.
4. Subir los cambios al servicio de repositorios `git push`.
