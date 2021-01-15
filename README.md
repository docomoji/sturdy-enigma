# Projet dans les grandes ~~angles~~ lignes
## Le nom :
Le nom vient de l’entreprise qui a “créé” les emojis, NTT DoCoMo. Le vrai créateur des emojis est [Shigetaka Kurita][begin].
Normalement le nom n’est pas déjà pris. Et aucun risque de copyright infringement. C'est donc une reference et un ~~mauvais~~ jeu de mot.

La page d’accueil du site devrait avoir un petit clin d’oeil aux [emojis originaux][original]. Surement des petites animations en fond, tres simples et discretes, mais presentes neanmoins.

## Speech Principal :
Faire deviner des mots, concepts ou expressions en utilisant seulement des emojis.
Le jeu se base sur le multijoueur et devrait permettre d’inviter ses amis lors de parties en ligne endiablées.

Exemple :
🚣‍♂️👩‍🦯 = naviguer à l’aveugle

## Technologies utilisées
#### Frontend
- [svelte][svelte]
- [milligram][milligram]
- [socket.io][socketiof]

#### Backend
- [express][express]
- [socket.io][socketiob]
- [mongodb][mongodb] | [mysql][mysql]

## Contraintes lié aux JPOs :
- prévoir un mode solo pour contrer la limite de jouabilite seule (ne serait ce qu'un peu)
- deadline le 28/02 → maquette jouable d’ici le 01/02 !

## Features principales :
#### Multijoueur
- création et gestion des salles.
- connecter les utilisateurs ensembles.

#### Catégories
- catégoriser les différents emojis.
- créer des catégories pour les parties.
- empêcher l’utilisation de certains emojis dans certaines catégories.

#### Parties
- instaurer un systeme de difficulté (5 emojis pour facile, 3 pour difficile)
- timer (Proposition & pour le guess)
- quand il reste la moitié du temps affichage de l’indice.
- entrée de l’indice et de la proposition en début de round.
- plus de points gagner si guess plus rapide.
- si c’est vraiment la merde, on affiche un indice textuel.


[begin]: https://edition.cnn.com/style/article/emoji-shigetaka-kurita-standards-manual/index.html
[original]: https://forum.nativesintech.org/uploads/default/original/1X/5c36611c9fb977d170721cd4c71817e6531e3502.png
[svelte]: https://svelte.dev/
[milligram]: https://milligram.io/
[express]: https://expressjs.com/
[socketiof]: https://socket.io/docs/v3/client-api/
[socketiob]: https://socket.io/docs/v3/server-api/
[mongodb]: https://mongodb.com/fr
[mysql]: https://mysql.com/fr/
