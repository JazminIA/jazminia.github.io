# Jazmín.IA 🌼

**Sistema embebido de visión por computador para el análisis de indicadores conductuales y su relación con el rendimiento del usuario.**

Jazmín.IA corre completo en una **Arduino UNO Q**: observa el rostro con una cámara USB, detecta señales de tensión y cansancio con MediaPipe, geometría facial y un modelo MobileNetV2 int8 de 13 Unidades de Acción, y da retroalimentación en la matriz LED de la placa y en una pantalla táctil. No guarda imágenes ni usa la nube.

👉 **Página del proyecto:** `https://<tu-usuario>.github.io/<nombre-del-repositorio>/`

Trabajo de grado de **Yuliana Ituyan Angulo** · Ingeniería Mecatrónica · Universidad Autónoma de Occidente (Cali, Colombia) · Director: Javier Ferney Castillo García · Póster en WiML @ NeurIPS 2026 (Sydney).

## Contenido del repositorio

- `index-jazminia.html` — la página (español e inglés).
- `index.html` — redirección para que GitHub Pages abra la página principal.
- `assets/` — logo, personaje, pantallas reales del modo producto y láminas técnicas.

## Cómo publicarla en GitHub Pages

1. En github.com, crea un repositorio público nuevo (por ejemplo `jazmin-ia`).
2. Botón **Add file → Upload files**: arrastra **todo el contenido** de esta carpeta (`index.html`, `index-jazminia.html`, `README.md`, `.nojekyll` y la carpeta `assets`). Clic en **Commit changes**.
3. Ve a **Settings → Pages**. En *Build and deployment* elige **Deploy from a branch**, rama **main** y carpeta **/ (root)**. Guarda.
4. En uno o dos minutos la página queda en `https://<tu-usuario>.github.io/jazmin-ia/`.

Para verla en inglés directamente: agrega `?lang=en` al final del enlace.
