# 🤖 KI-Agenten Prompt: CleanLeads OnePager Website

> **Verwendung:** Diesen Prompt vollständig in einen leistungsfähigen LLM eingeben (empfohlen: Claude Sonnet/Opus oder GPT-4o). Der Agent gibt fertigen, sofort lauffähigen HTML-Code aus.

---

## PROMPT

Du bist ein erfahrener Webdesigner, Conversion-Texter und B2B-Marketingstratege mit nachweislicher Expertise im DACH-Raum. Deine Aufgabe ist es, eine vollständige, produktionsreife OnePager-Website als einzelne HTML-Datei zu erstellen – inklusive CSS und JavaScript – für eine Agentur, die automatisierte Neukundengewinnung für Reinigungsunternehmen anbietet.

---

## ZIELGRUPPE

- Inhabergeführte Reinigungsfirmen (5–50 Mitarbeiter)
- Geschäftsführer oder Vertriebsverantwortliche
- Region: Deutschland / DACH-Raum
- Schmerzpunkte: keine Zeit für Akquise, Abhängigkeit von Empfehlungen, unplanbare Auftragslage

---

## TECHNISCHE ANFORDERUNGEN

- Eine einzige, vollständige HTML-Datei (kein externes CSS/JS außer Google Fonts via CDN)
- Vollständig responsiv (Mobile-first)
- Smooth Scroll Navigation
- Sticky Header mit Logo-Platzhalter und Anker-Links
- Animierte Scroll-Effekte (Fade-in beim Scrollen via IntersectionObserver)
- Kontaktformular (Frontend-seitig, mit einfacher Validierung)
- Alle Texte vollständig ausgeschrieben – keine Stichpunkte, keine Platzhalter wie „[TEXT HIER]"

---

## DESIGN-VORGABEN

**Ästhetik:** Refined Corporate Minimalism – seriös, modern, vertrauenswürdig. Denk an das visuelle Niveau von deutschen Unternehmensberatungen oder SaaS-Firmen wie Personio oder Factorial.

**Farben (exakt diese CSS-Variablen verwenden):**

| Variable    | Wert      | Verwendung                        |
|-------------|-----------|-----------------------------------|
| `--primary` | `#1B3A5C` | Dunkelblau – Hauptfarbe           |
| `--accent`  | `#2E7DC4` | Mittelblau – CTAs, Links          |
| `--surface` | `#F4F7FB` | Hellgrau-Blau – Sektionshintergründe |
| `--text`    | `#1A1A2E` | Fast-Schwarz – Fließtext          |
| `--muted`   | `#6B7A8D` | Grau – Sekundärtext               |
| `--white`   | `#FFFFFF` | Weiß                              |

**Typografie:**

- Überschriften: Google Font „Playfair Display" (serif, elegant, Autorität)
- Fließtext: Google Font „DM Sans" (modern, sehr gut lesbar)
- H1: 3.2rem, bold, Zeilenabstand 1.15
- H2: 2.2rem, semibold
- Body: 1.1rem, Zeilenabstand 1.75

**Räumlichkeit:**

- Großzügige Sektions-Abstände (padding: 100px 0)
- Max-Width Container: 1100px, zentriert
- Viel Weißraum – niemals überladen
- Dezente Trennlinien und Hintergrundwechsel zwischen Sektionen

---

## SEITENSTRUKTUR & VOLLSTÄNDIGE TEXTE

### NAVIGATION (Sticky Header)

- **Links:** Logo-Platzhalter „CleanLeads" (Text-Logo, `--primary` Farbe)
- **Rechts:** Anker-Links zu: Problem | Lösung | Prozess | Vorteile | Preise | Kontakt
- **Ganz rechts:** CTA-Button „Erstberatung sichern" (Akzentfarbe, abgerundet)

---

### 1. HERO SECTION

**Hintergrund:** Weiß mit einem feinen, diagonalen Raster-Muster (CSS-only, sehr dezent)

**Badge über der Headline:** Kleines Label „Automatisierte B2B-Leadgenerierung"

**Headline (H1):**
> „Mehr Aufträge für Ihr Reinigungsunternehmen – ohne Kaltakquise, ohne Zeitverlust."

**Subheadline:**
> „Wir identifizieren Ihre Wunschkunden, entwickeln professionelle Erstkontakt-E-Mails und automatisieren den gesamten Outreach – damit Sie sich auf das konzentrieren können, was Sie wirklich gut können: erstklassige Reinigungsleistungen."

