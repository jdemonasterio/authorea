# TODO PLAN

## Meeting 18/10
    * Do great review and read all. 
    * Fix typos and grammar.
    * Clean all TODOs.


## Meeting 04/10
    * [DONE] Ejemplo: dejar en terminos de los problemas migratorios: "no pudimos predecir las migraciones de este estilo". Destraducir de problema 1 a algo de las migraciones. Darle el hilo de la historia que estoy contando.
    * [DONE] Separar en Random Forests y Decision Tree vs. Gradient Boosting y Naive Bayes.
    * [DONE] El predictive error bounds de random forests pasar la demo a una apendice. Enunciarlo nomas. 

## Meeting 27/09
    * Fix master table presentation or chunk in two small tables.

## Meeting 20/09
    * [DONE] In table of contents, notify start of appendix somewehere. Correct the way it is presented.
    * [DONE] Separar el 6 en dos, tal vez uno de resultados mas concretos y otro de conclusion. Uno de resultados en resultados
        numericos y key insights de lo que vimos con los datos, la compilacion de todos los resultados en terminos de numeros y metodos, etc. Los problmeas que tienen, los metodos usados.
        En conclusiones mas a nivel de cosas de que aprendiste, eleccion de metodos, que aprendi, que sirven los CDRs para esto, que limitaciones tienen en prediccion y otras cuestiones mas alto nivel.

## Meeting 13/09
    * [DONE] En general, agrandar figures y dejarlas en su propio environment.
    * [DONE] Agregar runtime a la tabla. Por ahora es estetico.
    * [DONE] Fix roman numbers problem.

## Meeting 23/08
    * [DONE] Recortar teoria y pasar a un apendice. Todos los detours respecto del problema nuestro y que no se utilicen (demasiado desarrollo) que pasen al apendice y no se vayan tocando tambien
    * [DONE] Ninguna figura de afuera (o contadas excepciones). Que sean con datos propios directamente.
    * Meter una introduccion de c/capitulo para ordenar bien el hilo de la tesis.
    * [DONE] Documentar las cosas que vas probando y lo que te va pasando.
    * [DONE] Revisar notacion de los problemas y fixear.
    * [DONE] Cap. introduccion: alguien que solo lee el cap. 1, se queda con una buena idea de lo que se hizo en la tesis?
    * [DONE] Revisar el \cref{} con respecto a figures que aparecen con el tag de Secciones y con ecuaciones que tengan su name que diga "Equation". Fijarse de pasar todos los `$$` a un equation environment estilo `\begin{equation}`.
    * [DONE] Story telling un poco.


## Meeting 16/08
    * [DONE] Cambiar las figuras 4.4.3 y 4.4.4 que usan data foranea y reemplazar alguna de ellas con una instancia de un problema nuestro.
    * [DONE] Revisar todas las figuras y especificar de que problemas vienen estos resultados.
    * [DONE] Sacarle jugo a los resultados. Presentar algo mas en los numeros concretos y como esos son los resultados. Que aprendi del dataset, que hay para contar del dataset.
    * [DONE] Bajar a tierra los resultados de problemas 1 a 4 en los clasificadores con como esto se relaciona con los mapas.

## Meeting 12/07
    * [DONE] cambiar orden de idiomas en el abstract y en el titulo, primero ingles luego espanyol.

## Meeting 05/07
    * [DONE] captions con texto mas cargado. Para mirar el caption y entender de que se trata.
    * [DONE] agregar con que problema fitie la grafica. Y agregar los detalles de "que" otros parametros se estan usando como fijos.
    * [DONE] meter 2 imagenes de ejemplos de arboles con 2 corridas distintas a ver como van variando y hablar acerca de lo que se ve en los resultados.
    * Cap. 6 Results & Conclusion responder estas preguntas:
        - hacer explicita la respuesta a esta pregunta: ?Que tanto se puede predecir long term migrations usando datos de CDRs?
        - cuales fueron las mejores tecnicas? Que tuvieron a favor y en contra?
        - [DONE] Enganchar los resultados con lo que se vio en los mapas. Hablar de como los features del algoritmo estan relacionados con el armado del mapa y como se "valida" la hipotesis.
        - Agregar cuadro de doble entrada comparando los resultados con distintas metricas y algunos graficos mas comparativos. Mostrar problema 1,2,3,4 para c/clasificador. f1, roc_uac. precision, recall. tiempos de corrida.
        - Repasar los 4 problemas y resumir los mejores resultados de c/ algoritmo.

## Meeting 28/06
    * [DONE] Juntar Cap. 6 y 7.
    * [DONE] Agregar un poco de redundancia a las definiciones de los problemas.
    * [DONE] Decir que los problemas los vamos a retomar en el cap 4 y 5 bla bla para resolver ciertas cosas.
    * [DONE] Tener 5 Problems en vez de problems con items.
    * [DONE] Figura 4.2.1 agregar la grafica de CV de decision trees y referenciar al futuro.
    * [DONE] Meter mas figures overall.
    * [DONE] Add experiments/runs for Naive Bayes Classifier. Show how fast the implementation is and relate to how "non-parametric" this is i.e. easy to set up and use as a benchmarking for better, more complex models.

