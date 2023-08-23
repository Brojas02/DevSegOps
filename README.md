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

## Diferencias entre DevOps y DevSecOps
DevOps es una metodología bajo la cual los desarrolladores y los equipos de operaciones trabajan juntos para crear un marco de implementación más ágil y optimizado. DevSecOps tiene como objetivo automatizar las tareas de seguridad clave incorporando controles y procesos de seguridad en el flujo de trabajo de DevOps. DevSecOps amplía la cultura DevOps de responsabilidad compartida para incluir prácticas de seguridad.

Los enfoques de DevOps y DevSecOps son similares en algunos aspectos, incluido el uso de la automatización y los procesos continuos para establecer ciclos colaborativos de desarrollo. Sin embargo, DevOps prioriza la velocidad de entrega, mientras que DevSecOps desplaza la seguridad hacia la izquierda, lo que significa mover la seguridad al punto más temprano posible en el proceso de desarrollo.

 ![Tareas DevSecOps](https://cdn.ttgtmedia.com/rms/onlineimages/security-security_responsibilities_in_devsecops-f.png)

## Herramientas de DevSecOps 
ThreatModeler es una herramienta automatizada de modelado de amenazas que se puede implementar en las instalaciones o en una instancia en la nube. ThreatModeler monitorea continuamente los modelos de amenazas para entornos de computación en la nube, notificando a los usuarios sobre actualizaciones y cambios. ThreatModeler proporciona una interfaz de programación de aplicaciones bidireccional para integrarse fácilmente con herramientas IC/DC, lo que permite a los equipos construir infraestructuras seguras en la nube. ThreatModeler ofrece plantillas que se pueden reutilizar e información y marcos de amenazas integrados.

**_Acunetix:_** proporciona un escáner de seguridad de sitios web todo en uno para ayudar a los desarrolladores a encontrar vulnerabilidades lo antes posible en el ciclo de desarrollo. Acunetix permite a las organizaciones proteger sus activos web de los hackers al proporcionar tecnologías especializadas que los desarrolladores pueden usar para detectar más problemas y solucionarlos rápidamente.

**_Checkmarx:_** ofrece una herramienta de prueba de seguridad de aplicaciones estáticas (SAST) que busca vulnerabilidades de seguridad que se analizan en el código. Esta herramienta permite a los desarrolladores entregar aplicaciones seguras, completamente analizadas y probadas al incorporar análisis y pruebas de código de seguridad en el proceso de desarrollo. Y Checkmarx se integra fácilmente con cualquier entorno o herramienta de integración y desarrollo continuo.

**_Aqua Security:_** es una plataforma de seguridad que se especializa en la seguridad de aplicaciones en contenedores y sus infraestructuras, evitando intrusiones o vulnerabilidades a través del pipeline DevSecOps. Aqua cuenta con procesos y controles de seguridad en tiempo de ejecución muy estrictos. Esta herramienta se centra en las vulnerabilidades relacionadas con el acceso a la red y las imágenes de las aplicaciones. Aqua se integra con una variedad de infraestructuras, incluido Kubernetes, para proteger los clústeres en el nivel de red más bajo y controlar la actividad del contenedor en tiempo real utilizando perfiles de comportamiento basados en el aprendizaje automático.

> [!NOTE]
> Autores:
> Gabriel Vasquez.
> Brajhan Barrera.
> Jeison Quesada.
