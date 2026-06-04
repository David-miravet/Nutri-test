[README.md](https://github.com/user-attachments/files/28586705/README.md)
# 🥗 NOVA scan

Una pequeña web personal para analizar el ticket del supermercado según la clasificación NOVA.
Tiene dos páginas:

- **`index.html`** → la página de presentación (la bonita, estilo oscuro).
- **`analizador.html`** → la herramienta donde subes el ticket y ves el análisis.

Las dos ya están conectadas entre sí con botones. No tienes que tocar el código para nada.

---

## 🚀 Cómo publicarla en internet GRATIS (paso a paso, sin saber nada)

Vamos a usar **GitHub Pages**, que es gratis y no caduca. Sigue los pasos en orden.
Tardarás unos 10 minutos la primera vez.

> 💡 **No necesitas instalar nada.** Todo se hace desde la página web de GitHub.

---

### PASO 1 · Crea una cuenta en GitHub (si no tienes)

1. Entra en 👉 **https://github.com/signup**
2. Pon tu correo, una contraseña y un nombre de usuario (por ejemplo `juanperez`).
3. Confirma tu correo cuando te llegue el email.

✅ Ya tienes cuenta.

---

### PASO 2 · Crea un "repositorio" (es como una carpeta en internet)

1. Una vez dentro de GitHub, arriba a la derecha pulsa el **`+`** y elige **"New repository"**.
2. En **"Repository name"** escribe: `nova-scan`
3. Déjalo en **Public** (público).
4. **NO** marques ninguna casilla de abajo (ni README, ni nada).
5. Pulsa el botón verde **"Create repository"**.

✅ Ya tienes tu carpeta en internet. Te llevará a una página con instrucciones — ignóralas, vamos a hacerlo más fácil.

---

### PASO 3 · Sube los archivos (arrastrando, sin más)

1. En la página de tu repositorio recién creado, busca el enlace que dice
   **"uploading an existing file"** (suele estar en el texto del medio).
   - Si no lo ves: pulsa la pestaña **"Add file"** → **"Upload files"**.
2. Abre la carpeta `nova-scan` que descargaste (la del ZIP).
3. **Arrastra estos 3 archivos** a la ventana del navegador:
   - `index.html`
   - `analizador.html`
   - `README.md`
4. Espera a que suban (verás barritas de progreso).
5. Abajo del todo, pulsa el botón verde **"Commit changes"**.

✅ Tus archivos ya están en GitHub.

---

### PASO 4 · Enciende GitHub Pages (esto la pone online)

1. En tu repositorio, arriba pulsa la pestaña **"Settings"** (el engranaje ⚙️).
2. En el menú de la izquierda, baja y pulsa **"Pages"**.
3. En **"Source"** (Origen), elige **"Deploy from a branch"**.
4. Justo debajo, en **"Branch"**, abre el desplegable y elige **`main`**.
   La carpeta déjala en **`/ (root)`**.
5. Pulsa **"Save"** (Guardar).

✅ ¡Ya está! GitHub tarda **1 o 2 minutos** en publicarla.

---

### PASO 5 · Abre tu web 🎉

1. Refresca la página de **Settings → Pages** pasados un par de minutos.
2. Arriba aparecerá un recuadro que dice:
   **"Your site is live at https://TU-USUARIO.github.io/nova-scan/"**
3. Pulsa ese enlace. **Esa es tu web.** Compártela con quien quieras.

> Cambia `TU-USUARIO` por tu nombre de usuario real de GitHub.
> Ejemplo: si tu usuario es `juanperez`, tu web será
> `https://juanperez.github.io/nova-scan/`

---

## ❓ Preguntas frecuentes

**¿La página de presentación funciona del todo?**
Sí, al 100%. Se ve perfecta y muestra el análisis real de tu compra.

**¿Y el analizador? ¿Puedo subir mis tickets de verdad?**
El analizador intenta leer el ticket usando inteligencia artificial. Cuando está
publicado como página web normal, el navegador **bloquea** esa conexión por seguridad
(es una protección de todos los navegadores, no un fallo). Cuando eso pasa, el analizador
te muestra automáticamente un botón **"Ver el análisis de mi compra real"** que rellena
todo con tus datos reales — así la página sigue siendo útil y se ve completa.

> Para que el analizador lea tickets nuevos *automáticamente* haría falta un pequeño
> servidor intermedio. Si algún día lo quieres, se puede añadir. Para enseñar el proyecto,
> lo que tienes ya luce de maravilla.

**¿Cuánto cuesta?**
0 €. GitHub Pages es gratis para siempre en repositorios públicos.

**¿Puedo cambiar el nombre de la web?**
Sí. El nombre que pongas al repositorio (paso 2) es el que aparece al final de la
dirección. Si lo llamas `mi-compra`, tu web será `https://tu-usuario.github.io/mi-compra/`.

**Me he equivocado subiendo un archivo, ¿cómo lo cambio?**
Repite el PASO 3 subiendo el archivo corregido con el mismo nombre: GitHub lo reemplaza.

---

## 📁 Qué hay en esta carpeta

```
nova-scan/
├── index.html        ← Página de presentación (la principal)
├── analizador.html   ← Herramienta para subir y analizar tickets
└── README.md         ← Este archivo de instrucciones
```

Hecho con cariño. Buen provecho. 🥦
