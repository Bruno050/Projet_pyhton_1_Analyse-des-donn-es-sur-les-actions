## Analyse des Données Historiques des Actions et Revenus avec Création d'un Tableau de Bord Interactif
### Description
Dansce projet, il est demandé à un Data Analyst/ Scientist qui travaille pour une start-up de vente à découvert Le Travail consite à extraire les données finacieres comme les cours historique de l'action et chiffres d'affaires trimestriels des grandes entreprises connues depuis diverse sources en utilisant python et le web Scrapping. Ensuite, visualiser le tout avec un mini-dashboard afin d'identifeir les tendances.

Les actions sont tout simplement des part de la propriété d'une entreprise. Un actionnaire peut décider de les vendre ou non. Son profit est proportionnlle à la part des actions détenue.

Le cours de l'action varie de façon continue dans le temps. Nous utiliserons ul'API y-finance dont un aperçu des fontions utilisées sont detaillé par ce site web; https://aroussi.com/post/python-yahoo-finance.

### Le Problème
La stat up fait ce qu'on appelle le short selling ou la vente à découvert ou encore position short. Elle consiste à vendre un titre (dont la chutte est supposée) que l'on ne possède pas. L'objectif est de pouvoir ensuite le racheter à un prix inférieur à son prix de vente. Elle réalise une plus-value si et seulement si la chutte des cours a bel et bien eu lieu. Dans le cas contraire, elle réalise une perte.

Nous supposons ic que le choix de la start-up se porte sur les actions de TESLA et de GAMESTOP.

Parfois, les vendeurs à découvert se trompent ; par exemple, Tesla. Il y a quelques années, de nombreux vendeurs à découvert ciblaient Tesla. Ensuite, Tesla a commencé à devenir rentable, et les bénéfices ont augmenté ; ainsi, les actions de la société ont augmenté. Ceci était basé sur la performance de l'entreprise, donc le titre devrait continuer à augmenter et le vendeur à découvert devrait vendre le titre. Les actions récemment vendues à découvert peuvent augmenter pour des raisons qui ne sont pas basées sur les fondamentaux ; c'est moins durable.

Des investisseurs individuels utilisant le forum de la communauté en ligne Reddit nommé WallStreetBets ont commencé à acheter des actions de GameStop, un détaillant de jeux vidéo et informatiques perdant de l'argent. L’afflux de demande a fait monter en flèche les actions de GameStop. Tout cela a généré des milliards de dollars de pertes pour les hedge funds qui avaient vendu les actions à découvert.

### Leçon à titrer
Il n'est pas évident pour une telle start-up de choisir les actions.

### Solution: Un outils d'aide à la décision
L'idée est de visualiser le cours de actions de ces deux entreprises afin d'avoir une idée sur les risques s'il arrive que notre start-up choississe les actions des ces deux entreprises.

Elle consistera à afficher les revenues trimestrielle et les cours des actions de l'entreprise afin de degager une tendance.
