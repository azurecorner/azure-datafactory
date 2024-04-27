# azure-datafactory

Avec la variété des sources de données disponibles sur Azure et on-premise , il devient impératif de gérer et de coordonner la migration des données entre elles.
Parfois, il est nécessaire d'automatiser le transfert régulier des données dans le cadre d'une solution d'analyse d'entreprise plus vaste.

Les pipelines d'Azure Data Factory et Azure Synapse sont des solutions qui répondent parfaitement à ce besoin.

Dans cette session, nous allons explorer Azure Data Factory, ses différents composants, ainsi que les mesures de sécurité essentielles pour approvisionner et gérer Azure Data Factory

![data-driven-workflow](https://github.com/azurecorner/azure-datafactory/assets/108787059/b955e689-f48c-4e50-a520-104aee0429d8)
https://www.decivision.com/blog/microsoft-bi/presentation-de-azure-data-factory

![architecture-data-factory-1](https://github.com/azurecorner/azure-datafactory/assets/108787059/4358f59e-e125-4be8-9ddf-f0e3e70adb75)

https://learn.microsoft.com/fr-fr/training/modules/data-integration-azure-data-factory/5-understand-components

1. Public visé ?

Cette serie de tutoriel est destiné aux  professionnels de la data dans Azure (data engineer, data architect, étudiants). 

2. Quel problème spécifique cette session résoudra-t-elle ?
Cette session  permettra au participants de comprendre comment créer un service datafactory dans Azure pour creer des pipelines de données de manière sécurisée et évolutive 

3. Que pourra faire le public après avoir regardé cette session ?	
   Les participants pourront créer un service datafactory et un pipeline d'integration de données dans Azure via le portail Azure.

Dans cette session, je vais donc créer un service Azure Data Factory pour transférer des fichiers depuis un compte de stockage Azure vers un stockage Azure Data Lake Gen2. Pour cela, je vais créer les services suivants :

Un compte de stockage
Un stockage Azure Data Lake Gen2
Un coffre-fort Azure Key Vault
Un service Azure Data Factory
Deux Linked-Services , l'un pour se connecter au compte de stockage Azure en utilisant Azure Key Vault, l'autre pour se connecter au stockage Azure Data Lake Gen2
Un pipeline pour transformer et transférer le fichier vers le stockage Azure Data Lake Gen2

![Architecture drawio](https://github.com/azurecorner/azure-datafactory/assets/108787059/8ec2cdcd-014c-4164-86c9-05bfa89d795e)




 
