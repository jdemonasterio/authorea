# TODO PLAN

## In general:

## Data Description Chapter:
    * add counts users (barely 2m users in Mexico with homeantenna - 1947835 exacty, 
                    argentina has 21m of users)
    * add antennas distributions compared to national level.
    * [DONE] Better heatmap descriptions.

## Machine Learning Chapter 
    * fix logistic regression part:
    * add
    * add example of why it's important to do logReg regularization
    * add graphic example of a real decision tree (with nodes, etc.) 
            for a minor problem in our dataset.
    * [DONE] fix eze's recommendations on logReg part (minor fixes in equations).
    * [DONE] separate evaluation, problem, results and validation from intro.

## Results Chapter
    Ampliar de los papers ya agregar mas graficos comparativos

## Revision 17/02
    * Show an instance of overfitting the data with a decision Tree (with depth).
    * Focalizarse solamente en los que actualmente no viven en la zona endemica y comparar resultados entre distintos metodos y configuracion de parametros. e.g. regularizar el problema vs. sin regularizar el problema y comparar.
    * Mostrar ejemplos concretos de _porque_ es importante lo que se cuenta teoricamente.
    * Desbalance entre la profunidad teorica y la superficialidad de la aplicacion del problema.
    * iterar con la gente del DM las correcciones. (Patu, Mathieu).
    * [DONE] Rerun algorithms but excluding the Top N (N \in {1,2,3}) predictors/regressors. Or with highly correlated features.
    * [DONE] show an instance of overfitting the data comparing the learning curve of training vs CV set (tried with different params of sklearn's logReg classifier and still can't find a clear case of overfitting). 

### Dar instancias de:
    * logistic regression con o sin regularizacion, con o sin CV. y con todos/sin hiperparametros.
    * achicar/filtrar el dataset para hacer el problema mas complejo. (in working) 
        * X: solo users no_endemicos / Y: migrantes en cualquier direccion. / usuarios del DF
    * Do SVD.
    * [DONE] Naive Bayes example
    * [DONE]  eliminar ciertas features correlacionadas con el target variable (solo EPIDEMIC col, pues luego tengo mucha correlacion en las columnas de hipotesis, )
    * [DONE] gradient boosting sobre los mejores features de random forest.

# Maybe TODOs:
    ## Problem / Data Description Chapter
        - ampliar data description and visualizations
        - on how to present features: http://people.csail.mit.edu/romer/papers/TISTRespPredAds.pdf 

    ## Machine Learning Chapter
        - section Technical Observations (python, jupyter, sklearn, pandas, 
                                        sframes, graphlab, spark mllib, 
                                        theano, tensor flow, xgboost)

