# CONTROL_JOYSTICK






## Tabla de Contenidos

1. [Comentarios generales](#Comentarios-generales)
2. [Configuración del Joystick](#Configuración-del-Joystick)
3. [Prueba de conexión](#Prueba-de-conexión)
3. [Gráficos generados](#Gráficos-generados)


## Comentarios generales
Para poder controlar al TurtleBot con el control de Joystick tenemos que tener configurada la parte del Autosatart la cual inicializa al TurtleBot al encender la Jetson, si aún no está configurado puedes ir al repositorio [AUTOSART](https://github.com/ERICKLOCR/AUTOSART)

Se tiene que tener configurada la parte de comunicación mediante SSH entre computadora y Jetson. Puedes encontrar los pasos en el repositorio [SSH](https://github.com/ERICKLOCR/AUTOSART)

Se tiene que descargar el repositorio para poder ejecutar los scrips en matlab.
Para ello dirigite en la carpeta donde desa clonar el repositorio copia la dirección y la terminal coloca

```
cd DIRECCIÓN EN LA QUE SE DESEA CLONAR
```
Y posteriormente 

```
git clone httt
```



   
## Configuración del Joystick

Conectar el Joystick a la computadora y para saber que puerto le asigna la computadora, puede ser js0,js1,jsi
```
ls /dev/input/
```
<p align='center'>
    <img src=./IMÁGENES/j1.png alt="drawing" width="600"/>
</p>

En nuestro caso nos asignó js0 
```
sudo jstest /dev/input/js0
```
<p align='center'>
    <img src=./IMÁGENES/j2.png alt="drawing" width="600"/>
</p>


<p align='center'>
    <img src=./IMÁGENES/j3.png alt="drawing" width="600"/>
</p>


<p align='center'>
    <img src=./IMÁGENES/j4.png alt="drawing" width="600"/>
</p>

### En la computadora con Windows





