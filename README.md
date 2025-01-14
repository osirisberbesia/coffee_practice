# Práctica para prueba técnica

Se trabajarán con los datos de: 

* [Repositorio de Kaggle](https://www.kaggle.com/datasets/volpatto/coffee-quality-database-from-cqi)

## Encabezado de datos:

* Species: Categoría general de la especie del café
* Owner: Propietario del café o la finca
* Country.of.Origin: País de origen del café
* Farm.Name: Nombre de la granja/finca
* Lot.Number: Número de lote del café 
* Mill: Molino/procesador utilizado
* ICO.Number: número asignado por la Organización Internacional del Café (International Coffee Organization, ICO)
* Company: Nombre de la compañía asociada con el café
* Altitude: altura sobre el nivel del mar a la que se cultiva el café
* Region: Región específica de cultivo del café
* Producer: Productor o cultivador del café
* Number.of.Bags: Número de bolsas de café
* Bag.Weight: Peso de la bolsa de café, en kilogramos
* In.Country.Partner: Socio en el país de origen
* Harvest.Year: Año de cosecha del café
* Grading.Date: Fecha de clasificación del café
* Owner.1: Identificador único del propietario
* Variety: Variedad específica de la especie de café
* Processing.Method: Método de procesamiento del café (ej. lavado, natural)
* Aroma: Descripción del aroma del café
* Flavor: Descripción del sabor del café
* Aftertaste: Sabor residual del café después de ser ingerido
* Acidity: Nivel de acidez del café
* Body: Sensación del cuerpo del café en la boca
* Balance: Equilibrio de los diferentes sabores en el café
* Uniformity: Uniformidad del café en términos de sabor y calidad
* Clean.Cup: Limpieza del sabor del café
* Sweetness: Nivel de dulzura del café
* Cupper.Points: Puntaje asignado por el catador
* Total.Cup.Points: Puntaje total de la cata del café
* Moisture: Contenido de humedad del café
* Category.One.Defects: Defectos de primera categoría encontrados en el café
* Quakers: Granos de café que no se han desarrollado adecuadamente
* Color: Color del grano de café
* Category.Two.Defects: Defectos de segunda categoría encontrados en el café
* Expiration: Fecha de caducidad del café
* Certification.Body: Organismo certificador del café
* Certification.Address: Dirección del organismo certificador
* Certification.Contact: Contacto del organismo certificador
* unit_of_measurement: Unidad de medida utilizada para las altitudes
* altitude_low_meters: Altitud mínima de cultivo, en metros
* altitude_high_meters: Altitud máxima de cultivo, en metros
* altitude_mean_meters: Altitud media de cultivo, en metros

## Documento Google Sheets

[Enlace](https://docs.google.com/spreadsheets/d/115NV9xmySNbfob0UTHD5P6ybP531KJRwMP8MhhMR6I8/edit?usp=sharing)

## Verdades establecidas

* Humedad aceptada para considerar apto el café: de 8% a 12%
* Total.Cup.Points es la sumatoria de los valores en los campos: Aroma, Flavor, Aftertaste, Acidity, Body, Balance, Uniformity, Clean.Cup, Sweetness, Cupper.Points
* Partiendo de los métodos de procesamiento de café en el data set, se establece como uso común según tipo de procesamiento lo siguiente:
  * Natural / Dry: Fruity & Robust Flavor 
  * Pulped Natural / Honey: Balanced Flavor and Acidity 
  * Semi-washed / Semi-pulped: Low Acidity 
  * Washed / Wet: Clean Flavor 
  * Vacío: Other
  * Other: Other 
* Orden calificativo del café empezando por el mejor calificado:
  * Blue-Green (este es el color más deseado y se asocia con granos de alta calidad y frescura)
  * Bluish-Green
   * Green (este es el color más básico y puede indicar granos de menor calidad)
 * Category.One.Defects: se establece que se trabaja con una muestra de 100gr
 * Category.Two.Defects: se establece que se trabaja con una muestra de 300gr

## Otros Enlaces

[Specialty Coffee Association (SCA)](https://sca.coffee/value-assessment)

[Total Affective Score](https://sca.coffee/cuppingscore)

[GRAVIMET SM
 Tecnología para medir la humedad 
del café en el secado en silos](https://www.cenicafe.org/es/publications/avt0433.pdf)

[La humedad controlada del grano preserva la calidad del café](https://caldas.federaciondecafeteros.org/app/uploads/sites/11/2020/07/AVT0352-La-h%C3%BAmedad-controlada-del-grano-preserva-la-calidad-del-caf%C3%A9..pdf)

[SCAA Protocols | Grading Green Coffee Published by the Specialty Coffee Association of America](https://www.academia.edu/11404285/SCAA_Protocols_Grading_Green_Coffee_Published_by_the_Specialty_Coffee_Association_of_America_SCAA)