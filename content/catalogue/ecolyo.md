+++
title = 'Ecolyo'
draft = false
+++


![Logo Ecolyo](/images/ecolyo_logo.png)

## Ecolyo vous aide à suivre et agir sur vos consommations d'énergie et d'eau

[Ecolyo](https://ecolyo.com) est un service gratuit fourni par la Métropole de Lyon à ses habitants, disponible sur smartphone et ordinateur.

- Retrouvez au même endroit vos consommations d'électricité, de gaz et d'eau
- Suivez l'évolution de vos consommations dans le temps
- Avec les défis personnalisés, Ecolyo vous accompagne dans la réduction de vos consommations d'énergie et d'eau

## Infrastructure self data utilisée

Ecolyo repose sur un espace de stockage numérique personnel fourni gratuitement par la Métropole de Lyon, nommé [_“Ma Bulle”_](https://support.grandlyon.com/clouds-personnels-grand-lyon/) et propulsé par **Cozy Cloud**.

Les données et le code de l’application sont hébergées en France, chez OVH, avec une réplication sur 3 sites distincts.

Une fois dans leur bulle, les utilisateurs y ajoutent l'application Ecolyon et y connectent leurs compteurs intelligents :

- Linky pour l'électricité
- Téléo pour l'eau
- Gazpar pour le gaz

Les données de consommation d'eau et d’énergie du ménage sont ensuite utilisées par l'application pour produire des tableaux de bord, des comparatifs de période en période, ou bien à des ménages types.

## Méthode de déploiment

Un service de stockage numérique personnel fourni par la Métropole à ses habitants, accompagné d'une application interne à ce service de stockage numérique.

L’application Ecolyo utilise 3 connecteurs dont le rôle est de récupérer les données auprès des 3 fournisseurs :

- **Eau du Grand Lyon**,
- **Enedis** pour l'électricité
- **GRDF** pour le gaz.

## Dépôt git du code

Le code de cozy cloud est en grande partie public : [https://github.com/cozy](https://github.com/cozy).

Le code source d'Ecolyo est public sur  [la forge de la Métropole de Lyon](https://forge.grandlyon.com/web-et-numerique/factory/llle_project/ecolyo).

## Parties prenantes

- Métropole de Lyon
- Cozy
- Banque des Territoire

## Budget

## Contacts

- Marion Bertholon, Métropole de Lyon, Chargée de services numériques pour la transition énergétique
- Blandine Melay, Métropole de Lyon, Responsable du Service Energie Climat
- Maintenance technique : Délégation Développement économique, emploi & savoirs - Innovation numérique & systèmes d’information - Usages et services numériques - Développement des services numériques
