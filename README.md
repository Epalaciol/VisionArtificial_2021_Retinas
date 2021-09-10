# VisionArtificial_2021_Retinas
[Pagina Principal](https://epalaciol.github.io/VisionArtificial_2021_Retinas/index.html)


## Entrega Final:
 continuación se encuentra los links de la pagina HTML y los notebooks
- [Notebook Entrega Final](https://github.com/Epalaciol/VisionArtificial_2021_Retinas/blob/master/Exposicion_Final/TrabajoRetinas_Alejandra_final.ipynb)


##  Entrega 1:
A continuación se encuentra los links de la pagina HTML y los notebooks
- [Notebook Entrega 1 diapositivas bien](https://github.com/Epalaciol/VisionArtificial_2021_Retinas/blob/master/Exposicion/TrabajoRetinas_Alejandra.ipynb)
- [Notebook Entrega 1 diapositivas bien (DESCARGA automatica)](https://epalaciol.github.io/VisionArtificial_2021_Retinas/Exposicion/TrabajoRetinas_Alejandra.ipynb)

## Descripción del problema: 
https://drive.grand-challenge.org/DRIVE/

## Activar entornos virtuales 
Para evitar subir archivos tan pesado a github y toda la libreria vamos a crear un ambiente virtual, de preferencia este ambiente se va a llamar _visionenv_ (en caso de que se decida poner otro nombre tenga en cuenta ponerlo en .gitignore)

1. Primero nos paramos en la carpeta del proyecto  en consola se debe de ver algo como lo siguiente

```
/Desktop/Personal/Vision_2021/VisionArtificial_2021_Retinas
```
 lo importante es que al final de se vea el `/VisionArtificial_2021_Retinas`.

2. Estando ubicados en la carpeta del proyecto  ejecutamos el siguiente comando

```
python -m ven visionenv
```
en algunos casos este no puede funcionar y ejecutamos el siguiente:

```
python3 -m venv visionenv
```

3. Vemos que se creo una carpeta llamada visionenv. Ahora lo que debemos de hacer es prender el entorno virtual, para este paso  se depende del sistema operativo en el cual se este trabajando
 
**RECOMENDACION:** no apague/desactive el entorno virtual 

### Windows

- Para activar en entorno virtual corremos el siguiente Comando en la consola de comandos

``` 
visionenv\Scripts\activate
```

- Para desactivar el entorno virtual corremos el siguiente comando en la consola de comandos

```
deactivate
```


### Linux/ ubuntu 

- Para activar en entorno virtual corremos el siguiente Comando  en la consola de comandos
```
source visionenv/Scripts/activate
```
Algunas veces este puede no funcionar por lo cual ejecutamos el siguiente
```
source visionenv/bin/activate
```

- Para desactivar el entorno virtual corremos el siguiente comando en la consola de comandos

```
deactivate
```
4. Ya con el entorno virtual creado y prendido/activado procedemos a la instalacion de las librerias que esta usando el proyecto, para esto ejecutamos el siguiente comando `pip install -r requirements.txt`

5. Esperamos a que todo descargue y ya quedamos con el entorno virtual  totalmente funcional.

6. Ya que tiene el entorno de manera local para el uso de este en un futuro solo requiere los comandos descritos en el punto 3. 
