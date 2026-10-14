# Kozijnkompas

Digitale keuzetool voor materiaal- en isolatieoplossingen voor bestaande houten kozijnen in rijksmonumenten.

**Haci Koca & Omar Irchouq** · Built Environment · Projectmanagement · Hogeschool van Amsterdam  
Afstudeeratelier **100% Circulair – Nooit Slopen**

## Status

Werkend onderzoeksprototype, versie 1. De invoer, selectie, vergelijking en voorlopige onderzoeksrichting zijn aanwezig. Er zijn geen verzonnen technische scores, grenswaarden of automatische voorkeursoplossingen. De focus ligt op het volledige bouwdeel, niet alleen het glas.

## Bestanden

| Bestand | Inhoud |
|---|---|
| `index.html` | Basisstructuur, hoofdmenu en voettekst |
| `style.css` | Vormgeving en mobiele weergave |
| `app.js` | Pagina-inhoud, invoer, varianten, vergelijking en lokale opslag |

Geen installatie van pakketten of bouwstap nodig. Google Fonts is optioneel; bij geen verbinding worden systeemlettertypen gebruikt.

## Website lokaal bekijken

Download de repository via **Code → Download ZIP**, pak deze uit en open `index.html` in een browser. Voor een vaste lokale omgeving, gebruik vanuit deze map met Python 3:

```sh
python -m http.server 8000
```

Open vervolgens http://localhost:8000. Afhankelijk van je installatie heet het commando `python3` of `py`.

Invoer en feedback worden lokaal in de browser opgeslagen. Ze worden niet automatisch gedeeld met de andere onderzoeker.

## Samenwerken via GitHub

1. Begin met de nieuwste versie van `main`.
2. Maak voor een wijziging een eigen branch, bijvoorbeeld `haci-invoer` of `omar-varianten`.
3. Pas de bestanden aan en controleer de website lokaal.
4. Sla de wijziging op met een duidelijke commitbeschrijving.
5. Open een pull request naar `main`: hiermee leg je de wijziging ter controle voor.
6. Laat de ander de wijziging bekijken en voeg deze daarna samen.
7. Haal de nieuwe `main` op voordat je verder werkt.

Gebruik ieder een eigen account. GitHub bewaart versiegeschiedenis; jullie typen niet automatisch tegelijk in hetzelfde document. Werk bij voorkeur niet tegelijkertijd aan dezelfde regels in `app.js`.

## Werken met Codex

Open een lokale kopie van deze repository in Codex, of selecteer deze repository in een beschikbare Codex-cloudomgeving. Een GitHub-koppeling in deze chat betekent niet automatisch dat de andere gebruiker of elke Codex-omgeving al toegang heeft; ieder stelt de eigen toegang in.

Beschrijf een concrete wijziging, bijvoorbeeld:

> Pas alleen de tekst op de startpagina aan. Behoud de bestaande werking en voeg geen technische prestaties of scores toe.

Geef Codex altijd aan welke onderzoeksgegevens zijn onderbouwd. Controleer voorgestelde wijzigingen voordat je ze samenvoegt.

## Controle bij wijzigingen

- Start → invoer → minimaal twee varianten → vergelijking → resultaat.
- Lege waarden blijven onbekend; ze worden niet als nul verwerkt.
- De bestaande situatie blijft als referentie zichtbaar.
- Een eigen voorkeur blijft herkenbaar als gebruikerskeuze.
- Controleer mobiele weergave, toetsenbordbediening, afdrukken en downloads.
- Bij een lokale Node.js-installatie: `node --check app.js`.

De oorspronkelijke versie is gecontroleerd op JavaScript-syntaxis, paginarendering en basislogica. Een volledige visuele browsertest en professionele gebruikerstest moeten nog plaatsvinden.

## Onderzoeksgegevens nog nodig

- Definitieve varianten en complete opbouw per variant.
- Materiaalinventaris: bestaand, behouden, verwijderd en toegevoegd.
- Eenheid en systeemgrens voor materiaalgebruik.
- Thermische indicator en bepalingsmethode voor de volledige opbouw.
- Productgegevens met bron, datum, pagina en toepassingsvoorwaarden.
- Onderbouwde vergelijkingsregels en feedback van professionals.

## Online publicatie

Bestaande privéwebsite: https://kozijnkompas-haci-omar.alightshell.chatgpt.site

Deze GitHub-repository is een overdracht van de huidige websitecode. **Er is nog geen automatische verbinding tussen GitHub en de bestaande online website.** Een commit op GitHub verandert die website dus niet vanzelf. Voor online wijzigingen is een afzonderlijke publicatiestap nodig.

## Bronnen en afbakening

Bronverwijzingen staan in de website. Het item ‘Bronnen’ is op verzoek uit het hoofdmenu verwijderd; de broninhoud is behouden. Gebruik APA-7, controleer paginanummers en gebruik bronlinks zonder trackingparameters.

Het prototype ondersteunt voorselectie en vergelijking. Het is geen constructieberekening, volledige vergunningtoets, complete kostenraming of definitief uitvoerings- of restauratieadvies.
