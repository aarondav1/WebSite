---
layout: post
title:  Modelos de desarrollo de software 
date:   2020-08-13 15:01:35 +0300
image:  06.jpg
#tags:   Style
---
Un modelo de desarrollo de software es una representación de procesos a seguir para construir producto de calidad. Cada modelo representa un proceso desde una perspectiva particular y así proporcione información parcial sobre el proceso. 

Estos modelos generales no son descripciones definitivas de los procesos del software más bien son abstracciones de los procesos que se pueden utilizar para el desarrollo del software. Pueden ser adaptados según las necesidades y recursos del proyecto.

## Modelo cascada.
El modelo en cascada es un proceso de desarrollo secuencial, en el que el desarrollo de software se concibe como un conjunto de etapas que se ejecutan una tras otra. Se le denomina así por las posiciones que ocupan las diferentes fases que componen el proyecto, colocadas una encima de otra, y siguiendo un flujo de ejecución de arriba hacia abajo, como una cascada.

Royce propone un modelo compuesto por siete fases que se ha de ejecutar en diversas vueltas (iteraciones):
* Requisitos de sistema.
* Requisitos de software.
* Análisis.
* Diseño.
* Implementación.
* Prueba.
* Servicio.
El procedimiento popularmente conocido como waterfall model se basa en las fases definidas por Royce, pero solo prevé una iteración.

## Modelo iterativo.
Es un modelo derivado del ciclo de vida en cascada. Este modelo busca reducir el riesgo que surge entre las necesidades del usuario y el producto final por malos entendidos durante la etapa de recogida de requisitos.

Consiste en la iteración de varios ciclos de vida en cascada. Al final de cada iteración se le entrega al cliente una versión mejorada o con mayores funcionalidades del producto. El cliente es quien después de cada iteración evalúa el producto y lo corrige o propone mejoras. Estas iteraciones se repetirán hasta obtener un producto que satisfaga las necesidades del cliente.

__Ventajas del desarrollo iterativo:__
* El cliente espera poco hasta ver algo tangible. En cada iteración puede comprobar los avances y el beneficio que le reporta.
* Con cada entrega, el riesgo que se asume es pequeño, ya que si hay algún impedimento / cambio se puede pivotar / solventar con relativa facilidad en la siguiente iteración.
* El cliente aporta feedback muy pronto y el gap entre lo planeado y lo ejecutado se minimiza con la sucesión de las pequeñas iteraciones.
* La complejidad del proyecto se diluye en pequeñas partes menos complejas.

__Debilidades del desarrollo iterativo:__
* Implica tener un cliente involucrado durante el desarrollo y dispuesto a invertir los recursos necesarios en el proceso.
* La relación con nuestro cliente debe basarse en principios éticos y una colaboración mutua. El cliente debe compartir los valores y la visión de cómo abordar el desarrollo.
* Infunde responsabilidad en el equipo de desarrollo al trabajar directamente con el cliente, con lo cual no todo profesional puede verse involucrado.
* Conlleva fuertes penalizaciones en desarrollos en los cuales los requerimientos están previamente definidos y cerrados, porque es muy probable que esas especificaciones cambien notablemente.

## Modelo prototipado

El modelo de prototipos permite que todo el sistema, o algunos de sus partes, se construyan rápidamente para comprender con facilidad y aclarar ciertos aspectos en los que se aseguren que el desarrollador, el usuario, el cliente estén de acuerdo en lo que se necesita, así como también la solución que se propone para dicha necesidad y de esta forma minimizar el riesgo y la incertidumbre en el desarrollo.

Este modelo se encarga del desarrollo de diseños para que estos sean analizados y prescindir de ellos a medida que se adhieran nuevas especificaciones, es ideal para medir el alcance del producto, pero no se asegura su uso real. 


Este modelo principalmente se lo aplica cuando un cliente define un conjunto de objetivos generales para el software a desarrollarse sin delimitar detalladamente los requisitos de entrada procesamiento y salida.

