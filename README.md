# Who's your GOAT?

## About WYG

this app will help you figure out who truly is your favourite footballer of all time, as well as your top 100 (other options tend to only find your top #1, but I wanna go ABOVE and BEYOND)

this will be done using comparisons between players. Two players will be displayed, and you choose who your favourite is, We record this choice and present two different players. Each win and loss in comparisons for each player will be tracked, and all players will be ranked using an elo system. Utilising this elo system, the users will eventually end up with a list of their favourite players, from number 1 onwards, with the list perfecting and refining itself over time as the user compares mroe times.

There will be two modes, both usign the same comparison loop system. The first mode will help the user determine their own personal subjective favourite player (who is YOUR goat?). The second mode uses a seperate elo system to help the user discover who they believe the objective best plaer is (who is THE goat?). The resulting two different rankings will provide many different statistical analysis opportunities.

## Planned features

- core 1v1 + live rankings
- seperate rankings for the two modes
- player data will come from Wikidata
- if honours/trophies/stats about any player aren't 100% certain, they will be left out (accuracy rule)
- use photos of players when available, but also have initials used in the photo slot when not available
- using the system as a guest (no saving results) is an option
- accounts
- extra features include an undo, filters and a sharecard (compact concise display of info such as your top players in each mode/category/position,. making it customisable for what the user wants to be sharing)
- smart matchups will kick in afteer inital matchups are completed, where the system will select players for matchups that actually matter, or would heavily help/impact ratings as they stand
- the top-n detection feature will alert the user when the users top n (could be top 1, 10, 25, 50, 100 etc.) players in a given category has hit a point where changes likely wont happen as the user continues comparing.

## Tech Stack

- Frontend: React, TypeScript, Vite
- Backend: C# / ASP.NET Core Web API
- Database: PostgreSQL, with entity framework core
- Auth: ASP.NET Core Identity
- Testing: xUnit, Vitest, React Testing LIbrary, Playwright
- Devops: Docker, Docker Compose, Github actions
- Hosting: Azure
- Design: tbd

## General Version Roadmap

- [ ] v0.1: core loop function: have two modes, random player comparison matchups, elo ratings, live rankings
- [ ] v0.2: real player data from WikiData with photos/initials ad accuracet certain data on trophies/honours/stats
- [ ] v0.3: accounts
- [ ] v0.4: smart matchups plus 'top-n has been settled' detection
- [ ] v0.5: undo feature, filters, customiseable shareable top-n card
- [ ] v1.0: overall polish, full tests, launch
