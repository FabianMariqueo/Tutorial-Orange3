# Creando una regresion lineal

##	Crear un nuevo workflow

### Abrir la herramienta 

- Al momento de abrir la herramienta, nos encontramos con la siguiente pantalla.
#
![Inicio](img/InicioOrange.PNG)
#
- De las opciones disponibles seleccionaremos, *“New”* para crear un nuevo proyecto.
#
![nuevo](img/nuevoProyecto.PNG)
#
- Asignamos un nombre a nuestro trabajo.
#
![nombre](img/asignaNombre.PNG)

## Opciones disponibles

- Dentro de la paleta ubicada en la parte derecha, encontraremos una serie de opciones.
![opciones](img/paletaOpciones.PNG)

## Ingresar datos por archivo

- Para nuestro caso vamos a trabajar con datos q se encuentran dentro de una planilla excel, por lo tanto,
necesitaremos descargar los datos desde el siguiente [link](https://help.xlstat.com/customer/es/portal/articles/2062231-como-realizar-una-regresion-lineal-multiple?b_id=9283).

#
- Para cargar el archivo utilizaremos la opcion *"File"* que se encuetra dentro de la categoría Data de Orange
#
![file](img/opcionData.PNG)

#
- Dentro del elemento *"File"* seleccionaremos nuestro archivo excel con los datos. En este caso se llama
*demo01MultiReg.xls*.
#
![file](img/file.PNG)
#
- **Importante**: en la tabla que aparece debemos cambiar la opcion que aparece a *skip* en caso de que el dato de 
esa columna no nos interese. De lo contrario, debemos cambiar la opción a *feature*. Para nuestro ejemplo solo seleccionamos
los datos **Height** y **Weight**, y el resto de las columnas del archivo las ignoramos.
#![important](img/file-important.PNG)

## Dibujar los datos

Al momento de cargar los datos, los podemos graficar con la herramienta *Paint Data* que se encuentra en la categoría *Data*