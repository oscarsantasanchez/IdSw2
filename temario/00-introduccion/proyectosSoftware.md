# Proyectos de sofware

## Triángulo de hierro

<div align=center>

|![](/images/modelosUML/trianguloHierro.svg)||
|:-:|-|
La forma de hacer en este modelo del juego del desarrollo del software es que las fuerzas externas (clientes, directores de proyecto) eligen los valores de **tres variables** cualquiera. El equipo de desarrollo determina el valor resultante de la **cuarta variable**.|**Algunos directores de proyecto y clientes creen que pueden escoger el valor de las cuatro variables**. Cuando esto suceda, la calidad siempre desaparecerá, ya que nadie hace bien el trabajo cuando está sujeto a una fuerte presión. También, probablemente, el tiempo estará fuera de control

</div>

---

<div align=center>

|![](/images/modelosUML/variablesProyectoSoftware.svg)
|:-:
|**Variables de un proyecto de software**
|No hay una relación sencilla entre las cuatro variables
|Ej.: *no puedes reducir el tiempo a la mitad, gastando el doble*

</div>

### Ámbito

> Probablemente la más importante.

#### Naturaleza

Poco ámbito permite entregar más rápido, mas calidad (mientras el problema del cliente esté resuelto) y más barato.

El Ámbito **es** muy variable:

- Porque los programadores y el personal del negocio no tienen más que una idea vaga sobre lo que tiene valor en el software que se está desarrollando.
- Porque los requisitos nunca están claros al principio y los clientes no pueden decirnos exactamente lo que quieren.
- El desarrollo de una pieza de software cambia sus propios requisitos ya que tan pronto como el cliente ve la primera versión, aprenden lo que quieren para la segunda versión …​ o lo que realmente querían en la primera.

Y esto es un aprendizaje valioso, porque no hay posibilidades de especulación. Este aprendizaje solamente puede venir de la experiencia. Pero los clientes no pueden estar solos, necesitan gente que pueda programar, **no como guías, sino como compañeros**.

#### Gestión

Intentando no hacer demasiado mantenemos nuestra capacidad de producir la **calidad** requerida en un **tiempo** determinado.

Si se gestiona activamente el ámbito, se puede proporcionar a los directores de proyecto y clientes control sobre el **coste**, **calidad** y **tiempo**.

> **Eliminación del ámbito** es una de las decisiones más importantes en la gestión del proyecto

Si el tiempo está limitado por la fecha de lanzamiento de una versión, hay siempre algo que podemos diferir a la siguiente versión.

Si dejas fuera funcionalidad importante al final de cada ciclo de versión, el cliente quedará disgustado. Para evitar esto, se utilizan dos estrategias:

- Implementa en primer lugar los requisitos más importantes del cliente, de tal manera que si se deja después alguna funcionalidad, es menos importante que la funcionalidad que ya está incorporada al sistema.
- Consigue mucha práctica haciendo estimaciones y realimentando los resultados reales. Mejores estimaciones reducen la probabilidad de que tengas que dejar fuera funcionalidad.
- Cumple lo que te comprometes a hacer!!!.

### Tiempo

<div align=center>

|Poco||Mucho|
|-|-|-|
|Si damos a un proyecto poco tiempo, la calidad sufre, con el ámbito. Las restricciones de controlar proyectos controlando el tiempo, generalmente vienen de fuera, de las manos del cliente.|Disponer de más tiempo para la entrega puede mejorar la calidad e incrementar el ámbito.|Ya que la realimentación desde los sistema en producción es de mayor calidad que cualquier otra clase de realimentación, dar a un proyecto demasiado tiempo será perjudicial.|

</div>

Si la mayoría de los proyectos de tu organización son obsesivamente cortos, proyectos conducidos por el calendario, hay algo muy, muy malo. Cambios radicales en la organización del proceso de desarrollo software son necesarios, antes de que la compañía o su gente se arruine.
— Booch

