# 📚 Buscador Académico Multi-Fuente

Buscador de tesis y artículos científicos en 10+ fuentes académicas simultáneamente, con gráfica tipo Consensus y exportación a Excel.

---

## 🔐 Usuarios (modificar en `app.py`)

En la parte superior del archivo `app.py` hay un diccionario `USUARIOS`. Modifica las contraseñas antes de subir a GitHub:

```python
USUARIOS = {
    "admin":      "admin123",     # ← cambia esto
    "usuario1":   "pass2024",     # ← cambia esto
    "usuario2":   "pass2024",     # ← cambia esto
}
```

Para agregar más usuarios simplemente añade otra línea:
```python
    "maria":      "contrasena456",
```

---

## 📁 Estructura del proyecto

```
📂 tu-repositorio/
├── app.py              ← aplicación principal
├── requirements.txt    ← dependencias de Python
└── README.md           ← este archivo
```

---

## 🚀 Deploy en Streamlit Cloud (paso a paso)

1. **Crea cuenta** en https://streamlit.io (gratis)
2. **Sube los archivos** a un repositorio público en GitHub
3. En Streamlit Cloud → **New App**
4. Apunta al repositorio y al archivo `app.py`
5. Haz clic en **Deploy** → listo 🎉

Tu app estará en una URL así:
`https://tu-usuario.streamlit.app/`

---

## ✨ Funciones

- 🔐 Login con usuario/contraseña
- 📝 Ingreso de tema con detección automática de variables
- 📅 Rango de años configurable
- 🔬 10 fuentes científicas (OpenAlex, CrossRef, PubMed, Semantic Scholar, Europe PMC, DOAJ, arXiv, SciELO)
- 🏛️ 20 repositorios OAI-PMH de LATAM
- 📊 Gráfica interactiva tipo Consensus (clic para abrir documentos)
- 📥 Descarga en Excel y CSV
- 🎯 Clasificación por relevancia (ambas variables / una variable)
