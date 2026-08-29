# Guion de presentación — Sistemas Expertos

## Introducción — Camila

Hola, nosotros vamos a hablar sobre qué son los Sistemas Expertos, el conocimiento, la base de conocimiento, el motor de inferencia, la funcionalidad que tienen los Sistemas Expertos, una línea del tiempo de su evolución, los tipos, las ventajas y limitaciones, y los ejemplos de su aplicación en la ciencia a lo largo de los años.

El equipo está conformado por:

- Daniela Maite Reyes Arena
- Emiliano Narcizo Peralta Barrientos
- Camila Elizabeth Chi Hernández

---

## Introducción — Dani

Su propósito es simular, en cierta medida, el razonamiento de un experto humano. En esta presentación abordaremos su funcionamiento, componentes principales, tipos, evolución, ventajas, limitaciones y algunos de los Sistemas Expertos más representativos de la historia.

---

## Diapositiva 2 — ¿Qué es un Sistema Experto?

Un Sistema Experto es un sistema de Inteligencia Artificial diseñado para resolver problemas y tomar decisiones dentro de un área específica. Su funcionamiento se basa en conocimientos y reglas obtenidas de expertos humanos.

Por ejemplo, en el área médica puede analizar síntomas como fiebre, tos y dolor de garganta para generar una posible recomendación. Básicamente, recibe información, aplica sus reglas y obtiene una conclusión.

---

## Diapositiva 3 — ¿Qué es el conocimiento?

El conocimiento es toda la información que permite que el Sistema Experto pueda analizar una situación y tomar una decisión.

Está formado por hechos, conceptos, reglas y experiencias. Esta información puede obtenerse de expertos humanos, libros, documentos, bases de datos, manuales y procedimientos.

De esta manera, los datos se convierten en información, después en conocimiento y finalmente ayudan a tomar una decisión.

---

## Diapositiva 4 — Base de conocimiento

La base de conocimiento es el lugar donde se almacena y organiza todo el conocimiento que utiliza el Sistema Experto.

Principalmente contiene hechos y reglas. Por ejemplo, un hecho sería que un paciente tiene fiebre, mientras que una regla puede establecer que si tiene fiebre y tos, existe una posible infección respiratoria.

Sin embargo, esta base no toma decisiones por sí misma, sino que proporciona la información al motor de inferencia.

---

## Diapositiva 5 — Motor de inferencia

El motor de inferencia es el componente que toma los hechos de la base de conocimiento y aplica las reglas necesarias para obtener una conclusión.

Puede trabajar de dos formas:

- **Encadenamiento hacia adelante:** parte de los hechos hasta llegar a una conclusión.
- **Encadenamiento hacia atrás:** comienza con una posible conclusión y busca comprobar si existen los hechos necesarios para respaldarla.

---

## Diapositiva 6 — Funcionalidad de un Sistema Experto

La idea principal para explicar la funcionalidad del Sistema Experto es mostrar que recibe información, la analiza utilizando su conocimiento y genera una conclusión.

El motor de inferencia consulta y utiliza la base de conocimiento para transformar los datos proporcionados por el usuario en una conclusión.

### Ejemplo: posible infección respiratoria

Primero, el usuario proporciona algunos síntomas. En este caso, tenemos fiebre, tos y dificultad para respirar.

El sistema toma estas respuestas y las convierte en hechos que puede utilizar. Por ejemplo:

- Fiebre = Sí
- Tos = Sí
- Dificultad respiratoria = Sí

Después, el motor de inferencia compara estos hechos con las reglas que están almacenadas en la base de conocimiento.

Una de esas reglas establece que, si una persona presenta fiebre, tos y dificultad respiratoria, entonces puede existir una posible infección respiratoria y se recomienda realizar una evaluación médica.

Como en este caso se cumplen las tres condiciones, el motor de inferencia activa esa regla y genera una conclusión.

Finalmente, el sistema muestra el resultado al usuario. En este caso, recomendaría realizar una evaluación médica.

Obviamente, este es solamente un ejemplo para entender cómo funciona un Sistema Experto.

---

## Diapositiva 7 — Línea del tiempo de los Sistemas Expertos

Los Sistemas Expertos no aparecieron de un momento para otro, sino que fueron evolucionando junto con la propia Inteligencia Artificial.

