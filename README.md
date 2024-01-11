# Control PID para Bola en Viga

Este repositorio contiene el código fuente y recursos relacionados con la implementación de un controlador PID para el sistema de una bola sobre una viga. El controlador PID (Proporcional, Integral, Derivativo) se utiliza para lograr un seguimiento preciso y estable del sistema en distintas condiciones.

## Características Principales:

- Implementación del algoritmo PID para el control de posición.
- Adaptable a diversas situaciones y escenarios de la bola sobre la viga.
- Documentación detallada y comentarios en el código para facilitar la comprensión y extensión.
- Ejemplos y simulaciones que ilustran el comportamiento del sistema bajo diferentes configuraciones.


## Información Adicional del Estudio PDF:

- El PDF presenta un estudio sobre el diseño de un servomecanismo de posición para controlar la posición de una bola sobre una viga a partir del control del ángulo que forma la viga con el plano horizontal.

- Se proporciona un diagrama de bloques del servomecanismo de posición, que incluye la relación entre la posición angular del eje de salida del motor y la tensión de entrada al motor.

- Se demuestra que el sistema es inestable al emplear un regulador de acción proporcional-integral, utilizando el criterio de estabilidad y simulaciones en python.

- Se describe el uso de un sensor de posición proporcional en un extremo de la viga, el cual relaciona la tensión con la posición de la bola.

- Se justifica que empleando un regulador de acción proporcional-derivativa ("regulador PD") se puede estabilizar el sistema, y se aplican criterios de estabilidad para determinar los valores de Kp y Kd que hacen que el sistema sea estable.

- Los autores de este proyecto son Arnau González Almirall y Miriam de Juan Borrás, estudiantes de la Universidad Politécnica de Cataluña.


## Contribuciones:

¡Contribuciones y sugerencias son bienvenidas! Si encuentras mejoras, problemas o tienes nuevas ideas, no dudes en abrir un problema o enviar un pull request.

