# 🎯 Repaso de Rectas - Juego Interactivo

Un juego educativo interactivo para repasar las características de las rectas y su representación gráfica.

![Preview del Juego](https://img.shields.io/badge/Educativo-Matemáticas-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 📋 Descripción

Este juego ayuda a los estudiantes a practicar la relación entre diferentes formas de representar rectas:
- **Ecuación General** (forma implícita)
- **Ecuación Explícita** (y = mx + n)
- **Pendiente** (m)
- **Ordenada en el origen** (n)
- **Representación gráfica**

## 🎮 Cómo Jugar

1. Observa la ecuación general de cada recta en la primera columna
2. Arrastra las imágenes del banco inferior a las celdas correspondientes
3. Completa todas las filas relacionando cada recta con sus características
4. Haz clic en "Comprobar Respuestas" para validar tus resultados
5. ¡Observa tu puntuación y vuelve a intentarlo si quieres mejorar!

## 🚀 Publicación en GitHub Pages

### Paso 1: Crear repositorio en GitHub

1. Ve a [GitHub](https://github.com) e inicia sesión
2. Haz clic en el botón **"+"** (arriba a la derecha) → **"New repository"**
3. Configura el repositorio:
   - **Nombre**: `juego-rectas` (o el nombre que prefieras)
   - **Descripción**: "Juego interactivo educativo para repasar rectas"
   - **Público**: ✅ Marcar como público
   - **Add README**: ❌ No marcar (ya lo tenemos)
4. Haz clic en **"Create repository"**

### Paso 2: Subir archivos

**Opción A: Desde la web de GitHub (más fácil)**

1. En tu nuevo repositorio, haz clic en **"uploading an existing file"**
2. Arrastra estos archivos:
   - `index.html`
   - `README.md`
   - Toda la carpeta `img/` con las 20 imágenes PNG
3. Escribe un mensaje: "Primer commit - juego de rectas"
4. Haz clic en **"Commit changes"**

**Opción B: Usando Git (línea de comandos)**

```bash
# En tu carpeta local del proyecto
git init
git add .
git commit -m "Primer commit - juego de rectas"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/juego-rectas.git
git push -u origin main
```

### Paso 3: Activar GitHub Pages

1. En tu repositorio de GitHub, ve a **Settings** (Configuración)
2. En el menú lateral, haz clic en **Pages**
3. En "Source", selecciona:
   - **Branch**: `main`
   - **Folder**: `/ (root)`
4. Haz clic en **"Save"**
5. ¡Listo! En 1-2 minutos tu juego estará disponible en:
   ```
   https://TU-USUARIO.github.io/juego-rectas/
   ```

## 🌐 Otras Opciones de Publicación

### Netlify (Recomendada para principiantes)

1. Ve a [Netlify](https://www.netlify.com/)
2. Regístrate gratis con tu cuenta de GitHub
3. Haz clic en **"Add new site"** → **"Import an existing project"**
4. Conecta tu repositorio de GitHub
5. Deploy automático: ¡listo en segundos!
6. URL gratuita: `nombre-aleatorio.netlify.app` (puedes personalizarla)

### Vercel

1. Ve a [Vercel](https://vercel.com/)
2. Regístrate con GitHub
3. Haz clic en **"New Project"**
4. Importa tu repositorio
5. Deploy automático con URL personalizada

### CodePen (Para compartir rápidamente)

1. Ve a [CodePen](https://codepen.io/)
2. Crea un nuevo "Pen"
3. Copia el contenido de `index.html` al editor HTML
4. Sube las imágenes a un servicio como [Imgur](https://imgur.com/)
5. Actualiza las rutas de las imágenes en el código
6. Comparte el enlace público

## 📱 Características

- ✅ **Responsive**: Funciona en móviles, tablets y escritorio
- ✅ **Touch support**: Soporte táctil completo para dispositivos móviles
- ✅ **Feedback visual**: Animaciones al validar respuestas
- ✅ **Sistema de puntuación**: Muestra resultados con mensajes motivadores
- ✅ **Drag & Drop**: Interfaz intuitiva de arrastrar y soltar
- ✅ **Sin dependencias**: HTML, CSS y JavaScript puro

## 🛠️ Estructura del Proyecto

```
juego-rectas/
├── index.html          # Archivo principal del juego
├── README.md           # Este archivo
└── img/                # Carpeta con todas las imágenes
    ├── EkOrok1.png     # Ecuaciones generales (4 rectas)
    ├── EkEsp1.png      # Ecuaciones explícitas (4 rectas)
    ├── Malda1.png      # Pendientes (4 valores)
    ├── JatOrd1.png     # Ordenadas (4 valores)
    ├── Grafiko1.png    # Gráficas (4 representaciones)
    └── ...             # (20 imágenes en total)
```

## 🎨 Personalización

Puedes personalizar fácilmente:

- **Colores**: Modifica las variables CSS en el `<style>`
- **Número de rectas**: Cambia el array `families` en JavaScript
- **Imágenes**: Reemplaza los archivos PNG manteniendo los nombres
- **Textos**: Edita los títulos y descripciones en el HTML

## 📝 Licencia

Este proyecto es de uso educativo libre. Siéntete libre de usarlo, modificarlo y compartirlo.

## 🤝 Contribuciones

Si encuentras errores o tienes sugerencias de mejora:
1. Abre un **Issue** en GitHub
2. O haz un **Pull Request** con tus cambios

## 📧 Contacto

Creado con ❤️ para facilitar el aprendizaje de matemáticas.

---

## 🚨 Solución de Problemas

### Las imágenes no se cargan
- Verifica que todas las imágenes están en la carpeta `img/`
- Comprueba que los nombres coinciden exactamente (distinguen mayúsculas)
- Revisa la consola del navegador (F12) para ver errores

### No funciona en móvil
- Asegúrate de que estás usando la versión actualizada con soporte táctil
- Algunos navegadores antiguos pueden no soportar todas las funciones

### El drag & drop no funciona
- Prueba en un navegador moderno (Chrome, Firefox, Safari, Edge)
- Si es en móvil, usa el soporte táctil incluido

---

¡Disfruta del juego y aprende matemáticas de forma divertida! 🎓✨
