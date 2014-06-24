# Dominios

Todos los libros sobre **Gitbook.io** son accesibles a trav�s de la url **http://{{author}}.gitbooks.io/{book}/**.

Pero usted puede configurar su libro para utilizar un nombre de dominio personalizado (una funci�n gratuita en GitBook.io).

El proceso para agregar un dominio personalizado para su libro es f�cil.

1. A�ade tu nombre de dominio en la configuraci�n de libros.

Para utilizar su propio dominio, tendr� que hacer cambios con el registrador de dominios:

1. Inicie sesi�n en su registrador de dominios y busque la secci�n que le permite a�adir/editar registros, a menudo se encuentran en un men� de configuraci�n llamado 'Edit DNS', 'Host Records' o 'Zone File Control'.

2. Ajuste el registro www a un `CNAME` y establezca el campo URL para: ```www.gitbook.io```.

3. Para redirigir el dominio simple (`sudominio.com`) hacia `www.sudominio.com`, encontrar�s la opci�n de redirigirlo. Esto por lo general se puede encontrar en 'Forwarding', 'URL Forwarding' o 'URL Redirect'.


Puede pasar alg�n tiempo hasta que los cambios en su dominio se lleven a cabo. Para comprobar si est� listo o para configurar su dominio personalizado con GitBook, ingrese su nombre de dominio incluido el 'www'