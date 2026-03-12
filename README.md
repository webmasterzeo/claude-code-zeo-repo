# Claude Code Zeo Repo

Dit is de gedeelde skills-repo van ons agency. Iedereen die Claude Code gebruikt kan via deze repo dezelfde skills gebruiken. Skills worden centraal bijgehouden — updates die hier worden gepusht zijn direct beschikbaar voor het hele team.

## Wat zijn skills?

Skills zijn instructiesets die Claude Code uitbreidt met gespecialiseerde kennis en workflows. Denk aan: advertising audits, SEO content plannen, en meer. Je activeert ze met een slash command, bijvoorbeeld `/ads-google` of `/seo-content-cluster`.

## Vereisten

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) geïnstalleerd
- [Git](https://git-scm.com/downloads) geïnstalleerd
- Toegang tot deze GitHub repo (vraag een admin om je toe te voegen als collaborator)

## Installatie

### 1. Clone de repo

Open je terminal en kies een locatie waar je de repo wilt neerzetten:

```bash
git clone https://github.com/webmasterzeo/claude-code-zeo-repo.git
```

### 2. Start Claude Code vanuit de repo

```bash
cd claude-code-zeo-repo
claude
```

Dat is alles. Claude Code detecteert automatisch de `.claude/skills/` map en laadt alle skills.

### 3. Controleer of het werkt

Typ in Claude Code:

```
/ads
```

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
