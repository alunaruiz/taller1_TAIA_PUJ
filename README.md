# taller1_TAIA_PUJ
Taller 1 - Topicos avanzados en Inteligencia Artificial
Autores: 
Daniel Felipe Chavarro Sánchez
Alexander Luna Ruiz

1. Ejecutar el docker:
sudo docker run -it --name tfx --rm -p 8888:8888 -p 6006:6006 -v $PWD:/tfx/src --entrypoint /run_jupyter.sh  tensorflow/tfx:1.12.0
En este caso, la ejecución del docker file ejecuta a su vez las dependencias que se encuentran en el archivo requeriments.txt.

2. Una vez se cargue el docker, se ingresa a la URL generada por el comando 'docker run' y se ingresa con el token generado.

3. Se abre el archivo 'proyecto1_Topicos.ipynb'.

4. Se sigen las instrucciones dadas en el notebook.
