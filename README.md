# Codigo_Participante

Página para que los participantes del **Programa IA Engineer (NTT DATA | CREDICORP)** consulten su código de participante.

## Uso
1. Abrir `index.html` (o la URL publicada).
2. Escribir el **primer nombre** y el **primer apellido**, sin tildes, números ni símbolos.
3. Presionar **Ver mi código** o **Enter**. El código aparece en una ventana modal.

## Protección de datos
La lista de participantes no está en texto plano. Cada registro está cifrado con AES-GCM usando una clave derivada del nombre (PBKDF2-SHA256), así que al inspeccionar la página no se ven nombres ni códigos.

La página debe servirse por **https://** (por ejemplo GitHub Pages) o abrirse como archivo local, porque el navegador solo permite el descifrado en contextos seguros.
