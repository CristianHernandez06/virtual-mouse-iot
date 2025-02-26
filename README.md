# virtual-mouse-iot

# Ratón Virtual usando OpenCV

En este proyecto usaremos la alimentación en vivo de la cámara web para crear un ratón virtual mediante el seguimiento de la mano.

## Descripción del Proyecto
En este proyecto, utilizo mi mano como un ratón virtual que puede realizar todas las funciones de un ratón sin necesidad de tocar el sistema. Se usa la cámara web para detectar la mano, dibujando un recuadro alrededor de ella y enfocándose en dos dedos: el índice y el dedo medio. El dedo índice actuará como cursor, permitiendo moverlo por la pantalla; mientras que, para realizar un clic, se detecta la distancia entre el dedo índice y el dedo medio. Si ambos se juntan, se ejecuta la acción de clic.

Además, se ha añadido un factor de suavizado para corregir el movimiento inestable del cursor.

## Requisitos
Para que este proyecto funcione correctamente, se deben instalar los siguientes módulos:

- **OpenCV:**  
  OpenCV es una extensa librería de código abierto para visión por computadora, aprendizaje automático y procesamiento de imágenes. Soporta varios lenguajes de programación como Python, C++, Java, entre otros. Puede procesar imágenes y videos para identificar objetos, rostros o incluso la escritura a mano.  
  Se instala con:  
pip install opencv-python


- **Mediapipe:**  
Mediapipe es un framework para construir pipelines de aprendizaje automático multimodales (por ejemplo, video, audio, o cualquier dato de series temporales) y es compatible con múltiples plataformas (como Android, iOS, web y dispositivos edge).  
Se instala con:  
pip install mediapipe



- **Autopygui:**  
Autopygui es una biblioteca sencilla y multiplataforma para la automatización de la interfaz gráfica en Python. Incluye funciones para controlar el teclado y el ratón, buscar colores y bitmaps en pantalla, y mostrar alertas.  
Se instala con:  
pip install autopygui



## Nota Importante
He enfrentado varios problemas de dependencias a lo largo de este proyecto. Algunas de las incidencias y sus soluciones son las siguientes:
- **autopygui no se instala:** Esto ocurre porque autopygui actualmente no soporta versiones de Python superiores a la 3.8.
- **La cámara web no se abre:** Fue un error en mediapipe, corregido en las versiones más recientes de Python.

Por lo tanto, para que el proyecto funcione sin inconvenientes, es necesario degradar la versión de Python a la 3.8.

### Cómo Degradar la Versión de Python:
1. Desinstala Python desde "Agregar o quitar programas".
2. Ve a la carpeta AppData y elimina cualquier carpeta relacionada con Python.
3. Descarga Python 3.8 desde este enlace: [Python 3.8](https://www.python.org/downloads/release/python-380/).
4. Instálalo.
5. Abre la línea de comandos y ejecuta `pip` para confirmar la instalación.
6. ¡Listo! Tu versión de Python ha sido degradada.

## Créditos

Agradecimiento especial por el aporte de autopygui:

```CristianHernandez06```

## 📫 Contacto
<p align="center">
<a href="http://www.hxndev.com/"><img src="https://img.icons8.com/bubbles/50/000000/web.png" alt="Website"/></a>
<a href="mailto:chhxnshah@gmail.com"><img src="https://img.icons8.com/bubbles/50/000000/gmail.png" alt="Gmail"/></a>
<a href="https://github.com/HxnDev"><img src="https://img.icons8.com/bubbles/50/000000/github.png" alt="GitHub"/></a>
<a href="https://www.linkedin.com/in/hassan-shahzad-2a6617212/"><img src="https://img.icons8.com/bubbles/50/000000/linkedin.png" alt="LinkedIn"/></a>
<a href="https://www.instagram.com/hxn_photography/?hl=en"><img src="https://img.icons8.com/bubbles/50/000000/instagram.png" alt="Instagram"/></a>
</p>




