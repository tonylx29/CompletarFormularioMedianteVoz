# Generación de fichas de descripción de afloramientos y descripción macroscópica de rocas por voz

Esta guía proporciona instrucciones sobre cómo instalar Vosk, un kit de herramientas de reconocimiento de voz, junto con los requisitos necesarios para su funcionamiento.

## Universidad Nacional de Loja 
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcROxZ2VGD6VkPMD0pDcTCWbGb8GrOQnyGTyh5184RHz3xhjOUr-sQEtJG3E0Rp3_-tlWaE&usqp=CAU" alt="Texto alternativo" width="150"/>

**Información del Proyecto**

**Materia:**
Human Perception in Computer Vision

**Integrantes:**
- Luis Bermeo
- Anthony Luzuriaga
- Gerardo Quizhpe
- Alex Viñamagua

El proyecto se trata de usar el modelo Vosk en su versión en español para generar fichas de descripción de afloramientos y descripción macroscópica de rocas. Para la generación de la interfaz gráfica, el documento menciona que se utiliza la tecnología Gradio. Gradio es una biblioteca de Python que permite crear interfaces de usuario simples y rápidas para modelos de aprendizaje automático y otras aplicaciones interactivas. Proporciona una forma sencilla de diseñar y desplegar interfaces interactivas sin necesidad de conocimientos avanzados de programación de interfaces de usuario. Puedes encontrar más información sobre Gradio en su [documentación oficial](https://www.gradio.app/docs/).
<div style="text-align: center;">
<img src="https://www.adelean.com/img/posts/indexation_des_transcripts_image.png" alt="Texto alternativo" width="400"/>

Para obtener información detallada y ejemplos de código, consulta las páginas correspondientes en el documento.
</div>

## Propósito
El propósito de instalar Vosk es habilitar capacidades de reconocimiento de voz en tus aplicaciones o proyectos. Vosk ofrece un motor de reconocimiento de voz potente y eficiente que puede integrarse en diversas soluciones de software.

<div style="text-align: center;">
    <img src="https://www.sinologic.net/wp-content/uploads/2021/03/vosk_big.png" alt="Texto alternativo" width="200"/>
</div>

## Pasos para usar el proyecto.
1. **Descarga del modelo Vosk-esp**:
1. Dirijirse al siguiente link: https://alphacephei.com/vosk/models
2. Buscar el modelo en español, en este caso se tiene que buscar y descargar el modelo-vosk-es-0.42. Como se en la siguiente imagen.
![image](https://github.com/tonylx29/CompletarFormularioMedianteVoz/assets/85810032/d4ad0a3a-12c5-4e39-90b3-02c715fae30d)

2. **Luego de la descarga**: Después de la descarga, se tiene que pegar el modelo dentro de la carpeta del proyecto, en una carpeta llamado model, asi:
![image](https://github.com/tonylx29/CompletarFormularioMedianteVoz/assets/85810032/566d43bd-04b2-4e93-8c2b-63a46f28a79b)

![image](https://github.com/tonylx29/CompletarFormularioMedianteVoz/assets/85810032/0ecbefb0-ddbb-4f72-beb0-ad810201ea90)

3. **Descargue el proyecto de git.**

4.  **Corra el proyecto**. Corra todas las lineas de código del proyecto, hasta llegar a la ultima linea que donde se genera la interfaz abriendo un puerto.
Establezca un puerto por defecto, y corra el proyecto con **demo.launch()**, o cierre el proyecto y su puerto con **demo.close()**, que son las líneas comentadas, tal y como se muestra en la imagen.

![image](https://github.com/tonylx29/CompletarFormularioMedianteVoz/assets/85810032/2bb93056-04f2-490f-8325-dbd2f1bcebbc)

5. **Pruebe la interfaz**. Luego de a ver seguido todos estos pasos. Se le desplegara la interfaz en el puerto asignado.
![image](https://github.com/tonylx29/CompletarFormularioMedianteVoz/assets/85810032/9c50052f-4e8a-43eb-ae2c-03d91f83fc69)


Nota adicional:
Se tiene que descargar el modelo vosk de forma manual ya que por el peso del modelo hubo problemas al momento de subirlo al repositorio.


## Programas y Librerias
- Python
- Pyaudio
- Pygame
- gTTS
- Vosk-es
- json
- wave
- tempfile
- os
- time

## Información Adicional
- El documento incluye fragmentos de código para reproducir texto como audio usando Pygame y capturar voz usando modelos de Vosk.
- También proporciona orientación sobre la generación de documentos Word y el guardado de los resultados.
