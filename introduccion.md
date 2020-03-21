# Fases tradicionales del desarrollo de software

- Captura de requerimientos
- Análisis y Diseño
- Desarrollo
- Prueba (Testing)
- Despliegue

# Roles tradicionales en desarrollo de software

- Analista funcional (captura de requerimiento, análisis y diseño)
- Desarrollador / Programador (diseño y desarrollo software)
- Tester / QA (pruebas, verificación del software)

# Nuevas prácticas en desarrollo de software

- Programacion de a pares y en masa (mobbing)
- Unit testing y desarrollo guiado por pruebas (TDD)
- Integración continua / Despliegue continuo / Distribución continua

    Mantener el código en un estado desplegable en todo momento

- DevOps
- Máquinas virtuales, containers e infraestructura como código

# Ciclo de liberación del software

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
