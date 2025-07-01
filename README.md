# Comment exécuter une tâche ETL PySpark sur Google Cloud Dataproc ?

Cliquez sur l'image pour regarder la vidéo du tutoriel :

[![Exécuter un Pipeline ETL PySpark sur Cloud Dataproc - Tutoriel complet étape par étape](https://img.youtube.com/vi/RRI15I9T1Aw/hqdefault.jpg)](https://www.youtube.com/watch?v=RRI15I9T1Aw)

## Présentation

Cloud Dataproc est un service entièrement géré et évolutif permettant d'exécuter des tâches Apache Spark et Hadoop sur Google Cloud. Il simplifie la gestion de l'infrastructure et vous permet de vous concentrer sur l'écriture et le déploiement de vos pipelines de données.

Dans ce tutoriel, vous apprendrez à utiliser un script ETL PySpark existant et à l'exécuter en deux étapes :

* **Localement**, pour valider les transformations.
* **Sur un cluster Cloud Dataproc**, en utilisant les données stockées dans Cloud Storage et en écrivant le résultat dans BigQuery.

Cette approche reflète un workflow réel où le développement démarre localement, puis est déployé dans le cloud.

## Objectifs

À la fin de cet atelier, vous serez capable de :

* Créer et configurer un cluster Dataproc à l'aide de la CLI « gcloud ».
* Écrire et exécuter une tâche ETL PySpark localement sur votre machine. * Importez les données d'entrée et les scripts PySpark dans Google Cloud Storage.
* Déployez et exécutez votre pipeline ETL sur Dataproc.
* Chargez les données nettoyées dans BigQuery.
* Validez votre transformation en exécutant des requêtes SQL sur la table résultante.

---

**Article Medium de ce tutoriel** : https://medium.com/@afouda.josue/how-to-run-a-pyspark-etl-job-on-google-cloud-dataproc-d45e58724017