# Access Requests - GitHub Copilot

Detta repository används för att hantera ansökningar om GitHub Copilot-licenser inom Skogforsk.
En förutsättning är att du har ett github konto när du ansöker.

## Så här ansöker du

För att få tillgång till GitHub Copilot:

1. Bekräfta med din chef att du får ansöka om en licens!
   
2. Öppna en ny ärende via följande länk:
   https://github.com/skogforsk/access-requests/issues/new/choose

3. Välj formuläret **"GitHub Copilot - ansökan"**

4. Fyll i:
   - din chefs e-post
   - Ditt GitHub-användarnamn
   - Din arbets-e-post
   - (valfritt) syfte med användningen

## Verifiering

För att kunna tilldela licens behöver vi verifiera att GitHub-kontot tillhör rätt person.

Efter inskickat ärende:
- Vi kontrollerar informationen
- Du kan bli ombedd att bekräfta via din arbets-e-post
- Licens tilldelas efter godkännande

## Aktuell status

- Entra custom security attributes är införda för Copilot-spårning.
- Attributset: `SkogforskCopilot`
- Attribut:
   - `copilotSeat` (true/false)
   - `githubUsername`
   - `copilotStatus` (`pending`, `active`, `removed`)
- Nuvarande användare med seat är backfyllda och markerade som `active`.

## Nästa steg

Vi går vidare med att förbättra issue-flödet i GitHub så att godkända ärenden enklare kan driva uppdatering av Entra-attribut (mindre manuell hantering).

Målbild:
- ett tydligt onboardingsflöde från issue → verifiering → seat → Entra-attribut
- bättre spårbarhet i ärenden
- enklare uttag av rätt målgrupp för Copilot-kommunikation

## Kontakt

Vid frågor: patrick.livbom@skogforsk.se
