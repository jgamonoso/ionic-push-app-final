# Instalación de cordova
npm i -g cordova
ng add @ionic/cordova-builders

# Prepare android
ionic cordova prepare android
# Tras esto abrir el android estudio en el proyecto

# Con el movil conectado por cable y android estudio abierto ejecutar para instalar en dispositivo (modo live reload)
ionic cordova run android -l