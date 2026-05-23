Pour ce projet de CSF (Communication Sans Fil), on a eu avec mon collègue Mr. ANZEVINO comme idée d'un projet qui consiste à refroidir un objet éléctronique.

L'idée étant de poser l'objet sur le support, qui ce dernier comporte un capteur de température (qu'on trouve sur les cartes UCA fournis) et que si cet objet 
dépasse un certain seuil de température (défini dans le code dans Arduino IDE), cela ferait tourner un ventilateur qui permettra justement de refroidir l'objet
concerné. Bien entendu, si la température redescend sur un autre seuil défini, alors le ventilateur en question céssera de tourner. Or pour faire fonctionner 
le ventilateur. Le problème étant que ce dernier fonctionne sur minimum 5 Volts alors que la carte UCA était maximum d'alimentation à 3,3 Volt. Il était donc 
obligatoire d'ajouter un relais et aussi un V_bus pour réussir à faire tourner le ventilateur, ce qui laisse place à plus d'erreurs possibles malheuresement.

Mais pour revenir sur l'idée du projet, il fallait bien chosir un objet qui serait simple d'usage (pas trop volumineux par exemple) et si possible, un objet du 
quotidien que tout le monde utilise pour mettre en valeur ce projet qui pourrait toucher éventuellement le plus (+) de personne possible. 

C'est donc pour ça que nous avons choisi le téléphone portable qui respecte ces conditions, d'où le nom "RefroidPhone" (Faut que ça soit intuitive tout de 
même). Dans le cadre du cours "Communication sans fil". Notre projet devait également emglober l'utilisation du "sans fil" ; en l'occurrence l'utilisation du 
protole LoRaWAN qui était donc utilisé dans la partie code Arduino IDE.

La carte transmet la température via le protocole LoRaWAN au réseau TTN. Ce dernier fait alors le pont avec la plateforme Tago.io, qui se charge d'envoyer un 
email d'alerte dès que le seuil de température est franchi.

Dans les premières semaines, il fallait apprendre et comprendre le fonctionnement de GitHub (Obligatoire pour le rendu du projet final) puis la semaine d'après 
était le début de la partie codage, en commençant simplement par afficher en temps réel sur le serial monitor la température que detectait le capteur SHT. Plus 
les semaines avancées plus il fallait développer le GitHub avec notamment l'ajout de slides (diaporama) qu'on avait présenté pour l'évaluation du mi-semestre 
et jusqu'à quelques jours avant le rendu final la partie code à finir avec notamment l'ajout du protocole LoRaWAN et tout ce qui suit derrière (création TTN, 
Tago.io), avec également une autre partie "Document" qui indique "Qui s'est occupé de quoi dans le projet" entre nous.

Enfin, pour finaliser ce projet et lui donner une véritable dimension physique avant la présentation finale, nous sommes passés par le FabLab. Cela nous a 
permis de modéliser notre support en 3D et de l'imprimer à l'aide d'une imprimante 3D, afin d'avoir un véritable un bon rendu final sur lequel intégrer notre 
carte UCA et le ventilateur."
