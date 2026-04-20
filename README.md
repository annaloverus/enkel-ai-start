# Enkel AI-start

En praktisk guide för dig som vill börja jobba med personliga AI-processer — utan att vara utvecklare.

Det här repot visar hur du sätter upp två verktyg: **Obsidian** (din kunskapsbas) och **Claude Code** (din AI-assistent). Tillsammans bildar de ett system där du kan tänka, skriva och automatisera på ett sätt som passar hur just du jobbar.

---

## Vad gör de två verktygen?

### Obsidian
Obsidian är en app för anteckningar och kunskapshantering. Du skriver i vanliga Markdown-filer (text) som sparas lokalt på din dator (eller i iCloud/Dropbox om du vill). Det finns ingen inlåsning — filerna är dina.

I ett AI-arbetsflöde fungerar Obsidian som **minnet**. Här samlar du anteckningar, utkast, veckoplaner, budgetar och allt annat du vill att Claude ska kunna läsa och skriva till. Eftersom det är vanliga textfiler kan Claude läsa och uppdatera dem direkt.

### Claude Code
Claude Code är Anthropics officiella app för att jobba med Claude som en aktiv assistent — inte bara en chattbot. Du kan ge Claude tillgång till filer på din dator, köra kommandon och bygga automatiserade flöden.

I ett personligt arbetsflöde fungerar Claude Code som **utföraren**. Den läser dina Obsidian-filer, skriver nya anteckningar, hjälper dig tänka igenom beslut och kan utföra återkommande uppgifter (som att sammanfatta veckan eller kategorisera utgifter).

---

## Installation

### 1. Installera Obsidian

1. Gå till [obsidian.md](https://obsidian.md) och ladda ner appen för din plattform.
2. Öppna appen och skapa ett nytt **valv** (en mapp som Obsidian använder som sin databas).
   - Lägg den i en mapp du känner dig trygg med att ge AI tillgång till, t.ex. `~/Dokument/AI/Obsidian/` eller en iCloud/OneDrive-mapp om du vill komma åt anteckningarna även på telefonen.
3. Skapa din första fil — t.ex. `start.md` — och börja skriva.

Det finns mycket att utforska i Obsidian, och hur man tänker kring att strukturera sin kunskap i filer och mappar, men du behöver inte göra det på en gång. En enkel mappstruktur räcker för att komma igång.

### 2. Installera Claude Code

1. Gå till [claude.ai/code](https://claude.ai/code) och ladda ner **skrivbordsappen** för Mac eller Windows.
2. Logga in med ditt Anthropic-konto (eller skapa ett på [anthropic.com](https://anthropic.com)).
3. Öppna Claude Code och välj en **arbetsmapp** — välj samma mapp som ditt Obsidian-valv (Obsidian), eller en mapp ovanför den (AI).

Claude Code ser alla filer i den mapp du öppnar. Det är det som gör att den kan läsa och skriva dina anteckningar.

---

## Kom igång

När båda verktygen är installerade kan du börja enkelt:

1. Skapa en fil i Obsidian som heter `idag.md` och skriv tre saker du vill göra.
2. Öppna Claude Code med din Obsidian-mapp som arbetsmapp.
3. Skriv: *"Läs min idag.md och hjälp mig prioritera."*

Det är allt. Därifrån bygger du vidare i din egen takt.

---

## Nästa steg

I det här repot finns snart också ett par exempelskills — återanvändbara instruktioner som du kan ge Claude för att automatisera återkommande uppgifter:

- [`skills/weekly-review.md`](skills/weekly-review.md) — guidad veckoplanering
- [`skills/write-post.md`](skills/write-post.md) — hjälp att skriva ett inlägg

---

## Frågor?

Det här repot underhålls av [Anna Loverus](https://www.annaloverus.com). Hittar du något som är fel eller otydligt — skapa gärna en issue i Github (eller skriv till mig på Linkedin).