__CARACTERÍSTICAS:__
* El prototipo es una aplicación que funciona
* Los prototipos se crean con rapidez
* Los prototipos evolucionan a través de un proceso iterativo.
* Los prototipos tienen un costo bajo de desarrollo.

__Este modelo es útil cuando:__
* El cliente no identifica los requisitos detallados. 
* El responsable del desarrollo no está seguro de la eficiencia de un algoritmo, sistema operativo o de la interface hombre-máquina. 

## Modelo basado en componentes

El modelo de desarrollo basado en componentes incorpora muchas de las características del modelo espiral. Es evolutivo por naturaleza y exige un enfoque interactivo para la creación del software. Sin embargo, el modelo de desarrollo basado en componentes configura aplicaciones desde componentes preparados de software (clases).

El modelo de desarrollo basado en componentes conduce a la reutilización del software, y la reutilización proporciona beneficios a los ingenieros de software. Según estudios de reutilización, QSM Associates, Inc. Informa que el ensamblaje de componentes lleva a una reducción del 70 % del ciclo de desarrollo un 84% del coste del proyecto y un índice de productividad del 26.2. No hay duda que el ensamblaje de componentes proporciona ventajas significativas para los ingenieros del software.

El proceso unificado de desarrollo de software representa un número de modelos de desarrollo basado en componentes que han sido propuestos en la industria. El lenguaje de modelado unificado define los componentes. Utilizando una combinación del desarrollo incremental e interactivo, el proceso unificado define la función del sistema aplicando un enfoque basado en escenarios.


__Beneficios del Desarrollo de Software basado en Componentes__
El paradigma de ensamblar componentes y escribir código para hacer que estos componentes funcionen se conoce como Desarrollo de Software Basado en Componentes. El uso de este paradigma posee algunas ventajas:

* Reutilización del software. Nos lleva a alcanzar un mayor nivel de reutilización de software.
* Simplifica las pruebas. Permite que las pruebas sean ejecutadas probando cada uno de los componentes antes de probar el conjunto completo de componentes ensamblados.
* Simplifica el mantenimiento del sistema. Cuando existe un débil acoplamiento entre componentes, el desarrollador es libre de actualizar y/o agregar componentes según sea necesario, sin afectar otras partes del sistema.
* Mayor calidad. Dado que un componente puede ser construido y luego mejorado continuamente por un experto u organización, la calidad de una aplicación basada en componentes mejorará con el paso del tiempo.

## Modelo ágil

Desarrollo ágil de software. Es un marco de trabajo conceptual de la ingeniería de software que promueve iteraciones en el desarrollo a lo largo de todo el ciclo de vida del proyecto. Existen muchos métodos de desarrollo ágil; la mayoría minimiza riesgos desarrollando software en cortos lapsos de tiempo.

El software desarrollado en una unidad de tiempo es llamado una iteración, la cual debe durar de una a cuatro semanas. Cada iteración del ciclo de vida incluye:
* Planificación
* Análisis de requerimientos
* Diseño
* Codificación
* Revisión y documentación.

Una iteración no debe agregar demasiada funcionalidad para justificar el lanzamiento del producto al mercado, pero la meta es tener un demo (sin errores) al final de cada iteración. Al final de cada iteración el equipo vuelve a evaluar las prioridades del proyecto.

Los métodos ágiles enfatizan las comunicaciones cara a cara en vez de la documentación. La mayoría de los equipos ágiles están localizados en una simple oficina abierta, a veces llamadas "plataformas de lanzamiento" (bullpen en inglés). La oficina debe incluir revisores, escritores de documentación y ayuda, diseñadores de iteración y directores de proyecto.

Los métodos ágiles también enfatizan que el software funcional es la primera medida del progreso. Combinado con la preferencia por las comunicaciones cara a cara, generalmente los métodos ágiles son criticados y tratados como "indisciplinados" por la falta de documentación técnica.

