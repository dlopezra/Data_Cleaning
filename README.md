# WebScraping

M2.951 - Tipologia i cicle de vida de les dades - Pràctica 2 - Tractament dataset Titanic

## Membres de l'equip

La pràctica ha estat realitzada per **Daniel López**. 

## Fitxers de codi font

Podem trobar els fitxers de codi font a la carpeta **src**:

* **Titanic.rmd**: Fitxer en R que conté tot el codi de la pràctica.

## Documentació

Les respostes a la pràctica, així com la documentació generada la podem trobar a la carpeta **pdf**:

* **daniellopez_prac1.pdf**: document pdf amb les respostes a la pràctica.
* **euroleague.net.pdf**: document pdf amb l'avaluació inicial del site.

## Dataset

Per a la pràctica s'han generat dos datasets corresponents a les dades de les temporades 2017 i 2018 de l'Eurolliga que es troben a la carpeta **csv**:
* **euroleague.net2017.csv**: dades corresponents a la temporada 2017-2018.
* **euroleague.net2018.csv**: dades corresponents a la temporada 2018-2019.

## Requeriments

Per a poder executar el codi font abans esmentat es requereix la instal·lació de les següents llibrerires:
```
pip3 install requests
pip3 install lxml
pip3 install beautifulsoup4
pip3 install fpdf
pip3 install buildwith
pip3 install python-whois
```
## Execució

Per a poder executar l'script:
```
python basketscrapper.py <competició> <any>
```
On competició pot ser (**actualment només està definit el mòdul per l'eurolliga**): 
* euroleague
* acb
* nba

I any pot ser: 
* 2000
* 2016
* tots

### Exemples
```
python basketscrapper.py euroleague 2018
python basketscrapper.py euroleague tots
```
