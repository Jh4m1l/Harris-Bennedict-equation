# Harris-Bennedict-equation
# 🔥 Harris-Benedict · Calculadora TMB

Una **Progressive Web App (PWA)** para calcular la Tasa Metabólica Basal (TMB) y el gasto calórico diario total (TDEE) usando la ecuación revisada de Harris-Benedict.

## ✨ Características

- ⚡ Cálculo instantáneo de TMB y TDEE
- 📶 **Funciona sin conexión** (Service Worker)
- 📲 **Instalable** en móvil y escritorio
- 🌡️ Soporte para unidades métricas e imperiales
- 🎨 Diseño moderno y responsivo
- ♂️ ♀️ Fórmulas diferenciadas por género biológico

## 🧮 Fórmulas

**Hombres:**
```
TMB = 88.362 + (13.397 × peso en kg) + (4.799 × altura en cm) − (5.677 × edad)
```

**Mujeres:**
```
TMB = 447.593 + (9.247 × peso en kg) + (3.098 × altura en cm) − (4.330 × edad)
```

### Multiplicadores de actividad

| Nivel | Multiplicador |
|-------|--------------|
| Sedentario | TMB × 1.2 |
| Levemente activo | TMB × 1.375 |
| Moderadamente activo | TMB × 1.55 |
| Muy activo | TMB × 1.725 |
| Extra activo | TMB × 1.9 |

## 🚀 Publicar en GitHub Pages

1. Crea un repositorio en GitHub
2. Sube todos los archivos
3. Ve a **Settings → Pages → Source → main branch**
4. ¡Tu PWA estará disponible en `https://tuusuario.github.io/tu-repo/`!

## 📁 Estructura del proyecto

```
harris-benedict-pwa/
├── index.html          # App principal
├── manifest.json       # Manifiesto PWA
├── sw.js               # Service Worker (offline)
├── README.md
└── icons/
    ├── favicon.svg
    ├── icon-192.png
    └── icon-512.png
```

## 🛠️ Tecnologías

- HTML5, CSS3, JavaScript vanilla
- Web App Manifest
- Service Worker API
- Google Fonts (Syne + DM Sans)

## 📚 Referencias

- Roza, A.M. & Shizgal, H.M. (1984). *The Harris Benedict equation reevaluated.*
- Harris, J.A. & Benedict, F.G. (1918). *A biometric study of basal metabolism in man.*

## ⚠️ Aviso

Esta calculadora es orientativa. Consulta a un profesional de la salud o nutricionista para planes dietéticos personalizados.

---

Made with ❤️ · MIT Licensegit add .