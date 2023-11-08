# P4: Servidores virtuales de Apache #
Crea dos sitios web que compartirán IP y puerto, pero tendrán nombres DNS distintos para acceder a ellos. El nombre del primer dominio será daw.gimbernat.eug.es y el segundo tunombreyapellidos.gimbernat.eug.es, donde “tunombreyapellidos” contiene la inicial de tu nombre, el primer apellido, y la inicial de tu segundo apellido. De esta manera, si tu nombre es: Francisco Mesas Cervilla, el domino quedaría: fmesasc.gimbernat.eug.es.

• En el primer caso, daw.gimbernat.eug.es tendrá su directorio base en /var/www/daw/ conteniendo una página llamada index.html que ponga el nombre de la clase como título con un archivo css para aplicarle estilos al título.

• En el segundo caso, fmesasc.gimbernat.eug.es tendrá su directorio base en /var/www/fmesasc/ (el equivalente para vuestros nombres), conteniendo una página llamada index.html que contenga vuestro currículum aplicándole un estilo css para que se visualice correctamente.

Para ello, tendrás que crear un archivo de configuración (copiado de 000-default.conf) para cada uno de los dominios. Recuerda que con a2ensite puedes crear los enlaces simbólicos necesarios para añadir esta configuración a la ejecución de apache.

![Captura de pantalla 2023-11-08 120117](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/128b12fb-b5d6-4a14-af2a-38a1ee43a895)

![Captura de pantalla 2023-11-08 120154](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/e1958bfe-5a00-4ece-8c40-52100d28b8db)

![Captura de pantalla 2023-11-08 121018](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/a4611e4a-d001-49b3-b38b-00d03c80ff7a)

![Captura de pantalla 2023-11-08 120937](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/19a019f6-679f-463c-99eb-7b0a1b52c6d0)

![Captura de pantalla 2023-11-08 120238](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/7c18b8be-7287-4180-9bb7-b36790ff1851)

![Captura de pantalla 2023-11-08 120321](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/d2b3c1b1-0145-46e1-9cfd-0e848d377433)

![Captura de pantalla 2023-11-08 121119](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/26fe21e8-b45e-43fc-8eef-45c8c4da667d)

![Captura de pantalla 2023-11-08 121216](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/e4885da4-e6ec-4d49-8cbb-94d3d2bd023f)

![Captura de pantalla 2023-11-08 120421](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/939f6e5b-8cb0-4973-bd55-4409efdb8174)

![Captura de pantalla 2023-11-08 120522](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/0122dbfd-c96d-434c-8cbe-cabe5254fa56)

![Captura de pantalla 2023-11-08 120715](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/e148ef10-5cf3-4375-900a-fa537e233c72)

![Captura de pantalla 2023-11-08 120815](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/23f1cbf8-7ccc-47ba-b483-eda710bc9060)

![Captura de pantalla 2023-11-08 120758](https://github.com/miquelnicolas/despliegue-de-aplicaciones-web/assets/144775437/4ee45c26-e9a0-43ee-bde2-97cf049dfd58)
