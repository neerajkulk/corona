# Colorado Covid-19 projections using realtime update of R<sub>0</sub>

The main file here is `realtime_r0.ipynb`. In this notebook, we explore fitting a epidemiological model to predict the rate of spread of Covid-19 in Colorado. The rate of spread of Covid-19 is characterized by the reproductive rate  R<sub>0</sub>. Here, we try to estimate  R<sub>0</sub> using the realtime  R<sub>0</sub> model from  [Bettencourt, Ribeiro 2008](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0002185). This is Bayesian method that not only provides an estimate of R<sub>0</sub> , but also provides us with a probability distribution over likley values of  R<sub>0</sub>. 

Carefully analyzing the uncertainty in predictions if R<sub>0</sub> is essential to making accurate future predictions about the rate of spread of Covid-19. Please see  `realtime_r0.ipynb` for more details on the model. Feel free to make a PR if have ideas or suggestions to improve the model.


## Estimation of posteriors
![Estimation of Posteriors](./post.png)


## Projections for future deaths
![Future death predictions](./death_pred.png)


