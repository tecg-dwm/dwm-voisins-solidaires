# Les Voisins Solidaires

> HTML exercise given at [HEPL](https://hepl.be)

* * *

**Les Voisins Solidaire** is an educational project, which will be used for `Mobile UX/UI` courses.

**Note:** the school where the course is given, the [HEPL](https://hepl.be/fr/art560) from Liège, Belgium, is a french-speaking school. From this point, the instruction will be in French.

* * *

## Application de partage d'outils entre voisins

### Informations sur la cliente
- **Client&nbsp;**: Marie D.
- **Role&nbsp;**: Coordinatrice de l'organisation &laquo; *Les Voisins Solidaires* &raquo;
- **Niveau de technicité de la cliente&nbsp;**: Utilise un smartphone au quotidien pour des tâches administratives ou de loisir mais ne connait aucun termes techniques lié au design ou au développement d'applications mobiles.

### Contexte et problème

Marie coordonne une petite association qui a pour but d'aider les gens de son quartier à créer plus de liens entre eux.

Elle remarque quelque chose d'inquiétant&nbsp;: les gens ne se parlent plus et l'entraide diminue. Emprunter un tournevis ou une échelle devient de plus en plus compliqué.

Elle aimerait une application très simple qui permette aux voisins de prêter et d'emprunter des outils de manière humaine (pour tous donc) et respectueuse.

**Ce que Marie ne veux pas :**

- Des classements (entre les utilisateurs).
- Pas de commentaires, d'échanges de messages écrits.
- Une dimension commerciale ou addictive.
- Tout ce qui pousse les gens à être rapides ou parfaits.

### Cahier des charges
- Les gens peuvent voir quels outils leurs voisins prêtent.
- Les gens peuvent demander à emprunter un outil pour une durée déterminée et unique.
- Le propriétaire peut accepter ou refuser.
- Ils peuvent convenir d'une plage horaire et d'un lieu de rendez-vous.
  - L'emprunteur choisit d'abord une plage horaire.
  - Le propriétaire peut l'accepter ou proposer une autre plage.
  - Je ne veux pas que les gens partagent leur adresse personnelle, sauf s'ils le souhaitent vraiment.
  - L'application devrait proposer des lieux de rendez-vous communs et neutres, tels que (à l'entrée du supermarché, au coin de deux rues, à l'entrée du parc, au centre communautaire, ...).
  - L'application pourrait suggérer des lieux de rendez-vous proches du domicile du propriétaire, mais en utilisant uniquement une localisation approximative, jamais l'adresse exacte.
  - Les utilisateurs devraient également pouvoir choisir manuellement le lieu de rendez-vous.
  - Certains voisins préféreront peut-être appeler ou envoyer un SMS une fois le rendez-vous fixé. D'autres ne voudront pas du tout communiquer leur numéro. L'application devrait donc :
    - Demander à chaque personne si elle souhaite partager son numéro de téléphone, mais uniquement après que les deux parties se soient mises d'accord sur l'heure et le lieu de retrait et uniquement si elles appuient sur un bouton pour le partager.
    - Si quelqu'un ne se sent pas à l'aise pour partager son numéro, il devrait pouvoir continuer sans le faire.
- L'emprunteur peut confirmer qu'il a rapporté l'outil.
  
Les gens doivent également pouvoir :
- Ajouter un outil (nom, photo, brève explication).
- Indiquer un outil comme disponible ou indisponible.
  - Le propriétaire doit également décider de la durée pendant laquelle quelqu'un peut emprunter son outil. Mais uniquement à partir de choix prédéfinis (1 heure, 1 jour, 3 jours, 2 semaines, ...).
  - Peut-être autoriser les réservations uniquement pour les 7 jours suivants
- Modifier ou de supprimer un outil si nécessaire.

### Ce dont vous devez être capable

Marie n'est pas une experte de l'UX ou du Design d'applications mobiles, vous devez donc être capable de : 

- Lui expliquer comment une personne utilisera réellement l'application. Elle doit pouvoir imaginer l'expérience dans son ensemble sur base votre production.
- Lui expliquer pourquoi vous avez placé les éléments d'interface à cet endroit et selon cette disposition.
- Lui expliquer pourquoi vous avez choisi vos choix graphiques (couleurs, formes, images, etc.) et pourquoi vous pensez qu'ils correspondent à la demande initiale.
- Lui expliquer et justifier l'ordre dans lequel les utilisateur·rices vont parcourir l'application en fonction de leurs besoins.

## Grille d'autoévaluation

### A. Clarté des flux principaux 

- **0-25%**&nbsp;: Les flux sont confus, des étapes importantes manquent, les utilisateurs risquent de se retrouver bloqués. 
- **25-50%**&nbsp;: Le cheminement de base fonctionne, mais plusieurs étapes sont floues ou surchargées.
- **50-75%**&nbsp;: Les flux sont globalement clairs, avec seulement quelques ambiguïtés mineures.
- **75-100%**&nbsp;: Très facile à suivre, les flux semblent naturels et prévisibles.

### B. Respect des contraintes et des valeurs 

Pas de notes, pas de chat, pas d'adresses exposées sur la carte, pas de gamification.

- **0-25%**&nbsp;: Ignore les contraintes majeures (par exemple, ajoute un chat ou des notes).
- **25-50%**&nbsp;: Respecte partiellement les contraintes, mais certaines fonctionnalités contredisent la vision.
- **50-75%**&nbsp;: Globalement conforme, avec un ou deux choix de conception limites.
- **75-100%**&nbsp;: Entièrement conforme&nbsp;: simple, convivial, non transactionnel, respectueux de la vie privée.

### C. Conception des rendez-vous et des créneaux horaires

Qualité de la gestion des heures de ramassage/restitution et des lieux de rendez-vous.

- **0-25%**&nbsp;: Vague ou manquant ; les utilisateurs ne sauraient pas quand/où se rendre.
- **25-50%**&nbsp;: Existe, mais prête à confusion ou ressemble à un système de rendez-vous d'une application de petits boulots.
- **50-75%**&nbsp;: Assez claires, quelques frictions mais compréhensibles.
- **75-100%**&nbsp;: Simples, solides et conformes à la philosophie « créneau horaire + lieu prédéfini ».

### D. Contrôle par le propriétaire de l'outil

Capacité du propriétaire à définir la durée, la disponibilité et l'arrêt du prêt.

- **0-25%**&nbsp;: Propriétaire presque impuissant ; ne peut contrôler le prêt ou la durée.
- **25-50%**&nbsp;: Contrôle partiel, mais options clés manquantes (pas de durée maximale, pas de possibilité d'arrêter le prêt).
- **50-75%**&nbsp;: Contrôle raisonnable ; lacunes mineures.
- **75-100%**&nbsp;: Contrôle clair et simple : durée prédéfinie, disponibilité activable/désactivable, possibilité d'arrêter le prêt.


### E. Conception visuelle et hiérarchie de l'information 

- **0-25%**&nbsp;: Encombré, incohérent, difficile à lire.
- **25-50%**&nbsp;: Mise en page basique, visuels incohérents ou maladroits.
- **50-75%**&nbsp;: Globalement cohérent et lisible ; quelques imperfections.
- **75-100%**&nbsp;: Propre, calme et facilitant la compréhension ; système visuel cohérent.

### F. Principes fondamentaux d'accessibilité et d'inclusivité

- **0-25%**&nbsp;: Texte minuscule, faible contraste, icônes peu claires, aucune considération pour l'accessibilité.
- **25-50%**&nbsp;:  Quelques efforts, mais toujours problématique.
- **50-75%**&nbsp;:Généralement lisible et compréhensible.
- **75-100%**&nbsp;: Typographie, contraste, étiquettes d'icônes et taille du texte bien pensés.