**Buttons:**
- Primär (`--accent`): „Kostenlose Erstberatung sichern →"
- Sekundär (Outline): „Wie es funktioniert"

**Vertrauensleiste darunter (Icon + Text, horizontal):**
> ✓ DSGVO-konform &nbsp;&nbsp; ✓ 100% B2B-Fokus &nbsp;&nbsp; ✓ Keine Kaltakquise-Pflicht für Sie

---

### 2. PROBLEM SECTION

**Hintergrund:** `--surface`

**H2:** „Kennen Sie das?"

**Card 1 – Icon: Uhr**
- **Titel:** Keine Zeit für Neukundengewinnung
- **Text:** Als Inhaber oder Geschäftsführer eines Reinigungsunternehmens sind Sie täglich im Einsatz: Mitarbeiter koordinieren, Qualität sichern, Kundengespräche führen. Für systematische Akquise bleibt kaum Zeit – und genau das bremst Ihr Wachstum.

**Card 2 – Icon: Netzwerk/Verbindungen**
- **Titel:** Abhängigkeit von Empfehlungen
- **Text:** Empfehlungen sind wertvoll, aber unzuverlässig. Wenn der nächste Auftrag davon abhängt, ob jemand Sie weiterempfiehlt, haben Sie keine Kontrolle über Ihre eigene Pipeline. Das macht Planung und Wachstum nahezu unmöglich.

**Card 3 – Icon: Kompass/Markt**
- **Titel:** Harter Wettbewerb, wenig Sichtbarkeit
- **Text:** Der Reinigungsmarkt ist stark umkämpft. Potenzielle Gewerbekunden – Büros, Praxen, Einzelhandel – werden von Anbietern überhäuft. Ohne strukturierten, professionellen Erstkontakt gehen Sie im Rauschen unter.

---

### 3. LÖSUNG SECTION

**Hintergrund:** Weiß

**H2:** „Unsere Lösung: Systematische Neukundengewinnung auf Autopilot"

**Einleitungstext:**
> Wir übernehmen den gesamten Prozess der B2B-Kundenakquise für Sie – von der Zielgruppenanalyse bis zur Übergabe qualifizierter Kontakte. Dabei setzen wir auf datenbasierte Leadrecherche, individuelle Kommunikation und kontrollierten, automatisierten Versand. Das Ergebnis: planbare Anfragen, ohne dass Sie einen einzigen Akquise-Anruf tätigen müssen.

**Feature 1 – Zielgenaue Leadidentifikation**
> Wir recherchieren systematisch Unternehmen in Ihrem Einzugsgebiet, die als potenzielle Reinigungskunden in Frage kommen: Bürogebäude, Arzt- und Zahnarztpraxen, Kanzleien, Einzelhändler und Gewerbe. Jeder Lead wird manuell geprüft und qualifiziert.

**Feature 2 – Kuratierte Leadlisten mit vollständigen Kontaktdaten**
> Sie erhalten strukturierte Listen mit Unternehmensname, Branche, Ansprechpartner (sofern öffentlich verfügbar), E-Mail-Adresse und Standort. Keine generischen Datenbanken – nur relevante, geprüfte Kontakte für Ihre Region.

**Feature 3 – Individuell entwickelte Akquise-E-Mails**
> Unsere Texte klingen nicht wie Massenmails – weil sie keine sind. Wir entwickeln auf Ihr Unternehmen zugeschnittene E-Mail-Sequenzen, die professionell, klar und einladend formuliert sind. Kein Spam-Deutsch, keine leeren Versprechen.

**Feature 4 – Kontrollierter, automatisierter Versand**
> Der Versand erfolgt in täglichen Kontingenten (z. B. 30–50 Mails pro Tag), um Zustellbarkeit zu sichern und Spam-Filter zu umgehen. Jede E-Mail enthält eine klare Opt-out-Möglichkeit und entspricht den rechtlichen Anforderungen für gewerbliche B2B-Kommunikation.

---

### 4. PROZESS SECTION

**Hintergrund:** `--surface`

**H2:** „So funktioniert die Zusammenarbeit"

Fünf Prozessschritte in einer horizontalen Timeline (auf Mobile: vertikal), verbunden durch Linien/Pfeile.