## Meeting 21/06
    * [DONE] meter TODOs tags with command to make them appear in red to have it visualized on the pdf.
    * [DONE] Cap. machine learning: Arrancar con cuales son los problemas/hipotesis a testear. Definirlos antes de hablar de  Machine Learning y despues de data description.
    * [DONE] borrar defincion formal de overfit.

## Meeting 12/06
    * [DONE] Paginas en blanco, borrar, reordenar.
    * [DONE] Bad \cref s pointing to sections other than equations. (ask pedrof) (Problem was with correctly running biber and bitex.)
    * [Done] Falta abstract en ingles & spanish. (no pasar una carilla). Se extiende una carilla pero por el titulo del asbtract que ocupa media pagina. Habria que arreglar.
    * [Done] Titulo en ingles & spanish.

    * Cap 1. : Tiene que ser algo introductorio y que sea un extended abstract. Intro de la tesis. Que se hace.
        Porque sirve. Intro de chagas, el marco teorico, marco del proyecto, hablar CDRs y diseaseas (epidemiology), Machine Learning. Intro to _rest of thesis_: "En el Cap2 hacemos esto, en el 3 tal otra,
        en el 4".
        - ejemplo de intro: https://www.iro.umontreal.ca/~lecuyer/myftp/papers/pagerank.pdf
        - Menos copy-pasteo y mas integrado con la tesis actual.
        - dar resumen de lo que serian los "out of scopes" en la intro.

    * Chagas/epidemiologia en su propio capitulo (o en la intro ) y con comentarios sobre lo que hicieron otros. (trabajos recientes).
        - agregar referencia al paper de ASONAM donde presentamos parte de los resultados. (deMonasterio2016)

    * [Done] Parte de Machine Learning grande vs. el resto. Refactor para integrar evaluacion c/ tecnicas en estos siguientes capitulos:
        - [DONE] Preambulo como supervised classification problems (ver de mechar) + logreg
        - [DONE] bias variance, regularization.
        - [DONE] Tree techniques.
        - [DONE] La idea es ir mechando tecnicas con problemas para ilustrar los puntos teoricos que se hacen. *No* hacer todos los problemas para todas las tecnicas nomas. Sino ir contando algo a lo que se quiere llegar.

## Revision 17/02
    * [DONE] Show an instance of overfitting the data with a decision Tree (with depth).
    * [DONE]Focalizarse solamente en los que actualmente no viven en la zona endemica y comparar resultados entre distintos metodos y configuracion de parametros. e.g. regularizar el problema vs. sin regularizar el problema y comparar.
    * iterar con la gente del DM las correcciones. (Patu, Mathieu).
    * [DONE] Rerun algorithms but excluding the Top N (N \in {1,2,3}) predictors/regressors. Or with highly correlated features.
    * [DONE] show an instance of overfitting the data comparing the learning curve of training vs CV set (tried with different params of sklearn's      logReg classifier and still can't find a clear case of overfitting).

## Data Description Chapter:
    * [DONE] add counts users (barely 2m users in Mexico with homeantenna - 1947835 exacty,
                    argentina has 21m of users)
    * [DONE] add antennas distributions compared to national level.
    * [DONE] Better heatmap descriptions.

## Machine Learning Chapter
    * [DONE] fix logistic regression part:
    * [DONE] add example of why it's important to do logReg regularization
    * [DONE] add graphic example of a real decision tree (with nodes, etc.)
            for a minor problem in our dataset.
    * [DONE] fix eze's recommendations on bias, variance, generalization and Vapnik-Cherkovenkis. (tags in .tex are named EZECORRECTION).
    * [DONE] fix eze's recommendations on logReg part (minor fixes in equations).
    * [DONE] separate evaluation, problem, results and validation from intro.


### Dar instancias de:
    * [DONE] logistic regression con o sin regularizacion, con o sin CV. y con todos/sin hiperparametros.
    * [DONE] achicar/filtrar el dataset para hacer el problema mas complejo.
        * X: solo users no_endemicos / Y: migrantes en cualquier direccion. / usuarios del DF
    * [WILL NOT DO - too many techniques] Do SVD.
    * [DONE] Naive Bayes example
    * [DONE]  eliminar ciertas features correlacionadas con el target variable (solo EPIDEMIC col, pues luego tengo mucha correlacion en las columnas de hipotesis, )
    * [DONE] gradient boosting sobre los mejores features de random forest.


# Maybe TODOs:
    ## Problem / Data Description Chapter
        - [DONE] On how to present features: http://people.csail.mit.edu/romer/papers/TISTRespPredAds.pdf

    ## Machine Learning Chapter
        - [DONE] section Technical Observations (python, jupyter, sklearn, pandas, sframes, graphlab, spark mllib, theano, tensor flow, xgboost)

## In general:
    * [DONE] Talk about general low F1 scores with very bad precision in algorithms and acceptable recalls.
    * [DONE] Figures appearing in sub/sections different from where they are spawned $\rightarrow $ just use `\begin{figure}[H]`.
    * Minor spell check with computer spell checkers in sublime or `sudo apt-get install aspell-en`.
    * [DONE] Check bad `\cref` references for appendix subsections.
    * Better word wrapping for presented tables' header row. Words appear somewhat cluttered.
    * Iterar con la gente del DM las correcciones. (Patu, Mathieu, Lean).
