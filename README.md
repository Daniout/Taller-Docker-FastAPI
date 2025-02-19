Pasos para la creacion y ejecucion de una imagen en docker:

construcción de la imagen en la terminal de docker: docker build -t myimage .

ejecucion del contenedor con nuestra imagen: docker run -d --name mycontainer -p 80:80 myimage

Subida hacia docker hub: docker push daniout/myimage

Evidencias fotograficas dentro de la carpeta app con los procedimientos mas importantes utilizados para la realizacion del taller.
