# Brewing Data Cup
El BDC es el Hackathon de Ciencia de Datos organizado por [Grupo Modelo](https://en.wikipedia.org/wiki/Grupo_Modelo). El objetivo es seleccionar a los mejores Científicos de Datos para ingresar a las filas del equipo de la cervecera más grande del mundo.

# INVITACIÓN AL SLACK
Da click [aquí](https://join.slack.com/t/brewingdatacup2/shared_invite/enQtNTgzMjk0MDQ1MDQxLTcyZTBiNDFjNWI1YmRiZDZmYmM3MTMyY2VmYzU0ZDZlYzQ4NjhkZDgzOWUxZDdmM2VkNzg2ZmMxZjYwZDRkMzI)

## ¿De qué trata este reto?
### Contexto
Existen varias formas de pronosticar la demanda y una de ellas es encontrar el potencial de venta de los clientes, es decir, identificar que porcentaje adicional de cerveza se le puede ofrecer a un cliente.

Si te damos información geográfica de los clientes e información de google ¿Nos ayudarías a encontrar el potencial de venta de los clientes?

Tomando en cuenta que siempre se puede agregar información adicional, como por ejemplo del INEGI o de alguna otra fuente de información externa.

### Reto
Con la ayuda de las variables que hemos extraido de google junto con información externa que agreguen (económica, demográfica, clima, etc.), identifica drivers de crecimiento.

Variables a optimizar:
* Factores de crecimiento
* Forecast de demanda

## Diccionario de datos
![](https://i.imgur.com/NYqKOHPg.png)

La variable objetivo es `in_top`, que es una variable binaria que indica si un cliente tuvo crecimiento o no.

## Entregables
* Código fuente que pueda tomar como input un _.csv_ con las mismas columnas que tiene el de este repo y ejecute el modelo que entrenaron
* Presentación con explicación de variables que impactan, recuerda que incluso modelos de caja negra (e.g. Random Forest, Neural Networks) pueden ser interpretables con sistemas como [LIME](https://github.com/marcotcr/lime).

Como guía para la presentación, sugerimos que incluyas las siguientes secciones:
* Metodología
* Insights
* Estrategia