# 🎤 Kanye Says (App de frases aleatorias)

Una mini aplicación en Python que usa `Tkinter` y la API [kanye.rest](https://api.kanye.rest/) para mostrar frases aleatorias de Kanye West cada vez que haces clic.

---

## 🖥️ Vista general

- Interfaz gráfica con fondo personalizado
- Cada clic en el botón trae una nueva frase
- Usa API REST para obtener contenido dinámico

---

## 🚀 ¿Qué tecnologías se usaron?

- Python 3
- `Tkinter` — para la GUI
- `requests` — para acceder a la API REST
- `PhotoImage` — para imágenes en botones y fondos

---

## 📦 Estructura del proyecto

.

├── main.py

├── background.png

├── kanye.png

└── README.md


---

## ▶️ ¿Cómo correrlo?

1. Asegúrate de tener Python 3 instalado.
2. Instala `requests` si no lo tienes:

```bash
pip install requests
```

3. Ejecuta el programa:

python main.py

📡 API usada
Kanye REST API
Retorna frases aleatorias en formato JSON:

{
  "quote": "I feel like I'm too busy writing history to read it."
}

MIT © Carlos Esquerra Martínez
