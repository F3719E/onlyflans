##Revisar lo siguiente
1.- La configuracion de settings en 'static' debe ser de esta manera:

STATIC_URL = 'static/'
STATICFILES_DIRS = [
    os.path.join(BASE_DIR, 'web/static'),
]

##'Debe direccionar desde la carpeta web, donde esta la carpeta static'

2.-Le comparti una carpeta de bootstrap-4.0.0 para que copien las 2 carpetas
que trae, css y js y luego van al archivo 'base.html' que les comparto
y agregan los links  que incorporo, uds pueden probar agregando mas funcionalidades
yo agrego algunas basicas
3.- Agrego tambien un archivo css que uds creean a su gusto, recuerden, 'abajo del bootstrap'
4.- Las rutas basicas desde la carpeta web (aplicacion) al proyecto
5.- Si les pide que dentro de una app agregan la carpeta static y esto que les envio cumple lo solicitado
6.- agrego tambien un .env con 2 datos, se incrementara con el paso de los dias chic@s
pero vamos 'paso a paso'!!
7.- Revisen todo lo que les comento y despues me cuentan, adjunto una imagen del resultado
esta en carpeta -> web/static/img  