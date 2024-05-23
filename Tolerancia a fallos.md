En el diseño de la red de datos para el proyecto FloriSoft, se han implementado diversas estrategias y tecnologías para garantizar la tolerancia a fallos y la disponibilidad continua del servicio:

1. Redundancia de enlaces:
   - Se han establecido enlaces redundantes entre los principales dispositivos de red, como routers y switches.
   - Esto permite que, en caso de fallo de un enlace, el tráfico se pueda redirigir automáticamente a través de rutas alternativas, evitando interrupciones en la conectividad.

2. Protocolos de enrutamiento resilientes:
   - Se han configurado protocolos de enrutamiento dinámico, como OSPF (Open Shortest Path First) y EIGRP (Enhanced Interior Gateway Routing Protocol), en la red.
   - Estos protocolos mantienen tablas de enrutamiento actualizadas y son capaces de detectar y adaptar las rutas en caso de que se produzcan cambios en la topología de la red, como la caída de un enlace.
   - Esto asegura que el tráfico se pueda reenviar a través de rutas alternas de manera transparente para los usuarios.

3. Configuraciones de alta disponibilidad:
   - Se han implementado configuraciones de alta disponibilidad en los dispositivos críticos de la red, como routers y servidores.
   - Esto implica la implementación de pares de dispositivos redundantes, con mecanismos de conmutación por error automática.
   - En caso de que uno de los dispositivos falle, el otro asume el control y mantiene la disponibilidad del servicio, minimizando los tiempos de inactividad.

4. Monitorización y detección de fallos:
   - Se han implementado soluciones de monitorización y gestión de red que permiten la detección temprana de problemas y fallos en la infraestructura.
   - Estas herramientas de monitorización generan alertas y notificaciones, lo que permite a los administradores de red tomar acciones correctivas de manera oportuna.

5. Planes de recuperación ante desastres:
   - Se han establecido planes de recuperación ante desastres, que incluyen la creación de copias de seguridad, la replicación de datos y la identificación de sitios de recuperación alternativos.
   - Esto garantiza que, en caso de un evento catastrófico, la red y los servicios puedan ser restaurados rápidamente, minimizando el impacto en las operaciones de la empresa.

Gracias a estas estrategias y tecnologías, la red de datos de FloriSoft se ha diseñado para ser altamente disponible y resistente a fallos, asegurando la continuidad del servicio y la confiabilidad del sistema de gestión de inventario.
