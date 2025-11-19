---
title: "Prompt Engineering"
permalink: /prompt_engineering/
---

# **Prompt Engineering: Die entscheidenden Details**

##  **1. Was ist Prompt Engineering?**

**Prompt Engineering** ist die Kunst, präzise und effektive Anweisungen (Prompts) für KI-Systeme wie Chatbots oder Textgeneratoren zu formulieren. Ziel ist es, die bestmögliche Antwort oder das gewünschte Ergebnis zu erhalten.

**Warum ist das wichtig?**

- **Effizienz:** Gute Prompts sparen Zeit und vermeiden Missverständnisse.
- **Qualität:** Präzise Prompts führen zu besseren, relevanteren Antworten.
- **Kreativität:** Mit den richtigen Techniken kannst du die KI für komplexe Aufgaben nutzen – von Texten über Code bis hin zu Analysen.
-
### **Warum Präzision alles ist**

Jedes Wort, jede Struktur und jeder Kontext in deinem Prompt beeinflusst das Ergebnis. Bei fortgeschrittenen Methoden geht es darum, der KI nicht nur zu sagen, _was_ sie tun soll, sondern auch _wie_ sie denken soll

####  **A. Die drei Säulen eines guten Prompts**

1. **Klarheit:** Formuliere konkret und vermeide Mehrdeutigkeiten.
2. **Kontext:** Gib der KI alle notwendigen Hintergrundinformationen.
3. **Struktur:** Nutze klare Anweisungen und Formatierungen (z.B. Aufzählungen, Absätze).



#### **Wie entstehen KI-Antworten? – Einfach erklärt**

Stell dir die KI wie einen **super-schnellen, super-großen Textmixer** vor:

##### **1. Das „Gehirn“ der KI: Unmengen an Texten**

- Die KI wurde mit **Milliarden von Sätzen** aus Büchern, Artikeln, Webseiten und Gesprächen trainiert.
- Sie kennt **Muster**: Welche Wörter oft zusammen vorkommen, wie Sätze aufgebaut sind, welche Antworten zu welchen Fragen passen.
- **Aber:** Sie versteht die Texte nicht wie ein Mensch – sie erkennt nur statistische Zusammenhänge.

##### **2. Dein Prompt ist der „Startknopf“**

- Wenn du eine Frage stellst, durchsucht die KI ihr „Gedächtnis“ nach passenden Mustern.
- Sie berechnet: _„Welche Wortkombinationen passen am besten zu der Frage?“_ – ähnlich wie bei der Autovervollständigung auf dem Handy, nur viel komplexer.
- **Wichtig:** Die KI hat **kein Bewusstsein** – sie kombiniert nur Wörter so, dass sie „sinnvoll“ klingen.

##### **3. Schritt für Schritt: So entsteht die Antwort**

- Die KI beginnt mit deinem Prompt und sagt sich: _„Welches Wort kommt am wahrscheinlichsten als Nächstes?“_ – und dann das nächste, und das nächste.
- **Beispiel:** Du schreibst: _„Wie backe ich einen Kuchen?“_ → Die KI „weiß“ aus ihrem Training, dass danach oft Wörter wie _„Zutaten“_, _„Schritte“_, _„Backzeit“_ folgen.
- Sie baut die Antwort **Wort für Wort** auf, bis ein ganzer, logischer Text entsteht.

#####  **4. Warum sind manche Antworten besser als andere?**

- **Gute Prompts** geben der KI klare „Schienen“ – sie weiß genau, in welche Richtung sie „denken“ soll.
- **Schlechte Prompts** sind wie eine vage Wegbeschreibung – die KI muss raten und landet vielleicht woanders.

##### **5. Was die KI NICHT kann**

- **Echte Gedanken lesen:** Sie versteht nicht, was du _wirklich_ meinst – nur, was du schreibst.
- **Neues Wissen erfinden:** Sie kann nur kombinieren, was sie schon „gelesen“ hat (Stand: November 2024).
- **Gefühle haben:** Die KI simuliert nur Empathie – sie weiß nicht, was Trauer, Freude oder Sarkasmus wirklich sind.

---

##### **Vergleich:** Die KI ist wie ein **Koch, der nur Rezepte kennt, aber nicht schmecken kann**.

- Du sagst: _„Koche mir etwas Leckeres!“_ → Er rät und wirft alles in den Topf.
- Du sagst: _„Koche mir eine vegetarische Lasagne mit Spinat und Ricotta, Schritt für Schritt.“_ → Er folgt dem Rezept präzise.

