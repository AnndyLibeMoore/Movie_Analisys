Movie Analysis

Problema de negocio

Una plataforma de streaming para el hogar con presencia en todo el mundo, necesita impulsar su rendimiento utilizando datos de tendencias en el sector de manera estratégica. Como científicas de datos especializadas en la industria del entretenimiento se nos ha convocado
para analizar estos datos y ofrecer insights que puedan guíar próximas decisiones y aclaren las siguientes dudas:

1. ¿Cuál es la evolución del rating por tipo de contenido?
2. ¿Cuál es el rating promedio por género?
3. ¿Cuáles son los géneros que proporcionan mayor ROI?
4. ¿Cuáles son los países con mayor producción?
5. Top 5 series / Movies con mayor rating 
6. Conclusiones y recomendaciones

En este análisis nos enfocaremos en producciones de películas y series de televisión entre los años 1990 - 2023, este filtro se realizó con el objetivo de obtener información valiosa que podamos aplicar a esta nueva generación
ya que la tecnología y la facilidad de accesibilidad a los nuevos contenidos ha evolucionado este mundo del entretenimiento.

Analizaremos a continuación la duración de Series y películas:
![1 boxplot runtime con outliers](https://github.com/AnndyLibeMoore/Movie_Analisys/assets/111656138/20cb140f-c58a-42d8-9e90-1e96651f61dc)
![2 runtime sin outliers](https://github.com/AnndyLibeMoore/Movie_Analisys/assets/111656138/59cdb1af-0cc9-45b4-a73b-1561770a452a)

En las gráficas anteriores podemos ver la cantidad de minutos que dura la producción, como vemos en la primer gráfica vemos duraciones de más de 50000 minutos, pero para hacer un análisis adecuado filtramos y graficamos de nuevo obteniendo un promedio, vemos entonces en la segunda gráfica que la duración promedio de las producciones que nos interesan está entre 80 - 90 minutos.

![3histograma runtime](https://github.com/AnndyLibeMoore/Movie_Analisys/assets/111656138/8875938b-6cf2-4e3a-8c11-57fd89e67e51)

Esta gráfica nos muestra más detalladamente la cantidad de minutos de las producciones que seguiremos analizando.


![4histograma startyear](https://github.com/AnndyLibeMoore/Movie_Analisys/assets/111656138/abbe3ec0-abd4-41d8-aa32-98189713c8c0)
Aquí vemos un aumento en la cantidad de producciones, en el 2000 ya se producían más de 5.000 al año, en el 2012 ya más de 20.000 y así sucesivamente llegando a casi 25.000 por año.

![5 isadult](https://github.com/AnndyLibeMoore/Movie_Analisys/assets/111656138/de1b2efe-2ba2-4ac1-b0f2-d533603a6d11)

Aquí vemos que las producciones enfocadas al público solo adulto representan poco más del 1%.

![8histograma averrating](https://github.com/AnndyLibeMoore/Movie_Analisys/assets/111656138/e2f88712-4370-4d2f-9487-1470824d763f)
![7numvotes sin outliers](https://github.com/AnndyLibeMoore/Movie_Analisys/assets/111656138/e31d2e1a-f210-406e-b24f-e6357792c652)

Aquí vemos que la mayoría de producciones obtienen una puntuación promedio de entre 6-8 aunque la cantidad de votaciones es considerable y varía mucho.


![10 budget sin outliers](https://github.com/AnndyLibeMoore/Movie_Analisys/assets/111656138/db7d31b6-02d9-4c49-91c2-e625bf671454)
![12 rebenue sin outlilers](https://github.com/AnndyLibeMoore/Movie_Analisys/assets/111656138/13b7fa86-9723-4d24-a7cb-8fda977cad33)

Aquí vemos la distribución del revenue, recordemos que esta es una métrica absoluta de los ingresos que ha generado la producción y el promedio está en poco más de 10M, en la siguiente gráfica vemos la distribución de Budget que hace referencia al presupuesto asignado para tal producción y vemos que la mayoría de valores están entre 10M y 20M.

Con los datos anteriores podemos hacer el cálculo del ROI (Retorno sobre la Inversión) el cual se refiere a la cantidad de ingresos generados por cada unidad monetaria gastada en el presupuesto de producción. 
Para entender la interpretación del ROI tomemos como ejemplo un ROI de 4.16 esto hace referencia a que por cada unidad monetaria gastada en el presupuesto de producción, la película generó 4.16 unidades monetarias de ingreso adicional. Esto significa que la película generó 416% del costo de producción en ingresos adicionales.


![13roi](https://github.com/AnndyLibeMoore/Movie_Analisys/assets/111656138/3057a5b7-acb2-41d7-b826-00673bd4c158)
Aquí vemos que el ROI promedio es de menos del 100%.


INSIGHTS

1.¿Cuál es la evolución del rating por tipo de contenido?
![pregunta1](https://github.com/AnndyLibeMoore/Movie_Analisys/assets/111656138/d66c0d3d-7696-4bf7-b83c-6050ecde8c90)
Aquí vemos que aunque el público consume más películas que series de televisión  el rating de las series es muy superior al de las películas. En el 2004 el rating de series tuvo un bajón considerable y desde el 2020 el rating de ambos tipos de contenidos se ha disparado y sigue en aumento, esto puede deberse a la pandemia del 2020 que permitió quizás que las personas se refugiaran en este tipo de entretenimiento.


2.¿Cuál es el rating promedio por género?
![pregunta2](https://github.com/AnndyLibeMoore/Movie_Analisys/assets/111656138/893d854e-a196-40d7-846c-9ff7797e1aed)
Aquí vemos que los géneros con mayor cantidad de contenido son Acción, adultos y aventura, mientras que los de mayor rating son biografía, documental, short e historia.
por tanto no por mayor cantidad de producción significa un alto rating, por ejemplo la categoría Horror tiene el rating más bajo que las categorías Music y War aunque de 
horror hay más cantidad de contenido.


3.¿Cuáles son los géneros que proporcionan mayor ROI?
![pregunta3](https://github.com/AnndyLibeMoore/Movie_Analisys/assets/111656138/dd0b2cd9-bf6b-4bfa-889d-e85594b6bf0b)
Podemos  notar que los géneros que mayor ROI proporcionan son Ciencia ficción, fantasía y Aventura, esto se le acredita a las historias de larga duración que logran enganchar a la audiencia como se ha visto en los últimos años con los Universos de Marvel y Star Wars así como en series que siguen ganando audiencia como lo son Stranger Things y juego de Tronos que han batido récords de audiencia y ganancia.


4.¿Cuáles son los países con mayor producción?
![pregunta4](https://github.com/AnndyLibeMoore/Movie_Analisys/assets/111656138/b4b90872-5acb-4e81-ac53-3c0fe3e7e855)
Tenemos aquí un top 13 de los países de mayor producción frente al ROI que se genera por país, como vemos el país que mayor cantidad de producciones genera es USA con un sin embargo el país que mayor ROI genera es India seguido por Japón y la diferencia de producciones ante USA es bastante considerable.

En la siguiente gráfica podemos notar que USA tiene un total producido de 6334 con un ROI  solo del 1.14, sin embargo Japón tiene un total producido solo de 228 con un ROI de 1.08 por tanto a nivel de producción ganancia japón tiene el mejor porcentaje esto se le atribuye a la gran acogida que ha tenido la industria de animaciones como el Anime.
![Captura de pantalla 2024-06-30 212401](https://github.com/AnndyLibeMoore/Movie_Analisys/assets/111656138/c30a5618-4a28-4a39-9f79-7a18b06794aa)


5.Top 5 series / Movies con mayor rating
![pregunta5](https://github.com/AnndyLibeMoore/Movie_Analisys/assets/111656138/532b66a1-8c27-4028-9de0-ae8d90554270)
Aquí vemos que las 5 series y películas con mayor rating son podría decirse producciones clásicas, no son muy actuales pero siguen atrayendo público y su rating sigue en aumento.  



6. Conclusiones y recomendaciones
En base al análisis realizado, recomendamos a nuestro cliente que, para que la plataforma de streaming continúe obteniendo buenos resultados y aumentando sus suscripciones, tenga en cuenta los siguientes puntos:
Actualizar constantemente su catálogo: Mantener el contenido fresco y variado es crucial para retener y atraer a nuevos suscriptores.

No olvidar las producciones clásicas: Las producciones clásicas siguen atrayendo a una gran parte del público. Estar al tanto de las tendencias en redes sociales ayudará a identificar qué clásicos siguen siendo populares.

Invertir en producciones propias: Muchas plataformas de streaming invierten en sus propias producciones para fidelizar a los suscriptores. Las categorías de mayor rating y ROI son ciencia ficción, fantasía y aventura, por lo que invertir en este tipo de contenido sería beneficioso.

Fomentar el contenido corto: El rating de cortometrajes y contenido breve ha aumentado considerablemente en los últimos años. Invertir en este tipo de contenido o aumentar su presencia en la plataforma puede atraer a una audiencia más amplia.

Invertir en proyectos de larga duración: Proyectos como el Universo de Marvel, Star Wars o series como Stranger Things, que cuentan historias extensas, ayudan a mantener a los suscriptores comprometidos y atraen a nuevos usuarios.

Considerar las producciones por país: Es importante recordar qué producciones de qué países generan más ROI. Japón, por ejemplo, aunque produce menos contenido, genera un alto ROI. Aumentar el catálogo de producciones de países como Japón e India podría proporcionar más ganancias y atraer a más suscriptores.

Implementando estas recomendaciones, la plataforma de streaming puede mejorar su rendimiento y continuar creciendo en el competitivo mercado del entretenimiento en línea.














