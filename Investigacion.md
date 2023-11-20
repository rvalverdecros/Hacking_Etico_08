# Investigacion de El Pozo

Se nos ha mandado la tarea de buscar información sobre “El Pozo”, así que vamos a seguir unas pautas con las que vamos a llevar a cabo en análisis de la empresa

## Índice
1. [Información Whois] (#id1)
2. [Servidores DNS] (#id2)
3. [Servidores de Correo] (#id3)
4. [Subdominios] (#id4)
5. [Información adicional] (#id5)

## Información Whois<a name="id1"></a>

Para tener esta información, vamos a usar el comando de Linux (En este caso vamos a usar Kali Linux), whois.

* whois elpozo.com

Lo que nos sale es todo esto:

![](img/1.png)

En ella podemos sacar distinta información, como número de contacto, dirección de correo, creación del dominio, entre más cosas.

Ahora bien queremos investigar también cuál es la IP que usa la empresa, es por eso que vamos a usar otro comando que tiene Linux, para obtener la IP:

* nslookup elpozo.com

![](img/2.png)

Con ese comando y como se ve en la imagen hemos podido obtener la IP que usa El Pozo.

## Servidores DNS<a name="id2"></a>

Si queremos buscar el DNS de El Pozo, para eso vamos a la página web de dnsdumpster.com donde si ponemos elpozo.com, podemos obtener el DNS:

![](img/3.png)

## Servidores de Correo<a name="id3"></a>

Si queremos obtener servidores de correo, vamos a usar la herramienta de nslookup, con el cual podemos, los correos de El Pozo:

![](img/4.png)

También, como alternativa, podemos usar la herramienta de dig:

![](img/5.png)

## Subdominios<a name="id4"></a>

Para los subdominios, hemos usado dnsdumpster, el cual nos hace un mapeo del dominio y podemos ver en el siguiente enlace todos los subdominios que tiene El Pozo:

* [https://dnsdumpster.com/static/map/elpozo.com.png]

## Información adicional<a name="id5"></a>

Buscando más por Google, quiero ver la conexión que tiene la empresa a lo largo de todo internet, así que he podido encontrar todas las redes sociales de El Pozo.

He usado la página web de redessociales.de y he buscado El Pozo.

He podido obtener su Facebook, Twitter, Linkedin, Youtube, Instagram:

![](img/6.png)

Si podemos acceder a su Linkedin, podemos ver los trabajadores que hay en la empresa, y podemos sacar los nombres de ellos junto al rol, por ejemplo, podemos conseguir la persona que está a cargo del control de producción, trade Marketing..:

![](img/7.png)

Esta información es muy importante, porque podemos ver que tipo de persona esta trabajando en El Pozo, y podemos hacer  un análisis exhaustivo de los empleados de El Pozo.