Podemos comenzar en la década de 1950, cuando se establecieron algunos de los fundamentos de la Inteligencia Artificial. En esta etapa destacan trabajos como los de Alan Turing y posteriormente la conferencia de Dartmouth en 1956, donde se consolidó el término Inteligencia Artificial.

Después, en la década de 1960, comenzaron a desarrollarse sistemas que buscaban utilizar conocimiento especializado. Uno de los ejemplos más importantes fue DENDRAL, desarrollado en Stanford a partir de 1965. Este sistema trabajaba en el área de la química y ayudaba a determinar estructuras moleculares.

En la década de 1970 aparece otro sistema muy importante: MYCIN. También fue desarrollado en Stanford y estaba enfocado en el área médica. Su objetivo era ayudar a identificar infecciones bacterianas utilizando reglas basadas en conocimiento médico.

Posteriormente, durante la década de 1980, los Sistemas Expertos comenzaron a tener mayor presencia en el ámbito comercial. Un ejemplo importante fue XCON, que ayudaba a configurar sistemas informáticos de acuerdo con las necesidades de los clientes.

Sin embargo, durante la década de 1990 comenzó a disminuir el interés por los Sistemas Expertos tradicionales. Uno de los principales problemas era que adquirir el conocimiento de un experto y convertirlo en reglas podía ser complicado, además de que mantener y actualizar grandes cantidades de reglas era costoso.

Finalmente, en la actualidad, aunque ya no hablamos únicamente de los Sistemas Expertos tradicionales, muchas de sus ideas siguen presentes. Hoy podemos encontrar sistemas que combinan conocimiento, reglas y razonamiento con técnicas como el aprendizaje automático y otras áreas de la Inteligencia Artificial.

Entonces, podemos ver que los Sistemas Expertos fueron una etapa importante en la evolución de la Inteligencia Artificial.

---

## Diapositiva 8 — Tipos de Sistemas Expertos

Y conforme estos sistemas fueron desarrollándose, también surgieron diferentes formas de representar y utilizar el conocimiento. Por eso podemos encontrar distintos tipos de Sistemas Expertos.

El primer tipo son los **sistemas basados en reglas**. Estos trabajan principalmente con reglas del tipo «si-entonces». Por ejemplo, si una computadora no enciende y la fuente de alimentación no funciona, entonces el sistema puede recomendar revisar o reemplazar la fuente.

El segundo tipo son los **sistemas basados en casos**. Estos utilizan experiencias o problemas anteriores que tienen almacenados. Cuando reciben un problema nuevo, buscan casos similares y utilizan esa información para proponer una solución.

También tenemos los **sistemas basados en modelos**. Estos tienen un modelo de cómo debería funcionar determinado sistema o proceso. Entonces pueden comparar lo que debería estar sucediendo con lo que realmente está sucediendo para identificar posibles fallas. Por ejemplo, podrían utilizarse para detectar un problema en una máquina industrial.

Por último tenemos los **sistemas basados en redes semánticas**. Estos representan el conocimiento mediante conceptos y las relaciones que existen entre ellos. Por ejemplo, podemos relacionar un perro con el concepto de animal, y a partir de las relaciones entre conceptos el sistema puede obtener nueva información.

Entonces, aunque los cuatro tipos buscan utilizar conocimiento para resolver problemas, la diferencia principal está en **cómo representan y utilizan ese conocimiento**.

## Diapositiva 9 — Ventajas y limitaciones de los Sistemas Expertos

### Ventajas

- **Rapidez y capacidad de análisis:** Tienen una gran capacidad para procesar mucha información y aplicar una cantidad inmensa de reglas en poco tiempo.
- **Disponibilidad:** A diferencia de los humanos, que necesitan descansar, comer o realizar otras actividades, los sistemas expertos están disponibles siempre que se requiera consultar información o ejecutar un proceso.
- **Consistencia:** Aplican siempre las mismas reglas predefinidas a lo largo del tiempo, por lo que sus respuestas y evaluaciones son constantes y uniformes.
- **Conservación del conocimiento experto:** Permiten documentar y almacenar el conocimiento de personas especializadas en un área específica. Esto evita que la información se pierda y permite suplir temporalmente la ausencia de un experto humano.

---

### Limitaciones

