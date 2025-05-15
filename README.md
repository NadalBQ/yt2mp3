# 🎵 yt2mp3

**yt2mp3** es una herramienta de línea de comandos que permite descargar el audio en formato MP3 de una lista de vídeos de YouTube, de forma rápida y sencilla. Es un proyecto de desarrollo personal diseñado para automatizar el proceso de conversión desde enlaces de YouTube a archivos de audio.

---

## 🚀 ¿Cómo funciona?

Al ejecutar el programa, se inicia una sesión interactiva en la consola en la que se te solicitará:

1. **Ruta del directorio que contiene el archivo de enlaces** (por ejemplo: `C:\Users\TuNombre\Documentos`).
2. **Nombre del archivo que contiene los enlaces** (por ejemplo: `enlaces.txt`).
3. **Ruta del directorio de descarga** (por ejemplo: `C:\Users\TuNombre\Música\YTMP3`).

Una vez proporcionados estos datos, el programa:

- Lee la lista de enlaces de YouTube desde el archivo especificado.
- Comienza a descargar y convertir cada vídeo a MP3.
- Imprime en la consola el progreso de cada descarga.
- Se cierra automáticamente al finalizar el proceso.

---

## 🧰 Requisitos

Antes de ejecutar **yt2mp3**, asegúrate de tener lo siguiente instalado y correctamente configurado en tu sistema:

- [**ffmpeg**](https://ffmpeg.org/download.html)
- [**ffprobe**](https://ffmpeg.org/ffprobe.html)

Ambos ejecutables deben estar **incluidos en la variable de entorno `PATH`** para que el programa pueda invocarlos desde cualquier ubicación.

---

## 🛠 Dependencias y créditos

Este programa se apoya en la funcionalidad de [**yt-dlp**](https://github.com/yt-dlp/yt-dlp), una herramienta poderosa y mantenida activamente para la descarga de vídeos y audios desde múltiples plataformas.  
**yt2mp3** emplea sus instrucciones y opciones de conversión para facilitar la extracción de audio en formato MP3.

Agradecimientos al equipo de desarrollo de `yt-dlp` por su trabajo excepcional.

---

## 📂 Estructura esperada

Asegúrate de que tu archivo de texto contenga **un enlace de YouTube por línea**, por ejemplo:

https://www.youtube.com/watch?v=abc123
https://www.youtube.com/watch?v=xyz456

---

## ⚠️ Uso bajo tu propia responsabilidad

Este software se proporciona **únicamente con fines educativos y de desarrollo personal**.

- **yt2mp3 no promueve el uso del programa para la descarga de contenido protegido por derechos de autor** sin el permiso correspondiente.
- El uso del programa para actividades que infrinjan los **Términos de Servicio de YouTube** u otras plataformas es responsabilidad del usuario.
- **Cualquier consecuencia derivada del uso indebido de este programa recae exclusivamente sobre el usuario**.

---

## 📌 Estado del proyecto

Este proyecto está en desarrollo activo como parte del aprendizaje personal del autor. Se ofrece "tal cual", sin garantía de mantenimiento o soporte. Contribuciones o sugerencias son bienvenidas en el apartado de *Issues* o mediante *Pull Requests*.

