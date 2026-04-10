# Innovation Model Canvas

Das **Innovation Model Canvas** ist ein schlankes, rein browserbasiertes Werkzeug (Single-Page-Application) zur Strukturierung und Validierung von Innovationsvorhaben und Proof of Concepts (PoCs). Es hilft Teams dabei, komplexe Fragestellungen zielgerichtet auf einer einzigen Seite zu orchestrieren.

Dieses Tool wurde ursprünglich für das Innovationsmanagement konzipiert und benötigt **keinerlei Backend, Server oder Internetverbindung**. Es speichert sich samt Inhalt selbst als neue HTML-Datei ab.

## 🌟 Kernfunktionen

### 🎨 Das Interaktive Canvas
- **9-Feld-Struktur:** Ein standardisiertes Layout zur Beantwortung der wichtigsten Fragen vor dem Start eines PoCs:
  1. Ausgangslage
  2. Lösung & Hypothese
  3. Mehrwert
  4. Stakeholder / User
  5. Erfolgskriterien
  6. Perspektiven
  7. Daten und Compliance
  8. Ressourcen und Zeithorizont
  9. Risiken
- **Integrierte Methodik-Hilfe:** Jedes Feld verfügt über einen Info-Button, der sofort Leitfragen und Erklärungen (z.B. für PULL- und PUSH-Vorhaben) einblendet.
- **Flexibles Grid:** Die Spalten und Zeilen können per Drag & Drop frei in ihrer Größe angepasst werden.
- **Auto-Scaling:** Der Text skaliert (verkleinert) sich automatisch, wenn der Platz im Feld knapp wird.

### 📝 Integrierter Rich-Text-Editor
- **Floating Toolbar:** Sobald Sie ein Textfeld fokussieren, erscheint eine schwebende Toolbar (Fett, Kursiv, Listen).
- **Metadaten:** Oben können Projektname, Ersteller, Datum und Version eingetragen werden.

### 📌 Digitale Haftnotizen (Post-its)
- **Drag & Drop:** Ziehen Sie einfach eine neue Haftnotiz aus der Kopfzeile auf das Canvas.
- **Frei platzierbar:** Notizen können überall positioniert, editiert und wieder gelöscht werden.

### ⏱️ Änderungshistorie
- Das Tool beinhaltet eine einklappbare Tabelle im Fußbereich, um Versionen, Freigaben (Go/No-Go) und Bemerkungen im Zeitverlauf zu dokumentieren.

### 💾 Lokales Speichern (Self-Contained)
- **100% Portabel:** Das gesamte Tool besteht aus **einer einzigen HTML-Datei**.
- **Speichern-Logik:** Wenn Sie auf "Speichern" klicken, generiert das Script einen Klon von sich selbst (inklusive all Ihrer Texte, verschobenen Notizen und veränderten Grid-Größen) und lädt diesen als neue HTML-Datei herunter. Alternativ kann die geöffnete Datei überschrieben werden (Browser-abhängig).

### 🖨️ Druck- & PDF-optimiert
- Sobald Sie die Seite drucken (oder als PDF speichern), werden alle störenden UI-Elemente, Buttons und Raster-Anfasser automatisch ausgeblendet.

---

## 🚀 Erste Schritte (How to Use)

1. **Öffnen:** Laden Sie die Datei `innovation_model_canvas.html` herunter und öffnen Sie diese per Doppelklick in einem beliebigen modernen Browser (Chrome, Edge, Firefox, Safari).
2. **Methode verstehen:** Klicken Sie im Menü oben auf den Button **"ℹ️ Info"**, um das Zielbild und den Nutzen des Canvas zu verstehen. 
3. **Ausfüllen:** Klicken Sie in die 9 Felder und fassen Sie Ihr Vorhaben zusammen. Orientieren Sie sich an den kleinen "i"-Icons neben den Überschriften.
4. **Speichern:** Klicken Sie oben im Menü auf `Speichern` (überschreibt die lokale Datei, sofern der Browser dies zulässt) oder auf `Download Kopie`, um einen neuen Stand herunterzuladen.
5. **Teilen:** Sie können die gespeicherte HTML-Datei einfach per E-Mail oder Chat an Kollegen schicken. Diese können die Datei doppelklicken und genau dort weiterarbeiten, wo Sie aufgehört haben.

---

## 🛠️ Technische Details

- **Technologie:** Pures HTML5, CSS3 und Vanilla JavaScript.
- **Abhängigkeiten:** Absolut keine. Es werden keine externen Frameworks, Fonts, Icon-Sets oder Tracking-Skripte geladen.
- **Datenschutz:** 100% DSGVO/Data-Compliance-konform. Alle Daten bleiben lokal auf Ihrem Rechner in der Datei. Es findet keine Kommunikation mit einem Server statt.

---

## 📄 Urheberrecht & Lizenz

Um den Open-Source- und Kollaborationsgedanken zu fördern, ist dieses Repository dual lizenziert:

* **Methodik & Inhalt (Das Canvas an sich):** Lizenziert unter [Creative Commons Namensnennung - Weitergabe unter gleichen Bedingungen 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/deed.de).
* **Software & Quellcode:** Lizenziert unter der [GNU Affero General Public License v3.0 (AGPLv3)](https://www.gnu.org/licenses/agpl-3.0.de.html).

Das bedeutet: Sie dürfen die Methodik und den Code frei nutzen, anpassen und in Ihrem Unternehmen einsetzen. Wenn Sie den Code (die HTML/JS-Struktur) erweitern und Dritten (auch als Webdienst) anbieten, müssen Ihre Verbesserungen zwingend wieder unter derselben Lizenz offengelegt werden. Zudem muss der Urheber als Quelle genannt bleiben. 

Details entnehmen Sie der beiliegenden `LICENSE.md` sowie dem Code-Header in der HTML-Datei.
