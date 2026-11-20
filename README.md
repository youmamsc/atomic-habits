# Atomic Habits — Despertar

Aplicación web progresiva (PWA), gratuita y sin dependencias, para seguir un hábito de despertar temprano. Diseñada para uso individual desde el móvil: cada persona elige su horario; el repositorio **no contiene información ni registros de usuarios**.

## Funciones
- Configurar una hora objetivo, una hora habitual de partida y un objetivo orientativo de horas de descanso.
- Elegir adaptación progresiva o comenzar directamente con la meta.
- Registrar hora de despertar, hora de acostarse (opcional), días de recuperación y notas.
- Ver el reto de 21 días, porcentaje de cumplimiento, rachas, historial y estimaciones de descanso.
- Exportar e importar una copia de seguridad JSON.
- Instalarla en la pantalla de inicio del móvil y utilizarla sin conexión tras la primera carga.

## Publicación
Este repositorio contiene solo el **código estático**. Para publicar desde GitHub Pages: `Settings → Pages → Deploy from a branch → main → / (root) → Save`. La dirección resultante aparecerá en GitHub Pages. No hace falta servidor de base de datos.

## Uso en iPhone
Abre la web publicada en Safari y pulsa `Compartir → Añadir a pantalla de inicio`. Inicia el registro **desde la app instalada** si quieres mantener todos los datos dentro de esa app. En iOS, Safari y una web añadida a la pantalla de inicio pueden tener contenedores de almacenamiento diferentes.

Abre «Configuración y copia de seguridad» y personaliza tu hora objetivo. Los horarios que vienen por defecto son solo ejemplos; los valores que introduzcas **no se publican**.

## Privacidad y límites
- Los registros se almacenan en `localStorage` del navegador/dispositivo; **no hay servidor, cuenta, cookies analíticas, telemetría ni envío de registros a GitHub**.
- GitHub Pages sirve los archivos públicos del proyecto. El proveedor puede recibir solicitudes técnicas normales al cargar la web, pero **no recibe tus registros** mediante esta aplicación.
- No hay sincronización automática entre dispositivos. Cada navegador y cada instalación guardan sus propios registros.
- Si borras los datos de la app/navegador, desinstalas la app o cambias de móvil, puedes perder los registros. Usa «Exportar copia JSON» para conservarlos y «Importar copia» para restaurarlos.
- La exportación guarda un archivo donde la persona decida; si lo guarda en un servicio en la nube, ese archivo ya queda fuera del almacenamiento exclusivamente local.
- Las horas de sueño son estimadas a partir de horarios introducidos manualmente, no son mediciones de un wearable ni sustituyen asesoramiento de salud.

Consulta también [PRIVACY.md](PRIVACY.md).
