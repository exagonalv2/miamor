# 💕 Te Amo, Abril — Sitio Web Romántico

Un sitio web romántico hecho con Python (Flask) y desplegado en Railway.

## ✨ Vista previa

- Fondo de estrellas animadas 🌟
- Pétalos flotantes 🌸
- Contador de tiempo juntos ⏱️
- Carta de amor con modal 💌
- Corazones flotantes ♥

---

## 📁 Estructura del proyecto

```
te-amo-abril/
├── app.py               # Servidor Flask
├── templates/
│   └── index.html       # Página principal
├── requirements.txt     # Dependencias Python
├── Procfile             # Comando de inicio para Railway
├── railway.json         # Configuración de Railway
├── .gitignore
└── README.md
```

---

## ⚙️ Personalización

Antes de publicar, edita estos valores en `templates/index.html`:

### 1. Fecha de inicio de la relación
Busca esta línea y cambia la fecha:
```js
const START = new Date('2024-01-01T00:00:00');
```

### 2. Carta de amor
Cambia el texto dentro del modal:
```html
<p>
  Cada día a tu lado es el regalo más hermoso...
</p>
```

### 3. Poema
Edita el poema principal dentro de `<p class="poem">`.

---

## 🚀 Despliegue paso a paso

### Paso 1 — Subir a GitHub

```bash
# Dentro de la carpeta del proyecto
git init
git add .
git commit -m "💕 sitio para Abril"

# Crea un repo nuevo en github.com y luego:
git remote add origin https://github.com/TU_USUARIO/te-amo-abril.git
git branch -M main
git push -u origin main
```

### Paso 2 — Desplegar en Railway

1. Ve a **[railway.app](https://railway.app)** e inicia sesión con GitHub.
2. Haz clic en **"New Project"**.
3. Selecciona **"Deploy from GitHub repo"**.
4. Elige el repo `te-amo-abril`.
5. Railway detectará automáticamente Python y usará el `Procfile`.
6. En pocos segundos tendrás una URL pública como:
   `https://te-amo-abril-production.up.railway.app` 🎉

---

## 🏃 Correr localmente

```bash
pip install -r requirements.txt
python app.py
```

Abre http://localhost:5000

---

## 📜 Licencia

Hecho con ♥ para Abril.
