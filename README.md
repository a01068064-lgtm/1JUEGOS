# 🎮 MiniSteam — Arcade Web

Home estilo Steam para elegir entre 4 juegos clásicos. Hecho con **HTML / CSS / JS vanilla**, sin dependencias.

Entrada: abre `index.html`.

## 🕹️ Juegos

| Juego | Archivo | Descripción |
|---|---|---|
| 🧱 Tetris | `1tetris.html` | Bloques, líneas, velocidad fija. |
| ⭕ Gato | `1gato.html` | Tres en raya. PvP local o vs CPU. |
| 🐍 Snake | `1snake.html` | Come, crece, no choques. |
| 🏓 Pong | `1pong.html` | Vs CPU o 2P local. Gana con 5. |

## 📁 Estructura

```
Juegos/
  index.html
  1tetris.html
  1gato.html
  1snake.html
  1pong.html
  CSS/
    1styles.css
  JS/
    1main.js     → hero rotativo + buscador
    1tetris.js
    1gato.js
    1snake.js
    1pong.js
```

## 🚀 Uso

1. Descarga el repo.
2. Doble clic en `index.html` (no necesitas servidor).

Opcional con servidor:

```bash
python -m http.server 8000
```

## 🎮 Controles

- **Tetris:** ← → mover · ↓ bajar · ↑ rotar · P pausa
- **Gato:** clic en casilla, selector PvP / CPU
- **Snake:** flechas o WASD
- **Pong:** 1P `W/S` · 2P `↑/↓` · vs CPU: mouse o `↑/↓`

## 📜 Licencia

MIT.
