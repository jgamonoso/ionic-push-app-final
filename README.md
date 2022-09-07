# First install dependencies
npm i

# Start on VSC
ionic serve

# Instalación de cordova
npm i -g cordova
<!-- ng add @ionic/cordova-builders -->

# Prepare android
ionic cordova prepare android
# Tras esto abrir el android estudio en el proyecto

# Con el movil conectado por cable y android estudio abierto ejecutar para instalar en dispositivo (modo live reload)
npm i -g native-run
ionic cordova run android -l

# ---------- ---------- FIREBASE ---------- ---------- #
# Despues de hacer npm i

# Instalar herramients de firebase
npm install -g firebase-tools

# generación de la carpeta www
ionic build --prod

# Firebase Login
firebase login

# Firebase Init
firebase init

# Firebase deploy
firebase deploy
# (Si se cambia algo --> ionic build --prod y luego firebase deploy)