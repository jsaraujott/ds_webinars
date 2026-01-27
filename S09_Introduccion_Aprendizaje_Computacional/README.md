En el siguiente caso de estudio vamos a introducir algunos conceptos básicos asociados a la preparación de los datos y a la construcción de algoritmos que permitan desarrollar modelos de aprendizaje computacional. En este sentido, es importante aclarar que el propósito de desarrollar este tipo de modelos radica en una de las opciones siguientes:

* Por una parte, la necesidad de pronosticar eventos específicos expresados en variables (usualmente llamadas objetivos) a través de otras variables explicativas (comúnmente llamadas atributos). A estos casos se les conoce como modelos **supervisados**.
* Por otra, la necesidad de descubrir y evidenciar patrones específicos a través de variables explicativas (atributos). A estos casos, se les conoce como modelos **no supervisados**.

En ambas circuntancias resulta evidente la necesidad de contar con datos, pues es en estos donde se guarda información asociada a variables, tanto de tipo objetivo como atributos. Por lo tanto, es aquí donde nos concentraremos específicamente, iniciando con los modelos **supervisados**.

Vale igualmente comentarte que existen otros modelos cuyos objetivos no dependen de la existencia de datos como tal, sino en la especificación de las llamadas "bases de conocimiento". Te recomiendo que en este ámbito investigues sobre los que son los modelos **por refuerzo** o los modelos de **razonamiento aproximado**, muy útiles para los desarrollos de inteligencias artificiales y robótica.

Volviendo a los modelos **supervisados**, existen dos tipologías distintas que dependen de la clase a la que corresponda la variable objetivo. Así, si la misma es numérica (entero o flotante) los modelos a utilizar se conocen como de **regresión**. Caso contrario, si el objetivo es no numérico (string o buleano) los modelos son de **clasificación**.

Empecemos entonces con el contexto del presente caso.
