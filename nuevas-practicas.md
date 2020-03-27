## Nuevas prácticas y conceptos en desarrollo de software

- Programacion de a pares y en masa (mobbing)
- Unit testing y desarrollo guiado por pruebas (TDD)
- Integración continua / Despliegue continuo / Distribución continua

- Integración continua (Continuos Integration / CI)

    La integración continua es una práctica de desarrollo de software donde los miembros de un equipo integran su trabajo con frecuencia, generalmente cada persona se integra al menos diariamente, lo que lleva a múltiples integraciones por día. Cada integración se verifica mediante una compilación automatizada (incluida la prueba) para detectar errores de integración lo más rápido posible.

    La automatizacion implica diferentes pasos según el tipo de software y sus requerimientos, pero generalmente como mínimo realiza las tareas de compilación y la ejecución de pruebas.
    La ejecución de pruebas unitarias, funcionales y de integración son el paso fundamentarl de la integración continua ya que permiten validar los cambios.
    Otros pasos comunes son la medición de cobertura (coverage) y la verificación de código. También se pueden incluir pasos como chequeos de seguridad del software, la firma digital y pruebas de carga entre otras.

- Distribución continua (Continuos Delivery)
    Es el siguiente paso de la integración continua, se automatiza el despliegue de los cambios, lo que permite llevarlos a producción. Se dispara el proceso de forma manual.

- Despliegue Continuo (Continuos Deployment / CD)
    Como en la distribución continua, se automatiza el proceso de desplegar los cambios a producción, pero además se realiza automáticamente con cada integración.


- DevOps
- Máquinas virtuales, containers e infraestructura como código