**Schritt 1 – Analyse Ihrer Zielregion**
> Im ersten Schritt besprechen wir gemeinsam, in welchem geografischen Gebiet Sie neue Kunden gewinnen möchten, welche Branchen für Sie ideal sind und was Ihr Reinigungsunternehmen von Mitbewerbern unterscheidet. Diese Basis bestimmt die gesamte Kampagnenstrategie.

**Schritt 2 – Professionelle Leadrecherche**
> Unser Team recherchiert systematisch passende Unternehmen in Ihrer Zielregion. Wir filtern nach Branche, Größe und Relevanz und validieren alle Kontaktdaten manuell. Sie erhalten ausschließlich qualifizierte Leads – keine veralteten oder ungeprüften Einträge.

**Schritt 3 – Texterstellung & Freigabe**
> Wir entwickeln eine maßgeschneiderte E-Mail-Sequenz (in der Regel 2–3 Nachrichten), die Ihr Unternehmen professionell vorstellt und zu einer unverbindlichen Kontaktaufnahme einlädt. Sie erhalten die Texte zur Prüfung und Freigabe, bevor der Versand startet.

**Schritt 4 – Automatisierter Kampagnenversand**
> Nach Ihrer Freigabe starten wir den Versand – kontrolliert, DSGVO-konform und mit technischer Optimierung für maximale Zustellbarkeit. Wir überwachen die Kampagne laufend und passen bei Bedarf an.

**Schritt 5 – Übergabe interessierter Kontakte**
> Wer positiv reagiert – sei es durch Rückmeldung, Rückfrage oder konkretes Interesse – wird direkt an Sie weitergeleitet. Sie führen das Gespräch, wir haben die Vorarbeit geleistet.

---

### 5. VORTEILE SECTION

**Hintergrund:** `--primary` (dunkelblau, weißer Text)

**H2:** „Was Sie davon haben"

Vier Vorteils-Kacheln (2×2 Grid, weiße Cards auf dunklem Hintergrund):

**Vorteil 1 – Icon: Kalender – Planbare Neukundenanfragen**
> Statt auf Empfehlungen zu warten, erhalten Sie regelmäßig Rückmeldungen von potenziellen Kunden – kalkulierbar und skalierbar nach Ihren Wachstumszielen.

**Vorteil 2 – Icon: Uhr – Zeitersparnis durch Automatisierung**
> Die aufwendige Recherche, das Texten und der Versand laufen vollautomatisch. Sie investieren Ihre Zeit dort, wo sie am meisten zählt: in Ihr Kerngeschäft.

**Vorteil 3 – Icon: Pfeil nach oben – Skalierbar nach Bedarf**
> Ob 50 oder 500 Kontakte pro Monat – die Kampagne lässt sich flexibel anpassen. Sie entscheiden, wie stark Sie wachsen möchten.

**Vorteil 4 – Icon: Fokus/Ziel – Fokus auf Ihr Kerngeschäft**
> Kein Kaltakquise-Stress mehr. Ihr Team konzentriert sich auf Qualität und Kundenpflege – wir kümmern uns um den Erstkontakt.

---

### 6. RECHTLICHER HINWEIS SECTION

**Hintergrund:** Weiß, dezenter Rahmen (`border-left: 4px solid --accent`)

**H3:** „Rechtssicher und transparent"

> Unsere Dienstleistung richtet sich ausschließlich an den gewerblichen Bereich (B2B). Die Kontaktaufnahme per E-Mail im geschäftlichen Umfeld ist gemäß § 7 Abs. 2 Nr. 3 UWG unter bestimmten Voraussetzungen zulässig – insbesondere wenn ein sachlicher Bezug zur Geschäftstätigkeit des Empfängers besteht, was bei unseren zielgruppenspezifischen Kampagnen stets gegeben ist.
>
> Alle verarbeiteten Daten werden entsprechend der Datenschutz-Grundverordnung (DSGVO) behandelt. Jede versendete E-Mail enthält eine klare Opt-out-Möglichkeit, damit Empfänger ohne Aufwand widersprechen können. Widersprüche werden unverzüglich umgesetzt und dauerhaft vermerkt.
>
> Wir arbeiten nicht mit Spam oder ungezielter Massenkommunikation. Unser Ansatz basiert auf relevanter, personalisierter Geschäftsanbahnung mit echtem Mehrwert für den Empfänger.

---

### 7. BEISPIEL-E-MAILS SECTION

**Hintergrund:** `--surface`

**H2:** „So klingt professionelle Kaltakquise"

