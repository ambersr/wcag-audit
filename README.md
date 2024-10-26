# WCAG Audit 

Doe een WCAG audit op een bestaande website uit je eigen omgeving en rapporteer daarover.

De instructies van deze opdracht staan in [INSTRUCTIONS](https://github.com/fdnd-task/wcag-audit/blob/main/docs/INSTRUCTIONS.md).
 

## Geteste website

Website: PurpeBird -> https://purplebird.nl/

Het bedrijf waarvan ik de website heb getest is mijn werk: PurpleBird. Het is een online marketingbureau, we ontwerpen en ontwikkelen maatwerk websites. De website van PurpleBird is gebouwd met Wordpress en plugins. Aangezien we zelf websites ontwikkelen was ik erg benieuwd om te kijken of ook onze websites goed toegankelijkheid zijn voor alle gebruikers. 

Op de homepagina zijn een aantal contentblokken zichtbaar. Waaronder een slider, animaties, accordeon en nieuwsartikelen. Op de website word er gebruik gemaakt van een aantal hoofdkleuren, felpaars voor de knoppen en elementen die moeten opvallen, lichtgrijs en wit voor grote achtergrondvlakken en een donkerpaarse kleur voor kleine achtergrondvlakken. Er wordt gebruik gemaakt van een navigatie (header) en een footer met menu items.

<img width="600" alt="image" src="https://github.com/user-attachments/assets/05df2d88-dfe1-4415-83bc-c9fc5767828f">

#

## Lighthouse Accessibility testresultaat
<img width="600" alt="image" src="https://github.com/user-attachments/assets/f2fafa2c-1761-406b-a094-b9e5df63565b">

## Testbevindingen
Waar de website niet aan voldoet is de kleurcontrast. De lichtgrijze achtergrond in combinatie met een witte tekst is niet voldoende contrast. Daarnaast worden de headingelementen door elkaar gebruikt. Dit is niet goed voor de HTML-structuur en de semantiek van de code. Het is belangrijk dat de heading elementen op volgorde worden gebruikt. Doordat de website gebouwd is met Wordpress en de plugin Jetengine, zijn de classes van elementen benoemd door deze plugin. Dit zorgt ervoor dat de computer de namen niet begrijpt. De lighthouse test gaf daarom ook aan om ervoor te zorgen dat je classes de juiste benaming geeft zodat bijvoorbeeld een screenreader HTML elementen beter kan lezen.

Linkje naar mijn bevindingen in wiki: https://github.com/ambersr/wcag-audit/wiki
## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
