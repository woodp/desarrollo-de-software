# Introducción al desarrollo de software

El desarrollo de software es una disciplona joven. Hace poco más de 60 años que se programan computadoras, hace 40 se empezó a intentar sistematizar un proceso, y hace unos 30 se empezaron a introduciar paradigmas que permitan el manejo de la complejidad. Comparado con las ingenierías tradicionales que tienen siglos de antigüedad, es una actividad inmadura.


## Metodologías de software

- Cascada
- Iterativo: UP / RUP
- Agiles: Scrum, XP, Lean, Kanban

### Cascada (Waterfall)

#### Ciclo de vida

- Captura de requisitos
- Análisis y Diseño
- Desarrollo
- Pruebas (Testing)
- Despliegue
- Mantenimiento

#### Roles

- Analista funcional
- Diseñador
- Programador
- Tester / QA

Se capturaban todos los requisitos, y una vez elaborados y validados con el cliente se "congelaban". Muchas veces requiriendo la firma del cliente en este paso. A partir de este momento el cliente no podía pedir cambios hasta que el software fuera finalizado y entregado. En todo caso los cambios eran considerados una segunda etapa donde todo el proceso empezada desde cero.

Les programadores era consideraros como el equivalente de un obrero industrial que debía ejecutar el diseño que habían realizado les diseñadores en base a los requisitos elaborados por les analistas funcionales.
Los documentos tenían la misma o más importancia que el software e incluso flotaba la idea de que el código iba a poder ser generado automáticamente.


Los tiempos de entrega solían ser largos y muchos proyectos de software fracasaron en esta época. Esto llevó a que surgieran nuevas metodologías de desarrollo de software.

### UP: Unified Process

RUP: Rational Unified Process

Es un proceso iterativo que tiene forma de mini cascadas. Si bien cada iteración abarca todas las fases. En las primeras iteraciones tiene preponderancia la elaboración requisitos, luego en sucesivas iteraciones el diseño, después el desarrollo y por último el despliegue.

![Etapas de RUP](https://image.slidesharecdn.com/metodologarupfinal-170322045322/95/metodologa-rup-final-6-638.jpg?cb=1490158865)

Se aceptan cambios y se favorece la interacción con el cliente.

La calidad del producto debe evaluarse en todas las etapas del proceso.


### Metodologías ágiles




### Lean

Los siete principios del desarrollo Lean son: 
- Eliminar el desperdicio
- Generar calidad
- Crear conocimiento
- Diferir el compromiso
- Entregar rápidamente
- Respetar a las personas
- Optimizar el todo


## Nuevas prácticas y conceptos en desarrollo de software

- Programacion de a pares y en masa (mobbing)
- Unit testing y desarrollo guiado por pruebas (TDD)
- Integración continua / Despliegue continuo / Distribución continua

    Mantener el código en un estado desplegable en todo momento

- DevOps
- Máquinas virtuales, containers e infraestructura como código

## Ciclo de liberación del software

- Pre-alpha: antes del testing
    - Milestone: hito
- Alpha: versión que incluye testeo inicial, suele estar disponible únicamente internamente en la empresa, puede contener errores graves
- Beta - Preview: ya tiene toda la funcionalidad pero puede tener errores conocidos o desconocidos, es la primera versión que sale fuera de la empresa.
    - Gmail estuvo en beta desde su salida en 2004 hasta el 2009
- RC - Release Candidate: versión que que ya pasó por uno o más ciclos de beta testing y es candidata a ser un release estable.
- Stable release: versión estable del producto
- GA - General available: versión liberada al público general, en software comercial puede tener etapas posteriores al RC para estar disponible para su comercialización.
- LTS release: versión a la que la empresa le dará soporte a largo plazo (long term support)
- Descontinuado: ya no se ofrece soporte para el producto
    - ej: Windows XP

# Versionado Semántico (SemVer)

Dada una versión: MAYOR.MENOR.PARCHE:

- incrementar la versión *MAYOR* cuando hay cambios incompatibles con la version anterior (breaking changes),
- incrementar la versión *MENOR* cuando se agrega funcionalidad que es compatible hacia atrás, y
- incrementar la versión *PARCHE* cuando se arreglan defectos (bugs) (también manteniendo compatibilidad).

Además se puede agregar sufijos para indicar que es una versión beta o pre-release.

Ejemplos: 

    - 1.0.2
    - 0.0.3-beta
    - 0.4.5-pre-release

Versiones de Android:
| Nombre | Versión | Fecha de release |
| --- | --- | --- |
| Apple Pie | 1.0 | 23 de septiembre de 2008 |
| Banana Bread1 | 1.1 | 9 de febrero de 2009 |
| Cupcake | 1.5 | 25 de abril de 2009 |
| Donut | 1.6 | 15 de septiembre de 2009 |
| Eclair | 2.0 – 2.1 | 26 de octubre de 2009 |
| Froyo | 2.2 – 2.2.3 | 20 de mayo de 2010 |
| Gingerbread | 2.3 – 2.3.7 | 6 de diciembre de  || 2010 |
| Honeycomb | 3.0 – 3.2.6 | 22 de febrero de  |2011
| Ice Cream Sandwich | 4.0 – 4.0.5 | 18 de  |octubre | de 2011 |
| Jelly Bean | 4.1 – 4.3.1 | 9 de julio de 2012 |
| KitKat | 4.4 – 4.4.4 | 31 de octubre de 2013 |
| Lollipop | 5.0 – 5.1.1 | 12 de noviembre de  |2014
| Marshmallow | 6.0 – 6.0.1 | 5 de octubre de  |2015
| Nougat | 7.0 – 7.1.2 | 15 de junio de 2016 |
| Oreo | 8.0 – 8.1 | 21 de agosto de 2017 |
| Pie | 9.0 | 6 de agosto de 2018 |
| Android 10​ | 10.0 | 3 de septiembre de 2019 |
