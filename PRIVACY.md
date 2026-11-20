# Privacidad — Atomic Habits

Esta aplicación funciona como sitio web estático de código abierto. **No recopila, centraliza ni publica registros de hábitos.**

### Qué se guarda
La hora de levantarse, hora de acostarse si se facilita, fecha, tipo de día, notas, objetivos y ajustes se almacenan usando `localStorage` del navegador o de la aplicación instalada.

### Qué no se envía
No hay una API, base de datos, inicio de sesión, rastreadores publicitarios, herramientas analíticas ni servicios externos destinados a recibir los registros. El código no envía estos datos a GitHub ni a otros servidores. La carga normal de archivos del sitio se realiza mediante GitHub Pages.

### Quién puede acceder
Las personas que tengan acceso al dispositivo y al perfil de navegador podrían tener acceso a los datos locales. La aplicación **no cifra** el contenido de `localStorage`. Protege el teléfono con el bloqueo de pantalla.

### Copias y eliminación
Cada persona puede exportar sus propios registros en un archivo JSON. Ese archivo es responsabilidad de quien lo exporta y se puede guardar en el propio dispositivo o en otros servicios según su elección. Para eliminar los datos, se puede borrar el almacenamiento del sitio o de la aplicación instalada; no hay un servidor del proyecto del que solicitar su borrado.

### Alcance
Safari y la versión instalada pueden tener almacenes separados en iOS. Los datos no se sincronizan entre dispositivos ni se copian al código público del repositorio.
