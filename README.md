# 💕 Sitio San Valentín con Gatitos

Un sitio web especial para pedirle a tu pareja que sea tu San Valentín, con lluvia invertida de gatitos y corazones.

## 📸 Cómo agregar más fotos

1. Simplemente agrega tus imágenes (JPG, JPEG, PNG, GIF, WEBP) a la carpeta `gatitos/`
2. Ejecuta el script para regenerar el sitio:
   ```bash
   python3 generar-sitio.py
   ```
3. Abre `san-valentin.html` en tu navegador

## 🚀 Uso

### Primera vez
```bash
python3 generar-sitio.py
open san-valentin.html
```

### Cada vez que agregues más fotos
```bash
python3 generar-sitio.py
```

El script automáticamente encontrará todas las imágenes en la carpeta `gatitos/` y las incluirá en el sitio.

## ✨ Características

- 🐱 Lluvia invertida de imágenes de gatitos
- ❤️ Corazones flotantes (menos frecuentes)
- 🎯 Botón "No" que se escapa del cursor
- 🎉 Celebración especial cuando dice "Sí"
- 📱 Diseño responsive para móviles
- 🔄 Lee automáticamente todas las fotos de la carpeta gatitos/
- 🎮 **Easter Egg:** Juego de Flappy Bird con sorpresa especial al llegar a 20 puntos (pasajes para México! 🇲🇽✈️)

## 📁 Estructura

```
.
├── san-valentin.html    # Sitio web generado
├── flappy-bird.html     # Easter Egg: Juego Flappy Bird
├── generar-sitio.py     # Script para generar el HTML
├── gatitos/             # Carpeta con las imágenes
│   ├── foto1.jpeg
│   ├── foto2.jpeg
│   └── ...
└── README.md            # Este archivo
```

¡Disfruta! 💖