Stell dir die KI wie einen **superintelligenten, aber wortwörtlichen Assistenten** vor:

- **Die KI versteht nur, was du schreibst – nicht, was du meinst.** Wenn du sagst: _„Erzähl mir was über Hunde.“_, könnte die Antwort über Rassen, Geschichte, Haltung oder sogar Hunde in der Kunst gehen. Die KI rät, was du hören willst – und liegt oft daneben.

- **Jedes Wort ist ein Signal.** _„Beschreibe einen Hund“_ → allgemeine Antwort. _„Beschreibe einen Labrador Welpen für eine Tierheim-Anzeige“_ → konkret, emotional, zielgerichtet.

- **Die KI hat keine Intuition.** Sie kennt keine „Selbstverständlichkeiten“. Wenn du nicht sagst, _für wen_ oder _wofür_du die Info brauchst, fehlt ihr der Kontext.



---
##  **Methoden**

### **1. Basis-Methoden: Was wirklich zählt**

#### **A. Direkte Anweisungen**

**Worauf es ankommt:**

- **Keine Floskeln:** Vermeide „Könntest du mir bitte…“ – schreibe stattdessen: _„Liste die 5 wichtigsten Fakten über XY.“_
- **Aktionsverben:** Nutze starke Verben wie _„analysiere“_, _„vergleiche“_, _„fasse zusammen“_ statt _„könntest du mal…“_.

**Beispiel:** ❌ _„Könntest du mir vielleicht etwas über den Klimawandel erzählen?“_ → zu vage ✅ _„Erkläre die drei Hauptursachen des Klimawandels in je einem Satz.“_

---

#### **B. Rollen zuweisen**

**Worauf es ankommt:**

- **Spezifische Rolle:** Nicht nur _„Experte“_, sondern _„Senior-Marketingstratege mit 10 Jahren Erfahrung in der Lebensmittelbranche“_.
- **Erwartungshaltung:** _„Antworte wie in einem Pitch-Meeting für Investoren.“_

**Beispiel:** ❌ _„Stell dir vor, du bist ein Experte. Wie würde ich…“_ ✅ _„Du bist ein erfahrener UX-Designer. Beschreibe, wie du den Onboarding-Prozess für eine neue App gestalten würdest. Nutze dabei die Methode ‚Jobs-to-be-Done‘ und gehe auf die ersten 3 Schritte ein.“_

---

####  **C. Schritt-für-Schritt-Anleitungen**

**Worauf es ankommt:**

- **Logische Abfolge:** Nummeriere die Schritte oder nutze klare Absätze.
- **Zwischenergebnisse:** Fordere die KI auf, nach jedem Schritt eine kurze Zusammenfassung zu geben.

**Beispiel:** ✅ *„Erkläre mir die Blockchain-Technologie in 4 Schritten:

1. Grundprinzip (1 Satz)
2. Wie Transaktionen funktionieren (Beispiel)
3. Vorteile gegenüber Banken
4. Mögliche Risiken“*

---

#### **D. Few-Shot Prompting (Beispiele geben)**

**Worauf es ankommt:**

- **Konsistente Beispiele:** Alle Beispiele sollten im gleichen Stil, Tonfall und Detaillierungsgrad sein.
- **Klare Muster:** Zeige der KI, was du willst, indem du 2-3 perfekte Beispiele vorweg nimmst.

**Beispiel:** ✅ *„Hier sind drei Produktbeschreibungen im gewünschten Stil:

1. ‚Unser Bio-Tee – handgepflückt, sanft getrocknet, für pure Aromavielfalt.‘
2. ‚Die nachhaltige Yoga-Matte – rutschfest, schadstofffrei, für bewusste Bewegung.‘ Schreibe jetzt eine vierte für: ‚Unser neues Bambus-Geschirrset‘.“*

---

### **2. Fortgeschrittene Methoden: Der Unterschied liegt im Denken**

####  **A. Chain-of-Thought (CoT) Prompting**

**Worauf es ankommt:**

- **Denkprozess erzwingen:** Die KI soll nicht nur das Ergebnis liefern, sondern jeden Schritt erklären.
- **Fehler erkennen:** Du siehst, wo die KI logische Sprünge macht oder Annahmen trifft.

