# Base-de-publications-scientifiques
Il s’agit de créer une base Mongo, une collection, d’y insérer des données et de l’interroger grâce à Python. Les documents fournis correspondent à un extrait d’une base de publications scientifiques, The DBLP Computer Science Bibliography.

## Ressources

https://www.mongodb.com/docs/manual/

https://www.mongodb.com/languages/python

https://dblp.uni-trier.de/db/journals/vldb/vldb23.html

Le centre de recherche Breizhmeiz International souhaite un petit module d'accès simple aux publications scientifiques. On vous demande de mettre en place une base de données MongoDB, orientée documents, pour gérer l'accès à ces publications. De votre coté, vous allez tester les datas grâce à un petit script Python.

## Modalités 

- Créer la base DBLP et y ajouter une collection publis
- importer dans la base les données du fichier dblp.json 
- écrire le script Python pour tester la base
- exécuter le script et vérifier les résultats.

Le script Python doit permettre de : 
- Compter le nombre de documents de la collection publis; 
- Lister tous les livres (type “Book”) ; 
- Lister les livres depuis 2014 ; 
- Lister les publications de l’auteur “Toru Ishida” ; 
- Lister tous les auteurs distincts ; 
- Trier les publications de “Toru Ishida” par titre de livre ; 
- Compter le nombre de ses publications ; 
- Compter le nombre de publications depuis 2011 et par type ; 
- Compter le nombre de publications par auteur
- trier le résultat par ordre croissant ;

<i>Tous les affichages se font dans la console.</i>

Bonus: 
- demande le chemin d'un fichier json
- insére un ou plusieurs nouveaux documents, à partir de ce fichier, dans la collection publis.
- TEST: créer un fichier json à partir des informations trouvées sur le site proposé en lien.



