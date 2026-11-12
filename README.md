# semillero-2026-q4_c-Intro-SantiagoJaimes

## Estrategia y Negocio
La semana partió de una central: una buena propuesta requiere entender el negocio. Antes de escribir código hay que entender la lógica del negocio y el problema raíz que se trata. El análisis de requerimientos se hace con los expertos de dominio (SMEs), y los requerimientos se expresan en lenguaje funcional y no técnico. Después, la solución se divide en módulos y se estima a partir de una vista de características. Revisamos dos ciclos de vida del software. El primero es RUP, con fases de inserción, elaboración, construcción y transición. El segundo modelo en V, que asocia cada etapa de desarrollo con su nivel de pruebas. Todo esto se apoya en la regla 4P + T: Personas, Producto, Procesos y Proyecto, sostenidos por la tecnología. También vimos conceptos de apoyo como la Definition of Ready (DoR), los objetivos SMART y el diagrama de operaciones del proceso (DOP)
## Metodología y gestión 
El trabajo se organiza con Scrum. La semana empieza con una planning que define los entregables y sigue con dailies, donde cada uno cuenta qué hizo, qué hará y qué lo bloquea. Al cierre se entrega un incremento funcional. Para planear se usa la Estructura de Desglose de Trabajo (WBS/EDT), bajo el principio de "divide y vencerás": partir el proyecto en entregables pequeños y medibles hace que las estimaciones sean más precisas. El roadmap ordena los hitos del proyecto y la ruta de aprendizaje (roadmap.sh). El desarrollo se gestiona con ramas en Git, repositorios compartidos e integración y entrega continuas (CI/CD).
## Arquitectura y Diseño
Antes de ejecutar se hace un diseño conceptual del trabajo. Ese diseño se apoya en una arquitectura de referencia, es decir, en algo que ya funcionó antes. La arquitectura tiene cuatro bloques:
- Frontend y canales.
- Backend, que reúne los orígenes de datos, la integración y el almacenamiento.
- Analítica, con visualización y modelos.
- Automatización de código, compilación y despliegue.
Sobre estos bloques corren capas transversales de identidad y accesos, logging, configuración, seguridad y monitoreo. Además, hay que seguir las tendencias del mercado para que las tecnologías elegidas sean confiables y vigentes.
## Seguridad e inteligencia artificial
Vimos la gestión de identidad y accesos (IAM) y el concepto de Circle of Trust. Con Auth0 y OpenID Connect, varias aplicaciones confían en un mismo proveedor de identidad y el usuario inicia sesión una sola vez. En Keycloak, cada realm es un espacio aislado con sus propios usuarios, roles y clientes. En la parte de IA, OpenSearch y ElasticSearch indexan documentos que luego se conectan a un LLM para formar una arquitectura RAG, que permite responder con información propia de la organización. Por último, docassemble automatiza la generación de documentos a partir de formularios guiados.

## Mapa Mental

<img width="1880" height="391" alt="Assignment1 – Introduction " src="https://github.com/user-attachments/assets/8d680c10-edba-4dbd-8e66-4af59146e7f2" />
