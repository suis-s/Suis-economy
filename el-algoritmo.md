# Unicamente lo que el ser humano valoró sobrevivió. De aqui en adelante, quien valorará qué?

## Optimalidad actual
#### 0.0.1
La optimalidad actual con la informacion disponible de CommonCrawl es superior a la de Linkedin Ads e inferior a la de Google, dado que el acceso es a los datos de todas las paginas web en el mundo, por lo cual, tenemos conocimiento del 99% de las empreas en el mundo, salvo el 1% que no dispone de web. 

- Linkedin dispone del conocimiento de 58 millones de empresas.
- CommonCrawl dispone del conocimiento de 150 millones de empresas.

Como podemos capitalizar 1 dolar por cada una? Esa es la potencial produccion del algoritmo en esta versión: U$S 150.000.000, que luego se utilizan para nuevos movimientos, por lo que crecerá de forma exponencial, estable y predecible. 

Alcanzar esta versión de optimalidad del algoritmo me dará:
- Posibilidad de dar muestras de información de todos quienes probablemente comprarán X.
- Seguridad de que una vez me pidan, puedo entregar la informacion y cobrarla inmediatamente.
- Dar la información en gotas, facilitando el inicio de la relacion de intercambio.
- Usar yo mismo la informacion y con ello dar muestra de la rentabilidad de la misma.
- Obtener los recursos con los que optimizar a la siguiente version en la que accedo a la informacion de consumidores finales.

#### 0.0.2 
Una vez acceda a informacion de consumidores finales en LiveRamp o WPP, ahi la optimalidad del algoritmo asciende a posicionarse mas cerca de la optimalidad de Google y Facebook: miles de millones de dolares. 

---------------------------------
# Algoritmo actual
Para clasificar todas las páginas web según su contenido y luego ejecutar búsquedas sobre esos atributos en AWS, puedes seguir un enfoque que involucre varias etapas, desde la extracción y clasificación de datos hasta la implementación de un motor de búsqueda. Aquí te dejo un posible flujo de trabajo utilizando varios servicios de AWS:

Extracción de Datos:
Utiliza Amazon EMR para procesar y extraer datos relevantes de las páginas web almacenadas en el repositorio de Common Crawl en AWS S3. Puedes emplear Apache Spark o Apache Hadoop en un clúster de EMR para realizar operaciones de extracción y transformación de datos.

Clasificación de Contenido:
Implementa un modelo de clasificación de contenido utilizando un servicio de aprendizaje automático de AWS, como Amazon SageMaker. Entrena el modelo con datos etiquetados y luego utiliza el modelo para clasificar el contenido de las páginas web según categorías predefinidas.

Almacenamiento de Datos Clasificados:
Almacena los resultados de la clasificación junto con la información original de las páginas web en una base de datos gestionada, como Amazon DynamoDB o Amazon RDS, para facilitar el acceso y la recuperación de datos.

Indexación de Datos:
Indexa los datos clasificados en un motor de búsqueda, como Amazon Elasticsearch. Esto permitirá realizar búsquedas rápidas y eficientes basadas en los atributos clasificados.

Interfaz de Usuario y Motor de Búsqueda:
Desarrolla una interfaz de usuario para permitir a los usuarios realizar búsquedas en función de los atributos clasificados. Puedes utilizar servicios web para la interfaz, como AWS Amplify o Amazon API Gateway junto con AWS Lambda y un servidor web en Amazon EC2 o AWS Fargate.

Seguridad:
Implementa medidas de seguridad, como control de acceso y cifrado, para proteger tanto los datos almacenados como el acceso a la interfaz de usuario y al motor de búsqueda.

Programación de Tareas:
Utiliza servicios como AWS Step Functions para orquestar las diferentes etapas de tu flujo de trabajo, lo que facilita la coordinación y ejecución de tareas de manera eficiente.
