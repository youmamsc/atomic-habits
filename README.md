# Atomic Habits — 05:30
Aplicación web móvil (PWA) sin dependencias ni servidor. Registra hora de levantarse, sueño estimado, descansos, plan gradual de 21 días, historial, rachas y copias JSON.

## Publicar en GitHub Pages
En Settings → Pages → Build and deployment, selecciona Deploy from a branch, main y / (root). Guarda. GitHub Pages gratuito requiere un repositorio público; los privados requieren un plan compatible. La URL de publicación aparece en Settings → Pages.
En Safari del iPhone: Compartir → Añadir a pantalla de inicio. Tras una primera carga en línea, la aplicación funciona sin conexión.

## Privacidad y límites
No hay datos personales en el código. Los registros quedan en localStorage del navegador; no se suben a GitHub. No hay sincronización entre dispositivos, Garmin ni alarmas. Exporta tu copia JSON antes de borrar datos del navegador. Los días sin registro no se cuentan en el porcentaje, pero interrumpen la racha; los días de recuperación no cuentan para el reto ni interrumpen la racha. Cambiar el plan recalcula los objetivos anteriores.