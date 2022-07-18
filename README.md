# Quick Start Apigee Local Development
Este proyecto tiene la finalidad de servir como base y inicio rápido en el desarrollo local con Apigee, para poder utilizar este arfefacto así como los procedimientos a continuación mencionados es necesario contar con los siguientes requerimientos:

- Visual Studio Code v1.67.2+
- Extensión Cloud Code v1.18.2+
- Docker version 20.10.16

## Estructura de carpetas

- `src/main/apigee/apiproxies`: En esta ruta se almacenan cada uno de los ApiProxys que vamos a configurar, así mismo cada Proxy contendra una estrutura única de carpetas, de las cuales podemos mensionar `policies` la cual almacena las póliticas, la carpeta `targets` donde se almacena la configuración de los HTTP Connections y por último la carpeta `proxies` donde se se crea la configuración para asociar las póliticas, paths y targets.

- `src/main/apigee/environments`: En este directorio se definen los archivos de configuración para el contexto de ejecución local que se desean desplegar.

- `src/main/apigee/sharedflows`: En este directorio se definen los archivos de configuración de los flujos o Proxys que se pueden reusar para extender funcionalidad.

- `src/main/apigee/test`: Almacena la configuración de los recursos de prueba como productos de API, Apps o desarrolladores para el desarrollo en local.


Validar acceso

- http://localhost:8998/api/helloworld
- http://localhost:8998/api/person/json
- http://localhost:8998/api/person/xml
