# WriterAgent
Program and database to aid writers on the information included in their book (people, relations, characteristics, locations,...)
WriteAgent wants to be a program to help writers ¡, specially when they have several subjects, locations, relations, etc. and the idea is to help them to track the evolution trhough the novel.
Written with ChatGPT Codex.
# WriterAgent 🧠✍️

Eina per a escriptors per gestionar escenes, personatges, llocs i línies temporals, amb vista tipus “timeline” i metadades consultables.

## Estat
MVP en construcció. Busquem col·laboradors!

## Objectius (MVP)
- [ ] Models: Escena, Personatge, Lloc, Relacions
- [ ] Persistència SQLite
- [ ] UI mínima: llistar/crear escenes
- [ ] Import/export JSON
- [ ] Tests bàsics

## Com provar
1. Requisits: .NET 8 SDK, SQLite
2. `git clone ... && cd WriterAgent`
3. `dotnet build`
4. `dotnet test`
5. Executa `WriterAgent.App`

## Contribuir
Mira [CONTRIBUTING.md](CONTRIBUTING.md) i obre una *issue* amb la teva idea. Etiquetes *good first issue* disponibles.

## Llicència
[MIT](LICENSE)