__Algunos métodos ágiles de desarrollo de software:__
* Adaptive Software Development (ASD).
* Agile Unified Process (AUP).
* Essential Unified Process (EssUP).
* Feature Driven Development (FDD).
* Lean Software Development(LSD).
* Método de desarrollo de sistemas dinámicos (DSDM).
* Scrum.

## Modelo orientado a objetos.
Este enfoque realiza la construcción de modelos de un sistema por medio de la identificación y la especificación de un conjunto de objetos relacionados, que colaboran entre sí de acuerdo a los requerimientos establecidos para el sistema de objetos.
Este tipo de modelado implica la realización de las siguientes actividades:
1.	Identificar las clases, modelos y objetos. (objetos y atributos).
2.	Asociar estáticamente los objetos. (relaciones dependientes del dominio del problema).
3.	Especificación del comportamiento de los objetos. (Definir como se comportarán los objetos).
4.	Definir la jerarquía de herencia de las clases. 

Características:
* EL modelado Orientado a Objetos está basado en el paradigma orientado a objetos.
* Trata el almacenamiento de objetos (persistencia de los objetos).
* Define un lenguaje para le definición y manipulación de objetos.
* Incluye mecanismos para optimizar el acceso (Indexación y Clustering), el control de la concurrencia, seguridad y gestión de usuarios, facilidad de consulta y recuperación ante fallos.
* Debido a que es un esquema orientado a objetos incluye: Encapsulamiento, herencia, polimorfismo, etc.

## Modelo en espiral.

El modelo en espiral del proceso del software fue originalmente propuesto por Boehm (Boehm, 1988). Más que representar el proceso del software como una secuencia de actividades con retrospectiva de una actividad a otra, se representa como una espiral. Cada ciclo en la espiral representa una fase del proceso del software. Así el ciclo más interno podría referirse a la viabilidad del sistema. el siguiente ciclo a la definición de requerimientos. el siguiente ciclo al diseño del sistema, y así sucesivamente. 

1. Definición de objetivos. Para esta fase del proyecto se definen los objetivos específicos. Se identifican las restricciones del proceso y el producto, y se traza un plan detallado de gestión. Se identifican los riesgos del proyecto. Dependiendo de estos riesgos, se planean estrategias alternativas. 
2. Evaluación y reducción de riesgos. Se lleva a cabo un análisis detallado para cada uno de los riesgos del proyecto identificados. Se definen los pasos para reducir dichos riesgos. Por ejemplo, si existe el riesgo de tener requerimientos inapropiados, se puede desarrollar un prototipo del sistema, determinar objetivos. alternativas y restricciones. Planificar la siguiente fase del plan de desarrollo, integración y plan de prueba, evaluar alternativas, identificar y resolver riesgos.
3. Desarrollo y validación. Después de la evaluación de riesgos. se elige un modelo para el desarrollo del sistema. Por ejemplo. si los riesgos en la interfaz de usuario son dominantes. un modelo de desarrollo apropiado podría ser la construcción de prototipos evolutivos. Si los riesgos de seguridad son la principal consideración, un desarrollo basado en transformaciones formales podría ser el más apropiado, y así sucesivamente. El modelo en cascada puede ser el más apropiado para el desarrollo si el mayor riesgo identificado es la integración de los subsistemas. 
4. Planificación. El proyecto se revisa y se toma la decisión de si se debe continuar con un ciclo posterior de la espiral. Si se decide continuar. se desarrollan los planes para la siguiente fase del proyecto. La diferencia principal entre el modelo en espiral y los otros modelos del proceso del software es la consideración explícita del riesgo en el modelo en espiral. 

## Modelo basado en reutilización.

Esta aproximación se basa en la existencia de un número significativo de elementos reutilizables. El proceso de desarrollo, se centra en la integración de estos elementos en un sistema, en lugar de desarrollarlo desde cero. Incorpora muchas características del modelo en espiral. Es evolutivo por naturaleza.

