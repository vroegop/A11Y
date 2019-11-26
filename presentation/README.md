# Hands-on Sessies Presentatie
In deze repository vind je een template voor je hands-on sessie gemaakt binnen reveal.js

Het template kent een donkere en lichte variant. Aan jou de keuze welke je wilt gebruiken.

## Quickstart
Voor de mensen die eerder met nodejs/npm en git gewerkt hebben, volg de volgende stappen
om met je presentatie aan de slag te gaan:

- In je working copy voer je eenmalig `npm install` uit
- Voer `npm start` uit om je lokale webserver te starten
- Je presentatie kun je bewerken door presentatie.md aan te passen, of, als je wilt, de index.html zelf
- Commit en Push je presentatie in je eigen branch

Standaard is de donkere variant van het template actief, wil je de lichte gebruiken zorg dat je 
quintor.css veranderd in quintor_light.css in de index.html.

Meer info over reveal.js vind je in REVEALJS.md

## Presentatie bewerken
Je presentatie kun je bewerken door het aanpassen van het bestand "presentatie.md".
Hierin staan nu 3 voorbeeld-sheets, sheets worden zoals je kunt zien gescheiden door
3 streepjes ("---") op een regel met zowel daarboven als daaronder een lege regel.
Zo kun je eenvouding meer sheets toevoegen.

De opmaak is in markdown formaat, wil je weten wat hier mee mogelijk is dan kun je
[deze](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) pagina als referentie gebruiken.

Als je je wijzigingen opgeslagen hebt wordt je presentatie automatisch herladen in de browser
en kun je je wijzigingen gelijk bekijken.

## Donker vs. Licht thema
Er is zowel een Donker als een Licht thema beschikbaar, je bent vrij om te kiezen welke van
de twee je wilt gebruiken. Standaard is het donkere thema geselecteerd, als je de lichte variant
wilt gebruiken volg je de volgende stappen.

- Open index.html
- Op regel 10 vind je de volgende code:
```
<link rel="stylesheet" href="css/theme/quintor.css">
```

- Dit vervang je door:
```
<link rel="stylesheet" href="css/theme/quintor_light.css">
```

- Sla het bestand op en je hebt het lichte thema.

Wil je het donkere thema weer gebruiken dan pas je de regel weer aan voor de eerste.

## Wijzigingen committen en pushen
Zodra je wijzigingen gemaakt hebt wil je deze uiteindelijk ook terug stoppen in git.
Dit doe je door middel van een commit en een push. Op de command-line werkt dit als volgt:

```
git commit -a -m "Jouw commit message"
git push
```

"Jouw commit message" kun je aanpassen door een zinvol bericht, bijv. "Titelpagina en introductie toegevoegd"
Hou het bericht in ieder geval beknopt.

## Verder werken
Een volgende keer kun je verder werken door weer diezelfde `npm start` uit te voeren en "presentatie.md" verder
bij te werken. Vergeet niet te committen en te pushen aan het eind :)

## Werken met meerdere personen
Uiteraard kun je ook met meerdere personen aan je presentatie werken. De stappen zoals hierboven genoemd gelden
voor elk persoon binnen je presentatie. Het is handig om, als je verder werkt aan je presentatie, vooraf een 
`git pull` uit te voeren. Hiermee haal je de laatste wijzigingen op uit de git-repository. Nadat je jouw wijzigingen
hebt gedaan kun je weer committen en pushen zoals hierboven beschreven.

Het kan voorkomen dat je tegelijkertijd aan het werk bent geweest, persoon a heeft zijn wijzigingen gecommit en gepushed
en persoon b wil hetzelfde doen. Bij de push van persoon b zul je de melding krijgen dat de repository voorloopt op jouw
lokale werkkopie. Je zult dan een `git pull` moeten uitvoeren. Git zal vervolgens proberen (indien van toepassing) de
verschillende wijzigingen zo goed mogelijk samen te voegen. Als dat lukt kun je alsnog je commit en push doen. 
Mocht het git niet lukken dan krijg een zogenaamd "merge conflict" je zult dan het bestand handmatig moeten bijwerken om
de wijzigingen samen te voegen. De verschillende varianten staan duidelijk gemarkeerd in het bestand. Aan jou de taak
om dit bestand bij te werken zodat het er uit komt te zien zoals het eruit zou moeten zien. Nadat je dit gedaan hebt kun
je alsnog committen en pushen.

## Tot slot
Hieronder nog een paar handige links als referentie:

- [Reveal.js](https://github.com/hakimel/reveal.js)
- [Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

Vragen/Opmerkingen? Laat het weten!

