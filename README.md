# Codigo_Participante

Página para que los participantes del **IA Accelerator Program (NTT DATA | CREDICORP)** consulten su código de participante. Incluye las dos rutas: **IA Engineers** (códigos `AIE-`) y **Data Scientists** (códigos `DSC-`).

## Uso
1. Abrir `index.html` o la URL publicada: https://joelcollao.github.io/Codigo_Participante/
2. Escribir el **primer nombre** y el **primer apellido**, sin tildes, números ni símbolos.
3. Presionar **Ver mi código** o **Enter**. Se abre una ventana de bienvenida con el nombre, la función y el código, con los botones **Copiar código** y **Cerrar**.

## Protección de datos
La lista de participantes no está en texto plano. Cada registro (nombre, función y código) está cifrado con AES-GCM usando una clave derivada del nombre (PBKDF2-SHA256), así que al inspeccionar la página no se ven nombres, funciones ni códigos.

La página debe servirse por **https://** (por ejemplo GitHub Pages) o abrirse como archivo local, porque el navegador solo permite el descifrado en contextos seguros.
