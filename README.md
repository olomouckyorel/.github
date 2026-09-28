# Společná pravidla spolupráce

Veřejná dohoda a vzory pro repozitáře účtu olomouckyorel.

- [CONTRIBUTING.md](CONTRIBUTING.md): stručná dohoda pro lidské zadání a předání práce.
- [AGENTS.template.md](AGENTS.template.md): jediný zdroj společného agentního jádra v1.1.0 a vzor projektové části.
- [pull_request_template.md](pull_request_template.md): výchozí popis PR „Pro člověka / Pro agenta“.
- [AGENTS.md](AGENTS.md): pokyny pro úpravy tohoto repozitáře.

## Zavedení do projektu

1. Převezmi schválený společný blok ze vzoru do kořenového AGENTS.md.
2. Mimo označený blok uveď permalink vzoru v konkrétním commitu přijatém na výchozí větvi zdrojového repa. Doplň skutečné projektové příkazy, dokumenty a hranice; prázdná pole vynech.
3. Při přijetí do společného firemního repozitáře respektuj jeho místní dohodu. Osobní preference jednotlivce patří do jeho profilu, ne automaticky do týmových pravidel.
4. Ověř načtení v nástroji, který se skutečně používá, a chování na malé úloze. Další instrukční formáty přidávej jen při doložené potřebě.

GitHub používá výchozí CONTRIBUTING a PR šablony tam, kde repo nemá vlastní. Nekopíruje je do checkoutu a automaticky takto nedistribuuje AGENTS.md. Agent musí lokální pravidla načíst a popis PR vyplnit i přes API. Viz [GitHub documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

## Aktualizace

Zdroj společného bloku je AGENTS.template.md. Při změně zvyš verzi a zkontroluj návaznost lidské dohody a PR šablony; neopakuj v nich celé jádro. Po lidském merge připrav aktualizace aktivních projektů přes jejich PR; přenes jen společný blok a zachovej projektovou část. Kopie se samostatně neupravují a nová verze se neaktivuje vzdáleným načtením bez přijetí změny v projektu.

Projektový draft lze připravit souběžně se změnou vzoru. Před jeho přijetím však nejprve merguje člověk zdrojový PR; potom aktualizuj permalink na skutečný commit ve výchozí větvi a znovu porovnej společné bloky. Pokud byl přijat jiný obsah, převezmi jej a zopakuj dotčené kontroly. Pracovní commit návrhu není schváleným zdrojem.

Stav úkolů patří do PR/Issues. Tento veřejný repozitář není úložištěm interních projektových seznamů, přístupů ani provozní evidence.
