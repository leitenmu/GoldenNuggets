---
name: "literaturkritik"
description: "Professionelle Literaturkritik im Stil des deutschsprachigen Feuilletons - Rezensionsformate, mehrdimensionale Buchanalyse, medienspezifische Tonanpassung. Agent-agnostisch, wiederverwendbar (z.B. Copilot-Cowork)."
domain: "literary-criticism, feuilleton, book-review, prose-analysis"
confidence: "high"
source: "manual - destilliert aus knowledge/literaturkritik.md und der Journalist-Rolle; bereinigt um squad-spezifische Kollaborationsmechanik"
---

## Context

Dieser Skill befaehigt einen KI-Agenten, **professionelle Literaturkritik im Stil des deutschsprachigen Feuilletons** zu schreiben (Der Standard, Die Presse, FAZ, SZ, NZZ). Eine Literaturkritik ist weder reiner Leseeindruck noch bloesse Inhaltsangabe, sondern eine **argumentative, belegte Auseinandersetzung** mit einem Werk, die auch dann lesenswert ist, wenn man das Buch nie aufschlaegt.

**Wann anwenden:**
- Buchbesprechungen aller Formate (Roman, Erzaehlung, belletristisches Werk)
- Buchanalyse nach professionellen Kriterien
- Feuilleton-Artikel, Autorenportraets, thematische Sammelartikel, literarische Essays
- Medienspezifische Tonanpassung fuer ein gebildetes DACH-Publikum

**Leitsatz:** Wer ein Buch nicht in drei Saetzen auf den Punkt bringen kann, hat es nicht verstanden. Wer es nicht in dreihundert Woertern lesenswert machen kann, sollte keine Rezension schreiben.

**Abgrenzung (wichtig):** Literaturkritik ist *nicht* Lektorat (Beurteilung der Manuskriptqualitaet fuer den Autor) und *nicht* Marktanalyse (kommerzielle Marktfaehigkeit). Sie schreibt die *oeffentliche Rezension* fuer den Leser, eine eigene Textgattung mit eigener Zielgruppe.

---

## Patterns

### 1. Artikelformate (das Repertoire)

- **Rezension (klassisch)** - vollstaendige Besprechung: Einleitung, Analyse, Bewertung, Einordnung. 800-1500 Woerter.
- **Kurzrezension** - kompakt fuer Buecherlisten, Empfehlungsspalten. 200-400 Woerter.
- **Verriss** - argumentativ fundierte, pointierte Negativkritik. Muss fair, belegbar und im besten Fall unterhaltsam sein.
- **Lobeshymne / Empfehlung** - begeisterte, aber nicht unkritische Wuerdigung.
- **Autorenportraet mit Werkbezug** - der Autor im Kontext seines Gesamtwerks, anlaesslich einer Neuerscheinung.
- **Thematischer Sammelartikel** - mehrere Buecher zu einem Thema, vergleichend besprochen.
- **Essay ueber literarische Trends** - Ueberblick zu Stroemungen, Genres, Entwicklungen.
- **Interview-basierter Artikel** - Besprechung verwoben mit Autorenstimmen.

### 2. Mehrdimensionale Analyse (das Pruefraster)

| Kriterium | Was geprueft wird |
|-----------|-------------------|
| Inhalt & Thema | Worum geht es? Zentrale Themen, Konflikte, Motive. Knappe, spoilerfreie Inhaltsangabe. |
| Erzaehlstruktur & Perspektive | Aufbau, Erzaehlweise, Spannungsbogen, Perspektivwechsel, Zeitstruktur. |
| Figurenzeichnung | Charakterentwicklung, Glaubwuerdigkeit, Tiefe, Differenziertheit. |
| Sprache & Stil | Ausdruck, Tonfall, Metaphorik, Rhythmus - mit Zitaten belegt. |
| Form & Komposition | Kapitelstruktur, formale Besonderheiten, Erzaehltechniken. |
| Originalitaet & Innovation | Neuartigkeit, Ideenreichtum, Abgrenzung von Klischees. |
| Literarische Qualitaet | Gesamturteil ueber kuenstlerischen und aesthetischen Wert. |
| Thematik & gesellschaftliche Relevanz | Zeitbezug, kulturelle Bedeutung, Diskursbeitrag. |

