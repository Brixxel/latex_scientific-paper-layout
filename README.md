# LaTeX Projektvorlage

Diese LaTeX Vorlage eignet sich zur Erstellung von Projektdokumentationen, Abschlussarbeiten und Berichten. Die Struktur ist modular gestaltet und ermöglicht eine einfache Anpassung und Erweiterung.

## Ordnerstruktur

- **00-meta_config/**: Beinhaltet die Konfigurationsdatei `config.tex`, welche die LaTeX-Einstellungen und benutzerdefinierte Befehle enthält.
- **10-frontmatter/**: Enthält Dateien für den Vorderteil des Dokuments:
  - `abstract.tex`: Zusammenfassung der Arbeit
  - `acknowledge.tex`: Danksagungen
  - `acronyms.tex`: Akroynamverzeichnis
  - `ewerkl.tex`: Ehrenwörtliche Erklärung
  - `notation.tex`: Notationsverzeichnis
  - `titlepage.tex`: Titelseite
- **20-chapters/**: Beinhaltet die Kapitel des Dokuments:
  - `00-intro.tex`: Einleitung
  - `10-theorie.tex`: Theorieteil
  - `99-conclusion.tex`: Fazit und Ausblick
- **40-backmatter/**: Umfasst die Bibliographie:
  - `bibliography.bib`: Literaturverzeichnis im BibTeX-Format
- **50-appendix/**: Enthält Anhänge:
  - `appendix_1.tex`: Erster Anhang
- **60-figures/**: Verzeichnis für Bilder und Grafiken:
  - `img/logo/`: Logos wie `firmenlogo.jpg` und `logo_dhbw.jpg`

- **main.tex**: Hauptdokument, das alle Teile zusammenfügt.

## Nutzung

1. **Vorbereitung**: Stelle sicher, dass du eine gültige LaTeX-Distribution installiert hast (z.B. TeX Live oder MikTeX). Ein Texteditor wie TeXstudio oder Visual Studio Code mit dem LaTeX Workshop Plugin ist ebenfalls empfehlenswert.

2. **Bearbeitung der Metadaten**: Öffne `00-meta_config/config.tex` und passe die persönlichen Informationen sowie die Projektinformationen an (z.B. `\TitelDerArbeit`, `\AutorDerArbeit`).

3. **Inhaltliches Arbeiten**: Bearbeite die .tex-Dateien in den jeweiligen Verzeichnissen, um den Inhalt deines Dokuments zu erstellen und anzupassen.

4. **Bilder und Logos**: Füge deine eigenen Bilder im `60-figures/img/logo/` hinzu und passe ihren Dateinamen entsprechend in den .tex-Dateien an.

5. **Kompilieren**: Kompiliere `main.tex`, um das Dokument zu erstellen. Dies kann über den Befehl `pdflatex`, `xelatex` oder in einer IDE direkt geschehen.

## Anpassungen

- **Titelblatt**: Passe `titlepage.tex` nach deinen Anforderungen an.
- **Layout**: Bei Bedarf kannst du die Designaspekte in `config.tex` verändern, z.B. Schriftarten oder Seitenabstände.
- **Zusätzliche Kapitel oder Anhänge**: Erstelle neue .tex-Dateien in den entsprechenden Ordnern und binde sie in `main.tex` ein.

