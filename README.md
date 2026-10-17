# Demande de devis Télé-Marmotte

Le questionnaire en ligne de **Télé-Marmotte** (captations de concerts et spectacles, montage, mixage), pensé pour le téléphone : une question à la fois, une estimation du prix à la fin, et la demande arrive par email.

**Remplir une demande : https://telemarmotte.github.io/devis/**

Le site principal : https://www.tele-marmotte.com/

## Liens directs

On peut ouvrir le questionnaire avec le type de vidéo déjà choisi :

- `?type=spectacle` : un concert ou un spectacle entier
- `?type=teaser` : un teaser
- `?type=morceaux` : un ou quelques morceaux (live session)
- `?type=clip` : un clip
- `?type=docu` : un documentaire, un projet spécial
- `?type=autre` : autre chose

Exemple : https://telemarmotte.github.io/devis/?type=clip

## Réglages

Tout est dans `index.html`, en tête du script :

- `CONFIG` : adresse de réception, alias FormSubmit, logo, note sur les déplacements ;
- `T` : la grille de prix TTC (calibrée sur la captation complète à 800 €).

Les demandes sont envoyées par [FormSubmit](https://formsubmit.co/). Si l'envoi échoue, le client peut ouvrir sa messagerie avec la demande déjà rédigée.
