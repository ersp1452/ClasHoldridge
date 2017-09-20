# ClasHoldridge
Clasificación climática de Holdridge en programación modular con lenguaje python

Introducción
Las zonas de vida de Holdridge es un sistema de clasificación ecológica realmente útil debe tener  límites bien definidos, ser sensible a los pequeños cambios que ocurren en la vegetación (muchas  veces a corta distancia), ya sea en uno o varios de los factores ambientales que afectan el desarrollo o la presencia de los ecosistemas. También, el sistema debe reconocer los cambios introducidos por el efecto del hombre o de los animales y corresponder a unidades naturales discretas de tal forma que  puedan diferenciarse las unidades en el campo, ya sea con su vegetación original o donde esta haya  sido alterada fuertemente. Asimismo, para que un sistema ecológico tenga aplicación mundial, debe  estar definido por factores con aplicación en este mismo nivel y ser fácilmente obtenible en el mismo formato e idéntica exactitud.

Bases del sistema

El sistema se basa en la fisonomía o apariencia de la vegetación y no en la composición florística y los principales factores que tiene en cuenta para la clasificación de una región son la biotemperatura y la precipitación: los límites de las zonas de vida están definidos por los valores medios anuales de dichos componentes.
El sistema se basa en los siguientes tres parámetros principales:
* la biotemperatura media anual (en escala logarítmica). En general, se estima que el crecimiento vegetativo de las plantas sucede en un rango de temperaturas entre los 0 °C y los 30 °C, de modo que la biotemperatura es una temperatura corregida que depende de la propia temperatura y de la duración de la estación de crecimiento, y en el que las temperaturas por debajo de la de congelación se toman como 0 °C, ya que las plantas se aletargan a esas temperaturas.
* la precipitación anual en mm (en escala logarítmica);
* la relación de la evapotranspiración potencial (EPT) —que es la relación entre la evapotranspiración y la precipitación media anual— es un índice de humedad que determina las provincias de humedad.
* Las principales innovaciones del sistema Holdridge fueron el análisis de los efectos del calor mediante la biotemperatura; el uso de progresiones logarítmicas para obtener cambios significativos en las unidades de vegetación natural; y la determinación de la relación directa entre la biotemperatura y la evapotranspiración potencial (humedad) y la relación entre la humedad y la evapotranspiración real (y en definitiva, entre la evapotranspiración real y la productividad biológica).

Determinación de las zonas de vida

El programa ya tiene todos los procesos y solo se necesitan los datos a ingresar. Para
mayor información de este sistema de clasificación climática lo puede encontrar en el
siguiente enlace:
http://orton.catie.ac.cr/repdoc/A5519E/A5519E.PDF

Instrucciones del programa

Este programa comienza con la petición de datos como:
*Nombre de la región.
*Latitud y longitud de la región.
*Altitud.
*Y el intervalo de años que se tomó los datos de temperatura y precipitación (como 2000-2016).
Luego nos presenta un menú con 17 opciones las cuales serán explicados a continuación:
*La opción 0 es para terminar el programa.
*La opción 1 es para crear o resetear la tabla en donde se guardarán todos los datos que ingresemos y todo los resultados.
*La opción 2 es para mostrar la tabla.
*Las opciones 3, 4, 5, 6 y 7 se usa en caso se tenga datos mensuales.
*La opción 3 es para ingresar los datos de temperatura media mensual.
*La opción 4, 5 se utiliza en caso especiales que los datos de temperatura media mensual estén en el intervalo de 0 a 6 °C. Con estas dos opciones se introducen temperaturas máxima y mínima media mensual.
*La opción 6 es para ingresar los datos de precipitación mensual.
*La opción 7 es para procesar los datos mensuales y que luego esos resultados me sirvan para calcular la zona de vida de Holdridge.
*Las opciones 8, 9, 10, 11 y 12 se usa en caso se tenga datos anuales
*La opción 8 es para ingresar los datos de temperatura media anual.
*La opción 9, 10 se utiliza en caso especiales que los datos de temperatura media anual están en el intervalo de 0 a 6 °C. Con estas dos opciones se introducen temperaturas máxima y mínima media mensual.
*La opción 11 es para ingresar los datos de precipitación anual.
*La opción 12 es para procesar los datos anuales y que luego esos resultados me sirvan para calcular la zona de vida de Holdridge.
*Las opciones 13, 14, 15 y 16 se usan para poder hallar la zona de vida, provincia de humedad, piso altitudinal y región latitudinal. Estos deben ser utilizadas simultáneamente, es decir, se debe utilizar esas opciones juntas.
*La opción 17 se usa para mostrar los datos característicos de la región.
