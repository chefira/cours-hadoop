# cours-hadoop
**Cours Hadoop SIO 2018** *- notes par Yoannis*


Structure du cour?
- [] Vision de l'écosystème
- [] Cas d'usage
- [] Critères de sélection
- [] Le Datalake


## L'écosystème Hadoop

### HDFS
* Système de fichier distribué
* Abstraction du stockage pour faciliter la manipulation des fichiers (Scalabilité)
* Fiabilité; Résilience; Disponibilité
* Expose une interface pour optimser le processing (intelligence dans GFS avec des métadonnées)


### HBase
* Base de donnée distribuée


### Hive
* Langage de requetage SQL


### YARN
* Gestion de ressources


### PIG
* ETL, batch


### ~~OOZIE~~
* scheduler


### TEZ
* *TODO*


### MEZOS
* Gestion de ressources


### Zookeeper
* Bon fonctionnement des services entre eux
* Implémente un algorithme de consensus; Permet de gérer certains états de fonctionnement


### Spark
* Engine pour calcule de donnée distribuée (microbatch)


### SparkStreaming
* Spark pour le streaming


### KAFKA
* Permet de contenir les évènements dans une architecture en flux (queue)


### Flume
* Déplacer des quantitées de données (fichiers)


### STORM
* event processing framework


### Impala
* Réponse au problème de latence et requêtage de HIVE (SQL compliant) (Framework)


### MapReduce
* Implémentation Hadoop de l'algorithme de Google


### Ambari
* Administration graphique du cluster Hadoop


### Slider
* Long running service possible


- - -
