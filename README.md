# Drime
Drime est une base de données de rimes créé par [Antoine Amarilli (a3nm)](https://a3nm.net/index.html.fr).
Elle est présentée ici sous la forme d'un fichier au format SQL. 

## Informations

La liste des informations disponibles dans la base est détaillée dans la [page d'aide du projet](https://drime.a3nm.net/about).
Les tables comprennent, outre les mots, l'écriture phonétique, le nombre de syllabes minimal et maximal ainsi que des informations sur les rimes féminines ou les mots élidables, etc.

## Format

La base de données Drime est générée par un script python à partir de la base de données [Lexique 3](http://louphole.com/bibliotech/lexique/).
Pour des questions de practicité, pour ceux qui comme moi souhaitent uniquement le résultat final de l'opération, j'ai récupéré, avec l'aide d'un ami pythoneux, la base dans un fichier au format SQL.

## Exemples d'utilisation

La boîte à outils [Poetify JS](https://github.com/WhiteFangs/PoetifyJS) repose sur la base de données Drime pour récupérer les rimes des mots, et donc par extension, les applications [Panoryma](http://louphole.com/applications/panoryma/) et [Parolyma](http://louphole.com/applications/parolyma/) également ! 
