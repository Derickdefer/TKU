# TKU
El programa es un sistema de cotización de seguros que calcula el precio final de un seguro basado en varios factores. El usuario ingresa sus datos (nombre, edad, estado civil, cantidad de hijos, propiedades y salario), y el programa aplica recargos al precio base según las condiciones del asegurado. El proceso se repite hasta que el usuario ingresa la palabra "Salir".

Partes del problema a considerar:
Requisitos principales:

El asegurado debe ser mayor de edad (18 años o más).

Se aplican recargos basados en:

Edad del asegurado.

Edad del cónyuge (si está casado).

Cantidad de hijos.

Cantidad de propiedades.

Salario del asegurado.

Recargos:

Edad del asegurado y cónyuge:

10% si tiene entre 18 y 24 años.

20% si tiene entre 25 y 49 años.

30% si tiene 50 años o más.

Hijos: 20% del precio base por cada hijo.

Propiedades: 35% del precio base por cada propiedad.

Salario: 5% del salario del asegurado.

Interacción con el usuario:

El programa solicita datos mediante prompt.

Permite realizar múltiples cotizaciones hasta que el usuario ingrese "Salir".

Validaciones:

Verifica que el asegurado sea mayor de edad.

Convierte las entradas del usuario a números para realizar cálculos.

Mejoras posibles sobre el programa:
Validación de entradas:

Actualmente, el programa no valida si el usuario ingresa datos no numéricos en campos como edad, salario o cantidad de hijos. Podría mejorarse para evitar errores si el usuario ingresa texto en lugar de números.

Guardar historial de cotizaciones:

Podría almacenar las cotizaciones realizadas al final o permitir exportarlas.

Personalización del precio base:

Permitir que el usuario ingrese el precio base del seguro en lugar de tenerlo fijo.

Optimización de código:

Reducir la repetición de código, especialmente en los cálculos de recargos por edad (asegurado y cónyuge).

Más opciones de recargos:

Incluir otros factores que puedan afectar el precio del seguro, como historial médico, tipo de propiedad, etc.

Confirmación antes de salir:

Preguntar al usuario si está seguro de salir antes de terminar el programa.
