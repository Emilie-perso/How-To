# How-To

## Spark

### Qu'est-ce que Spark ? 

Spark est un ensemble de librairies dans le lequel le développeur peut piocher (framework) pour faire du calcul distibué sur un ensemble de données massives.

### Pourquoi Spark ? 

Spark a été inventé en support de Map Reduce qui été alors la principal outils de calcul de données volumineuses, pour améliorer les performances de calculs. 
Map Reduce qui a été inventé par Yahoo dans le cadre du projet Apashe Hadoop, permet de faire du calcul de données massives en utilisant plusieurs machines qu'on appelle un noeud. Chaque noeud est alors chargé d'effectuer un calcul. Le résultat de ce calcul entre les étapes Map et Reduce est stocké sur le disque de la machine.
Spark lui au contraire utilise le traitement en mémoire c'est-à-dire qu'il stocke les résultats intermédiaires de traitement sur la mémoire vive , ce qui permet d'accéder plus rapidement aux données qui ont été traitées.

### Avantages de Spark par rapport à Map Reduce 

#### Facilité de prise en main 

Spark propose plusieurs Apis en Python, Java, Scala, R qui permettent de développer facilement des applications dans le langage dans le lequel on est à l'aise alors que Map Reduce est seulement en Java.
Utilisation de moins de ligne de code.

### Performance

Dû à son traitement en mémoire Spark est davantage plus rapide que Map Reduce.

### Type de traitement 

Spark permet le traitement de données par lots mais aussi de traiter des fluxs en temps réel. 

### Ecosytème riche 

Spark propose plusieurs librairies :
Une librairie pour faire du machine learning 
Une librairie pour faire du traitement de données en temps réel, les fameux flux streaming 
Une librairie pour faire du requêtage sql 
Une librairie pour faire pour manipuler les données graphes. 

### HDFS dans Spark Hadoop ?

Hdfs est un système de stockage de fichier semblable à celui qu'on trouve sur notre PC. 
Pour lire les fichiers, vous pouvez utiliser Hive et faire du requêtage sql, ou naviguer via le cli hadoop, ou utiliser Python/Scala et créer un dataframe pour lire les données. 
Le format de données présent dans HDFS sont les suivants : 
Avro 
ORC
txt
Parquet 

#### ORC c'est quoi ? 

#### Parquet c'est quoi ? 

#### Avro c'est quoi ? 

### Quel format de données choisir ? 

### Qu'est ce que YARN ? 

### 