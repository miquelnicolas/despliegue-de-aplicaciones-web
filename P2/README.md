# P2: Administración de servidores web #

## 1. Instale en una máquina virtual un sistema operativo con base Linux (se recomienda Debian o Ubuntu) e instale apache2. ##

![Captura de pantalla 2023-10-04 122135](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/04be2c7f-fc1c-40b1-8d9c-2a58b815c895)

## 2. Explique con sus palabras que es una petición GET, POST, PUT y DELETE, remarcando sus diferencias. ##

GET se usa para obtener datos, POST para enviar datos, PUT para actualizar/recuperar recursos, y DELETE para eliminar recursos. Cada uno tiene su propósito y características específicas, lo que los hace adecuados para diferentes situaciones en el desarrollo web y la interacción con servidores.

## 3. Cambie del puerto 80 al puerto 4444 el servidor apache2. Muestra desde el navegador su funcionamiento adjuntando una captura de pantalla. ##
![Captura de pantalla 2023-10-04 123553](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/fb922944-8942-4e87-8cad-679f4530d49f)
![Captura de pantalla 2023-10-04 122749](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/b4257a8d-1ab7-47ec-9a5d-3d26017c13bd)
![Captura de pantalla 2023-10-04 122929](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/fa9608a5-4435-485d-84d8-dac366bd959a)
![Captura de pantalla 2023-10-04 123422](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/43f39a1a-9685-4212-bad6-f28568bb8403)
![Captura de pantalla 2023-10-04 123443](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/048b210e-ad72-4ba4-9bff-4042f645811a)
![Captura de pantalla 2023-10-04 130611](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/5ca84b86-1acb-495c-94f8-6495c2b9ac5a)

## 4. Instale un certificado SSL y configure su Apache para servir contenido a través de HTTPS en el puerto 4444. Muestre desde el navegador cómo se muestra el sitio web como "seguro" (aunque sea un certificado autofirmado). ##
![Captura de pantalla 2023-10-04 125534](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/a70cd6cd-0580-4ece-be49-998c1239bc5a)
![Captura de pantalla 2023-10-04 125434](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/2acb6dc4-0b20-48cd-915f-74b3348ba2a4)
![Captura de pantalla 2023-10-04 130742](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/e7ee2365-8ef1-43cc-ba5a-5df6c439f08e)
![Captura de pantalla 2023-10-04 131658](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/b8b04460-34a0-4a69-b28d-caa4355b43af)

## 5. ¿Dónde se encuentran los ficheros de configuración de Apache2? ##
- Ubicación principal.
- Explora el archivo apache2.conf. Identifica las secciones principales y describe su propósito.
- sites-available y sites-enabled: Explica la diferencia entre estos dos directorios y cómo funcionan juntos.
- mods-available y mods-enabled: Explica la diferencia entre estos dos directorios.



## 6. ¿Dónde se encuentran los ficheros de ejecución de Apache2? ##
- Ubicación principal
- Control del servicio: Utiliza el binario de ejecución para iniciar, detener, recargar y reiniciar el servidor Apache2 explicando la diferencia entre cada uno de los comandos utilizados.
- Comprobación de sintaxis: Usa el binario de Apache para verificar la sintaxis de tu configuración. Esto es útil para asegurarse de que no haya errores antes de reiniciar el servidor.

## 7. ¿Dónde se encuentran los ficheros de monitorización de Apache2? ##
- Ubicación principal
- error.log y access.log: Explica la diferencia entre estos dos archivos. Abre y revisa las entradas recientes en cada uno de ellos.
- Rotación de logs: Investiga cómo funciona la rotación de logs en Apache2. ¿Por qué es importante? ¿Cómo se configura?
- Monitorización en tiempo real: Utiliza herramientas como tail -f para monitorear en tiempo real los accesos a tu servidor web y posibles errores.
- Análisis de logs: Instala y usa herramientas como goaccess para analizar y obtener estadísticas visuales a partir de tus logs de Apache2.

## 8. ¿Qué es un Firewall? ¿Para qué sirve? ¿Por qué es necesario? Instale y configure un Firewall en la máquina virtual para que solo permita tráfico HTTP y HTTPS. Bloquee todo el resto de los puertos y demuestre su funcionamiento. ##

## 9. Explica con tus palabras las diferentes partes de una URL ##

## 10. Explica el funcionamiento del protocolo HTTP con tus palabras ##

## 11. ¿Qué es un archivo .htaccess? Proporcione un ejemplo de cómo se puede utilizar para reescribir URL o restringir el acceso a ciertas partes de su sitio web. ##

