![Universidad de América](https://www.google.com/search?sca_esv=678f334ebb2e9f3d&q=uamerica&uds=AMwkrPt94q4_YZEgas_DfQYD0xIjBP602SDf_k0UIqKJWdtmgtFv741wwExXqWDBjeXUDX-Md49P8kF0F25pUzuZl7o_RPxP_jtRA64fAa72lq4dcbWJaIF5I6ot0-x3boja14rVMiGZQoqMKNTBatUcBuMs6JDw3EM9yDp7t-1kLeRgSBJl-sFRaE3zSAbqvOOa5_r8jAmZSDErKuIvdimhBcp_CnsC0UY5Pr1wXotqWkd-aRnhtyaP-TeQPn2x0PU2LU6LtvaojVIeM91nwvNu0OxttY6oM8HqbazNHikx-LdPKkCnES8&udm=2&prmd=ivsnmbtz&sa=X&ved=2ahUKEwiU2b-j8N6FAxUkTDABHSsUAakQtKgLegQIGBAB&biw=1366&bih=599&dpr=1#vhid=F51QgrVYQDCzdM&vssid=mosaic)

FACULTAD DE CIENCIAS ECONOMICAS Y CONTABLES PROGRAMA DE ESTADISTICA Y CIENCIA ACTUARIAL
#DETECCIÓN TEMPRANA DEL RIESGO DE ABANDONO DE CLIENTE DE UNA COMPAÑÍA DE TELECOMUNICACIONES
ÓSCAR EDUARDO APONTE ALGECIRA
Bogotá, Colombia 2024
 
#DETECCIÓN TEMPRANA DEL RIESGO DE ABANDONO DE CLIENTEs DE UNA COMPAÑÍA DE TELECOMUNICACIONES


Este repositorio contiene un notebook que permite analizar los datas para la predicción de abandono de clientes de una compañia telefonica. En el repositorio encontrará la carpeta data que tiene los datos CVS. que tiene la información de una compañia de telefonía.

#JUSTIFICACIÓN

En la actualidad es ineludible el crecimiento de la tecnología y los servicios digitales que generan un mercado globalizado más competitivo e innovador, lo que produce un reto para las compañías lograr fidelizar a sus clientes. La retención de estos es una tarea ardua que necesita del estudio de diferentes estrategias económicas, publicitarias, modelos estadísticos y matemáticos apoyados en herramientas poderosas como los softwares que generen aprendizajes automatizados en los cuales se puedan soportar para la toma de decisiones más acertadas para la compañía. La competitividad y los múltiples servicios que se encuentran hoy en día al servicio de los clientes, son un reto a los cuales las compañías están obligadas a adaptarse para evitar pérdidas, por ello es importante la detección temprana del riesgo de abandono de clientes, ya que diferentes estudios han determinado que mantener un cliente en la compañía es mucho más rentable que atraer uno nuevo, por lo que la retención de clientes es uno de los objetivos principal de las compañías.
El objetivo de este proyecto es realizar un modelo de detección de clientes que posiblemente quieran abandonar la compañía mediante la medición de diferentes variables y el aprendizaje automatizado, con el propósito de realizar estrategias para la retención de cliente.


#OBJETIVO

Obtener una base de datos con veracidad de una compañía telefónica que contenga una variedad de datos independientes que tengan incidencias para poder llegar a tener una relación con el abandono de los clientes de la compañía.


ACTIVIDADES

1.	Revisar la base de datos cumpla con las condiciones de las 5V que se requieren para la caracterización de la Big Data y su tipo de archivo
 
2.	Determinar los tipos de datos que tengo y su estructura
3.	Caracterizar los datos relevantes que me determinen una relación de abandono del cliente
4.	Realizar la limpieza requerida de los datos determinantes para el estudio y modelamiento
5.	Realizar un análisis descriptivo, para posteriormente realizar inferencia sencilla y determinar si datos determinísticos
6.	Aplicar diferentes técnicas de aprendizaje automatizado con el fin de evaluar el comportamiento de cada una y así hacer un modelo que pondere un resultado final
7.	Presentar resultados concretos para realizar una próxima toma de decisiones.

#RESULTADO FINAL


Se presentará un modelo predictivo y aplicable para la detección temprana de clientes que estén en riesgo de abandono de la compañía, determinando si las variables cualitativas o cuantitativas afectan más la salida de clientes, con el fin de reducir costos en atraer nuevos clientes y sacar provecho de los datos para obtener mejores oportunidades de negocio y una ventaja competitiva.

 
#Introducción 
El mundo de las telecomunicaciones se ha vuelto crucial tanto en países avanzados como en aquellos que están en proceso de desarrollo. Con el constante avance tecnológico y la creciente cantidad de empresas en el mercado mundial, la competencia se ha vuelto más intensa que nunca. Las compañías están trabajando arduamente, implementando diferentes estrategias para poder mantenerse a flote en este entorno tan competitivo.
El churn (o la deserción de clientes) es una tendencia de los clientes a abandonar una marca y dejar de ser un cliente que paga en un negocio en particular. El porcentaje de clientes que dejan de usar los productos o servicios de una empresa durante un período de tiempo particular se denomina tasa de abandono (abandono) de clientes. Una de las formas de calcular una tasa de abandono es dividir el número de clientes perdidos durante un intervalo de tiempo determinado por el número de clientes adquiridos, y luego multiplicar ese número por el 100 por ciento. Por ejemplo, si obtuvo 150 clientes y se perdió tres el mes pasado, su tasa de rotación mensual es del 2 por ciento.
La experiencia del cliente, también conocida como Customer Experience (CX), se ha convertido en un elemento clave en la estrategia de cualquier negocio. Una excelente experiencia del cliente puede marcar la diferencia entre mantener a un cliente leal, o perderlo frente a la competencia.
De hecho, según diversos estudios, cuesta entre 5 y 25 veces más conseguir un nuevo cliente que retener uno existente. (Fuente: Harvard Business Review)
Estadísticas reveladoras muestran cómo la experiencia del cliente impacta los resultados financieros de una empresa:
Un aumento del 5% en la retención de clientes puede aumentar las ganancias en un 25% a 95%. (Fuente: Harvard Business Review)
 El 86% de los clientes estarían dispuestos a pagar más por una mejor experiencia del cliente. (Fuente: SuperOffice)
El 73% de los clientes citan la experiencia del cliente como un factor importante en su decisión de compra. (Fuente: PwC)
El 77% de los clientes recomendaría una empresa a otros después de tener una experiencia positiva. (Fuente: Temkin Group)

#Compresión de Datos

Antes de profundizar en el análisis de datos, es crucial comprender bien las características de los datos que estamos estudiando. Esto nos ayuda a tener una visión más clara antes de adentrarnos en explicar los hallazgos. Durante esta fase inicial, llevamos a cabo lo que llamamos Comprensión de los Datos. Algunos pasos de preparación son bastante simples, como asegurarse de que los datos tengan un formato adecuado y eliminar duplicados. Otros pasos, más complejos, los abordaremos más adelante durante el 

#Análisis Explicativo de Datos.
Caracterización de la Data

1.  La base de datos se trae es un archivo CSV.
2.  Se obtienen de la plataforma Kaggle, derivados de Escuela de Tecnología Digital Purwadhika de Indonesia, en cual se analiza una compañía telefónica
3. La base de datos es de Información Estructurada 
4. Contiene una combinación de variables cuantitativas y cualitativas que se utilizan para analizar el comportamiento de los clientes 

#Las 5 V de Big Data
1. Volumen: Nos enfrentamos a grandes volúmenes datos.       
2. Velocidad: Velocidad, la de generación y la actualización de los datos     
3. Variedad: Los datos son diversos      
4. Veracidad: La veracidad de la fuente impacta el grado de fiabilidad     
5. Valor:  El valor que generan los datos es relevante        


#Ciclo de Vida de los datos Generación

1.   Gobernanza de Datos es pública
2.   Metadatos y Catalogación es clara


Este conjunto de datos nos brinda información sobre los clientes de una empresa de telecomunicaciones y si han decidido dejar de utilizar sus servicios o no. Para las compañías de telecomunicaciones, perder clientes es muy importante, ya que retener a los clientes existentes suele ser más beneficioso que conseguir nuevos. Con estos datos, podemos analizar qué factores influyen en la decisión de los clientes de abandonar el servicio y también podemos crear modelos que nos ayuden a predecir cuáles clientes podrían estar en riesgo de irse.

#Metodologías y tipos de análisis de datos actuales

1. Análisis Descriptivo
2. Análisis Exploratorio
3. Análisis de sentimiento
4. Análisis Predictivo
5. Análisis Prescriptivo


#Aplicación de aprendizaje automatizado Machine learning 
#Ajustes del Modelo
#Evaluación del modelo
#Explicación y resultados del Modelo


