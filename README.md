# Movilidad urbana y productividad económica en ciudades de LATAM

Este proyecto tiene como fin entregar un reporte para entender cómo la movilidad urbana (niveles de congestión, tiempos de viaje, retrasos) se relaciona con la productividad económica (PIB per cápita, desempleo) en las principales ciudades latinoamericanas y después poder identificar en qué ciudades invertir en infraestructura de transporte para aumentar la productividad y el bienestar de la población.

Estas son las librerías empleadas para el proyecto: 

```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt 
```
### **¿Las ciudades con mayor PIB per cápita también presentan más congestión? ¿O sucede lo contrario, o no existe una relación clara?**

No sucede lo contrario, más tampoco presentan mayor congestion. Solo 2 ciudades entran en el parametro de un PIB alto (CDMX y Montevideo) pero tomando estas 2 como ejemplo, 1 de ellas cuenta con el mayor PIB per capita y a su vez con la menor congestion de todo el grupo. No hay una relación explisitamente clara entre el PIB per capita y la cantidad de congestión, más tambien podríamos deducir que aquellas ciudades que entran en el PIB p/ capita medio-alto cuentan con una congestión equivalente o cerca de ella dando a entender que la clase trabajadora labura en una similitud de horario. Al ver la tabla mostrada anteriormente, la mayoria de las ciudades se encuentran en un PIB per capita medio-medio alto pero no todos cuentan con un congestión alta en tráfico, tal vez un estudio de ciudades más amplio pueda demostrar mayores ejemplos de un PIB per capita alto junto a un retraso por minutos mayor.
