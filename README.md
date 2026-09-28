# Společná pravidla spolupráce

Veřejná dohoda a vzory pro repozitáře účtu olomouckyorel.

- [CONTRIBUTING.md](CONTRIBUTING.md): plná dohoda pro lidi a agenty.
- [AGENTS.template.md](AGENTS.template.md): společné agentní jádro v1.0.0 a vzor projektové části.
- [pull_request_template.md](pull_request_template.md): výchozí popis PR „Pro člověka / Pro agenta“.
- [AGENTS.md](AGENTS.md): pokyny pro úpravy tohoto repozitáře.

## Zavedení do projektu

1. Převezmi schválený společný blok ze vzoru do kořenového AGENTS.md.
2. Mimo označený blok uveď permalink vzoru v konkrétním commitu. Doplň skutečné projektové příkazy, dokumenty a hranice; prázdná pole vynech.
3. Při přijetí do společného firemního repozitáře respektuj jeho místní dohodu. Osobní preference jednotlivce patří do jeho profilu, ne automaticky do týmových pravidel.
4. Ověř načtení v nástroji, který se skutečně používá, a chování na malé úloze. Další instrukční formáty přidávej jen při doložené potřebě.

GitHub používá výchozí CONTRIBUTING a PR šablony tam, kde repo nemá vlastní. Nekopíruje je do checkoutu a automaticky takto nedistribuuje AGENTS.md. Agent musí lokální pravidla načíst a popis PR vyplnit i přes API. Viz [GitHub documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

## Aktualizace

Zdroj společného bloku je tato šablona. Měň ji spolu s odpovídající částí CONTRIBUTING.md v jednom PR a zvyš verzi. Po lidském merge připrav aktualizace aktivních projektů přes jejich PR; přenes jen společný blok a zachovej projektovou část. Kopie se samostatně neupravují a nová verze se neaktivuje vzdáleným načtením bez přijetí změny v projektu.

Stav úkolů patří do PR/Issues. Tento veřejný repozitář není úložištěm interních projektových seznamů, přístupů ani provozní evidence.
