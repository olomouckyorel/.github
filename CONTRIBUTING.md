# Pravidla spolupráce

GitHub je společný zdroj pravdy pro rozpracovanou i dokončenou práci. Tato pravidla platí pro lidi i automatizované agenty.

## Před zahájením práce

1. Zkontroluj otevřené Pull Requesty včetně Draft PR.
2. Pokud už existuje Pull Request pro stejný úkol, pokračuj v jeho větvi. Nevytvářej souběžnou kopii stejné práce.
3. Jinak vytvoř novou větev z aktuální výchozí větve na GitHubu (`main`, případně `master`).
4. Zachovej všechny nesouvisející změny a používej oddělené pracovní prostředí.

## Uložení práce

- Rozpracovaná práce: commit, push a Draft Pull Request.
- Hotová práce: commit, push a Pull Request připravený ke kontrole.
- Další změny posílej do stejné větve a stejného Pull Requestu.
- Poznámky a budoucí nápady ukládej jako GitHub Issue.

## Běžné pokyny vlastníka

- **„Ulož to jako rozpracované.“** Znamená: udělej commit, pushni stejnou pracovní větev, vytvoř nebo aktualizuj Draft Pull Request a doplň předávací shrnutí. Pull Request neoznačuj jako připravený a nemerguj ho.
- **„Připrav to k začlenění.“** Znamená: dokonči dohodnutý rozsah, proveď přiměřené kontroly, udělej commit, pushni pracovní větev, vytvoř nebo aktualizuj Pull Request připravený ke kontrole a doplň konečné shrnutí. Pull Request nemerguj.

## Předání práce dalšímu agentovi

Každý Pull Request, včetně Draft PR, musí obsahovat stručné a průběžně aktualizované shrnutí:

- **Cíl:** Co se řeší a proč.
- **Hotovo:** Co už bylo provedeno.
- **Aktuální stav:** Co funguje, co bylo ověřeno a s jakým výsledkem.
- **Zbývá:** Co ještě není dokončeno.
- **Další krok:** Kde a jak má pokračovat další agent.
- **Rizika a blokery:** Známé problémy, nejistoty nebo potřebná rozhodnutí.

Před ukončením práce agent toto shrnutí aktualizuje podle skutečného stavu. Nesmí tvrdit, že je něco hotové nebo ověřené, pokud pro to nemá důkaz.

## Bezpečnost a schválení

- Nikdy nezapisuj přímo do výchozí větve.
- Nepoužívej force-push ani nepřepisuj historii.
- Neukládej hesla, API klíče, tokeny ani jiné citlivé údaje.
- Nemaž větve, repozitáře ani cizí práci bez výslovného pokynu.
- Před předáním stručně popiš změny a provedené kontroly.
- Pull Request kontroluje a merguje vlastník účtu.
- Pokud jsou pokyny nejasné nebo se dostanou do konfliktu, zastav se a požádej o rozhodnutí.

Po mergi GitHub pracovní větev automaticky odstraní.
