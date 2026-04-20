# Enkel AI-start

En praktisk guide för dig som vill börja jobba med personliga AI-processer — utan att vara utvecklare.

Det här repot är ett startpaket. Du laddar ner det, öppnar det i Claude Code och pekar det mot ditt Obsidian-valv. Sedan har du ett system där Claude kan läsa och skriva dina anteckningar, hjälpa dig planera veckan och utföra återkommande uppgifter.

---

## Vad gör de två verktygen?

### Obsidian
Obsidian är en app för anteckningar och kunskapshantering. Du skriver i vanliga textfiler (Markdown) som sparas lokalt på din dator — eller i iCloud/Dropbox om du vill. Det finns ingen inlåsning. Filerna är dina.

I det här systemet fungerar Obsidian som **minnet**. Här samlar du anteckningar, utkast, veckoplaner och allt annat du vill att Claude ska kunna läsa och skriva till.

### Claude Code
Claude Code är Anthropics officiella app för att jobba med Claude som en aktiv assistent — inte bara en chattbot. Du öppnar en mapp på din dator, och Claude kan läsa och skriva filer direkt i den.

I det här systemet fungerar Claude Code som **utföraren**. Den läser dina Obsidian-filer, skriver nya anteckningar, hjälper dig tänka igenom beslut och kan utföra återkommande uppgifter med hjälp av skills (mer om det nedan).

---

## Installation

### 1. Installera Obsidian

1. Gå till [obsidian.md](https://obsidian.md) och ladda ner appen.
2. Öppna appen och skapa ett nytt **valv** — det är bara en vanlig mapp som Obsidian använder som sin bas.
   - Förslag: `Dokument/AI/Obsidian/` eller en iCloud/Dropbox-mapp om du vill komma åt anteckningarna på telefonen också.
3. Skapa en första fil och börja skriva. Det räcker.

### 2. Installera Claude Code

1. Gå till [claude.ai/code](https://claude.ai/code) och ladda ner **skrivbordsappen** för Mac eller Windows.
2. Logga in med ditt Anthropic-konto (eller skapa ett på [anthropic.com](https://anthropic.com)).

### 3. Ladda ner det här startpaketet

Ladda ner (klona) det här repot till din dator. Om du inte är van vid Git: klicka på den gröna knappen **Code** uppe till höger på den här sidan och välj **Download ZIP**. Packa upp mappen och lägg den någonstans du hittar den, t.ex. `Dokument/AI/enkel-ai-start/`. Du kan döpa den till något roligare.

### 4. Öppna startpaketet i Claude Code

Öppna Claude Code och välj `enkel-ai-start/` (eller vad du döpte den till) som arbetsmapp. Nu ser Claude alla filer i den mappen — inklusive dina skills, jag kommer berätta mer om dem snart.

### 5. Peka Claude mot ditt Obsidian-valv

Öppna filen `CLAUDE.md` i startpaketet och fyll i sökvägen till ditt Obsidian-valv. Det är den instruktion Claude läser varje gång du startar en ny session.

---

## Mappstruktur

```
AI/
├── enkel-ai-start/        ← det här repot, öppnas i Claude Code
│   ├── CLAUDE.md          ← dina instruktioner till Claude
│   └── skills/            ← återanvändbara kommandon
│       ├── weekly-review.md
│       └── meeting-prep.md
└── Obsidian/              ← ditt Obsidian-valv
    └── (dina anteckningar)
```

---

## Skills

Skills är instruktionsfiler som du anropar med ett snedstreck, t.ex. `/weekly-review`. Claude läser filen och utför uppgiften steg för steg.

Det här startpaketet innehåller två exempelskills:

- [`skills/weekly-review.md`](skills/weekly-review.md) — guidad veckoplanering som läser och skriver dina veckofiler i Obsidian
- [`skills/meeting-prep.md`](skills/meeting-prep.md) — hjälp att förbereda inför ett möte, med genomtänkta diskussionspunkter och agenda

Du kan redigera dem direkt, eller lägga till egna.

---

## Kom igång

1. Installera Obsidian och skapa ett valv.
2. Installera Claude Code.
3. Ladda ner det här repot och öppna mappen i Claude Code.
4. Fyll i ditt Obsidian-valv i `CLAUDE.md`.
5. Skriv `/weekly-review` och se vad som händer.

**En sak att tänka på:** Claude läser de filer du pekar den på. Be den aldrig analysera dokument från okända källor om du inte är beredd på att innehållet kan försöka påverka hur den beter sig med dolda instruktioner. Skills kan du lägga till från källor du litar på — men granska alltid en skill-fil innan du använder den. Det är vanlig text och tar inte många sekunder.

---

## Frågor?

Det här repot underhålls av [Anna Loverus](https://www.annaloverus.com). Hittar du något som är fel eller otydligt — skapa gärna en issue på GitHub eller skriv till mig på LinkedIn.
