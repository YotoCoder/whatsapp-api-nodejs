# Instalación

1. Descarga o clona este repositorio
2. Entre al directorio del proyecto.
3. Ejecute `yarn install` para instalar depencias se recomienda nodejs 16.

# Docker compose

<code>docker compose up -d</code>

# Creas el token
http://localhost:3333/instance/init

abres el link

# Escaneas el QR
http://localhost:3333/instance/qr?key=TU-CLAVE-SECRETA

# Endpoind para enviar mensaje
http://localhost:3333/message/text?key=TU-CLAVE-SECRETA&id={phone}&message={message}
