# AD Mérida Dashboard 🏟️

Página estática premium para seguir la actualidad del AD Mérida (Primera Federación), automatizada con GitHub Actions y Web Scraping de **LaPreferente**.

## ✨ Características
- **Datos Reales 2025/2026**: Sincronización de resultados y clasificación de la temporada actual.
- **Sincronización Automática**: Actualización cada 6 horas mediante un script de Python.
- **Sin Dependencias de API**: Utiliza scraping de una de las fuentes más fiables del fútbol español, por lo que no requiere claves de API externas.
- **Diseño Premium**: Interfaz oscura con los colores oficiales del club (Grana #B22222 y Oro #D4AF37).

## 🚀 Configuración Paso a Paso

### 1. Preparar el Repositorio
Sube el contenido de la carpeta `MeridaAD` a tu repositorio de GitHub. Asegúrate de que la estructura incluya:
- `docs/` (la web)
- `scripts/` (el motor de datos)
- `.github/` (la automatización)

### 2. Activar GitHub Pages
1. Ve a **Settings > Pages** en tu repositorio.
2. En **Build and deployment > Source**, selecciona **`GitHub Actions`**.
   *(No hace falta seleccionar rama, el robot se encarga de todo).*

### 3. Lanzamiento Inicial
El sistema actualizará los datos automáticamente cada 6 horas, pero puedes forzar la carga inicial:
1. Ve a la pestaña **Actions**.
2. Selecciona el flujo de trabajo **Update Data and Deploy**.
3. Haz clic en **Run workflow**.

## 🛠️ Tecnologías
- **Frontend**: HTML5, CSS3 (Vanilla), JavaScript (ES6+).
- **Backend/Scraping**: Python 3 + `BeautifulSoup4` + `requests`.
- **Automatización**: GitHub Actions.
- **Fuentes**: Bebas Neue & Barlow (Google Fonts).

---
*Desarrollado para la afición del AD Mérida. ¡Vamos Romano!*
