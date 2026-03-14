# Claude Code Zeo Repo

Dit is de gedeelde skills-repo van ons agency. Iedereen die Claude Code gebruikt binnen VS Code kan via deze repo dezelfde skills gebruiken. Skills worden centraal bijgehouden — updates die hier worden gepusht zijn direct beschikbaar voor het hele team.

## Wat zijn skills?

Skills zijn instructiesets die Claude Code uitbreiden met gespecialiseerde kennis en workflows. Denk aan: advertising audits, SEO content plannen, en meer. Je activeert ze met een slash command, bijvoorbeeld `/ads-google` of `/seo-content-cluster`.

---

## Vereisten

Installeer het volgende voordat je begint:

- [VS Code](https://code.visualstudio.com/)
- [Node.js](https://nodejs.org/) (LTS versie)
- [Git](https://git-scm.com/downloads)
- Toegang tot deze GitHub repo (vraag een admin om je toe te voegen als collaborator)

---

## Eenmalige installatie

### Stap 1 — Claude Code extensie installeren

1. Open VS Code
2. Ga naar Extensions (`Ctrl+Shift+X` / `Cmd+Shift+X`)
3. Zoek naar **Claude Code** en installeer de extensie
4. Log in via het Webmaster account

### Stap 2 — Repo clonen

1. Druk op `Ctrl+Shift+P` (Mac: `Cmd+Shift+P`)
2. Typ: **Git: Clone**
3. Plak de URL: `https://github.com/webmasterzeo/claude-code-zeo-repo.git`
4. Kies een map op je computer en klik **Open**

### Stap 3 — Skills installeren

1. Druk op `Ctrl+Shift+P` (Mac: `Cmd+Shift+P`)
2. Typ: **Tasks: Run Task**
3. Kies: **Install Skills**
4. Wacht op de bevestiging: `✓ Skills geïnstalleerd!`
5. Herstart de Claude Code extensie in VS Code

De skills zijn nu beschikbaar in **elke map** die je opent in VS Code.

### Stap 4 — Controleer of het werkt

Typ in Claude Code:/ads


Als je een advertising audit workflow ziet, werkt alles.

---

## Up-to-date blijven

Wanneer er nieuwe skills worden toegevoegd of bestaande worden bijgewerkt:

1. Druk op `Ctrl+Shift+P` (Mac: `Cmd+Shift+P`)
2. Typ: **Tasks: Run Task**
3. Kies: **Update Skills**
4. Wacht op de bevestiging: `✓ Skills bijgewerkt!`
5. Herstart de Claude Code extensie in VS Code

---

## Beschikbare skills

| Command | Wat het doet |
|---|---|
| `/ads` | Volledige multi-platform advertising audit |
| `/ads-google` | Google Ads deep analysis |
| `/ads-meta` | Meta (Facebook/Instagram) Ads analyse |
| `/ads-linkedin` | LinkedIn Ads analyse |
| `/ads-tiktok` | TikTok Ads analyse |
| `/ads-youtube` | YouTube Ads analyse |
| `/ads-microsoft` | Microsoft/Bing Ads analyse |
| `/ads-audit` | Account health check over alle platforms |
| `/ads-budget` | Budget allocatie & bidding strategie review |
| `/ads-competitor` | Competitor ad intelligence |
| `/ads-creative` | Creative quality audit |
| `/ads-landing` | Landing page assessment |
| `/ads-plan` | Strategisch advertentieplan opstellen |
| `/seo-content-cluster` | SEO content clusters & keyword research |

---

## Problemen?

- **Skills verschijnen niet?** Voer de **Install Skills** taak opnieuw uit en herstart Claude Code.
- **Geen toegang tot de repo?** Vraag een admin om je GitHub-account toe te voegen als collaborator.
- **Nieuwe skills worden niet geladen?** Voer de **Update Skills** taak uit en herstart