La reutilización es ahora el enfoque estándar para la construcción de muchos tipos de sistemas de negocios.

El proceso tiende a estructurarse en dos subprocesos distintos y separados:
* El desarrollo para reutilización: construcción de elementos reutilizables dentro de un dominio concreto.
* El desarrollo con reutilización: construcción de aplicaciones utilizando elementos reutilizables.

__Ventajas:__
* Reducir el tiempo de desarrollo.
* Reducir los costos.
* Incrementar la productividad.
* No tener que reinventar las soluciones.
* Facilitar la compartición de productos del ciclo de vida.
* Mayor fiabilidad
* Mayor eficiencia (Aunque al principio pueda parecer que no)
* Consistencia y la familiaridad, los patrones dentro del software serán más consistentes, tendiendo a facilitar el mantenimiento del producto.

__Desventajas:__
* Necesidad de invertir antes de obtener resultados.
* Carencia de métodos adecuados.
* Necesidad de formar al personal.
* Convencer a los “manager”.
* Dificultad para institucionalizar los procesos.
* Unidades de software que se reutilizan.
* Reutilización de sistemas de aplicación.
* Se incorpora sin ningún cambio en otros sistemas.
* Configuración de la aplicación para diferentes clientes.

## Modelo de métodos formales.
Un método formal es un camino a la construcción y análisis de modelos matemáticos que permitan una atomización del desarrollo de sistemas informáticos. Se caracterizan por emplear técnicas y herramientas matemáticas para lograr una facilitación a la hora de encarar la construcción o el análisis de un modelo matemático de un sistema. Los métodos formales se refieren entonces al uso de técnicas de la lógica y de la matemática discreta para especificar, diseñar, verificar, desarrollar y validar programas. En la lógica formal como en los métodos formales el objetivo es el mismo, “reducir la dependencia de la institución y el juicio humano para evaluar argumentos”. Los métodos menos rigurosos enfatizan en la formalización y renuncian a la computación, definición que implica un amplio espectro de técnicas, y una gama igualmente amplia de estrategias. 

### Clasificación
La clasificación más común se realiza en base al modelo matemático subyacente en cada método, de esta manera podrían clasificarse en:
Especificaciones basadas en lógica de primer orden y teoría de conjuntos: permiten especificar el sistema mediante un concepto formal de estados y operaciones sobre estados. Los datos y relaciones/funciones se describen en detalle y sus propiedades se expresan en lógica de primer orden. La semántica de los lenguajes está basada en la teoría de conjuntos. Los métodos de este tipo más conocidos son: Z, VDM y B.


__Especificaciones algebraicas:__ proponen una descripción de estructuras de datos estableciendo tipos y operaciones sobre esos tipos. Para cada tipo se define un conjunto de valores y operaciones sobre dichos valores. Las operaciones de un tipo se definen a través de un conjunto de axiomas o ecuaciones que especifican las restricciones que deben satisfacer las operaciones. Métodos más conocidos: Larch, OBJ, TADs.

__Métodos basados en álgebra de procesos:__ modelan la interacción entre procesos concurrentes. Esto ha potenciado su difusión en la especificación de sistemas de comunicación (protocolos y servicios de telecomunicaciones) y de sistemas distribuidos y concurrentes. Los más conocidos son: CCS,CSP y LOTOS.

__Métodos basados en Redes de Petri:__ una red de petri es un formalismo basado en autómatas, es decir, un modelo formal basado en flujos de información. Permiten expresar eventos concurrentes. Los formalismos basados en redes de petri establecen la noción de estado de un sistema mediante lugares que pueden contener marcas. 

__Métodos basados en lógica temporal:__ se usan para especificar sistemas concurrentes y reactivos. Los sistemas reactivos son aquellos que mantienen una continua interacción con su entorno respondiendo a los estímulos externos y produciendo salidas en respuestas a los mismos, por lo tanto, el orden de los eventos en el sistema no es predecible y su ejecución no tiene por qué terminar.



