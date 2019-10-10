# Answers

Nom : Descamps  
Prénom : Jules-Yan

# 1.
Citez deux avantages du PaaS sur le IaaS ?

Le premier avantage du PaaS sur le IaaS est le fait que ce n'est pas à l'utilisateur de s'occuper du versionning, il ne doit pas faire les montée de version, ni d'installation de patch.
Le deuxième avantage du PaaS sur le IaaS est que les développeurs peuvent personnaliser les applications à leur souhait. Le service PaaS rend le développement, le test et le déploiement d'applications rapides, simples et rentables.

# 2.
Quelle est la différence entre le PaaS et le Serverless ?

Les applications Serverless évoluent instantanément, automatiquement et à la demande, sans aucune configuration supplémentaire de la part du développeur ou du fournisseur. En revanche, alors que les développeurs peuvent programmer des applications hébergées sur PaaS pour pouvoir scale à la demande des utilisateurs, il ne s’agit pas d’une caractéristique intrinsèque de PaaS et ils devront donc  effectuer un certain nombre de prévisions pour s’occuper correctement du scaling.


# 3.
Que veut dire Serverless ?

L’architecture serverless est un modèle dans lequel le fournisseur de services cloud (AWS, Azure ou Google Cloud) est responsable de l’exécution d’un morceau de code en allouant de manière dynamique les ressources. Et il ne facture que la quantité de ressources utilisées pour exécuter le code.  Le code envoyé au fournisseur de cloud pour l’exécution est généralement sous la forme d’une fonction. Par conséquent, serverless est parfois appelé “Functions as a Service” ou “FaaS”.

# 4.
Citez les trois propriétés désirable du Serverless ?

-Scalabilité dynamique : Résilience supportée nativement par la plateforme

-Gestion fine : Pay-per-use sur le cloud

-Ephémère : La plateforme attends les requêtes et n’instancie que les fonctions a la demande, qui ne ”vivent” le temps délivrer le résultat

# 5.
Comment s'appelle la plus petite unité de compute déployable en Serverless ?


Le Function a as Service

Les fonctions sont les plus petites unitées. De meme que les 3 propriétés citées ci dessus, une fonction est éphémère (son life cycle ne dure que le temps de la requête), est Scalable (la plateforme pourra supporter la charge si elle augmente)

