# Lovelace Météo France weather-card

Projet reprit de https://github.com/Imbuzi/meteo-france-weather-card, pour une adaptation de la carte https://github.com/bramkragten/weather-card dédié à Météo France.

![Weather Card](https://github.com/hacf-fr/lovelace-meteofrance-weather-card/blob/Meteo-France/meteofrance-weather-card.png?raw=true)

## Prérequis

L'intégration ["Méteo France"](https://www.home-assistant.io/integrations/meteo_france) doit être installée et configurée.

Cette carte esy prévue pour s'installer depuis [HACS](https://hacs.xyz/) (Home Assistant Community Store). L'installation de ce composant est décrit sur son site.

## Installation:

Ajoutez l'adresse https://github.com/hacf-fr/lovelace-meteofrance-weather-card dans "Custom repositories" sur HACS, dans la catégorie "Lovelace".

Une fois le dépôt ajouté, il apparait dans la liste des dépôts additionnels avec pour titre "Lovelace Meteofrance Weather Card". Cliquez dessus et utiliser l'option "Install this repository in HACS". 
Laisser le choix de la version dans la dernière en date et utiliser l'option "Install".
Il vous est demandé de recharger l'interface, accepter avec l'option "Reload".


A ce stade, la carte est disponible dans la liste des cartes à ajouter dans votre "Tableau de bord".

## Configuration:

La carte est a ajouter depuis votre tableau de bord en mode édition.

Utiliser le + en bas à droite pour afficher la liste des cartes.

Sélectionner la carte personnalisée "Carte Météo France" et la configurer.

Définir un nom de carte et sélectionner l'Entity weather correspondant à celle de l'intégration Météo France.

Les autres entités (Risque de pluie, UV, etc) sont automatiquement calculées sauf "Vigilance Météo" que vous devez sélectionner.
