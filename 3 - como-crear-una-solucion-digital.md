# Tecnologías y plataformas

En este capítulo vamos a hablar y definir el **corazón tecnológico** de nuestra estrategia. Es la base sobre la que el resto de estrategias, tácticas y futuros desarrollos se sostendrán, por lo que tenemos que hacerlo bien desde un primer momento.

La tecnología avanza muy rápido por lo que es crucial hacer uso de **estándares de programación** o **plataformas modulares fácilmente escalables**. Un término que tenemos que tener presente es *legacy* o heredado.

> El término **legacy** se refiere a un sistema informático o aplicación web que ha quedado anticuado pero que sigue siendo utilizado por los usuarios.

Si no somos capaces de diseñar nuestra aplicación pensando en las necesidades futuras, crearemos una solución únicamente apta a corto plazo pero que a largo plazo no cubrirá nuestras necesidades. Nuestro objetivo es disponer de una solución tecnológica **ágil y escalable**.

El concepto *Big Data* -aunque a nivel informático no supone nada nuevo- ha cambiado por completo la arquitectura software de las empresas. Si antes buscábamos aplicaciones que solucionaban problemas existentes, ahora buscamos aplicaciones que solucionan problemas existentes **de forma óptima** y preparadas para solucionar los problemas del futuro más cercano. 

Por ello, la **programación distribuida** y en especial el término **escalabilidad**, han cobrado mucha fuerza en los últimos años.

## Escalabilidad en aplicaciones

Dentro de la arquitectura de sistemas y de programación existe el **término escalable**. Cuando una aplicación comienza a dar signos de desgaste, bien por una carga de trabajo excesiva, un número de usuarios demasiado grande o por la imposibilidad de exprimir de forma eficiente los recursos con los que cuenta, llega el momento de escalarla. Podemos llevar a cabo dos tipos de escalados, **vertical** u **horizontal**.

### Escalado vertical (up)

También denominado *up*, quizá sea el escalado más rápido y económico que podemos realizar. Se trata de aumentar los componentes *hardware* que utiliza nuestra aplicación. Por ejemplo, aumentando la memoria RAM conseguiremos mejorar la velocidad de ejecución, mejorando la capacidad de disco podremos almacenar más datos, etc.

Las principales ventajas son que nos permite escalar de forma rápida y no afecta para nada a la aplicación (*software*). Su principal desventaja es que no podemos escalar verticalmente de forma indefinida y llegará un punto en el que seguir mejorando el hardware resultará muy costoso.

## Escalado horizontal (out)

Este tipo de escalado nos ofrece una posibilidad de crecimiento infinito ya que se trata de añadir, de forma ilimitada, nuevos servidores que permitan ejecutar nuestra aplicación de forma distribuida. Nuestra aplicación estaría utilizando un clúster.

> Un clúster es una red de ordenadores unidos entre sí que se comportan como si se tratase de una sola máquina.

Otras ventajas de implementar este escalado -además de un crecimiento infinito- sería la tolerancia a fallos, una alta disponibilidad del sistema y la posibilidad de aplicar un balanceo de carga que nos ayude a distribuir las ejecuciones de forma controlada por todos los nodos que conforman el clúster.

A la hora de diseñar nuestra solución tecnológica tenemos que tener presente la posibilidad de un escalado horizontal (vertical no hay problema ya que prácticamente todas las arquitecturas lo aceptan) ya que será la clave para que podamos utilizarla -de forma eficiente- a largo plazo.

## Plataformas tecnológicas

Existen múltiples plataformas tecnológicas que nos ayudarán en el diseño y desarrollo de nuestra solución web. Elegir una en detrimento de las otras dependerá fundamentalmente de nuestros recursos y necesidades.

Quizá las plataformas más conocidas a día de hoy sean la de Google Cloud y Amazon Web Services.
