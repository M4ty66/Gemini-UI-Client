# Gemini UI Client 🚀

Una interfaz web ligera, rápida y moderna para interactuar con la API oficial de Google Gemini, diseñada para funcionar como un cliente web local o como una aplicación independiente de escritorio.

---

## ✨ Características y Mejoras
- **Motor Oficial Gemini:** Adaptado desde cero para consumir la API de Google (compatible con modelos Flash, Pro y Preview).
- **Organización Inteligente:** Los modelos se agrupan automáticamente en categorías visuales (Flash, Flash Lite, Pro, Preview) y se filtran los modelos incompatibles de voz o imágenes.
- **Historial Local:** Guarda tus conversaciones automáticamente en el navegador (`localStorage`) con opción de exportar e importar en formato `.json`.
- **Multimedia:** Soporta subida de imágenes y lectura de archivos de código (TXT, JS, PY, HTML, etc.).
- **Diseño Adaptativo:** Interfaz oscura, moderna, con renderizado de Markdown, bloques de código copiables y soporte para fórmulas matemáticas (MathJax).

---

## 🛠️ Cómo Empezar
1. Clona o descarga este repositorio en tu computadora.
2. Abre el archivo `Gemini client.html` (o `index.html`) en tu navegador web.
3. Introduce tu **API Key de Gemini** (puedes conseguir una gratis en [Google AI Studio](https://aistudio.google.com/)).
4. Selecciona tu modelo favorito y comienza a chatear.

---

## 🖥️ Truco Pro: Ejecutar como Aplicación de Escritorio (Sin pestañas - Mejora el rendimiento)

Si usas un navegador basado en Chromium (como **Supermium**, **Google Chrome** o **Microsoft Edge**), puedes hacer que este cliente funcione como un programa independiente de Windows, sin barras de direcciones ni pestañas:

1. Ve a tu escritorio, haz clic derecho en un espacio vacío y selecciona **Nuevo > Acceso directo**.
2. En la ruta del elemento, pega el siguiente comando (ajustando la ruta según dónde tengas guardado tu archivo):
 "C:\Program Files\tu\navegador.exe" --app="C:\Ruta\De\Tu\Carpeta\Gemini client.html"
 
    *(Nota: Si usas Chrome o Edge, cambia la primera parte por la ruta de su respectivo `chrome.exe` o `msedge.exe`)*.
3. Haz clic en **Siguiente**, asígnale un nombre (ej. *Gemini UI*) y haz clic en **Finalizar**.

---

## 🎨 Cómo Ponerle el Logo de Gemini

Para que tu acceso directo luzca como una aplicación real con el logo de Gemini:

1. Descarga el logo de Gemini en formato PNG y conviértelo a formato **`.ico`** (puedes usar webs gratuitas como *ICO Convert*). Guarda el archivo como `gemini.ico` en la misma carpeta del proyecto.
2. Haz clic derecho sobre el acceso directo que creaste en el escritorio y selecciona **Propiedades**.
3. En la pestaña *Acceso directo*, haz clic en el botón **Cambiar icono...**
4. Busca y selecciona tu archivo `gemini.ico`, haz clic en **Aceptar** y luego en **Aplicar**.
---

## 📜 Créditos y Agradecimientos
* Este proyecto está basado en el excelente trabajo de [N1xUser/OpenAI-HTML-Client](https://github.com/N1xUser/OpenAI-HTML-Client).
* Modificado, adaptado a la API oficial de Google Gemini, optimizado y estructurado por [M4ty66](https://github.com/M4ty66).