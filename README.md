# 📚 Cuaderno de Estudio

Una aplicación web para crear esquemas visuales, tarjetas de estudio con IA y exportar todo en PDF o Word.

## ✨ Funciones

- **Múltiples materias** — Crea cuadernos para cada asignatura con su propio ícono y color
- **Temas por materia** — Cada materia tiene sub-temas (Ej: Biología → La Célula, Mitosis...)
- **Editor de esquemas** — Dibuja cajas, óvalos, flechas y texto libremente con cuadrícula
- **Tarjetas con IA** — Genera tarjetas pregunta/respuesta automáticamente con Claude AI
- **Exportación** — PDF del esquema, PDF completo de todos los temas, imagen PNG, Word (.doc)
- **Datos locales** — Todo se guarda en el navegador (localStorage), sin servidor

## 🚀 Cómo usar

1. Descarga el archivo `index.html`
2. Ábrelo en cualquier navegador (Chrome, Firefox, Safari, Edge)
3. ¡Listo! No necesita instalación ni servidor

## 🌐 Publicar en GitHub Pages (acceso desde cualquier dispositivo)

1. Crea un repositorio en GitHub (puede ser privado o público)
2. Sube el archivo `index.html`
3. Ve a **Settings → Pages**
4. En *Source* selecciona `Deploy from a branch` → `main` → `/ (root)`
5. Espera 1-2 minutos y tendrás una URL tipo:
   `https://tu-usuario.github.io/tu-repositorio/`

Accede a esa URL desde cualquier dispositivo y tendrás tu cuaderno disponible.

> **Nota:** Los datos se guardan en localStorage del navegador, así que cada dispositivo tiene su propio almacenamiento. Para sincronizar entre dispositivos considera usar la función de exportar/importar.

## ⌨️ Atajos de teclado (en el editor de esquemas)

| Tecla | Acción |
|-------|--------|
| `V` | Herramienta Seleccionar |
| `B` | Herramienta Caja |
| `O` | Herramienta Óvalo |
| `A` | Herramienta Flecha |
| `T` | Herramienta Texto |
| `Delete` / `Backspace` | Eliminar forma seleccionada |
| `Ctrl+Z` | Deshacer |
| `Escape` | Cancelar acción |
| Doble clic | Editar texto de una forma |

## 🛠️ Tecnologías

- HTML5 + CSS3 + JavaScript vanilla
- Canvas API para el editor de esquemas
- Anthropic Claude API para generación de tarjetas
- localStorage para persistencia de datos
