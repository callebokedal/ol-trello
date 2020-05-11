# ol-trello
Visualisering av Trello-information

## Användning

1. En förutsättning är att du har ett Trello-konto med behörighet för de "boards" du vill hantera
2. Navigera till https://callebokedal.github.io/ol-trello och följ instruktionerna

## Säkerhet
- Denna applikation behöver läs-rättigheter till din Trello-data (ej skriv-rättigheter) för att fungera. Detta är helt enligt Trello's API:er (https://developer.atlassian.com/cloud/trello/guides/rest-api/api-introduction/). 
  - Ingen annan får access, endast sidan i din webbläsare. Koden som körs finns tillgänglig att granska här på https://github.com/callebokedal/ol-trello.
  - Du kan själv ta tillbaka accessen (detta görs i Trello).
- Du anger själv vilka domäner som ska få tillgång till din data (via inställningar i Trello). Detta innebär att du har full kontroll på var accessen via API:et är giltigt.
