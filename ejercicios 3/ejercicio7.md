#Ejercicio 7

##Apartado A: Destruir toda la configuración creada anteriormente

Para destruir lo configurado anteriormente debemos usar:

    juju destroy-environment local
    
![](snapshot9.png)

##Apartado B:Volver a crear la máquina anterior y añadirle mediawiki y una relación entre ellos.

Llevamos a cabo:

    juju bootstrap
    juju deploy mysql
    juju deploy mediawiki
    
![](snapshot7.png)
![](snapshot8.png)
![](snapshot10.png)
