# Introducción

## Introducción

### Motivación

El espíritu de este gitbook es acercar NodeJS a cualquiera que tenga una mínima experiencia en programación pero en el pasado ha luchado por entender los conceptos propios del lenguaje y los patrones específicos que brinda.

Algunos documentos que encontramos intentan iniciar al lector, predispuesto a ensuciarse las manos rápidamente, a una buena cantidad de conceptos teóricos que pueden generar el efecto adverso en quien quiera empezar con algo nuevo.

Otros eliminan esta barrera pero intentan suplir los conceptos teóricos con herramientas y modulos preexistentes, que pueden llevar al lector a perderse en un sinfin de detalles que, a priori, cree que no le serán útiles por no poder entender como éstas harán efectivas sus ansiedades de ver código en funcionamiento.

Sin duda es valorable el esfuerzo de quien desinteresadamente publica su trabajo para ayudar a otros, el material aquí propuesto busca explicar estos mismos conceptos pero desde otro enfoque.

### Estrategia

Planteadas las dificultades, la estrategia propuesta es dividir el camino de aprendizaje en etapas llamadas **secciones**, internamente divididas en **capítulos**.

Estas secciones comprenden el desarrollo de un proyecto de inicio a fin, siempre alineado con lo que el lenguaje ofrece como fuerte \(ej: una API Rest, una webapp, un integración con una API de terceros, etc\).

Cada sección al iniciar pone de manifiesto cual será el proyecto a realizar y progresivamente, capítulo tras capítulo, desarrollar las características que lo componen y mejorarlas.

Para sorpresa de quienes ya hayan tenido un acercamiento a otros tutoriales en estos temas especficos podrán constatar que deliberadamente son incluidas algunas malas prácticas, anti patrones o errores, pero aún con ellos permiten que el resultado final sea el esperado.

Esta decisión a la hora de diseñar este gitbook permite que en la sucesión de capítulos se señalen estas falencias y como mejorarlas.

Sin embargo, nunca a lo largo de este documento se intentará mejorar u optimizar algo que no haya sido desarrollado en primera instancia, ej: Devolver un mensaje dinámico si aún nuestra app no devuelve un mensaje fijo.

### Estructura

Como ya se detalló en el apartado de Estrategia, el material se divide en secciones que engloban un proyecto determinado, estas secciones a su vez son divididas en capítulos que trabajan todos los aspectos de diseño e implementación de los mismos.

Algunos de estos capítulos introducen conceptos nuevos para mejorar lo hecho en capítulos anteriores, otros llevarán al lector a replantearse por qué eso que vio funcionando en el capítulo anterior no es tan prolijo como debera ser o incluso otros simplemente forzarán a refactorizar o actualizar porciones de código para apegarse a nuevos stándares.

Respecto a este último punto, es probable que el lector con menos experiencia pueda tener la sensación de estar "sacrificando" mucho de su código solo para cumplir con un standard, a modo de animar al lectora a implementar estos cambios pero sin que su código principal esté en riesgo, los capítulos que son sobre estos asuntos proveen scripts aparte con fragmentos de código para que puedan ser probados por separados, animando y dando seguridad para luego hacerlos parte del proyecto principal.

### Contenido

Las diferentes secciones harán foco en muchos temas adems de NodeJS, como API Rests y buenas prácticas para diseñarlas, seguridad, interfaz con bases de datos, Docker, deploy, serverless, etc.