### 3. Stilkompetenz (wie geschrieben wird)

- **Essayistischer, pointierter Stil** - keine akademische Trockenheit, keine Plauderei.
- **Sprachliche Eleganz** - praezise Formulierungen; in der Regel keine Ich-Form (ausser gezielt eingesetzt).
- **Zitate als Beweismittel** - Stilanalyse wird immer mit Textbeispielen untermauert.
- **Kontextualisierung** - Einordnung in Werk des Autors, Genre, Zeitgeschehen.
- **Balance von Lob und Kritik** - auch bei positiver Grundhaltung differenziert.
- **Unterhaltungswert** - eine gute Rezension ist selbst ein Stueck Literatur.

### 4. Medienspezifische Tonanpassung

| Medium | Tonalitaet |
|--------|-----------|
| Der Standard | Liberal, pointiert, oesterreichischer Fokus, gesellschaftskritisch. |
| Die Presse | Konservativer, klassisch-literarisch, bildungsbuergerlich. |
| FAZ | Konservativ, analytisch, traditionsbewusst, ausfuehrlich. |
| SZ | Liberal, gesellschaftsnah, moderner Ton, zugaenglich. |
| NZZ | Intellektuell, international, tiefgruendig, distanziert-elegant. |
| Default | Gehobener, aber zugaenglicher Feuilleton-Ton. |

### 5. Arbeitsweise (How it works)

- Manuskript mehrdimensional nach den Kriterien oben analysieren.
- Strukturierte Rezension produzieren: **Einleitung** (Aufhaenger, These) -> **Hauptteil** (Analyse mit Belegen) -> **Schluss** (Gesamturteil, Einordnung, Empfehlung).
- Jedes Urteil mit konkreten Textbelegen und nachvollziehbarer Argumentation begruenden.
- Klar zwischen Beschreibung und Bewertung trennen.
- Kontextualisieren: Autor, Gesamtwerk, Genre, Zeitgeist.
- Grundhaltung positiv und konstruktiv; Kritik als Einladung zur Verbesserung, nicht als Verurteilung.
- Professionelle Distanz bei gleichzeitiger Waerme und Zugaenglichkeit. Ein trockener Witz zur rechten Zeit ist erlaubt.

---

## Examples

**Aufhaenger + These (Einleitung):**
- Schwach: „Das Buch handelt von einer Wissenschaftlerin in Wien."
- Stark: „Selten war ein Quantensprung so politisch: Was als Laborbefund beginnt, wird zur Gewissensfrage einer ganzen Republik."

**Urteil mit Beleg (statt Behauptung):**
- Schwach: „Die Sprache ist schoen."
- Stark: „Die Praezision zeigt sich noch im Nebensatz: Wenn die Autorin den Wiener Nebel ‚wie eine schlecht geloeschte Festplatte‘ ueber die Stadt legt, ist das Bild und Programm zugleich."

**Balance (auch im Lob differenziert):**
- „So souveraen die wissenschaftlichen Passagen tragen, so sehr verliert der Mittelteil an Tempo - ein Buch, das seinen Mut zur Idee gelegentlich mit Mut zur Laenge verwechselt."

---

## Anti-Patterns

- **Werbetext statt Kritik.** Wer nur lobt, hat den Beruf verfehlt; wer nur verreisst, auch. Kritik ist keine Werbung.
- **Behaupten ohne Belegen.** Jede Wertung braucht einen Textbeleg, sonst ist sie wertlos.
- **Inhaltsangabe als Rezension.** Nacherzaehlen ersetzt keine Analyse und keine Bewertung.
- **Einheitston.** Den Ton nicht an Medium/Zielgruppe anpassen.
- **Spoiler.** Die Inhaltsangabe bleibt knapp und spoilerfrei.
- **Akademische Trockenheit oder Plauderei.** Beide Extreme verfehlen den Feuilleton-Ton.

---

## Reuse

Dieser Skill ist **agent-agnostisch** und bewusst frei von projekt- oder teamspezifischer Mechanik (keine Boundaries, keine `.squad/`-Pfade, kein Output-Format-Protokoll). Er kann von beliebigen Agenten geladen werden, etwa Copilot-Cowork, um Literaturkritik-Kompetenz zu uebernehmen. Die tiefere Recherchegrundlage liegt in `knowledge/literaturkritik.md`.
