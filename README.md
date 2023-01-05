# <h1 align=center> **PROYECTO INDIVIDUAL Nº3** 
# <h1 align=center> **Nicolás Lira M.** </h1>

# <h1 align=center>**`Data Analysis`**</h1>

<p align="center">
<img src="https://www.simplilearn.com/ice9/free_resources_article_thumb/Business_Analytics_vs_Data_Analytics.jpg"  height=300>
</p>

## Contexto

La industria de las telecomunicaciones ha jugado un papel vital en nuestra sociedad, facilitando la información a escala internacional y permitiendo la comunicación continua incluso en medio de una pandemia mundial. La transferencia de datos y comunicación se realiza en su mayoría a través de internet, líneas telefónicas fijas, telefonía móvil, casi en cualquier lugar del mundo.

## Rol a desarrollar

En este contexto, una empresa prestadora de servicios de telecomunicaciones me encarga la realización de un análisis completo que permita reconocer el comportamiento de este sector a nivel nacional. Consideraré que la principal actividad de la empresa es brindar acceso a internet, pero también es importante considerar el resto de los servicios.

Con el fin de monitorear la eficacia de los objetivos de la empresa, se me pide visualizar en un dashboard el siguiente KPI y establecer 3 KPIs adicionales producto de mi análisis:

    Evaluar el aumento o disminución de la variación porcentual trimestral del servicio de internet, cada 100 hogares por provincia.

Los datasets se encuentra en "https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/" 


## EDA

Mi EDA trata sobre "Tendencias de tecnologias para distribución de internet".
A priori, se revisaron los datasets a usar; "Penetración de Internet", "Velocidad promedio de ancho de banda por tecnología y provincia", "Accesos a internet por tecnología" y "Ingresos de las distribuidoras de Internet a nivel nacional".
Se verificaron datos nulos, caracteres en columnas, eliminación de columnas innecesarias y cambio de nombre para otras (está comentado).
El objetivo de "Penetración de internet" va relacionado con el KPI de Variación Porcentual, que da cuenta de que tanto se ha expandido Internet a los hogares argentinos y qué tan rápido o lento.
El objetivo de "Velocidad promedio" es dar cuenta de la población quiere tecnologias de internet con mayor ancho de banda. y/u otros servicios (ej: cablemodem puede traer TV cable).
El objetivo de "Accesos por tecnología" ver la tendencia clara que los clientes (ex-clientes en algunos casos) empiezan a preferir, siendo muy probable, mayor velocidad u otros servicios (ej: cablemodem puede traer TV cable).
Por último, "Ingresos totales" declara contundentemente que desde la fibra óptica empezó a ser demandada los ingresos se quintuplicaron lo que nos lleva a la conclusión:
A pesar de no mostrar valores numericos se ve claramente en representaciones gráficas que algunas tecnologias están destinadas a desaparecer mientras que otras están experimentando un boom por todos los beneficios que otorgan. ADSL requiere línea telefónica dedicada y está destinada a desaparecer mientras que cablemodem sobrevivirá un tiempo ya que aparte de un ancho de banda "medio" puede brindar el servicio de TV cable. Pero sin miedo a equivocarme, la fibra óptica será el vencedor ya que tiene un ancho de banda enorme y velocidad vertiginosa además de que también puede tener TV cable.




Adjunté un anexo.py , donde hay algunas definiciones conceptuales que me ayudaron en este proyecto. 

## SPEECH

La tecnología ha avanzado a pasos agigantados, sobretodo en las últimas 3 décadas. Se puede ver en muchos ámbitos de la vida cotidiana. Desde televisores robustos a "pantallas planas", automóviles eléctricos que se manejan solos, teléfonos fijos a inálambricos, que ya no sólo 
pertenecen al hogar, sino que funcionan en cualquier parte del mundo y computadores que sólo podrían haber sido parte de la imaginación hace 30 años.
Pero, sin dudas una de las tecnologias más revolucionarias de los últimos 30, incluso 40 años, es internet en la manera que nos permite interactuar con, literalmente, el resto del mundo.
Por eso, hoy como analista de datos, después de revisar varios datasets de las telecomunicaciones en Argentina podré guiar a la empresa para que haga buenas inversiones en las tecnologías de internet fija que son tendencia hoy en día.
Para eso identificaré indicadores de medida de actividad/resultado o KPI que son clave a la hora de reconocer tendencias.

Indicador 1) Variación porcentual
Indicador 2) Velocidad promedio de internet; podemos identificar claramente las tendencias. (CONTRA Y PROS)
Indicador 3) ADSL% - Cablemodem% - Fibra% . Crecimiento y desaparación de tecnologias de internet.
Indicador 4) Fibra%  desde 2018 -> Ingresos aumentan exponencialmente

A pesar de identificar tendencias no pude mostrar valores numericos, pero se ve claramente en los gráficos. En conclusión, la empresa debería invertir en la distribución de tecnologias de fibra óptica y Cablemodem en menor grado.

** CONTRA - ADSL requiere linea telefonica y es lento, quedará obsoleto.
** PRO - Cablemodem Puede traer television por cable, es un poco mas rapido que ADSL
** CONTRA - No es mucho mas rapido que ADSL y la TV será reemplazada por la fibra óptica

Gracias por escuchar, preguntas?
