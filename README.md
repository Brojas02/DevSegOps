# ¿Qué es DevSecOps?
**_DevSecOps_** significa desarrollo, seguridad y operaciones. Se trata de un enfoque 
que aborda la cultura, la automatización y el diseño de plataformas, e integra la 
seguridad como una responsabilidad compartida durante todo el ciclo de vida de la TI.

![DevSecOps](https://miro.medium.com/v2/resize:fit:1400/0*hHrFoyntyRG_WLg9.png)

## DevSecOps vs DevOps
DevOps no solo concierne a los equipos de desarrollo y operaciones. Si desea aprovechar 
al máximo la agilidad y la capacidad de respuesta de los enfoques de DevOps, [La seguridad 
de la TI](https://www.redhat.com/es/topics/security) 
también debe desempeñar un papel integrado en el ciclo de vida completo de sus aplicaciones.  
¿A qué se debe? Antes, el papel de la seguridad estaba aislado y a cargo de un equipo específico en 
la etapa final del desarrollo. Cuando los ciclos de desarrollo duraban meses o incluso años, no pasaba 
nada. Pero eso quedó en el pasado. Una metodología efectiva de DevOps garantiza ciclos de desarrollo 
rápidos y frecuentes (a veces de semanas o días), pero las prácticas de seguridad obsoletas pueden 
revertir incluso las iniciativas de DevOps más eficientes.

![Equipo DevSecOps](https://www.redhat.com/rhdc/managed-files/devsecops-collab-405x308_0.png)

## Seguridad del entorno y de los datos
+ **_Estandarice y automatice el entorno:_** los servicios deben tener la menor cantidad de privilegios posible 
para reducir las conexiones y los accesos no autorizados.

+ **_Centralice las funciones de control de acceso y de identidad de los usuarios:_** el control de acceso estricto y los 
mecanismos de autenticación centralizados son fundamentales para proteger los microservicios, ya que la autenticación se inicia en varios puntos.

+ **_Aísle de la red y entre sí aquellos contenedores que ejecutan microservicios:_** se incluyen tanto los datos en tránsito como en reposo, ya que ambos 
pueden ser objetivos de gran valor para los atacantes.

+ **_Cifre los datos entre las aplicaciones y los servicios:_** una plataforma de organización de contenedores con funciones de 
seguridad integradas disminuye las posibilidades de accesos no autorizados.

+ **_Incorpore puertas de enlace de API seguras:_** las API seguras aumentan la supervisión de los enrutamientos y las autorizaciones. 
Al disminuir la cantidad de API expuestas, las empresas pueden reducir las superficies de ataque.
