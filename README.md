# Accessible Website

Ontwerp en maak voor een opdrachtgever een component/pagina/site toegankelijk volgens WCAG richtlijnen.

De instructie van deze leertaak staat in [INSTRUCTIONS](https://github.com/fdnd-task/all-human-accessible-website/blob/main/docs/INSTRUCTIONS.md)

## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
In dit project heb ik me gefocust op het compleet maken van de responsive designs. Ook heb ik een aantal van de WCAG richtlijnen gecheckt en toegepast op het gebied van teogankelijkheid. Verder heb ik een navigatie toegevoegd voor smaller devices. Hetgeen waar ik helaas nog niet aan toegekomen ben is het voorstel om een scroll back up button uit te werken.

Beginnend over de WCAG richtlijnen die ik bekeken heb: 
* Ik heb gekeken naar de alt attributen. Deze worden voorgelezen wanneer een afbeelding niet laadt of iemand deze niet kan zien door bijvoorbeeld blindheid. Deze heb ik beschrijvende informatie gegeven of leeg gelaten, vaak hadden de plaatjes niet per se een beschrijvende rol. Zo leest een screen reader niet alle onbelangrijke afbeeldingen voor.
* Ook heb ik gelet op de heading levels, zodat er met een screen reader de juiste geselecteerd kunnen worden.
* De tab toets heb ik getest en deze loopt door alle linkjes heen.
* Ook heb ik het kleurcontrast getest. Deze was op AA level helemaaal in orde. Voor AAA niveau was deze een kleine fout bij de blauwe kleur, maar dit zie ik niet als groot probleem.

<img src=assets/color-contrast-blue.png alt="" height=360px>



### _**smallest viewport**_
Dit is de smallest viewport die ook op 320px werkt zonder horizontale scrollbar etc. Deze heeft een in- en uitklapmenu (hamburger-menu).

<img src=assets/smallest-viewport.png alt="" height=360px>


### _**smaller viewport**_
Er was in het ontwerp alleen een small en large viewport geleverd. Voor het maatje ertussen heb ik zelf het ontwerp bedacht en de eerste drie articles onder elkaar gezet, zoals duidelijk wordt in de afbeelding hieronder. Op dit tussenmaatje was de navigatie nog te groot, dus heb ik hier nog het hamburger-menu laten werken.

<img src=assets/smaller-viewport(articles).png alt="" height=360px>


### _**bigger viewport**_
Eigenlijk is de grotere viewport gewoon zoals het ontwerp. Waar nog aan gewerkt moet worden zijn uiteraard de dingen die met javascript moeten gebeuren, zoals de filter buttons, extra items laden etc.

<img src=assets/big-viewport.png alt="" height=250px><img src=assets/big-viewport2.png alt="" height=250px>



### _**hamburger menu**_
<img src=assets/ham-menu-animatie.png alt="" height=360px>
Hier zie je nog dat wanneer het hamburger menu geopend wordt op een iets breder scherm de achtergrond een mooie zwarte waas krijgt. Ook veranderen de drie streepjes in een sluiting kruisje met een animatie.



<a href="https://julesbruins.github.io/all-human-accessible-website/">link naar de site</a>

## Kenmerken
Ik heb voor mijn HTML veel sections gebruikt en deze allemaal een class gegeven. Verder heb ik in de CSS veel genest. Ook staan de media queries echt in het element genest. Verder is er Javascript toegepast op het hamburger menu te laten werken. Hierbij hoort veel verschillende CSS. Een van de belangrijkste is de media querie <a href="https://github.com/julesbruins/all-human-accessible-website/blob/e1b704967bf6aa3976918c748022cd14f43d82b3/styles.css#L582-L603">van de navigatie</a> hierbij zie je dat de navigatie tevoorschijn komt op groot scherm en het hamburger-menu verdwijnt. 


## Bronnen

## Licentie
This project is licensed under the terms of the [MIT license](./LICENSE).
