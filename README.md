# Desarrollando mi Propio Transcriptor de Reuniones

Este proyecto consiste en un script de Python que permite transcribir y mejorar el texto de reuniones presenciales. Está diseñado para aquellos que necesitan una solución para convertir grabaciones de audio en texto sin depender de plataformas de videollamadas como Zoom o Google Meet. El script automatiza el proceso de conversión, transcripción, mejora del texto y generación de resúmenes, usando varias bibliotecas de Python.

## Características principales:

* Conversión de formatos de audio: Transforma archivos M4A a MP4 utilizando FFmpeg.
* Unificación y división de audio: Combina múltiples archivos de audio en un solo archivo y los divide en segmentos manejables de 5 minutos.
* Transcripción automática: Usa Whisper para convertir el audio en texto.
* Mejora de la redacción: Integra técnicas de procesamiento de lenguaje natural (NLP) con la API de OpenAI para corregir errores y mejorar la calidad del texto.
* Generación de resúmenes: Extrae y sintetiza los puntos clave de la reunión.
* Automatización del flujo de trabajo: Elimina archivos temporales y organiza el entorno de trabajo.

## Tecnologías y bibliotecas utilizadas:
* Whisper: Para la transcripción del audio.
* Pydub: Para la manipulación de archivos de audio.
* FFmpeg: Utilizado para la conversión de formatos de audio.
* Pandas: Para el manejo y análisis de los datos transcritos.
* OpenAI: API para mejorar la redacción y generar resúmenes.

## Consideraciones Legales:
Antes de grabar cualquier reunión, asegúrate de obtener el consentimiento de todos los participantes. Grabar sin permiso puede tener implicaciones legales.

### Futuras Mejoras:
Planeo automatizar el envío de audios a través de WhatsApp y recibir el texto procesado de forma automática para facilitar aún más el flujo de trabajo.

# Sígueme en mis redes sociales
Si quieres saber mas de este fascinante mundo de la inteligencia artificial y el análisis de datos te invito a que me sigas en mis redes sociales, como Edgar Arnoldo Sierra, Edgar Sierra o Noyomedicen
