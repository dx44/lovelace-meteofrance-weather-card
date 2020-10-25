# Lovelace meteo France weather card

Projet reprit de https://github.com/Imbuzi/meteo-france-weather-card, pour une adaptation de la carte https://github.com/bramkragten/weather-card dédier à Météo France.

![Weather Card](https://github.com/Axellum/weather-card/blob/Meteo-France/weather-card.gif.png?raw=true)

## Installation:

Ajoutez l'adresse https://github.com/hacf-fr/lovelace-meteofrance-weather-card dans "Custom repositories" sur HACS, "Category": "Lovelace".

Ajouter dans "Configuration" / "Tableaux de bord Lovelace" / "Ressources" l'adresse de la carte:

```yaml
/hacsfiles/lovelace-meteofrance-weather-card/meteofrance-weather-card.js
```

## Configuration:

```yaml
type: custom:weather-card
entity: weather.yourweatherentity
current: true
details: false
forecast: true
hourly_forecast: false
number_of_forecasts: 5
```
