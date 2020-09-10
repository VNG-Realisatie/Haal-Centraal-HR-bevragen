# Haal Centraal HR bevragen

## Introductie
De Haal Centraal HR Bevragen API is in ontwikkeling in het kader van een verkenning.
Doel van de verkenning binnen het programma Haal Centraal is om de verstrekking van gegevens op basis van API’s, ontworpen vanuit het gebruikersperspectief, te verkennen voor het handelsregister.

Op basis van user stories is een goals canvas opgesteld welke weer de basis vormt voor het API-design. Eventuele bijdrages in de vorm van issues of user stories zijn welkom

 Doel van het programma Haal Centraal is om de verstrekking van basisgegevens aan binnengemeentelijke afnemers te outsourcen naar Landelijke Registraties (RvIG, Kadaster, KVK). Dit moet leiden tot een forse reductie van lokale kopieën bij gemeenten.

In principe willen we voor iedere activiteit op een lokale kopie een Haal Centraal alternatief te bieden in de vorm van een API.

# Planning Haal Centraal
https://eu-rm.roadmunk.com/publish/29a13c572a0dfc79f1d0386fc572e15383afe11f

### Toegevoegde waarde voor gemeenten
- sneller aansluiten afnemers
- goedkoper aansluiten afnemers (x aantal binnegemeentelijke aansluiters x 355 gemeenten)
- lagere investeringen (geen lokale kopie/ gegevensmagazijn)
- lagere beheerkosten (geen gegevensbeheer lokale kopieën)
- hogere ROI: hergebruik API Landelijke Registratie door alle gemeenten
- betere technologie-business alignment (Landelijke Registratie voert sneller een wijziging door dan 355 afzonderlijke gemeenten)
- meer focus op de businessvraag van afnemers (i.p.v. op betrouwbaarheid etc. lokale kopieën)
- maximale compliancy op de gemeentelijke softwaremarkt (aansluiting gemeente x = 100% herbruikbaar in gemeente y)

### Toegevoegde waarde voor leveranciers
- leveranciers kunnen zich richten op het bieden van toegevoegde waarde voor burgers, bedrijven en medewerkers i.p.v. plumbing concerns.

## Context
Haal Centraal is een G5 initiatief (Amsterdam, Rotterdam, Den Haag, Utrecht en Eindhoven). Het concept is getoetst in de BRK pilot van de gemeente Den Haag met het Kadaster op basis van de RSGB bevragingen standaard (voorloper BRP- en BRK-bevragen). De businesscase is gebaseerd op ervaringscijfers van de gemeente Den Haag en de softwareontwikkeling gedurende de pilot.

## HR bevragen
Deze repository beschrijft het project om tot een API voor de Basisregistratie Handelsregister (HR) te komen.

## Documentatie

* HR Bevragen: [Technische specificaties van de **resolved** versie](./specificatie/genereervariant) (Open API Specificaties), [Technische specificaties van de **unresolved** versie](./specificatie) (Open API versie) en ook in [Swagger-formaat](https://petstore.swagger.io/?url=https://raw.githubusercontent.com/VNG-Realisatie/Haal-Centraal-HR-bevragen/develop/specificatie/openapi.yaml)

* Specificaties van de develop versie in [Swagger-formaat](https://petstore.swagger.io/?url=https://raw.githubusercontent.com/VNG-Realisatie/Haal-Centraal-HR-bevragen/develop/specificatie/genereervariant/openapi.yaml)

## Licentie
Copyright &copy; VNG Realisatie 2018
Licensed under the [EUPL](https://github.com/VNG-Realisatie/Haal-Centraal-HR-bevragen/blob/master/LICENCE.md)
