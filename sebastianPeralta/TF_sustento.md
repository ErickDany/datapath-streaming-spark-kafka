# Real Time Processing Datapath
Trabajo Final del modulo de Real Time Processing - DEP8 (2023)

El proyecto consistio en implementar un flujo de ingesta y procesamiento de datos en real time. Apoyandose de la tecnología y herramientas que nos brinda Spark y Kafka en Python.

El contexto del proyecto es el streaming constante en eventos deportivos. Se propone que el servicio de Kafka reciba data relacionada al desempeño de equipos en multiples partidos minuto a minuto. Mediante operaciones de agregación es capaz de producir un output con datos relevantes. Algunos casos de uso es la transmisión en vivo de la posesion o precision de los equipos en television, analisis de desempeño para los analistas de los equipos, calculo de probabilidades en sitios de apuestas, etc.

Al desarrollar el proyecto si surgieron algunas dificultades como el jupyter que colapsaba de vez en cuando. Sin embargo, se logró completar el ebjetivo. 

Sería interesante poder replicar este ejercicio con un ambiente mas poderoso, sin las limitaciones de mi equipo local.

- Resultados (topic: matchesF)

![alt text](https://raw.githubusercontent.com/ErickDany/datapath-streaming-spark-kafka/main/sebastianPeralta/assets/first.PNG)

![alt text](https://raw.githubusercontent.com/ErickDany/datapath-streaming-spark-kafka/main/sebastianPeralta/assets/sec.PNG)

![alt text](https://raw.githubusercontent.com/ErickDany/datapath-streaming-spark-kafka/main/sebastianPeralta/assets/third.PNG)

