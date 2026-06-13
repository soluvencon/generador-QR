🛍️ QR Designer Pro - Generador de Códigos QR Gratuito
VersiónLicenciaEstado

Una aplicación web 100% gratuita, local y sin dependencias de servidor para generar códigos QR altamente personalizados. Diseñada especialmente para negocios de domicilios, restaurantes, delivery y marketing, permitiendo crear códigos QR que no caducan y que no dependen de suscripciones de terceros.

Captura de pantalla de la app(Reemplaza esto con una imagen real tuya)

✨ Características principales
🚀 100% Local y Privado: Todo se procesa en tu navegador. No se envían datos a servidores externos. Tu información es tuya.
♾️ QRs Eternos (Estáticos): Genera códigos QR que nunca caducan ni se bloquean por falta de pago.
🎨 Estilos Personalizables:
Formas de los puntos (Cuadrados, Bolitas, Redondeados).
Formas de las esquinas (Cuadradas, Circulares, Extra redondeadas).
Colores ilimitados para el QR y el fondo.
🖼️ Logos e Íconos Centrales:
Sube tu propio logo (PNG/JPG) con ajuste automático de margen blanco para no romper el QR.
Selección de íconos vectoriales integrados (Cubiertos, Plato, Moto, Café, Carrito, Ubicación).
🛍️ 12 Marcos/Contornos Exclusivos:
Bolsas de Domicilio: Estilo Domidelis (2 asas), Tirita Elegante (1 asa), Tote Ecológica, Kraft (Papel).
Marcos de Apps: Cabecera de Delivery, Marco de Celular (Redes Sociales).
Descuentos: Ticket de Domicilio, Cupón, Tarjeta de Regalo.
Geolocalización: Pin de Mapa.
Clásicos: Escudo / Insignia.
📝 Texto Dinámico: Agrega textos como "ESCANEA QR" o "¡PIDE AQUÍ!" dentro o fuera del marco.
📥 Descarga en Alta Calidad: Exporta tu diseño en formato PNG o SVG listo para imprimir.
🛠️ Cómo usarlo
Descarga el archivo de este repositorio.index.html
Ábrelo con cualquier navegador moderno (Chrome, Edge, Firefox, Safari).
¡Empieza a diseñar! Los cambios se actualizan en tiempo real en la vista previa.
Descarga tu QR e imprímelo.
💡 El "Hack" Profesional: QRs Eternos pero Modificables
Los códigos QR generados aquí son estáticos (no caducan). Sin embargo, si en el futuro cambias la URL de tu app o página web, el QR impreso dejaría de funcionar.

La solución (Gratis):En lugar de poner tu URL final en el QR, usa un enlace de redirección propio. Por ejemplo, usando GitHub Pages:

Crea un repositorio en GitHub y activa GitHub Pages.
Sube un archivo con este código:index.html
<!DOCTYPE html><html lang="es"><head>    <meta charset="UTF-8">    <meta http-equiv="refresh" content="0; url=https://www.tu-pagina-final.com/">    <title>Redirigiendo...</title>    <script>window.location.replace("https://www.tu-pagina-final.com/");</script></head><body>    <p>Si no eres redirigido automáticamente, <a href="https://www.tu-pagina-final.com/">haz clic aquí</a>.</p></body></html>
En la app QR Designer Pro, genera el QR apuntando a 'https://tunombre.github.io/tu-repo/.
Resultado: El QR impreso nunca cambia, pero si un día cambias tu negocio de URL, solo modificas el archivo en GitHub y el QR redirigirá a la nueva dirección mágicamente. ¡Sin pagar por QRs dinámicos!
💻 Tecnologías Utilizadas
HTML5, CSS3, JavaScript (Vanilla)
Estilo de código QR - Librería para la generación y estilizado avanzado del QR.
📜 Licencia
Este proyecto está bajo la Licencia MIT. Eres libre de usarlo, modificarlo y distribuirlo para tus propios proyectos o negocios. ¡No más suscripciones a generadores de QR!

Hecho con ❤️ la comunidad de desarrolladores y emprendedores.
