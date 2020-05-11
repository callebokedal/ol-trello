# ol-trello
Vislaulisering av Trello-inforamtion

## Användning

- Man behöver ha ett konto i Trello kopplat till de "boards" man vill visa upp
- Navigera till https://callebokedal.githubpages.com/ol-trello och följ instruktionerna

## Säkerhet
- Denna applikation behöver åtkomst till din Trello-data för att fungera. Detta är helt enligt Trello's API:er (https://developer.atlassian.com/cloud/trello/guides/rest-api/api-introduction/). 
  - Ingen annan får access, endast sidan i din webbläsare. Koden som körs finns tillgänglig att granska här på https://github.com/callebokedal/ol-trello.
  - Du kan själv ta tillbaka accessen (detta görs i Trello).
- Du anger själv vilka domäner som ska få tillgång till din data (via inställningar i Trello). Detta innebär att du har full kontroll på var accessen via API:et är giltigt.
