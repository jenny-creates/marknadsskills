# Marknadsskills

Tre skills för Claude som tar ett marknadsteam från idé till lärdom: planera kampanjen, räkna på målet och utvärdera resultatet.

En skill är en instruktion som lär en AI-assistent ett arbetssätt, så att hela teamet får samma kvalitet varje gång i stället för att var och en skriver egna prompter.

## Innehåll

| Skill | När du använder den | Vad du får |
| --- | --- | --- |
| [kampanjbrief](skills/kampanjbrief/SKILL.md) | Före kampanjen | En brief på en sida med mål, målgrupp, budskap, kanaler, tidplan och öppna frågor |
| [rakna-baklanges](skills/rakna-baklanges/SKILL.md) | När målet ska sättas | Hur många affärer, leads och besök som krävs för att nå målet, och om det är rimligt |
| [kampanjutvardering](skills/kampanjutvardering/SKILL.md) | Efter kampanjen | Mål mot utfall, förklaringar och lärdomar som går att återanvända |

De tre hänger ihop. Briefen sätter målen, räkna-baklänges prövar om de håller, och utvärderingen jämför mot samma mål när kampanjen är klar.

## Kom igång

1. Ladda ner mappen för den skill du vill använda.
2. Lägg till den som skill i Claude (Inställningar → Skills), eller lägg mappen i `.claude/skills/` om du använder Claude Code.
3. Skriv som vanligt, till exempel "gör en brief för vår höstkampanj". Claude väljer rätt skill själv.

## Tankarna bakom

- **Inga påhittade siffror.** Alla tre skills ber om teamets egna siffror och märker tydligt ut det som är antaganden.
- **Ärligt före snyggt.** Utvärderingen lyfter missar lika tydligt som framgångar.
- **Kort före komplett.** En brief på en sida blir läst. En på tio sidor blir det inte.
- **Generiskt.** Här finns inga företagsspecifika uppgifter. Lägg till er egen målgrupp, tonalitet och era egna nyckeltal för bäst resultat.

## Bra att veta

Det här är ett personligt projekt utan koppling till någon arbetsgivare.

## In English

Three Claude skills in Swedish for marketing teams: write a one-page campaign brief, work backwards through the funnel from a revenue target, and run an honest post-campaign evaluation.

## Licens

MIT, se [LICENSE](LICENSE).
