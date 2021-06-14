# Test_Spotahome
In this file we have the answer to the question 2 and the commands used to solve the first part of the exercise.

Spanish:
De cara a resolver la pregunta analítica, si me ciño a la información proporcionada por los csvs:
	En primer lugar, habría que pararse a pensar qué tipo de cine queremos tener, si uno de nicho en el cual mostremos películas de culto, alternativas o uno comercial. Si fuese el primero, a la hora de elaborar un ranking le daría más peso al rating de las votaciones que al número de votaciones de una película, un 70%-30%, sin embargo, si lo que buscamos es un cine comercial, haría una media de las votaciones ponderada con el número de votantes. Obviamente, la selección de una película alternativa no sólo se puede realizar en base a estos datos, pero sí después de un filtrado manual se le dará más peso al rating que al número de valoraciones.

Si tuviésemos más información disponible, como el número favoritos de cada película, adiciones a listados de los usuarios, número de visitas a la página de la película de imdb, rating de críticos de cine, etiquetas... podríamos realizar un análisis mucho más exhaustivo, metiendo estas variables en un modelo en el cual la salida serían las TOP x películas mejor valoradas dadas todas estas variables. Además, de cara a la selección de películas para el cine de nicho, podríamos utilizar las etiquetas de imdb para realizar un filtrado previo.

English:
In order to solve the analytical question, if I use only the information provided by the CSv's:

In the first place, we should think about what type of cinema we want to have, if a niche one in which we show cult/alternative films or just a commercial movie theater. If we have the first one, when we prepare the film ranking, We would give more weight to the rating of the votes than to the number of votes for a movie, 70%-30% for example, 
however, if what we are looking for is a commercial cinema, I would recommend to do the votes weighted average with the number of voters. Obviously, We cannot define a film as alternative using only data, but after a manual filtering we can do the analitical process mentioned.

If we have more information available, such as the times a film was added as favorite, additions to user lists films, number of visits to the imdb film page, film review ratings, tags... we could do a more exhaustive analysis, putting these variables in a model in which the output would be the TOP x best rated films given all these variables. In addition, for the movie selection of the niche cinema, we could use the imdb tags to carry out a previous filtering.


git clone https://github.com/Alex199177/Test_Spotahome

git checkout -b ReadCsv  --creamos una rama dev de trabajo

git add Test_Spotahome.ipynb

git commit -m "Read Csv"

git add Test_Spotahome.ipynb 

git commit -m "Calculo media por anio"


git add Test_Spotahome.ipynb


git commit -m "Grafica"


git push origin ReadCsv


git checkout -b add_comments


git add Test_spotahome.ipynb


git push origin add_comments



