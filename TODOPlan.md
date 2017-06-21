\# TODO PLAN

## In general:

## Data Description Chapter:
    * add counts users (barely 2m users in Mexico with homeantenna - 1947835 exacty,
                    argentina has 21m of users)
    * add antennas distributions compared to national level.
    * [DONE] Better heatmap descriptions.

## Machine Learning Chapter
    * fix logistic regression part:
    * add example of why it's important to do logReg regularization
    * add graphic example of a real decision tree (with nodes, etc.)
            for a minor problem in our dataset.
    * [Half Done] fix eze's recommendations on bias, variance, generalization and Vapnik-Cherkovenkis. (tags in .tex are named EZECORRECTION).
    * [DONE] fix eze's recommendations on logReg part (minor fixes in equations).
    * [DONE] separate evaluation, problem, results and validation from intro.

## Results Chapter
    Agregar cuadro de doble entrada comparando los resultados con distintas metricas y algunos graficos mas comparativos.

## Revision 17/02
    * Show an instance of overfitting the data with a decision Tree (with depth).
    * [DONE]Focalizarse solamente en los que actualmente no viven en la zona endemica y comparar resultados entre distintos metodos y configuracion de parametros. e.g. regularizar el problema vs. sin regularizar el problema y comparar.
    * Mostrar ejemplos concretos de _porque_ es importante lo que se cuenta teoricamente.
    * iterar con la gente del DM las correcciones. (Patu, Mathieu).
    * [DONE] Rerun algorithms but excluding the Top N (N \in {1,2,3}) predictors/regressors. Or with highly correlated features.
    * [DONE] show an instance of overfitting the data comparing the learning curve of training vs CV set (tried with different params of sklearn's      logReg classifier and still can't find a clear case of overfitting).

### Dar instancias de:
    * [DONE] logistic regression con o sin regularizacion, con o sin CV. y con todos/sin hiperparametros.
    * [DONE] achicar/filtrar el dataset para hacer el problema mas complejo.
        * X: solo users no_endemicos / Y: migrantes en cualquier direccion. / usuarios del DF
    * [DONE] Do SVD.
    * [DONE] Naive Bayes example
    * [DONE]  eliminar ciertas features correlacionadas con el target variable (solo EPIDEMIC col, pues luego tengo mucha correlacion en las columnas de hipotesis, )
    * [DONE] gradient boosting sobre los mejores features de random forest.

## Meeting 21/06
    * [DONE] meter TODOs tags with command to make them appear in red to have it visualized on the pdf.
    * Cap. machine learning: Arrancar con cuales son los problemas/hipotesis a testear. Definirlos antes de hablar de  Machine Learning y despues de data description.
    * borrar defincion formal de overfit.

## Meeting 12/06
    * Paginas en blanco, borrar, reordenar.
    * Bad \cref s pointing to sections other than equations. (ask pedrof)
    * [Done] Falta abstract en ingles & spanish. (no pasar una carilla). Se extiende una carilla pero por el titulo del asbtract que ocupa media pagina. Habria que arreglar.
    * [Done] Titulo en ingles & spanish.
    * Cap 1. : Tiene que ser algo introductorio y que sea un extended abstract. Intro de la tesis. Que se hace.
        Porque sirve. Intro de chagas, el marco teorico, marco del proyecto, hablar CDRs y diseaseas (epidemiology), Machine Learning. Intro to _rest of thesis_: "En el Cap2 hacemos esto, en el 3 tal otra,
        en el 4".
        - Menos copy-pasteo y mas integrado con la tesis actual.
    * Chagas/epidemiologia en su propio capitulo y con comentarios sobre lo que hicieron otros. (trabajos recientes).
        - agregar referencia al paper de ASONAM donde presentamos parte de los resultados. (deMonasterio2016)

    * [Half Done] Parte de Machine Learning grande vs. el resto. Refactor para integrar evaluacion c/ tecnicas en estos siguientes capitulos:
        - Preambulo como supervised classification problems (ver de mechar) + logreg
        - bias variance, regularization.
        - Tree techniques.

    La idea es ir mechando tecnicas con problemas para ilustrar los puntos teoricos que se hacen. *No* hacer todos los problemas para todas las tecnicas nomas. Sino ir contando algo a lo que se quiere llegar.
    * Conclusiones: results summaries, para ir comparando las distintas tecnicas.
        - Mostrar problema 1,2,3,4 para c/clasificador. f1, roc_uac. precision, recall. tiempos de corrida.
    * Pedidos de entrega: links de netmob dengue.

# Maybe TODOs:
    ## Problem / Data Description Chapter
        - on how to present features: http://people.csail.mit.edu/romer/papers/TISTRespPredAds.pdf

    ## Machine Learning Chapter
        - section Technical Observations (python, jupyter, sklearn, pandas,
                                        sframes, graphlab, spark mllib,
                                        theano, tensor flow, xgboost)
