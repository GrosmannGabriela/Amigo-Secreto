# 🎁 Amigo Secreto

Este proyecto es un pequeño programa en **JavaScript** que permite:
- Agregar nombres de amigos a una lista.
- Mostrar los amigos agregados en pantalla.
- Realizar un sorteo aleatorio para elegir un "amigo secreto".

El objetivo principal es **practicar la lógica de programación**, el manejo del DOM y el uso de eventos en JavaScript.

---

## 📂 Archivos principales
- **index.html** → Estructura de la página y campos de entrada.
- **style.css** → Estilos del proyecto.
- **app.js** → Lógica de agregar, mostrar y sortear amigos.

---

## ⚙️ Funcionalidades
1. **Agregar amigo**
   - Se escribe un nombre en el campo de texto.
   - Se presiona **Enter** o el botón de agregar.
   - El nombre se agrega a la lista si no está vacío.
   - Si el campo está vacío, aparece un mensaje de alerta.

2. **Mostrar lista**
   - Los nombres ingresados se muestran en una lista `<ul>` en pantalla.
   - Cada nuevo amigo se agrega visualmente de forma automática.

3. **Sortear amigo secreto**
   - Al presionar el botón de sorteo, el programa elige un nombre al azar de la lista.
   - Muestra el resultado en pantalla.
   - Si la lista está vacía, avisa al usuario que debe agregar al menos un amigo.

4. **Agregar con tecla Enter**
   - El usuario puede presionar **Enter** en el campo de texto para agregar amigos, sin usar el mouse.

---

## 📦 Instalación y uso
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/TU_USUARIO/amigo-secreto.git
