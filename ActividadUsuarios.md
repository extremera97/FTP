# Actividad1(Guiada)

(Lo aconsejable para realizar es contar con máquinas Ubuntu 18.04 que es donde se han realizado las pruebas, y que tengan instalado tanto webmin como filezilla, si no se cuenta con webmin este link te llevará a un tutorial sobre como instalarlo,importante poder utilizar permisos de root en la máquina). [https://clouding.io/kb/como-instalar-webmin-en-ubuntu-18-04/]

Una vez tengamos todo listo podemos empezar:

1.Lo primero de todo es crear el usuario pero, ¿cómo haremos eso? muy sencillo accedemos a este apartado dentro de webmin.

![Captura](./imagenes/Captura.PNG)

Una vez estemos ahí accederemos donde pone **users and groups**, una vez lo hagamos se nos abrirá este asistente:

![Captura2](./imagenes/Captura2.PNG)

Una vez estemos ahí tendremos que darle a **create new user** cuando le demos nos abrirá un asistente nuevo:

![Captura3](./imagenes/Captura3.PNG)

Aquí es donde le daremos un nombre de usuario, para tenerlo mejor organizado lo llamaremos usuarioftp y la contraseña  le pondremos la que queramos nosotros. Después de este paso y de darle a **save changes** ya tendríamos el usuario creado, ahora pasaremos a crear el grupo ftp para tenerlo todo mejor organizado:
(**¡IMPORTANTE! PONER CONTRAEÑA DE LA CUAL NOS ACORDEMOS**)

![Captura4](./imagenes/Captura4.PNG)

Y al igual que con los usuario tendremos que clickar en **create new group** y se abrirá un asistente:

![Captura5](./imagenes/Captura5.PNG)

Aquí le pondremos el nombre del grupo, y en la parte de abajo donde pone **Members** buscaríamos el usuarioftp que hemos creado y lo uniríamos al grupo. 

Ahora vamos a comprobar que efectivamente nuestro usuario se puede conectar al servidor:(*Para conectarnos al servidor tenemos que poner ftp dirección ip del servidor*)

![Captura6](./imagenes/Captura6.PNG)

Como podemos observar nos pide un nombre usuario, simplemente tendríamos que escribir el nombre que hemos creado antes, una vez lo ingresemos nos pedirá la contraseña, por eso es importante que os acordéis de ella:

![Captura7](./imagenes/Captura7.PNG)

[Volver a la página principal](README.md)
