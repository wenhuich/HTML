# HTML

### HTML1
Mostrar los 5 lenguajes separados por comas:
```
<html>
  <head></head>
  <body>PHP - Java - JavaScript - C -
C++</body>
</html>
```
![1](https://user-images.githubusercontent.com/91631138/143610569-29652903-cd84-4d4e-875d-6cb902e0acab.png)

### HTML2
Mostrar los distintos tipos de lenguajes por filas
```
<html>
<head></head>
<body>PHP
  <br>JavaScript
    <br>Java
      <br>C
        <br>C++</body>
      </html>  
```
![2](https://user-images.githubusercontent.com/91631138/143612469-9ff2666c-32ba-4c68-955a-a3e3f006d3a5.png)

### HTML3
Mostrar dos párrafos y en el primero, varios saltos de líneas:
```
<html>
  <head></head>
  <body>
    <p>SQL, Structure Query Language (Lenguaje de Consulta Estructurado) es un lenguaje de
programacion para trabajar con base de datos relacionales como MySQL, Oracle, etc.
      <br>MySQL es un interpretador de SQL, es un servidor de base de datos.
        <br>MySQL permite crear base de datos y tablas, insertar datos, modificarlos, eliminarlos,
ordenarlos, hacer consultas y realizar muchas operaciones, etc., resumiendo: administrar bases
de datos.</p>
        <p>Este tutorial tiene por objetivo acercar los conceptos iniciales para introducirse en el mundo de
las bases de datos.</p>
      </body>
    </html>

```
![3](https://user-images.githubusercontent.com/91631138/143612733-067691e3-3bab-4776-b8ae-4bc742096a4c.png)

### HTML4
Mostrar subtítulos en los dos párrafos:
```
<html>
<head>
</head>
<body>
<h1>Tipos de datos en MySQL</h1>
<h2>varchar</h2>
<p>
se usa para almacenar cadenas de caracteres. Una cadena es una secuencia de caracteres. Se coloca
entre comillas (simples): 'Hola'.<br>
El tipo "varchar" define una cadena de longitud variable en la cual determinamos el máximo de
caracteres. Puede guardar hasta 255 caracteres. Para almacenar cadenas de hasta 30 caracteres,
definimos un campo de tipo varchar(30).
</p>
<h2>int</h2>
<p>
Se usa para guardar valores numéricos enteros, de -2000000000 a 2000000000
aproximadamente.<br> Definimos campos de este tipo cuando queremos representar, por
ejemplo, cantidades.
</p>
</body>
</html>

```
![4](https://user-images.githubusercontent.com/91631138/143612865-efff4d3d-c61d-4885-bdf5-96a6ec59d37d.png)

### HTML5
Mostrar letras negritas en el primer párrafo, en los otros tres, letras curva:
```
<html>
<head>
</head>
<body>
<p><strong>Típos de datos</strong> en MySQL</p>
<p><em>TEXTO</em>: Para almacenar texto usamos cadenas de caracteres. Las cadenas se
colocan entre comillas simples. Podemos almacenar dígitos con los que no se realizan
operaciones matemáticas, por ejemplo, códigos de identificación, números de documentos,
números telefónicos. Tenemos los siguientes tipos: varchar, char y text.</p>
<p><em>NUMEROS</em>: Existe variedad de tipos numéricos para representar enteros,
negativos, decimales. Para almacenar valores enteros, por ejemplo, en campos que hacen
referencia a cantidades, precios, etc., usamos el tipo integer. Para almacenar valores con
decimales utilizamos: float o decimal.</p>
<p><em>FECHAS Y HORAS</em>: para guardar fechas y horas dispone de varios tipos: date
(fecha), datetime (fecha y hora), time (hora), year (año) y timestamp.</p> </body>
</html>
```
![5](https://user-images.githubusercontent.com/91631138/143612993-ae3ad11c-9f1d-44c1-9e11-0aac647122dd.png)

### HTML6
Mostrar un enlace con nombre "Noticias" y título "Página principal":
```
<html>
<head>
</head>
<body>
<h1>Página principal.</h1>
<a href="pagina2.html">Noticias</a>
</body>
</html>
```
![6](https://user-images.githubusercontent.com/91631138/143613340-981b0740-6645-4f10-9e9a-58e6cf8a6109.png)

### HTML7
Mostrar un enlace con nombre "Salir" y título "Noticias":
```
<html>
<head>
</head>
<body>
<h1>Noticias.</h1>
<a href="pagina1.html">Salir.</a>
</body>
</html>
```
![7](https://user-images.githubusercontent.com/91631138/143613560-7ed151e0-0390-4932-bb57-8392f9f53469.png)

### HTML8
Mostrar un enlace a google:
```
<html>
<head>
</head>
<body>
<a href="http://www.google.com">Buscador Google</a>
</body>
</html>
```
![8](https://user-images.githubusercontent.com/91631138/143613617-7e57517b-07ff-4544-a794-f885d1004297.png)

![8_1](https://user-images.githubusercontent.com/91631138/143613625-5b5830ee-c68c-448b-bcc6-68feb6aebb14.png)

### HTML9
Mostrar un enlace que contenga el correo del cliente:
```
<html>
<head>
</head>
<body>
<h1>Contacto</h1>
<a href="mailto:juanancaravaca@gmail.com">Enviar mail.</a>
</body>
</html>
```
![9](https://user-images.githubusercontent.com/91631138/143613793-ea817c7d-0814-42ee-8bf7-dcb9d72012e3.png)

### HTML10
Mostar el enlace de los titulos que vayas a poner en la página:
```
<html>
<head>
</head>
<body>
<h1>Tutorial de MySQL</h1>
<a href="#introduccion">Introducción</a><br>
<a href="#mostrarbasedatos">show databases</a><br>
<a href="#creaciontabla">Creación de una tabla y mostrar sus campos</a><br>
<a href="#cargarregistros">Carga de registros a una tabla y su recuperación</a><br>
<a name="introduccion"></a>
<h2>Introducción</h2>
<p>
SQL, Structure Query Language (Lenguaje de Consulta Estructurado) es un lenguaje de
programacion para trabajar con base de datos relacionales como MySQL, Oracle, etc.<br>
MySQL es un interpretador de SQL, es un servidor de base de datos.<br></p>
<a name="mostrarbasedatos"></a>
<h2>show databases</h2>
<p>
Una base de datos es un conjunto de tablas.<br></p>
<a name="creaciontabla"></a>
<h2>Creación de una tabla y mostrar sus
campos</h2> <p>
Una base de datos almacena sus datos en tablas.<br></p>
<a name="cargarregistros"></a>
<h2>Carga de registros a una tabla y su
recuperación</h2> <p>
Usamos "insert into". Especificamos los nombres de los campos entre paréntesis y separados por
comas y luego los valores para cada campo, también entre paréntesis y separados por
comas.<br>
</p>
</body>
</html>
```
![10](https://user-images.githubusercontent.com/91631138/143614032-eddbde75-95cb-4312-9522-8dbd6d1948ac.png)

### HTML11
Mostrar una foto en la página y si arrastras el raton encima de la foto verás un comentario:
```
<html>
<head>
</head>
<body>
<img src="https://avatars.githubusercontent.com/u/10197701?s=400&u=5f1e6fbfda101df156a5ad8d4f10f15f509f6e74&v=4" alt="El mejor profesor del mundo">
</body>
</html>
```
![11](https://user-images.githubusercontent.com/91631138/143614127-56ff15b6-98a0-4d58-9a4e-6bee39a7e318.png)

### HTML12
Pinchar una de las siguientes enlace para ver la foto:
```
<html>
<head>
</head>
<body>
<h2>Presione alguna de las imagenes para conocer más sobre esa obra.</h2>
<a href="pagina2.html"><img src="/imagenes/foto1.jpg" alt="Pintura Geométrica"> </a>
<a href="pagina3.html"><img src="/imagenes/foto2.jpg" alt="Pintura Geométrica"> </a>
</body>
</html>

```
![12](https://user-images.githubusercontent.com/91631138/143616092-a6deffc8-97b2-43bf-8248-4f3934417bb1.png)

### HTML13
```
<html>
<head>
</head>
<body>
<p>Esta obra fue desarrollada en el año 2003</p>
<a href="pagina1.html">Retornar</p>
</body>
</html>

```
![13](https://user-images.githubusercontent.com/91631138/143616416-73c3d1e7-19bd-498a-b5c8-749961113e33.png)

### HTML14
Mostrar el orden de los nombres;
```
<html>
<head>
</head>
<body>
<ol>
<li>Rodriguez Pablo</li>
<li>Gonzalez Raul</li>
<li>Lopez Hector</li>
</ol>
</body>
</html>
```
![14](https://user-images.githubusercontent.com/91631138/143616481-bd41d2c9-89e0-4320-96cb-5cf7af5fb33f.png)

### HTML15
Mostrar las enumeraciones de los países y algunos enlaces dentro de ellos;
```
<html>
<head>
</head>
<body>
<ol>
<li>Argentina
<ul>
<li><a href="http://www.lanacion.com.ar">La Nación</a></li>
<li><a href="http://www.clarin.com.ar">Clarín</a></li>
<li><a href="http://www.pagina12.com.ar">Página 12</a></li>
</ul>
</li>
<li>España
<ul>
<li><a href="http://www.elpais.es">El País
Digital</a></li> <li><a
href="http://www.abc.es">ABC</a></li>
<li><a href="http://www.elmundo.es">El Mundo</a></li>
</ul>
</li>
<li>México
<ul>
<li><a href="http://www.jornada.unam.mx">La Jornada</a></li>
<li><a href="http://www.el-universal.com.mx">El Universal</a></li>
</ul>
</li>
</ol>
</body>
</html>
```
![15](https://user-images.githubusercontent.com/91631138/143616601-9295234b-d4ee-4075-8721-26fc997a7064.png)

### HTML16
Mostrar una tabla con los paises y el número de habitantes:
```
<html>
<head>
</head>
<body>
<table border="1">
<caption>Población de los paises con mayor cantidad de
habitantes.</caption> <tr>
<th>Paises</th><th>Cantidad de habitantes</th>
</tr>
<tr>
<td>China</td><td>1300 millones</td>
</tr>
<tr>
<td>India</td><td>1080 millones</td>
</tr>
<tr>
<td>Estados Unidos</td><td>295 millones</td>
</tr>
</table>
</body>
</html>
```
![16](https://user-images.githubusercontent.com/91631138/143616737-f495df18-41a0-4e31-be7d-0f7b8ba74aa8.png)

### HTML17
Mostrar una tabla de recursos con la facturación de los últimos tres meses:
```
<html>
<head>
</head>
<body>
<table border="1">
<tr>
<th rowspan="4">Recursos</th><th colspan="4">Facturación de los últimos tres meses</th>
</tr>
<tr>
<td>Discos Duros</td><td>23000</td><td>27200</td><td>26000</td>
</tr>
<tr>
<td>CPU</td><td>73000</td><td>67300</td><td>51000</td>
</tr>
<tr>
<td>Monitores</td><td>53000</td><td>72000</td><td>88000</td>
</tr>
</table>
</body>
</html>
```
![17](https://user-images.githubusercontent.com/91631138/143616819-91d6f983-2361-42f1-a6ec-669040e1fb13.png)


