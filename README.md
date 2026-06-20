# Vision_Artificial_Modelo

César Octavio Ríos Tinoco              23310390

Victor Manuel Hernandez Ortega         23310386

Instrucciones de uso:

1- Se ingresa al Notebook de Google Colab
https://colab.research.google.com/drive/1hWygByiLFx_MjXuMp58jr_k7-jcLOtrg#scrollTo=MZaQil4x-gmw
2-Si es la primera vez que se prueba se ejecuta desde el principio
3-Si ya se han realizado pruebas anteriores se empieza a ejecutar desde el apartado para subir la imagen a analizar
<img width="901" height="222" alt="image" src="https://github.com/user-attachments/assets/cca89978-acbd-4959-b60d-5b31d150412d" />
3.1- Al subir la imagen a analizar se le tiene que cambiar el nombre de la imagen en las siguientes secciones de codigo y se corren en el orden que se encuentran
<img width="890" height="340" alt="image" src="https://github.com/user-attachments/assets/55adf161-beb5-4dee-8e90-3aa2dd5153f2" />
4- Al ejecutar el ultimo cuadro de codigo se muestra el resultado de la imagen analizada
<img width="894" height="460" alt="image" src="https://github.com/user-attachments/assets/a16c5d94-f436-4505-9261-6e29fbb7e7ae" />


Caso de Estudio:
En las plantas de reciclaje la clasificacion de residuos suele realizarse manualmente lo que es ineficiente, conlleva un costo operativo mas alto, los trabajdores que se encargan del separado se exponen a peligros por revisar y manipular los residuos, ademas de la baja velocidad de clasificacion

Con este proyecto se busca reducir los puntos anteriores ya que no es necesario que los trabajadores esten manipulando los residuos, lo que hace que el costo operativo sea menor, no haya errores de clasificacion y se aumente la velocidad de clasificacion, entre otros

Por medio de un modelo YOLO se busca entrenar para que detecte los diversos residuos reciclables como lo es:
- Plastico
- Latas de aluminio
- Carton
- Cristal

Las Herramientas y materiales necesarios para poder llevar a cabo este proyecto en la industria son necesarias:
- Camaras HD
- Computadora 
- Actuadores (Brazos Roboticos o compuertas)
- Banda transportadora (Donde pasaran todos los residuos)

Proceso en la industria:
- Los residuos entrar en la banda transportadora
- La camara captura la imagen
- YOLO identifica que tipo de residuo es
- Se determina la categoria
- Se activa el actuador necesario para separarlo

