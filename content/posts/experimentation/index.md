+++
title = '(Expérimentation) MongoDB et Laravel enfin ensemble ?'
date = 2024-01-25T18:21:47+01:00
draft = false
+++

## Contexte

Lors de mes études à la HEIG-VD, j'ai eu l'opportunité de suivre un cours optionnel sur l'Ethical Hacking, une aventure qui m'a plongé dans l'univers de la sécurité informatique 🛡️. 

L'objectif : comprendre les fondamentaux de la sécurité en développant un site web avec les protections étudiées en cours.

Aujourd'hui, je ne vais pas vous détailler l'ensemble du projet, même s'il fut captivant. Je souhaite plutôt partager avec vous une expérimentation que j'ai menée.

Pour mettre le projet en contexte, mon équipe et moi étions chargés de créer un site web. 

Nous avons opté pour Laravel, un choix naturel puisque c'était une plateforme maîtrisée par tout le groupe 💻. 

Quant à la base de données, les consignes spécifiaient MongoDB, un système de gestion de bases de données orienté documents 📄.

## Laravel x MongoDB

Au démarrage du projet, je me suis lancé dans des recherches sur l'intégration de MongoDB dans Laravel et, coup de chance, je suis tombé sur un article tout frais annonçant une nouveauté de taille : [Laravel venait d'intégrer officiellement le package "jenssegers/laravel-mongodb"](https://laravel-news.com/mongodb-laravel-integration) 🎉.

Anciennement, pour intégrer Laravel et MongoDB, on devait s'en remettre à cette bibliothèque qui étendait Eloquent, permettant l'utilisation de modèles et de constructeurs de requêtes. 

Et Jackpot ! Cela tombait bien car comme nous devions justement utiliser MongoDB et pourquoi ne pas tester cette nouvelle intégration.

L'installation s'est révélée être plutôt simple : installer le driver PHP pour MongoDB, intégrer le package via Composer et effectuer quelques ajustements dans les fichiers de configuration pour établir MongoDB comme notre système de connexion principal 🔧.

Un petit point à noter, comme c'était une nouvelle intégration, la documentation manquait parfois lorsque l'on voulait effectuer certains points spécifiques, mais je suis confiant que cela sera amélioré avec le temps 📚.

## Conclusion

L'adoption officielle par Laravel d'un package pour MongoDB est une excellente nouvelle. 

Elle garantit une meilleure maintenance et des mises à jour fréquentes ⚙️, une réactivité accrue face aux problèmes de sécurité 🔒, et promet une documentation de plus en plus complète et détaillée 📖.

Lien vers le projet : [EthH-KPM - 2024](https://kevinpasteur.myportfolio.com/ethh-kpm)