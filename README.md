# 2º GSI – Bezmiliana EJECUTANDO Y GESTIONANDO CONTENEDORES

## 19 de octubre del 2026

## Samuel Rivas Fernández

![Portada](img/01.png)

## **Descarga de imagenes**

## Primero instalo las imágenes de ubuntu, debian, mariadb, mysql y httpd

![pull ubuntu](img/02.png)
![pull debian](img/03.png)
![pull mariadb](img/04.png)
![pull mysql](img/05.png)
![pull httpd](img/06.png)

## Y estas son las imágenes descargadas

![Imgenes de docker](img/07.png)

## **Arranca un contenedor**

## Creo el contenedor y arranco el ubuntu

![arranco ubuntu](img/08.png)

## Salgo del ubuntu

![proceso de ubuntu](img/11.png)

## Y muestro que me he salido

![pull httpd](img/09.png)

## Arranco de nuevo el contenedor

![](img/10.png)

## Y en otra terminal muestro los contenedores activos

![][image12]

## Muestro el fichero /etc/os-release sin meterme a la máquina 

![][image13]

## **Ejecutar servicios desde contenedores**

## Arrancar el contenedor de php-apache que se llame web y que sea accesible desde el puerto 8181

## ![][image14]docker  ps compruebo si el contenedor está activo

![][image15]

## Creo el index.html

![][image16]

## Ahora copio el index.html

![][image17]

## Creo el PHP

## ![][image18]

## Y subo el php también

![][image19]

## Y aqui se ve como se puede ver la web desde el navegador

![][image20]

![][image21]

## Ahora instalo la base de datos

![][image22]

![][image23]

## Y la base de datos funciona perfectamente

![][image24]

## **Obtener información de los contenedores**

## Compruebo la IP del contenedor web

![][image25]

## Y compruebo el puerto del contenedor web

![][image26]

## Compruebo la IP de la base de datos

![][image27]

## Y su puerto

![][image28]

