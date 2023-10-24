# P3: Módulos de Apache #

## Ejercicio 1 ##
Añade en tu servidor el módulo mod_info y explique para que se utiliza este plugin:
![Captura de pantalla 2023-10-10 100125](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/4fee2958-8403-4e33-a760-a8d75478c43f)
![Captura de pantalla 2023-10-10 105417](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/cfcbe710-8b46-4f6d-adab-318d4d46f56f)


Proporciona información detallada sobre la configuración y el estado del servidor. Este módulo es parte del conjunto de módulos conocidos como "mod_info" que se utilizan para obtener información sobre el servidor web Apache y su configuración.

## Ejercicio 2 ##
Oculta la versión del sistema y sistema de apache.

Modificar y añadir las dos últimas líneas en este archivo:
![Captura de pantalla 2023-10-18 130515](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/2a31ce83-f2cd-4ccc-843f-da263ae75030)


## Ejercicio 3 ##
Crea una carpeta en la raíz del path del servidor con el nombre public y otra con el nombre private. Permite que la carpeta public se visualice y el resto de las carpetas que se creen, incluyendo private, no se muestren. A continuación, puede observar cómo se debe de mostrar la carpeta public:

![Captura de pantalla 2023-10-10 081436](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/8cabaf62-81ab-47c5-858c-e72e44a95fd6)

![Captura de pantalla 2023-10-18 133901](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/2607daf3-4eff-470e-b9ba-22365df0eb36)
![Captura de pantalla 2023-10-18 134039](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/5b7f3237-22a5-476e-acd1-64c50f58b0f2)
![Captura de pantalla 2023-10-18 133533](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/63024504-d9bf-4eff-bd32-7db2aaf49c81)
![Captura de pantalla 2023-10-18 133758](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/905d43ca-b1de-470d-a6d3-479b0229c03d)
![Captura de pantalla 2023-10-18 134136](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/93aa900c-3b1b-4c30-9703-ad0d7be095bc)
![Captura de pantalla 2023-10-18 134219](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/bf2dff6a-9f60-4c5e-b0aa-3c5d809e94cd)


## Ejercicio 4 ##
Prueba de acceder poniendo www. delante de tu URL actual. ¿Funciona? En caso negativo, haz que funcione mediante el módulo mod_rewrite. Investigue como utilizar el archivo .htacess para implementarlo.

![Captura de pantalla 2023-10-24 094410](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/20f309a4-ad45-4753-a14e-b73f455ea8ec)

![Captura de pantalla 2023-10-24 094012](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/a33cb746-e53a-4b59-a865-4a74e49a2a10)

![Captura de pantalla 2023-10-24 094215](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/09fa64af-0fa1-414f-a3ae-da0a0b1e6ca3)

![Captura de pantalla 2023-10-24 094244](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/4c187201-c095-4ec0-83dc-272d54d8f66d)

![Captura de pantalla 2023-10-24 093658](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/3a870e55-a0c7-4de1-bda0-4016ba5de1c3)


## Ejercicio 5 ##
Muestra los directorios de Apache con un tema diferente. Puedes utilizar https://github.com/ramlmn/Apache-Directory-Listing u otra alternativa que te llame la atención.



## Ejercicio 6 ##
(Extra: 1 punto) Crea tu propio tema para el ejercicio anterior, sin dependencias externas.

