# Tractament dataset Titanic

M2.951 - Tipologia i cicle de vida de les dades - Pràctica 2 - Tractament dataset Titanic

## Membres de l'equip

La pràctica ha estat realitzada per **Daniel López**. 

## Fitxers de codi font

Podem trobar els fitxers de codi font a la carpeta **src**:

* **Titanic.rmd**: Fitxer en R que conté tot el codi de la pràctica.

## Documentació

Les respostes a la pràctica, així com la documentació generada la podem trobar a la carpeta **pdf**:

* **Titanic.pdf**: document pdf amb les respostes a la pràctica.
* **Titanic.html**: document html amb les respostes a la pràctica.

## Dataset

Els datasets utilitzats i generats per a la pràctica es troben a la carpeta **csv**:
* **train.csv**: dades corresponents a la mostra de training dels passatgers del Titanic.  
* **test.csv**: dades corresponents a la mostra de test dels passatgers del Titanic.  
* **train_clean.csv**: dades corresponents a la mostra de training processada dels passatgers del Titanic.  
* **test_clean.csv**: dades corresponents a la mostra de test processada training dels passatgers del Titanic.  
* **gender_submission.csv**: dades corresponents a la mostra de training dels passatgers del Titanic.  
* **test.csv**: dades corresponents a la mostra de test training dels passatgers del Titanic que indica si el passatger va sobreviure o no.  
* **test_lr_pred.csv**: dades corresponents a la predicció mitjançant el model de regressió lineal de la mostra de test.  
* **test_rf_pred.csv**: dades corresponents a la predicció mitjançant el model de random forest de la mostra de test.  

## Requeriments

Per a poder executar el codi font abans esmentat es requereixen les següents llibreries:
```
library(knitr)
library(kableExtra)
library(pROC)
#library(nortest)
library(ggplot2)
library(dplyr)
library(DescTools)
library(missForest)
library(corrplot)
library(ggthemes)
```
