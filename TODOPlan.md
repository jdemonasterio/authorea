# TODO PLAN

## In general:

## Data Description Chapter:
    * counts users (barely 2m users in Mexico with homeantenna - 1947835 exacty, 
                    argentina has 21m of users)
    * antennas distributions compared to national level.
    *

## Machine Learning Chapter     
    * fix logistic regression part:
    * separate evaluation, problem, results and validation from intro.

## Results Chapter
    Ampliar de los papers ya agregar mas graficos comparativos

## Revision 17/02
    * show an instance of overfitting the data comparing the learning curve of training vs CV set (tried with different params
        of sklearn's logReg classifier and still can't find a clear case of overfitting)
    * completar la experimentacion con la parte de prediccion.
    * Rerun algorithms but excluding the Top N (N \in {1,2,3}) predictors/regressors. Or with highly correlated features.
    * Focalizarse solamente en los que actualmente no viven en la zona endemica y comparar resultados entre distintos 
        metodos y configuracion de parametros. e.g. regularizar el problema vs. sin regularizar el problema y comparar.
    * Mostrar ejemplos concretos de _porque_ es importante lo que se cuenta teoricamente.
    * Desbalance entre la profunidad teorica y la superficialidad de la aplicacion del problema.
    * iterar con la gente del DM las correcciones. (Patu, Mathieu).


    ### Dar instancias de:
        * eliminar ciertas features correlacionadas con el target variable (solo EPIDEMIC col, pues luego tengo mucha 
            correlacion en las columnas de hipotesis, las de llamados vulnerables desde/hacia 
            la zona de riesgo) (in working) . 
        * logistic regression con o sin regularizacion, con o sin CV. y con todos/sin hiperparametros.
        * un ejemplo de naive bayes. (in working)
        * achicar/filtrar el dataset para hacer el problema mas complejo. 
        * Need to first better filter out data in certain cases and log that filter/type of target variable.
        (In working)
        * Do SVD.

# Maybe TODOs:

    ## Problem / Data Description Chapter
        - ampliar data description and visualizations
        - buena descripcion de los heatmaps
        - on how to present features: http://people.csail.mit.edu/romer/papers/TISTRespPredAds.pdf 

    ## Machine Learning Chapter
        - section Technical Observations (python, jupyter, sklearn, pandas, 
                                        sframes, graphlab, spark mllib, 
                                        theano, tensor flow, xgboost)

