# taller-Mapreduce
Durante el taller de MapReduce, el profesor puso a disposición de los alumnos varios archivos conteniendo información bibliográfica sobre publicaciones técnicas y científicas. Como hablamos en clase, es interesante analizar dicha información y saber sobre qué temas se está publicando más (análisis de palabras del título de las publicaciones), con cuántas publicaciones cuenta cada autor, cuántas publicaciones se ha publicado en solitario, etc. El alumno tiene libertad para improvisar realizando los análisis que considere oportuno y de utilidad. Presentad una pequeña memoria en formato libre explicando los resultados obtenidos.

Se debe entregar el proyecto eclipse (comprimido) con todo el código y el correspondiente archivo pom.xml (maven) de configuración. Además, se plantea al alumno que explique de forma muy breve el uso de HUE en base a ejemplos con los archivos de datos entregados.

Posibles problemas: El tamaño de bloque de una configuración HDFS suele ser 128 o 256 MBs. Ejecutar procesos mapReduce con cientos o miles de archivos con tamaño muy inferior al tamaño de bloque es ineficiente porque no aprovecha bien el potencial de Hadoop y crea un número excesivo de mappers. Una solución es emplear SequenceFiles, otra más sencilla es, quizá mejor mediante código, conseguir que todos los archivos entregados formen un único archivo antes de entrar al proceso mapReduce, esta parte es totalmente opcional.

NOTA: Aunque se haga en grupo, recordad realizar todos la entrega, por favor, adjuntad un txt con los miembros del grupo y la nota que cada uno propone para sus compañeros. Esta calificación puede ser numérica o cualitativa (aprobado, notable...)

