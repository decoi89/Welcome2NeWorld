# Welcome2NeWorld

Este proyecto está diseñado para ser utilizado como página de aterrizaje al escanear una etiqueta NFC. Su función principal es facilitar la conexión a una red WiFi y redirigir a los usuarios a la descarga de dos aplicaciones esenciales para el acceso y gestión de funciones en NeWorld.

---

## 🔧 Funcionalidad

- 📲 **Detección automática del sistema operativo (Android / iOS)**  
  Según el dispositivo, los botones redirigen a la **Play Store** o la **App Store** correspondientes para cada aplicación.

- 📶 **Acceso a red WiFi**  
  Incluye un código QR escaneable para conectarse manualmente a la red en caso de que la conexión automática no funcione.

- 📥 **Botones de descarga inteligentes**  
  Dos botones permanentes:
  - **Tuya App**
  - **Int_egra App**  
  Al pulsarlos, cambian su estilo y texto a `"Abriendo..."`.

- 🖼️ **Zona de imágenes de convivencia**  
  Rejilla de 3 columnas con normas visuales para fomentar la buena convivencia. Puedes añadir más imágenes simplemente cargándolas en el repositorio.

---

## 📁 Archivos importantes

- `index.html` — Página principal del sitio.
- `background.png` — Cabecera de la web.
- `icon.png` — Icono representativo superior.
- `wifi-qr.png` — Código QR para conexión WiFi.
- `convivencia1.jpg`, `convivencia2.jpg`, etc. — Imágenes normativas.

---

## ✏️ Personalización

Puedes editar fácilmente el contenido desde el archivo `index.html` o añadir nuevas imágenes en la sección final. Los botones están programados en JavaScript para adaptarse automáticamente al sistema operativo.

---

## 🚀 Uso con GitHub Pages

Este repositorio está pensado para ser alojado mediante **GitHub Pages**, y ser enlazado desde una etiqueta NFC para que los dispositivos móviles accedan directamente a esta página al escanearla.