- **Dependencia de la calidad del conocimiento:** Un sistema experto es tan bueno como la información y los datos que se le proporcionan. Si contiene reglas erróneas o datos incorrectos, las conclusiones tampoco serán válidas.
- **Dificultad para adquirir conocimiento experto:** Extraer, organizar y codificar el conocimiento de expertos humanos es un proceso sumamente complejo, riguroso y costoso.
- **Falta de sentido común:** A diferencia de los seres humanos, no poseen una comprensión natural del entorno. Están limitados a seguir estrictamente las reglas preestablecidas sin poder razonar más allá de ellas.
  - *Ejemplo:* Un sistema experto de climatización detecta que la temperatura sube e incrementa la potencia del aire acondicionado al máximo, sin considerar que hay una ventana abierta por la cual se está desperdiciando energía.
- **Riesgo de obsolescencia:** Las disciplinas y la ciencia evolucionan constantemente. Si la base de conocimiento no se actualiza con frecuencia, el sistema queda obsoleto rápidamente.

---

## Diapositiva 10 — Ejemplos de Sistemas Expertos en la historia

### 1. MYCIN (Ámbito médico)
Desarrollado para apoyar en el diagnóstico de infecciones bacterianas. Analizaba síntomas, resultados de laboratorio y datos del paciente utilizando aproximadamente **600 reglas** para identificar la posible bacteria causante y sugerir un tratamiento adecuado.

### 2. DENDRAL (Ámbito químico)
Diseñado para analizar datos obtenidos mediante espectrometría de masas y determinar la estructura molecular de compuestos químicos. Fue uno de los primeros sistemas en demostrar que el conocimiento especializado podía aplicarse eficazmente para resolver problemas científicos complejos.

### 3. XCON (Ámbito de computación y negocios)
Utilizado por *Digital Equipment Corporation* (DEC) para configurar sistemas informáticos según los requerimientos específicos de cada cliente. Aplicaba reglas para seleccionar componentes compatibles y optimizar el ensamblaje. Fue uno de los primeros sistemas expertos en implementarse con gran éxito a escala comercial.


---

## Conclusión — Dani

En conclusión, los Sistemas Expertos permiten aplicar conocimientos y reglas para resolver problemas y apoyar decisiones. Además, fueron fundamentales para el desarrollo de la Inteligencia Artificial que conocemos actualmente.

---

## Conclusión — Camila

A partir de estos ejemplos, podemos darnos cuenta de que los Sistemas Expertos ya tenían aplicaciones importantes mucho antes de que apareciera la Inteligencia Artificial generativa que conocemos hoy en día.

Su desarrollo surgió principalmente de la investigación científica y de la necesidad de aprovechar el conocimiento de los expertos para resolver problemas cada vez más complejos y específicos.

Por esta razón, los Sistemas Expertos fueron una parte importante en la evolución de la Inteligencia Artificial, ya que demostraron que una computadora podía utilizar conocimientos y reglas para analizar información, razonar y apoyar la toma de decisiones.

Muchas de estas ideas siguen presentes en diferentes sistemas de IA que utilizamos actualmente.

---
## Conclusión Emiliano: 

Como conclusión sobre los *sistemas expertos, es fundamental destacar que representan herramientas de gran relevancia dentro del campo de la **Inteligencia Artificial (IA)*. Su propósito principal es emular el razonamiento y la lógica humana para resolver problemas complejos a partir de reglas predefinidas y bases de conocimiento estructuradas.

* *Emulación de la lógica humana:* Permiten abordar y solucionar problemáticas específicas siguiendo estructuras lógicas formales y bases de datos especializadas.
* *Eficiencia y consistencia:* Desde sus inicios, han demostrado un alto nivel de precisión, confiabilidad y consistencia en sus resultados.
* *Complemento de la IA Generativa:* 
  * Aunque la IA generativa ha cobrado un gran protagonismo en los últimos años, suele presentar riesgos como las "alucinaciones" (invención de datos) o falta de determinismo.
  * Los sistemas expertos, al regirse por reglas estrictas y deterministas, *no cometen ese tipo de inconsistencias ni inventan información*.
* *Vigencia y aplicación actual:* Su combinación e integración con modelos modernos de IA los mantiene como una herramienta vigente, robusta e indispensable en el entorno tecnológico actual.
