# 🗒️ Notepad (Web)

Un bloc de notas en el navegador, inspirado en un editor clásico, hecho en **HTML + CSS + JavaScript** (sin frameworks).  
Incluye **pestañas**, **numeración de líneas**, **buscar/reemplazar**, **modo oscuro**, y **guardado de archivos** con soporte para **File System Access API** (cuando el navegador lo permite).

## ✨ Funcionalidades

- 📑 **Múltiples pestañas**
  - Crear pestañas nuevas
  - Cerrar pestañas
  - Renombrar (doble clic o menú contextual)
  - Reordenar con **drag & drop**
- 🔢 **Números de línea** sincronizados con el scroll
- 🔎 **Buscar y reemplazar**
  - Siguiente / anterior
  - Reemplazar / reemplazar todo
  - Distinguir mayúsculas
  - Buscar en todas las pestañas
- 💾 **Guardar archivo**
  - Si el navegador soporta `showSaveFilePicker`: guarda directamente en tu sistema
  - Si no: descarga un archivo (fallback)
  - Detecta tipo de archivo por extensión (`.txt`, `.js`, `.json`, `.md`, `.py`, etc.)
- 🌓 **Modo oscuro**
  - Persistente con `localStorage`
- 💾 **Persistencia automática**
  - Guarda contenido y pestañas en `localStorage` para continuar donde lo dejaste
- ⌨️ **Atajos de teclado**
  - `Ctrl + S`: Guardar
  - `Ctrl + M`: Nueva pestaña
  - `Ctrl + F`: Buscar/Reemplazar
  - `Tab`: indentar con 4 espacios
  - `Shift + Tab`: desindentar (si aplica)
  - En buscar: `Enter` siguiente, `Shift + Enter` anterior, `Esc` cerrar panel

## 🧱 Tecnologías

- **HTML** (estructura)
- **CSS** (estilo + modo oscuro)
- **JavaScript** (lógica de pestañas, búsqueda, guardado y persistencia)

## 🚀 Cómo usar

### Opción 1: Abrir local
1. Descarga o clona el repo:
   ```bash
   git clone https://github.com/tu-usuario/tu-repo.git
