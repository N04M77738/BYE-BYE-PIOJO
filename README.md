# Bye Bye Piojos — sitio (HTML + CSS + Python/Flask)

Mismo sitio de antes, ahora dividido en archivos separados y servido con un
pequeño servidor Flask en Python.

## Estructura

```
bye-bye-piojos/
├── requirements.txt
├── templates/
│   └── index.html         ← el HTML
└── static/
    └── style.css           ← el CSS
```

## Cómo correrlo en VS Code

1. Descomprimí la carpeta y abrila en VS Code.
2. Abrí una terminal (`` Ctrl+` `` / `` Cmd+` ``). Se recomienda un entorno virtual:
   ```
   python -m venv venv
   venv\Scripts\activate      # Windows
   source venv/bin/activate   # Mac/Linux
   ```
3. Instalá Flask:
   ```
   pip install -r requirements.txt
   ```
4. Corré el servidor:
   ```
5. Abrí http://localhost:5000 en el navegador.

## Notas

- No usa ninguna API ni clave — es un sitio informativo simple servido por Python.
- Para editar el contenido, tocá `templates/index.html`.
- Para editar estilos (colores, tipografía, layout), tocá `static/style.css`.
- `app.py` corre en modo `debug=True`, así que se recarga solo cuando guardás
  cambios — ideal mientras editás. Para producción, quitá `debug=True`.
