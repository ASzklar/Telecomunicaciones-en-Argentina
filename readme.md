Segundo proyecto individual de la etapa labs
Cohorte 01 de Soy Henry de la carrera Data Science en modalidad part time

A partir de la data sobre telecomunicaciones en Argentina obtenida en https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/ se realiza un análisis exploratorio. A pesar de que el principal objetivo de este proyecto era la parte de EDA, KPIs y dashboard fue necesario realizar previamente algunas transformaciones ya que la data no estaba del todo limpia.

Dentro de la carpeta principal del repositorio pueden encontrar los 16 archivos .csv originales en crudo. Y dentro de la carpeta Data limpia se encuentran los mismos pero luego de las transformaciones, que son los que utilicé para el EDA.

En el archivo ETL.ipynb se trabajaron las transformaciones y en EDA.ipynb el análisis exploratorio de los datos.

En base a ese EDA los KPIs elegidos son:
- Proporción de Fibra óptica respecto del total de conexiones
- Promedio nacional de acceso a internet por cada 100 hogares
- Velocidad media de bajada
- Promedio de ganancia trimestral en dólares

Y la conclusión es que si bien en Argentina hay factores como la inflación y cambios drásticos de políticas que influyen fuertemente en el sector de las telecomunicaciones mejorar permanentemente los servicios brindados a la población es fundamental para mantener y/o aumentar la ganancia en dólares. Aún cuando esta misma pueda sufrir altibajos temporales, a largo plazo la tendencia es en alza.

Cuando hablo de mejorar los servicios me refiero a ofrecer velocidades de conexión a internet lo más altas posibles e ir poniendo a disposición de los usuarios las mejores tecnologías. En este caso sin duda la fibra óptica viene cumpliendo ese papel. Dejo un interesante link al respecto de sus beneficios: https://www.rankia.com/blog/mejores-ofertas-internet/1994689-diferencias-adsl-fibra-optica

Fuente que utilicé para convertir pesos a dólares: http://estudiodelamo.com/cotizacion-historica-dolar-peso-argentina/

![Alt text](image.png)
![Alt text](image-1.png)
![Alt text](image-2.png)
![Alt text](image-3.png)

Mi nombre es Adrian Szklar, muchas gracias por haber llegado hasta acá y para todo tipo de sugerencias, observaciones, correcciones, etc dejo mis mails:
szklaradrian@gmail.com
szklaradriandatos@gmail.com