---
title: Technologien
permalink: /ki-heute/technologien/
---
## Funktionsprinzipien heutiger KI

### Maschinelles Lernen

**Maschinelles Lernen (Machine Learning, ML)** ist ein zentraler Bestandteil der KI und bezeichnet Algorithmen, die aus Daten lernen, ohne explizit programmiert zu werden. Es gibt drei Hauptansätze:

- **Überwachtes Lernen (Supervised Learning):** Das Modell wird mit einem **Datensatz** trainiert, der aus Eingabedaten und den dazugehörigen Ausgabedaten besteht. Ziel ist es, eine Funktion zu lernen, die Eingaben korrekt auf Ausgaben abbildet.
- **Unüberwachtes Lernen (Unsupervised Learning):** Das Modell erhält nur Eingabedaten und muss selbstständig Muster oder Strukturen erkennen, z. B. durch **Clustering**.
- **Bestärkendes Lernen (Reinforcement Learning):** Das Modell lernt durch Belohnungen und Bestrafungen. Es führt Aktionen aus und erhält Feedback, das es nutzt, um seine Strategie zu optimieren.

**Datensatz:** Eine Sammlung von Daten, die zum Trainieren eines Modells verwendet wird. Ein Datensatz kann strukturiert (z. B. Tabellen) oder unstrukturiert (z. B. Texte, Bilder) sein. Datensätze sind die Grundlage für das Training von KI-Modellen und bestimmen maßgeblich deren Leistung und Genauigkeit.

**Clustering:** Ein Verfahren des unüberwachten Lernens, bei dem ähnliche Datenpunkte zu Gruppen (Clustern) zusammengefasst werden, um Muster zu erkennen. Clustering wird häufig in der **Marktsegmentierung**, **Bildverarbeitung** und **Anomalieerkennung** eingesetzt, um Strukturen in Daten zu identifizieren, die nicht offensichtlich sind.

---

### Neuronale Netze

**Neuronale Netze** sind Computermodelle, die von der Struktur des menschlichen Gehirns inspiriert sind. Sie bestehen aus künstlichen Neuronen, die in Schichten organisiert sind:

- **Eingabeschicht (Input Layer):** Erhält die Rohdaten, z. B. Pixelwerte eines Bildes oder Wörter eines Textes. Diese Schicht ist für die Aufnahme und Vorverarbeitung der Eingabedaten verantwortlich.
- **Verborgene Schichten (Hidden Layers):** Verarbeiten die Daten durch Gewichtung und Transformation. Jedes Neuron in einer Schicht ist mit den Neuronen der vorherigen Schicht verbunden. Die Anzahl und Komplexität der versteckten Schichten bestimmen die Fähigkeit des Netzes, komplexe Muster zu erkennen.
- **Ausgabeschicht (Output Layer):** Gibt das Endergebnis aus, z. B. eine Klassifizierung oder Vorhersage. Diese Schicht bestimmt die finale Ausgabe des neuronalen Netzes, wie z. B. die Klassifizierung eines Bildes oder die Generierung eines Textes.

**Hidden State:** Ein zentrales Konzept in **rekurrenten neuronalen Netzen (RNNs)**. Der Hidden State speichert Informationen über vorherige Eingaben und gibt sie an die nächste Verarbeitungseinheit weiter. Dadurch kann das Netz sequenzielle Daten (z. B. Texte) verarbeiten und Kontext über die Zeit hinweg bewahren. Der Hidden State ermöglicht es RNNs, Abhängigkeiten zwischen zeitlich entfernten Eingaben zu erkennen.

**Deep-Learning-Modelle:** Neuronale Netze mit vielen verborgenen Schichten, die komplexe Muster in großen Datenmengen erkennen können. Deep-Learning-Modelle sind besonders leistungsfähig, benötigen aber auch mehr Rechenleistung und Daten. Sie werden in einer Vielzahl von Anwendungen eingesetzt, von der **Bild- und Spracherkennung** bis hin zur **autonomen Steuerung** von Fahrzeugen.

---

### Trainingsprozess und Optimierung

Beim **Training** eines KI-Modells wird es mit Daten gefüttert, um seine internen Parameter (Gewichte) so anzupassen, dass es die gewünschten Ausgaben produziert. Ein zentrales Verfahren hierfür ist **Gradient Descent**:

- **Gradient Descent:** Ein iterativer Algorithmus, der die Gewichte des Modells schrittweise anpasst, um den **Fehler** (die Differenz zwischen vorhergesagter und tatsächlicher Ausgabe) zu minimieren. Der Gradient gibt die Richtung des steilsten Anstiegs der Fehlerfunktion an, und der Algorithmus bewegt sich in die entgegengesetzte Richtung, um den Fehler zu reduzieren.
- **Backpropagation:** Ein Verfahren, das den Fehler rückwärts durch das Netz propagiert, um die Gewichte effizient anzupassen. Es berechnet den Gradient für jedes Gewicht im Netz und passt es entsprechend an. Backpropagation ist ein zentraler Bestandteil des Trainings neuronaler Netze und ermöglicht das effiziente Lernen aus Fehlern.

**Fehler:** Ein Maß dafür, wie stark die Vorhersage des Modells von der tatsächlichen Ausgabe abweicht. Ziel des Trainings ist es, diesen Fehler zu minimieren. Der Fehler wird oft durch **Verlustfunktionen** (Loss Functions) quantifiziert, die die Abweichung zwischen der vorhergesagten und der tatsächlichen Ausgabe messen.

---

### Inferenz

Die **Inferenz** ist der Prozess, bei dem ein trainiertes Modell auf neue, unbekannte Daten angewendet wird, um Vorhersagen oder Entscheidungen zu treffen. Im Gegensatz zum Training, das rechenintensiv ist, ist die Inferenz oft schneller und wird in Echtzeit-Anwendungen eingesetzt. Inferenz ist der Schritt, in dem das Modell sein gelerntes Wissen anwendet, um nützliche Ergebnisse zu liefern, z. B. die Übersetzung eines Textes oder die Erkennung eines Objekts in einem Bild.
