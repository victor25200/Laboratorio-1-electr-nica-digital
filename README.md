# Laboratorio 1 eléctronica digital
## Circuito equivalente  74LS04
[![image.png](https://i.postimg.cc/bwJczFLM/image.png)](https://postimg.cc/svt0mmk9)
## Circuito equivalente  CD4069
[![image.png](https://i.postimg.cc/Vsr8tT8c/image.png)](https://postimg.cc/rzk3Xfsh)
## Integrado 74LS04
### Tiempo de subida
[![image.png](https://i.postimg.cc/XqPb4C6q/image.png)](https://postimg.cc/JHjgQtnC)
El tiempo de subida es de 104 nS
### Tiempo de bajada
[![image.png](https://i.postimg.cc/G2D1jpWs/image.png)](https://postimg.cc/njn5FncH)
El tiempo de bajada es de 338 nS
### Tiempo de retardo
[![image.png](https://i.postimg.cc/SRfmL5WF/image.png)](https://postimg.cc/N2LhBdJp)
El tiempo de retardo es de 84 nS
### Datasheet
Segun el datasheet su tiempo de bajada retardo y subida deben estar entre los 10 y 15 nS.
### Fan-In
Su fan-In es de uno por lo tanto cada compuerta solo puede resivir una entrada.
### Fan-Out
Su fan-Out no se pudo determinar se hiso la medicion  hasta 5 y funcionaba bien, pero tipicamente es de alrededor de 10 unidades de carga.
### Disipación de potencia 
Vcc = 2.22 V
Icc = 12.38 mA
Potencia disipada = (Vcc)(Icc)
Pd = (2.22V)(14.38mA) =31 mW
## Integrado CD4069
### Tiempo de subida
[![image.png](https://i.postimg.cc/KvshbghB/image.png)](https://postimg.cc/gnRTqjJ2)
El tiempo de subida es de 118 nS
### Tiempo de bajada
[![image.png](https://i.postimg.cc/htbwjJH2/image.png)](https://postimg.cc/Yv08DS2F)
El tiempo de bajada es de 1.16 uS
### Tiempo de retardo
[![image.png](https://i.postimg.cc/J48SWcFs/image.png)](https://postimg.cc/0rtVYmPv)
El tiempo de retardo 496 ns
### Datasheet
Segun el datasheet su tiempo de bajada retardo y subida deben estar entre los 30 y 50 nS.
### Fan-In
Su fan-in es de uno por lo tanto cada compuerta solo puede resivir una entrada.
### Fan-Out
Su fan out es de 5 unidades de carga.
### Disipación de potencia 
Vcc = 3.25 V
Icc = 13.23 mA
Potencia disipada = (Vcc)(Icc)
Pd = (3.25V)(14.38mA) =42.99 uW
###  Tabla comparativa: tiempos de subida, bajada y retardo de los integrados de forma experimental.
|Tiempo|74LS04| CD4069 |
| ------------ | ------------ | ------------ |
| Subida |  104 nS |  118 nS |
| Bajada  | 338 nS  |  1.16 uS |
|  Retardo |  84 nS | 496 ns  |
## Conclusiones
- El integrado 74LS04 En teoria sus tiempos de subida, bajada y retardo son mas rapido que el Cd4069 y según las mediciones realizadas se evidencia que es , sin embargo en una de las mediciones dio como resultado lo contrario esto puede ser debido a distintos factores como temperatura, desgaste del integrado e intrumentos, resitencias internas del mismo, error humano, etc.
- El integrado CD4069 tiene una menor dicipación de potencia que el integrado 74LS04 lo que significa que su eficiencia energética es mejprr lo que hace que su vida util y durabilidad sea mayor
- El integrado 74LS04 tiene una mayor fan-out que el CD4069 esto significa que si nececitamos conectar una salida de un integrado a varia entredas es preferible usar un 74LS04 




