## Induccion

14 21 28 de noviembre  y 3 de diciembre son los encuentros presenciales
# Arquitectura de seguridad
Una arquitectura de seguridad es un marco estrategico que alinea personas, procesos y tecnologia con los objetivos del negocio y la gestion de riesgos.

La seguridad no es responasbilidad unica del area ed tecnologia de una compania sino mas bien de todos los involucrados con el negocio. 

### Arquitectura de seguridad empresarial :
Debe diseñar como debe integrarse la seguridad en el negocio, procesos, personas y tecnología. Tiene un enfoque estratégico y de diseño


### Sistema de gestion de seguridad de la información:
Gestionar los riesgos de seguridad de la información de forma continua y  tiene un enfoque gestion y operación.

 Imagina que la empresa quiere construir una ciudad: 
	- La arquitectura de seguridad es el plano maestro de la ciudad> donde debe ir cada cosa y como deben conectarse.
	- El SGSI es el sistema de gobierno que asegura que la ciudad siga siendo segura. Evalúa riesgos, crea normas, verifica cumplimientos , mide indicadores  y soluciona errores.

Limitar la arquitectura de seguridad únicamente a la tecnología es una de las fallas de diseño mas costosas y comunes en las organizaciones


Politicas de seguridad en las empresas
Procesos: Politicas, controles y gestion del riesgo alineados del objetivo del negocio. Por ejemplo una política es no usar dispositivos peronales de un individuo en la red de la empresa. 
Personas: Cultura, roles y concienciacion. El factor humano que define la postura de seguridad.
Tecnologia: Controles de seguridad como firewall, segmentacion, IPS, IDS, EPP, EDR, XDR, DLP, VPN que habilitan y sostienen la estrategia.
Impacto en el negocio: Continuidad operativa, reputacion y cumplimiento dependen de una gestion integrada. 

Todo ataque sea etico o no comienza por la fase de reconocimiento. Identificacion del personal clave. Esto se hace mediante tecnicas OSINT quiere decor busquedas de informacion en fuentes publicas. Asi los atacantes obtienen informacion sobre integrantes del equipo de desarrollo.
![[Pasted image 20261112192126.png]]


La ISO/IEC 27001:2022 nos dice que la seguridad no es solo TI: son 4 dimensiones y 93 controles donde el 63%  no son tecnológicos (59 de 93 controles). Procesos, personas y entorno físico pesan mas que la tecnología: la seguridad es de toda la organización.


## Zero Trust
Zero trust es una arquitectura de seguridad donde cada solicitud se autentica y autoriza según identidad, estado del dispositivo y contexto, sin confiar en la ubicación de red. Se concede el acceso necesario, por sesión y a recursos concretos, y se segmenta para limitar el movimiento lateral. 

Anterior al 2019 los esquemas de seguridad se limitaban a que solo se podia ingresar a la red de la empresa desde el lugar físico como la oficina y se rechaza cualquier conexión fuera de esta. Actualmente el panorama cambio pues ahora se permite el ingreso desde fuera pero se trata a todos como un hacker que esta dentro de la red y se le monitorea constantemente. 

El motor de políticas decide, el administrador de políticas ordena y el punto de aplicación permite o bloquea cada acceso, con apoyo de identidad, telemetría e inteligencia de amenazas.

Cada usuario tiene un perfil dependiendo su rol con una colección de permisos para cada uno.

## SABSA 
Esta arquitectura diseña la seguridad a partir de las necesidades del equipo. Sherwood Applied Business Security Architecture parte de objetivos, riesgos y atributos del negocio para justificar cada control. Tienes capas como Contextual, conceptual, lógica, física y de componentes, con una visita operacional atraviesa todas las capas. En cada capa se responde que, porque, como, quien, donde y cuando, y se obtiene una matriz de vista coherentes.

Cada control se rastrea hasta un requisito del negocio, lo que permite mostrar su valor, priorizar inversiones y gestionar el riesgo. 

Elegir una arquitectura o otra depende completamente de la organización y de criterios como su tamaño o la profundidad que se le quiera dar a este papel.



### Tres enfoques complementarios para disenar y gobernar la seguridad
![[Pasted image 20261112202321.png]]

# Certificaciones en ciberseguridad
![[Pasted image 20261112202535.png]]![[Pasted image 20261112202551.png]]

OSCP es muy importante por ejemplo para un perfil de red team aunque es bastante compleja de conseguir. Se debe apuntar a hacking etico y a pentesting. 

![[Pasted image 20261112203916.png]]