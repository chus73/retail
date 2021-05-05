# Estadística descriptiva de datos de retail en R

El mundo moderno de principios de este siglo XXI ha experimentado un aumento del comercio internacional. Más aun, en estos momentos en los que la pandemía del Covid asola nuestro mundo, el **e-commerce** ha experimentado un aumento considerable en su crecimiento. Este cambio evidencia una tendencia en la sociedad en cuanto a hábitos de consumo se refiere. Según la consultora eMarketer, especializada en comercio electrónico, en un estudio realizado antes de la pandemia, ya estimaba un crecimiento en las ventas de retail online para el año 2020 del 12, 5%, con una proyección para el 2023 de los 40.120 millones de dólares a nivel mundial

(fuente: Expansión economía digital - <https://www.expansion.com/economia-digital/2020/08/20/5f3d852f468aeb11628b45c3.html>).

El crecimiento en las ventas realizadas mediante portales web, exige la recogida de información y el tratamiento de **grandes volúmenes de datos**, a la par de una exigencia en los tiempos de respuesta, que permitan adaptarse rápidamente a los cambios del sector. Es por ello, que se hace necesario un procesamiento de datos los más industrializado posible.

El objetivo de nuestro estudio se centrará en procesar un dataset que cuente con un volumen considerable de de transacciones, demostrando que es posible su procesamiento en corto plazo, y respondiendo a preguntas analíticas que permitan ayudar a determinar las estrategias de negocio.

## Descripción del dataset

Para la realización de nuestro estudio, hemos contado con un dataset que contiene transacciones de venta on-line de una empresa con base en UK del sector retail, ocurridas entre diciembre del 2019 y diciembre del 2011. El dataset, lo componen más de un millón de registros con 8 atributos que describirán la temporalidad de la transacción, el artículo, el usuario que ha realizado la compra, así como su país de procedencia y la cantidad y el precio unitario de la venta.

El dataset trabajado pertenece a UCI - Machine Learning Repository, y fue donado en Septiembre del 2019. En el siguiente link puede encontrarse la información referente a la fuente de datos, así como el enlace para su descarga.

<https://archive.ics.uci.edu/ml/datasets/Online+Retail+II>

Debido al componente multinacional del dataset, que contiene transacciones de más de 40 países, se enriquecerá con datos aportados por el Banco Mundial. En concreto, buscaremos el Producto Interior Bruto de los países en los años de observación, con el fin de determinar **si un mayor o menos PIB** influye en el volumen de artículos comprados.

La elección del dataset se encuentra alienada con el problema de negocio planteado en la introducción. Permite la aplicación de algoritmos de clusterización, tanto supervisados, como no supervisados, así como de reglas de asociación, con el fin de poder responder a las preguntas que negocio determine.
