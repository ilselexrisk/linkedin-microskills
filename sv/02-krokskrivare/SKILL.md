---
name: linkedin-krokskrivare
description: Skriv 10 krokar (första 1–3 raderna) för ett LinkedIn-inlägg på svenska, baserade på mönster från de bästa B2B-kreatörerna. Använd när ett inlägg behöver en öppning.
---

# LinkedIn Krokskrivare

## Varför den här skillen finns
LinkedIn visar ungefär de första 140 tecknen före "…visa mer". Klickar ingen där läser ingen resten. Toppkreatörer som Justin Welsh och Jasmin Alić skriver ofta kroken **sist** – när de vet vad inlägget faktiskt levererar.

## Indata
- **Ämne eller utkast:** vad inlägget handlar om (helst ett utkast).
- **ICP-kort** (från `linkedin-icp-definierare`), eller åtminstone vem det riktar sig till och vilken smärta det tar upp.
- **Bevis:** verkliga siffror, tidsramar eller resultat.

## Regeln
En krok är ett **löfte**. Inlägget måste hålla det.

## 8 krokmönster
| # | Mönster | Form | Inspirerat av |
|---|---|---|---|
| 1 | **Tät trovärdighet** | Resultat med exakta siffror + ny utmaning + öppen loop som slutar med ":" | Adam Robinson |
| 2 | **Mitt i scenen** | Börja i ett specifikt ögonblick – plats, tid, vad någon sa | Lara Acosta, Dave Gerhardt |
| 3 | **Löfte + återkrok** | Rad 1 = löftet. Rad 2–3 = varför det spelar roll | Jasmin Alić |
| 4 | **Motvals** | "[Vanlig sanning] stämmer inte." + skälet på rad 2 | Chris Walker |
| 5 | **Skyltning** | Hur du vet: "Efter [N] [saker] har jag lärt mig…" | Jasmin Alić |
| 6 | **Specifik lista** | "[N] [saker] som [konkret resultat] på [tid]:" | Justin Welsh |
| 7 | **Före / efter** | "[Månad/år]: [dåligt läge]. Idag: [bra läge]." | Vanligt kreatörsformat |
| 8 | **Överraskande fakta** | En verklig siffra/nyhet + "så här påverkar det [ICP]" | Justin Welsh, Ruben Hassid |

Undvik "Har du någonsin undrat…?"-frågor. Data från 309 000 inlägg (Ordinal) visar att berättelsekrokar slår frågekrokar.

## Svensk ton – viktigt
- **Lagom slår hype.** Översätt inte amerikanska krokar rakt av. "Det här förändrade ALLT 🚀" fungerar sämre på svenska; "Det här ändrade hur vi säljer." fungerar bättre.
- Inga superlativ du inte kan backa upp ("världens bästa", "galet").
- Du-tilltal, vardaglig svenska, korta ord. Undvik onödiga anglicismer ("leverage", "game changer") om inte målgruppen själv pratar så.
- Torr humor och självdistans fungerar ofta bättre än dramatik.

## Process
1. Hitta den **enda** sak läsaren ska ta med sig. Skriv den som en mening.
2. Skriv 10 krokar med minst 6 olika mönster.
3. Kontrollera varje krok:
   - Under ~140 tecken före första radbrytningen?
   - Innehåller något **specifikt** (siffra, namn, tidsram)?
   - Talar till ICP:ns smärta, inte till "alla"?
   - Lever texten upp till den?
   - Låter den som en svensk människa, inte som en översättning?
4. Rangordna topp 3 med en rads motivering.

## Utdataformat
```
KÄRNBUDSKAP: …

KROKAR
1. [mönster] …
…
10. [mönster] …

TOPP 3
#… – varför
#… – varför
#… – varför
```

## Undvik
- Klickbete som texten inte lever upp till.
- Emojiväggar, VERSALER, "🚨".
- Påhittade siffror. Saknas data – använd en berättelsekrok.

## Lämnar över till
`linkedin-berattelseinlagg` (om texten saknas) eller `linkedin-inlaggsformaterare` (om den finns).