**Einleitungstext:**
> Damit Sie sich ein Bild von unserem Kommunikationsstil machen können, zeigen wir Ihnen zwei Beispiele – sachlich, klar und auf Augenhöhe.

Zwei E-Mail-Kacheln im E-Mail-Client-Look (mit „Von:", „An:", „Betreff:"):

---

**E-Mail 1 – Erstkontakt**

**Betreff:** Professionelle Reinigung für Ihre Praxis – kurze Anfrage

> Sehr geehrte Damen und Herren,
>
> mein Name ist [Name], und ich schreibe Ihnen im Auftrag von [Reinigungsunternehmen] aus [Stadt]. Wir sind auf die professionelle Reinigung von Arzt- und Zahnarztpraxen spezialisiert und betreuen bereits mehrere Praxen in Ihrer Region.
>
> Da wir aktuell unsere Kapazitäten erweitern, möchten wir Sie kurz fragen, ob bei Ihnen derzeit Interesse an einem Angebot für regelmäßige Reinigungsleistungen besteht – oder ob Sie möglicherweise mit Ihrem bestehenden Dienstleister nicht vollständig zufrieden sind.
>
> Falls ja, würde ich mich über eine kurze Rückmeldung freuen. Ich halte die Nachricht bewusst kurz und verspreche: kein Druck, kein Verkaufsgespräch – nur ein ehrliches Angebot.
>
> Mit freundlichen Grüßen,
> [Name] | [Unternehmen] | [Telefon]
>
> P.S. Falls Sie kein Interesse haben, genügt eine kurze Antwort – ich werde mich dann nicht wieder melden.

---

**E-Mail 2 – Follow-up (nach 5 Tagen ohne Antwort)**

**Betreff:** Kurze Nachfrage – Reinigung für [Unternehmensname]

> Sehr geehrte Damen und Herren,
>
> vor einigen Tagen hatte ich Ihnen eine kurze Anfrage bezüglich unserer Reinigungsleistungen geschickt. Vielleicht ist die Mail im Alltagsstress untergegangen – das verstehe ich sehr gut.
>
> Ich möchte lediglich sicherstellen, dass Sie die Möglichkeit hatten, sie zu lesen. Falls kein Interesse besteht, ist das selbstverständlich völlig in Ordnung – ich freue mich über eine kurze Rückmeldung.
>
> Sollten Sie jedoch offen für ein unverbindliches Gespräch sein, stehe ich gerne zur Verfügung.
>
> Mit freundlichen Grüßen,
> [Name] | [Unternehmen]

---

### 8. PREISSTRUKTUR SECTION

**Hintergrund:** Weiß

**H2:** „Investition, die sich rechnet"

**Einleitungstext:**
> Unsere Leistungspakete werden individuell auf die Größe Ihres Unternehmens, Ihr Zielgebiet und Ihre Wachstumsziele abgestimmt. Es gibt kein Einheitspaket – weil jedes Reinigungsunternehmen andere Voraussetzungen mitbringt.

| Paket | Starter | Standard ⭐ | Professional |
|---|---|---|---|
| **Preis** | Auf Anfrage | Auf Anfrage | Auf Anfrage |
| **Für** | Einsteiger & lokale Betriebe | Wachsende Betriebe | Skalierungswillige Unternehmen |
| Leadrecherche | 1 Region | Bis zu 3 Regionen | Unbegrenzte Regionen |
| Leads/Monat | Bis zu 200 | Bis zu 600 | Individuell |
| E-Mail-Sequenzen | 1 Sequenz (2 Nachrichten) | 2 Sequenzen (je 3 Nachrichten) | Vollständiges Kampagnen-Management |
| A/B-Testing | – | ✓ Betreffzeilen | ✓ Vollständig |
| Reporting | Monatlich | Wöchentlich + Beratungsgespräch | Monatliches Strategiegespräch |
| CRM-Integration | – | – | Auf Anfrage |

> **Hinweis:** Alle Preise auf Anfrage. Wir erstellen Ihnen gerne ein maßgeschneidertes Angebot nach einem kostenlosen Erstgespräch.

Standard-Card hervorheben: `--accent` Hintergrund, weißer Text, Badge „Beliebteste Wahl".

---

### 9. KONTAKT / CTA SECTION

**Hintergrund:** `--surface`

**H2:** „Bereit für planbare Neukundenanfragen?"

**Text:**
> Buchen Sie jetzt Ihr kostenfreies Erstgespräch – ohne Verpflichtung, ohne Verkaufsdruck. Wir analysieren gemeinsam Ihr Potenzial und zeigen Ihnen konkret, wie viele qualifizierte Kontakte wir monatlich für Sie generieren können.

**Kontaktformular (links, 60% Breite):**
- Felder: Vorname, Nachname, Unternehmensname, E-Mail, Telefon (optional)
- Textarea: „Ihre Nachricht / Was beschäftigt Sie aktuell?"
- Checkbox: „Ich habe die Datenschutzerklärung gelesen und stimme zu."
- Submit-Button: „Jetzt Erstgespräch anfragen →" (`--accent`, volle Breite)

**Vertrauens-Info-Box (rechts, 40% Breite):**
- 📞 Wir melden uns innerhalb von 24 Stunden
- 🔒 Ihre Daten werden nicht weitergegeben
- 💬 Kein Verkaufsdruck – nur ehrliche Beratung
- ✅ Kostenlos & unverbindlich

---

### 10. FOOTER

**Hintergrund:** `--text` (dunkel), weißer Text, dreispaltig

**Spalte 1 – Logo + Kurztext:**
> CleanLeads unterstützt Reinigungsunternehmen im DACH-Raum bei der systematischen und rechtssicheren Neukundengewinnung.

**Spalte 2 – Navigation:**
Impressum | Datenschutz | Kontakt | AGB (Platzhalter)

**Spalte 3 – Kontakt:**
- E-Mail: info@cleanleads.de *(Platzhalter)*
- Telefon: +49 (0) 123 456789 *(Platzhalter)*
- Ort: Deutschland

**Unterzeile:** © 2025 CleanLeads – Alle Rechte vorbehalten.

---

## UNTERSEITEN

Als separate `<section id="impressum">` & `<section id="datenschutz">` oder als Modal/Toggle-Ansicht umzusetzen.

### IMPRESSUM

> **Angaben gemäß § 5 TMG**
>
> [Unternehmensname]
> [Straße, Hausnummer]
> [PLZ, Ort]
>
> Vertreten durch: [Name des Geschäftsführers]
> Telefon: [Telefonnummer]
> E-Mail: [E-Mail-Adresse]
>
> Registergericht: [Amtsgericht]
> Registernummer: [HRB-Nummer]
> USt-IdNr.: [Umsatzsteuer-ID]
>
> Verantwortlich für den Inhalt nach § 55 Abs. 2 RStV:
> [Name], [Adresse]

---

### DATENSCHUTZERKLÄRUNG

Vollständige DSGVO-konforme Datenschutzerklärung mit folgenden Abschnitten:

1. **Verantwortlicher** (Platzhalter)
2. **Erhebung und Verarbeitung personenbezogener Daten**
   - Kontaktformular: Welche Daten, Zweck, Rechtsgrundlage (Art. 6 Abs. 1 lit. b DSGVO)
   - E-Mail-Kommunikation: Speicherdauer, Löschung
3. **Cookies und Tracking** – Hinweis: Diese Website verwendet keine Tracking-Cookies ohne Einwilligung
4. **Ihre Rechte** – Auskunft, Berichtigung, Löschung, Widerspruch, Datenübertragbarkeit
5. **Beschwerderecht bei der Aufsichtsbehörde**
6. **Hinweis zur B2B-E-Mail-Kommunikation** – Auftragsverarbeitung, Opt-out-Verfahren, Datenlöschung
7. **Kontakt Datenschutzbeauftragter** (Platzhalter)

---

## ABSCHLIESSENDE ANWEISUNGEN AN DEN AGENTEN

- Erstelle **NUR funktionierenden, vollständigen Code** – kein Pseudocode
- Alle oben stehenden Texte müssen **1:1 im Code erscheinen** (vollständig ausgeschrieben)
- Kein Text darf durch „[Platzhalter]" oder „[...]" im **sichtbaren Bereich** ersetzt werden, außer bei Firmendaten (Impressum)
- Das Formular soll **clientseitig validieren** und bei Absenden eine Erfolgsmeldung anzeigen (kein Backend nötig)
- **Smooth-Scroll** und **IntersectionObserver** für Einblend-Animationen sind Pflicht
- Der Code muss **sofort im Browser lauffähig** sein
- Gib **ausschließlich den fertigen HTML-Code** aus, ohne Erklärungen davor oder danach

---

*Erstellt für: CleanLeads – Automatisierte B2B-Neukundengewinnung für Reinigungsunternehmen*
