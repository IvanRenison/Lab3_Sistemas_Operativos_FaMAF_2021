## Corrección
* Grupo:  27
* Docente: Milagro Teruel
* Commit: 92afb66
* Porcentaje: 100

|  | Concepto | Comentario | Estado |
|---|---|---|---|
| Entrega & Informe | En tiempo: 25/10/21 a las 23:59 |  | ok |
|  | Commit de todos los integrantes |  | ok |
|  | Commit frecuentes |  | ok |
|  | No Entregaron código objeto y/o ejecutables |  | ok |
|  | Nivel de legibilidad, formato y estructura del informe |  | ok |
|  | Responden a la pregunta: ¿Qué tipo de planificador tiene xv6? |  | ok |
|  | Responden a la pregunta: ¿Qué longitud tiene un quantum? |  | ok |
|  | Responden a la pregunta: ¿Hay alguna forma de que a un proceso se le asigne menos tiempo? |  | ok |
|  | Responden a la pregunta: ¿Se puede producir *starvation* en el nuevo planificador?  |  | ok |
|  |  |  |  |
| Calidad del Codigo | Comentarios explicativos en el código |  | ok |
|  | Uniformidad Idiomática |  | ok |
|  | Consistencia en los TABs, espacios, identacion |  | ok |
|  | Líneas de codigo "cortas" y bloques de codigo "chicos" |  | ok |
|  | Nombres de variables informativos y utilizacion de constantes |  | ok |
|  | Inicialización de todas las variables |  | no |
|  | Respetan (o mejoran) el coding style de xv6 |  | ok |
|  | Codigo redundante |  | ok |
|  | Sencillez y legibilidad |  | ok |
|  | ¿Tocaron solo los archivos pertinentes? (`proc.c`, `trap.c` etc.) |  | ok |
|  | ¿Definieron constantes? |  | ok |
|  | Modularizacion y encapsulamiento |  | ok |
|  |  |  |  |
| Funcionalidad | Definición de prioridad por cada proceso en struct proc. |  | ok |
|  | Inicialización a prioridad alta en allocproc o userinit y fork |  | ok |
|  | Baja de prioridad en transición RUNNING => RUNNABLE. (yield) |  | ok |
|  | Alza de prioridad en transición RUNNING => SLEEPING. (sleep) |  | ok |
|  | Impresión del campo nuevo de struct proc en procdump. |  | ok |
|  | El código funciona correctamente para cualquier valor de NPRIO. |  | ok |
|  | Cada vez que se planifica se vuelve a buscar desde la prioridad más alta. |  | ok |
|  | Cada nivel de prioridad debería ser round robin por su cuenta. (e.g. guardar la posición en la que quedó para cada nivel) |  | ok |
|  |  |  |  |
| Puntos estrellas | Priority boost |  | ok |
|  | Distintas longitud de quantums |  | ok |
|  | Planificador optimizado con operacion hlt |  | no |
|  | Analisis multiprocesador |  | no |
|  | Tickless kernel |  | no |
|  | Syscall para consulta tiempo asignado al proceso |  | no |