# CityRecommenderBayesian
Sistema inteligente de recomendación de destinos turísticos en Colombia, basado en redes bayesianas para generar sugerencias según las preferencias del usuario.

Para un correcto funcionamiento se debe crear un proyecto en unity y añadir las carpetas Resources, Scenes y Scrips a la carpeta assets del proyecto
Tambien se debe añadir el prefab "image" en la misma instancia
![Captura de pantalla 2024-12-04 200547](https://github.com/user-attachments/assets/60ffc53e-0934-4f53-8d1b-2d8178e3cd5d)
luego se deben añadir todas las escenas al scene list como se muestra a continuación
![Captura de pantalla 2024-12-04 200302](https://github.com/user-attachments/assets/c61bf4e1-1930-4e8e-9f4a-06a551c88701)
tambien es necesario instalar la libreria pomegranate en su editor de python con el comando
pip install pomegranate
Para un correcto funcionamiento del programa debe ejecutar el codigo "Ejecutable" que se encuentra dentro de la carpeta "Red Bayesiana" el cual es el servidor que conecta la interfaz de unity con el modelo y procesa las respuestas dadas por el usuario atraves de unity.
