# Claude Code Zeo Repo

Dit is de gedeelde skills-repo van ons agency. Iedereen die Claude Code gebruikt binnen VS Code kan via deze repo dezelfde skills gebruiken. Skills worden centraal bijgehouden — updates die hier worden gepusht zijn direct beschikbaar voor het hele team.

## Wat zijn skills?

Skills zijn instructiesets die Claude Code uitbreiden met gespecialiseerde kennis en workflows. Denk aan: advertising audits, SEO content plannen, en meer. Je activeert ze met een slash command, bijvoorbeeld `/ads-google` of `/seo-content-cluster`.

---

## Vereisten

Zorg dat je de volgende zaken hebt geïnstalleerd voordat je begint:

1.  **[VS Code](https://code.visualstudio.com/)** (Visual Studio Code)
2.  **[Node.js](https://nodejs.org/)** (Noodzakelijk voor Claude Code)
3.  **Toegang tot deze GitHub repo** (Vraag een admin om je toe te voegen als collaborator)

---

## Installatie & Setup

Volg deze stappen om de werkomgeving in te richten:

### 1. Claude Extension & Login
1.  Open **VS Code**.
2.  Ga naar **Extensions** (icoontje in de zijbalk of `Ctrl+Shift+X`).
3.  Zoek naar **Claude Code for VS** en installeer de extensie.
4.  Log in via het **Webmaster account**.

### 2. Git & Repo installatie via Claude
Je hoeft geen ingewikkelde terminal-commando's te gebruiken. Je kunt Claude simpelweg opdracht geven om de omgeving voor je klaar te zetten. Open de Claude chat in VS Code en typ:

* **Stap A:** *"Vraag aan Claude om Git te installeren op dit systeem."*
* **Stap B:** *"Vraag aan Claude om de github repo `https://github.com/webmasterzeo/claude-code-zeo-repo.git` te installeren en te openen."*

### 3. Controleer of het werkt
Zodra de repo is geladen, detecteert Claude automatisch de `.claude/skills/` map. Typ in de chat:

```text
/ads

Als je een advertising audit workflow te zien krijgt, werkt alles.

## Gebruik

Alle skills zijn beschikbaar als slash commands. Typ `/` in Claude Code om een overzicht te zien van beschikbare skills. Enkele voorbeelden:

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

## Up-to-date blijven

Wanneer er skills worden toegevoegd of bijgewerkt, pull je de laatste versie:

```bash
cd claude-code-zeo-repo
git pull
```

Start daarna Claude Code opnieuw om de wijzigingen te laden.

## Problemen?

- **Skills verschijnen niet?** Zorg dat je Claude Code start vanuit de `claude-code-zeo-repo` map, niet vanuit een andere directory.
- **Geen toegang tot de repo?** Vraag een admin om je GitHub-account toe te voegen als collaborator.
- **Verouderde skills?** Draai `git pull` en herstart Claude Code.
