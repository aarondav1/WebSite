---
layout: post
title:  Ciclo de vida del software y Paradigmas de desarrollo
date:   2018-07-17 15:01:35 +0300
image:  04.jpg
#tags:   Life
---
El ciclo de vida de un producto software es el desarrollo desde su fase inicial hasta la final, esto supone una gran complejidad cuando el objetivo es un gran sistema software pues hay muchos factores y problemas a tratar, como la cantidad de requisitos, el entendimiento entre el equipo de desarrollo y el cliente, la gestión del equipo, y el manejo de cantidades masivas de código. Por ejemplo: Un sistema que se encargue de las reservas, anulaciones y ventas de boletos de vuelo para un conjunto de compañías aéreas que se pueda usar en cualquier lugar del mundo. El desarrollo de este sistema tomaría años de desarrollo.

Para facilitar el desarrollo de software están los paradigmas, son una agrupación de métodos, herramientas y procedimientos con el fin de describir un modelo, entre ellos tenemos:
* Paradigma clásico o en cascada.
* Paradigma clásico con prototipado.
* Paradigma ágil.
* Paradigma en espiral. 

Cada paradigma tiene diferentes enfoques sobre como llevar a cabo el proyecto, aunque comparten los pasos principales del ciclo de vida del software. Podemos escoger el que mejor se apegue a nuestros requisitos. Si ninguno de estos paradigmas se adecua al problema por resolver, entonces el desarrollador se verá obligado a combinar los paradigmas o definir uno nuevo.

## Paradigma en cascada.

![]({{ site.baseurl }}/images/11.jpg)
*Minimalism*
 
__*Las fases del modelo cascada:*__
* El análisis y definición de requerimientos: Se analizan las necesidades de los usuarios finales del software a desarrollar para determinar que objeticos debe cumplir.
* Diseño del sistema y software: Se descompone y organiza el sistema de forma que pueda desarrollarse por separado, aprovechando las ventajas del desarrollo en equipo.
* Pruebas de implementación de unidades: Se desarrolla el código fuente haciendo uso de prototipos.
* Integración y pruebas del sistema: Se ensamblan los elementos ya programados y se comprueba su funcionamiento. La prueba se centra en la lógica interna del software. 
* Operación y mantenimiento: El software obtenido se pone en producción. En el desarrollo surgen cambios, para corregir errores o bien para introducir mejoras. El software sufre cambios después de que se entrega al cliente. Los cambios ocurrirán debidos a que hayan encontrado errores, a que el software deba adaptarse.

__*Problemas del Modelo de Cascada:*__
* Inflexible división del proyecto en fases distintas hace que sea difícil responder a las necesidades cambiantes de los clientes.
* Por lo tanto, este modelo sólo es apropiado cuando los requisitos son bien entendidos y los cambios serán bastante limitados durante el proceso de diseño.
* Pocos sistemas tienen requisitos estables.
*El modelo de cascada se utiliza sobre todo para los grandes proyectos de ingeniería de sistemas en que un sistema se desarrolla en varios lugares.
* El principal inconveniente del modelo de la cascada es la dificultad de acomodar el cambio después de que está en marcha el proceso. En principio, una fase tiene que ser completada antes de pasar a la siguiente fase.

## Paradigma prototipado.

![]({{ site.baseurl }}/images/12.jpg)
*Minimalism*

__*El paradigma de construcción de prototipos tiene tres pasos:*__ 
* Escuchar al cliente. Recolección de requisitos. Se encuentran y definen los objetivos globales, se identifican los requisitos conocidos y las áreas mas importantes.
* Construir y revisar la maqueta (prototipo). 
* El cliente prueba la maqueta (prototipo) y lo utiliza para refinar los requisitos del software. 

__*Este modelo es útil cuando:__*
* El cliente no identifica los requisitos detallados. 
* El responsable del desarrollo no está seguro de la eficiencia de un algoritmo, sistema operativo o de la interface hombre-máquina. 

## Paradigma Ágil

![]({{ site.baseurl }}/images/13.jpg)
*Minimalism*

El paradigma AGIL es un esquema sociológico creado por el sociólogo americano Talcott Parsons en los años 1950. Es una pintura sistemática de ciertas funciones sociales, que cada sociedad debe encontrar para ser capaz de mantener la vida social estable. El paradigma AGIL es la parte de la teoría de acción más grande de Parsons, perfilada en su libro notable La Estructura de Acción social, El Sistema social y con trabajos posteriores, que pretende construir un mapa unificado de todos los sistemas de acción, y por último "sistemas vivos." En efecto, realmente el sistema de AGIL sólo apareció en su primera forma complicada en 1956 y Parsons amplió el sistema en varias capas de la complejidad durante el resto de su vida intelectual. Al final de su vida añadió una nueva dimensión al sistema de  acción que llamó el paradigma de las condiciones humanas, dentro de ese paradigma, el sistema de acción ocupó la dimensión integral.

Los requisitos previos funcionales de sistemas de acción (incluso el sistema social).
La teoría de los curas es una parte del paradigma de la teoría de acción. AGIL representan el esquema funcional del sistema de acción general entero (incluso el paradigma de condición humano), de modo que AGIL también defina el sistema cultural, el sistema de personalidad etc. El sistema social representa la parte integrante del sistema de acción y es de esta manera sólo un subsistema dentro del mayor todos sistemas. Por ejemplo, el pedido del sistema cultural respecto del esquema funcional AGIL es:
__A__: Symbolization cognoscitivo.
__G__: Symbolization expresivo.
__I__: Symbolization moral y evaluativo.
__L__: Symbolization constitutivo.

## Paradigma en espiral.

![]({{ site.baseurl }}/images/14.jpg)
*Minimalism*

__Cada ciclo de la espiral se divide en cuatro sectores:__
1. Definición de objetivos. Para esta fase del proyecto se definen los objetivos específicos. Se identifican las restricciones del proceso y el producto, y se traza un plan detallado de gestión. Se identifican los riesgos del proyecto. Dependiendo de estos riesgos, se planean estrategias alternativas. 
2. Evaluación y reducción de riesgos. Se lleva a cabo un análisis detallado para cada uno de los riesgos del proyecto identificados. Se definen los pasos para reducir dichos riesgos. Por ejemplo, si existe el riesgo de tener requerimientos inapropiados, se puede desarrollar un prototipo del sistema, determinar objetivos. alternativas y restricciones. Planificar la siguiente fase del plan de desarrollo, integración y plan de prueba, evaluar alternativas, identificar y resolver riesgos.
3. Desarrollo y validación. Después de la evaluación de riesgos. se elige un modelo para el desarrollo del sistema. Por ejemplo. si los riesgos en la interfaz de usuario son dominantes. un modelo de desarrollo apropiado podría ser la construcción de prototipos evolutivos. Si los riesgos de seguridad son la principal consideración, un desarrollo basado en transformaciones formales podría ser el más apropiado, y así sucesivamente. El modelo en cascada puede ser el más apropiado para el desarrollo si el mayor riesgo identificado es la integración de los subsistemas. 
4. Planificación. El proyecto se revisa y se toma la decisión de si se debe continuar con un ciclo posterior de la espiral. Si se decide continuar. se desarrollan los planes para la siguiente fase del proyecto. La diferencia principal entre el modelo en espiral y los otros modelos del proceso del software es la consideración explícita del riesgo en el modelo en espiral. 

