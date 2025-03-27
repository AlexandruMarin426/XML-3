Ejercicio 1.
Crea un documento XML que represente un catálogo de software informático. Utiliza
espacios de nombres para diferenciar entre software de sistemas operativos y software
de aplicaciones de oficina. Asegúrate de que el documento está bien formado.
Instrucciones:
• Nombre del Archivo: softwareCatalogYourName.xml (cambia YourName por tu
nombre completo)
• Estructura del Documento:
o Declaración XML estándar al inicio.
o Elemento raíz: <catalogo>.
o Dos espacios de nombres:
 os: Para software de sistemas operativos.
 office: Para software de aplicaciones de oficina.
• Incluye al menos tres elementos para cada tipo de software.
• Cada elemento de software debe contener:
o nombre: Nombre del software.
o version: Versión actual del software.
o desarrollador: Nombre del desarrollador o compañía.
o url: URL para más información (opcional).
Ejercicio 2.
El siguiente documento xml contiene información de libros, pero a su vez se quiere
utilizar html para mostrar la información.
Modifica el archivo para que no haya conflictos:
<html>
 <head><title>Book Review</title></head>
 <body>
 <bookreview>
 <title>Introducción a XML</title>
 <table>
 <tr align="center">
 <td>Author</td>
 <td>Price</td>
 <td>Pages</td>
 <td>Date</td>
 </tr>
 <tr align="left">
 <td><author>Simon St. Laurent</author></td>
 <td><price>31.98</price></td>
 <td><pages>352</pages></td>
 <td><date>1998/01</date></td>
 </tr>
LENGUAJES DE MARCAS - CSS
 </table>
 </bookreview>
 </body>
</html>