**Beispiel:** ❌ _„Wie viel kostet es, ein Café zu eröffnen?“_ ✅ *„Berechne die Startkosten für ein Café in Berlin mit 50 Sitzplätzen. Gehe dabei Schritt für Schritt vor:

1. Mietkosten (durchschnittlicher qm-Preis in Berlin-Mitte)
2. Ausstattung (Küche, Möbel, Kaffeemaschine – liste die wichtigsten Posten auf)
3. Personalkosten (für die ersten 3 Monate)
4. Sonstige Kosten (Genehmigungen, Marketing) Erkläre jede Annahme, die du triffst.“*

**Warum das besser ist:** Die KI muss ihre Rechnung offenlegen – du siehst, ob sie realistische Zahlen nutzt oder etwas übersehen hat.

---

#### **B. Tree-of-Thought (ToT) Prompting**

**Worauf es ankommt:**

- **Mehrere Wege aufzeigen:** Die KI soll verschiedene Lösungsansätze entwickeln und bewerten.
- **Entscheidungshilfe:** Du bekommst nicht nur eine Antwort, sondern eine Analyse der Optionen.

**Beispiel:** ✅ *„Ich möchte in 6 Monaten 5.000 € sparen. Ich habe ein Nettoeinkommen von 2.500 €/Monat und feste Ausgaben von 1.800 €. Entwickle 3 verschiedene Sparstrategien:

1. Konservativ (geringes Risiko)
2. Aggressiv (höhere Rendite, mehr Risiko)
3. Kreativ (z.B. Nebenverdienst, Ausgabenoptimierung) Bewerte jede Strategie nach Risiko, Aufwand und Erfolgswahrscheinlichkeit.“*

**Warum das besser ist:** Du siehst Vor- und Nachteile jeder Option und kannst bewusst wählen.

---

#### **C. Reflexions-Prompting**

**Worauf es ankommt:**

- **Selbstkritik einfordern:** Die KI soll ihre eigene Antwort hinterfragen.
- **Verbesserungsvorschläge:** Nicht nur „Das ist gut/schlecht“, sondern konkrete Alternativen.

**Beispiel:** ✅ *„Hier ist mein Lebenslauf: [Text einfügen].

1. Analysiere Stärken und Schwächen.
2. Liste 3 konkrete Verbesserungen auf (z.B. Formulierung, Struktur, Inhalte).
3. Schreibe eine überarbeitete Version mit den wichtigsten Änderungen.“*

**Warum das besser ist:** Du bekommst nicht nur Feedback, sondern direkt eine optimierte Version.

---

#### **D. Meta-Prompting**

**Worauf es ankommt:**

- **Prompt-Optimierung:** Die KI hilft dir, bessere Prompts zu schreiben.
- **Zielklärung:** Du lernst, was du wirklich brauchst.

**Beispiel:** ✅ *„Ich möchte einen Prompt schreiben, der mir hilft, bessere Blog-Artikel zu planen. Frage mich gezielt nach:

1. Zielgruppe
2. gewünschter Stil
3. Struktur des Artikels
4. gewünschte Länge Dann schlage mir einen optimierten Prompt vor.“*

**Warum das besser ist:** Du lernst, wie man Prompts strukturiert, und bekommst maßgeschneiderte Vorlagen.

---

### **3. Typische Fehler & wie du sie vermeidest**

|Fehler|Beispiel|Lösung|
|---|---|---|
|Zu vage|_„Erzähl mir was über KI.“_|_„Erkläre die 3 wichtigsten Anwendungen von KI im Gesundheitswesen – je in 2 Sätzen.“_|
|Kein Kontext|_„Schreibe einen Text.“_|_„Schreibe eine Produktbeschreibung für eine Smartwatch für Senioren. Zielgruppe: 60+, Fokus auf Einfachheit und Sicherheit.“_|
|Zu komplex|_„Analysiere die globale Wirtschaftslage und ihre Auswirkungen auf…“_|_„Nenne die 3 größten wirtschaftlichen Herausforderungen 2025 und wie sie den deutschen Mittelstand betreffen.“_|

---

### **4. Praxistipp: So übst du Prompt Engineering**

1. **Starte einfach:** Nimm eine Basis-Methode und verfeinere sie Schritt für Schritt.
2. **Vergleiche Ergebnisse:** Probiere verschiedene Formulierungen aus und vergleiche die Antworten.
3. **Lerne von der KI:** Nutze Meta-Prompting, um Feedback zu deinen Prompts zu bekommen.

---