### Coste

<div align=center>

|Poco||Mucho|
|-|-|-|
|No permite resolver el problema del negocio del cliente. Todas las restricciones sobre el coste pueden volver locos a los directores de proyecto.|Dentro del rango de inversión que pueda sensatamente hacerse, gastando más dinero puedes **aumentar el ámbito**, o puedes intentar de forma más deliberada **aumentar la calidad**, o puedes (hasta cierto punto) **reducir el tiempo de salida al mercado**.|Mucho dinero puede engrasar la maquinaria un poco, pero demasiado dinero pronto crea más problemas que resuelve.|
|Especialmente si están sujetos a un proceso de presupuesto anual, están tan acostumbrados a considerarlo todo desde la perspectiva del coste y cometerán grandes errores al ignorar las restricciones sobre cuánto control te proporciona el coste.|También puede reducir las desavenencias: máquinas más rápidas, más especialistas técnicos, mejores oficinas.|Mayores costes a menudo alimentan objetivos tangenciales, como estatus o prestigio (- "Tengo un proyecto de 150 personas!"" - y respira profundamente”)|

</div>

### Calidad

> Hay una extraña relación entre la calidad interna (*que miden los programadores*) y externa (*que mide el cliente*).

|||
|-|-|
Sacrificar temporalmente la calidad interna para reducir el tiempo de salida al mercado del producto, con la esperanza que la calidad externa no se vea muy dañada es tentador a corto plazo. Y puedes con frecuencia hacerlo impunemente generando una confusión en cuestión de semanas o meses. Al fin y al cabo, los problemas de calidad interna te alcanzan a ti y hacen que tu software sea prohibitivamente caro de mantener.|A menudo, al insistir en la mejora de la calidad puedes hacer que el proyecto esté listo en menos tiempo, o puedes conseguir hacer más en un una cantidad de tiempo dada. Se trabaja mejor si no se desmoraliza al producir software basura.

## Características del software

<div align=center>

|||
|-|-|
|Fiabilidad|cumpla una determinada función bajo ciertas condiciones durante un tiempo determinado.|
|Extensibilidad|habilidad de tener la posibilidad de se extendido con nuevas funcionalidades.|
|Usabilidad|sencillo de usar porque facilita la lectura de los textos, descarga rápidamente la información y presenta funciones y menús sencillos, por lo que el usuario encuentra satisfechas sus consultas y cómodo su uso.|
|Accesibilidad|pueda ser accedido y usado por el mayor número posible de personas, indiferentemente de las limitaciones propias del individuo o de las derivadas del contexto de uso.|
|Seguridad|proteger los datos que tiene, maneja y dispone para preservar la confidencialidad, la integridad y la disponibilidad.|
|Confidencialidad|acceso a la información mediante autorización y control para prevenir la divulgación no autorizada de la información.|
|Integridad|para modificar la información mediante autorización.|
|Disponibilidad|degradación en cuanto a accesos para prevenir interrupciones no autorizadas.|
|Interoperabilidad|habilidad de dos o más sistemas o componentes para intercambiar información y utilizar la información intercambiada.|
|Portabilidad|habilidad de reutilizar en vez de crear un nuevo software cuando se pasa de una plataforma a otra.|
|Escalabilidad|habilidad para reaccionar y adaptarse sin perder calidad cuando aumentan el tamaña del sistema de información.|

</div>

### Mantenibilidad

Habilidad de conservar su funcionamiento normal o para restituirlo una vez se ha presentado un evento de falla o un nuevo requisito

<div align=center>

![](/images/modelosUML/mantenibilidad.svg)

</div>

- **Correctiva**, para la eliminación de errores de cualquier otra cualidad.
- **Perfectiva**, para la modificación de su funcionalidad con cualquier otra cualidad.
- **Adaptativa**, para la modificación de su infraestructura para cualquier otra cualidad.

<div align=center>

|Mantenible|No mantenible|
|:-:|:-:|
|**Fluido**<br>se puede entender con facilidad|**Viscoso**<br>no se puede entender con facilidad.|
|**Flexible**<br>se puede cambiar con facilidad|**Rígido**<br>no se puede cambiar con facilidad.|
|**Fuerte**<br>se puede probar con facilidad|**Frágil**<br>no se puede probar con facilidad|
|**Reusable**<br>se puede reutilizar con facilidad|**Inmóvil**<br>no se puede reutilizar con facilidad|

</div>

#### Viscosidad vs fluidez

|Producida por (mal) diseño|Producida por (mala) gestión del entorno|
|-|-|
|La viscosidad en el diseño de software ocurre cuando es más fácil y tentador tomar atajos que deterioran la arquitectura que realizar cambios que preserven la integridad del diseño original.|La viscosidad del entorno ocurre cuando las limitaciones técnicas o la ineficiencia de las herramientas de desarrollo (como tiempos de compilación extensos o sistemas de control de versiones lentos) inducen a los desarrolladores a tomar decisiones que comprometen el diseño para evitar la fricción con estas herramientas.|
|En un sistema de pagos, se opta por añadir if/else para manejar pagos internacionales que implementar la solución correcta creando nuevas clases que mantengan el diseño existente.|En un proyecto con compilaciones de 15 minutos, se opta por colocar todo el código nuevo en un solo módulo (aunque no sea su lugar) en lugar de distribuirlo correctamente, solo para evitar recompilaciones extensas.|

#### Rigidez vs flexibilidad

Cuando **un cambio aparentemente simple en el software desencadena una cascada de modificaciones en módulos dependientes**, convirtiendo tareas sencillas en proyectos extensos e impredecibles, lo que eventualmente puede llevar a una resistencia organizacional a realizar cualquier cambio.

|||
|-|-|
|En un sistema de facturación, cambiar el formato de una fecha de DD/MM/YYYY a MM/DD/YYYY parece simple, pero requiere modificar: el módulo de entrada de datos, el de validación, el de almacenamiento en base de datos, el de generación de reportes, el de exportación a PDF, el de integración con otros sistemas...|Lo que parecía un cambio de 2 días se convierte en un proyecto de 3 semanas, haciendo ***que la gerencia termine evitando cualquier modificación al sistema por temor a estos efectos cascada***.|
|**Lo que comienza como una deficiencia de diseño, termina siendo una política de gestión adversa:**|**Se ha instalado la rigidez oficial...**|

#### Inmovilidad vs reusabilidad

Cuando el software **no puede reutilizarse en otros contextos porque sus componentes están tan fuertemente acoplados** que el esfuerzo de separar las partes deseadas de sus dependencias supera el beneficio de la reutilización, llevando a la reescritura del código.

|Sí|pero...|
|-|-|
|Un desarrollador encuentra un módulo de validación de direcciones postales que podría usar en su proyecto nuevo|pero este módulo está tan entrelazado con el sistema de facturación original (depende de su base de datos, de su sistema de logging, de sus clases de usuario...) que resulta más práctico escribir uno nuevo desde cero que intentar extraer la funcionalidad deseada.|

#### Fragilidad vs fortaleza

Cuando un cambio en el software causa **errores inesperados en partes aparentemente no relacionadas**, creando un círculo vicioso donde cada corrección introduce más problemas que soluciones, lo que eventualmente lleva a la pérdida de confianza entre stakeholders y desarrolladores.

|||
|-|-|
|En un sistema de comercio electrónico, al modificar el cálculo de descuentos en el carrito de compras...|Inesperadamente fallan: el sistema de notificaciones por email, el proceso de generación de facturas y el módulo de sincronización con el inventario.
|Al intentar corregir estos errores...|Surgen nuevos problemas en el sistema de pagos y en el módulo de envíos, haciendo que los gerentes duden de realizar cualquier modificación por temor a "romper" más funcionalidades.
