# F-Praktikum Template Repository

This repository contains the LaTeX template for documenting the six experiments of the Fortgeschrittenen Praktikum (F-Praktikum, FPR). Each experiment requires both an analysis and a protocol in the form of a scientific paper. The template is structured to help you easily format your reports, following the guidelines provided here:  
https://www.physik.hu-berlin.de/de/studium/bachelor/f-praktikum/reportguide

## Repository Structure

The repository contains the following main directories:

### 1. `figures/`
This folder contains subfolders for images and graphs used in the protocols. The idea is that each subfolder contains the images and graphs for each protocol.


### 2. `protocolls/`
This folder is where all your protocol documents will be stored. Each protocol should follow the provided LaTeX template structure:

- **Introduction**: A brief overview of the experiment, its relevance, and context within the research field. In most cases, this section can be kept very short. For more details, refer to the description provided in the template:  
  _"The introduction can be kept very short. In the case of a publication, it serves to classify the work carried out within the research landscape and to prepare the reader who is not a specialist in the subject for the subject matter."_

- **Materials and Methods**: Provide a concise description of the experimental setup, including the devices used (with model numbers) and any special procedures or software. Diagrams or sketches can be included to enhance clarity. The template's guidance:  
  _"In Materials and Methods, the experimental setups are described, the devices or experimental systems used with type designation and also special procedures for data evaluation/software, if necessary."_

- **Analysis and Discussion**: Present your results, evaluate them, and discuss them in relation to previous works. Ensure that results are given with error statements and that graphical representations (e.g., graphs with error bars) are included.  
  _"In evaluation and discussion, the results are presented, analyzed, and discussed. The accuracy of the results is assessed, and they are compared with those from other works. A result without an error statement is not a result."_

- **Conclusion**: Summarize the key findings and the broader implications of your results.  
  _"The conclusions are summarized at the end, offering a concise wrap-up of the work and its results."_

### 3. `settings/`
This folder contains the configuration files for customizing the protocols.

- **`acronyms_de.tex`**: Contains predefined German acronyms. You can freely add personal acronyms here as needed.

- **`acronyms_eng.tex`**: Contains predefined English acronyms. You can freely add personal acronyms here as needed.

- **`commands.tex`**: This file contains custom commands for your LaTeX document.

- **`index.ist`**: If you want to include an index in your protocol, here are the settings for the index.

- **`packages.tex`**: All necessary LaTeX packages are loaded in this file. If you are using Overleaf, packages will load automatically. However, if you're working with MiKTeX or other local environments, you may need to install missing packages manually.

- **`settings.tex`**: This file contains the global settings for the protocols, such as page geometry, author information, link color customization, and formatting for code listings. Key settings include:

  - Line 9: `\addbibresource{}` – Add the path to your personal bibliography file here. Ensure that you include a `.bib` file for proper referencing.

- Table Folder: If needed, you can create a separate folder for tables and reference them in your protocol.

## How to Use

1. Clone this repository to your local machine or download the zip file. If you want to use Overleaf, the zip file is the preferred version because you can upload the zip file.
2. Update the `settings.tex`, `acronyms_de.tex`, and `acronyms_eng.tex` files as needed for your specific experiment and protocol.
3. Add figures to the appropriate subfolders within `figures/`.
4. Write your protocols in the `protocolls/` folder, following the LaTeX template structure.
5. Ensure that your bibliography file is included and referenced correctly in `settings.tex`.

For further instructions on formatting and content guidelines, please refer to the F-Praktikum Report Guide:  
https://www.physik.hu-berlin.de/de/studium/bachelor/f-praktikum/reportguide

---

# F-Praktikum Template Repository (German Version)

Dieses Repository enthält die LaTeX-Vorlage zur Dokumentation der sechs Experimente des Fortgeschrittenen Praktikums (F-Praktikum, FPR). Jedes Experiment erfordert sowohl eine Analyse als auch ein Protokoll in Form eines wissenschaftlichen Papiers. Die Vorlage ist so strukturiert, dass Sie Ihre Berichte leicht formatieren können. Sie folgt den Richtlinien, die Sie hier finden:  
https://www.physik.hu-berlin.de/de/studium/bachelor/f-praktikum/reportguide

## Verzeichnisstruktur

Das Repository enthält die folgenden Hauptverzeichnisse:

### 1. `figures/`
Dieser Ordner enthält Unterordner für Bilder und Grafiken, die in den Protokollen verwendet werden. Die Idee ist, dass jeder Unterordner die Bilder und Grafiken für jedes Protokoll enthält.


### 2. `protocolls/`
In diesem Ordner werden alle Ihre Protokolldokumente gespeichert. Jedes Protokoll sollte der vorgegebenen LaTeX-Vorlagenstruktur folgen:

- **Einleitung**: Eine kurze Übersicht über das Experiment, seine Relevanz und den Kontext im Forschungsbereich. In den meisten Fällen kann dieser Abschnitt sehr kurz gehalten werden. Für weitere Details siehe die Beschreibung in der Vorlage:  
  _"Die Einleitung kann sehr kurz gehalten werden. Im Fall einer Veröffentlichung dient sie dazu, die durchgeführte Arbeit innerhalb der Forschungslandschaft einzuordnen und den fachfremden Leser auf das Thema vorzubereiten."_

- **Material und Methoden**: Geben Sie eine prägnante Beschreibung des experimentellen Aufbaus, einschließlich der verwendeten Geräte (mit Modellnummern) und spezieller Verfahren oder Software. Diagramme oder Skizzen können hinzugefügt werden, um die Klarheit zu erhöhen. Beschreibung der Vorlage:  
  _"In Material und Methoden werden die Versuchsaufbauten beschrieben, die verwendeten Geräte oder experimentellen Systeme mit Typenbezeichnung und ggf. spezielle Verfahren zur Datenauswertung/Software."_

- **Auswertung und Diskussion**: Präsentieren und bewerten Sie Ihre Ergebnisse und vergleichen Sie diese mit anderen Arbeiten. Stellen Sie sicher, dass die Ergebnisse mit Fehlerangaben versehen sind und dass grafische Darstellungen (z.B. Diagramme mit Fehlerbalken) enthalten sind.  
  _"In Auswertung und Diskussion werden die Ergebnisse präsentiert, analysiert und diskutiert. Die Genauigkeit der Ergebnisse wird bewertet und mit anderen Arbeiten verglichen. Ein Ergebnis ohne Fehlerangabe ist kein Ergebnis."_

- **Schlussfolgerung**: Fassen Sie die wichtigsten Erkenntnisse und die weiteren Implikationen Ihrer Ergebnisse zusammen.  
  _"Die Schlussfolgerungen werden am Ende zusammengefasst und bieten einen knappen Überblick über die Arbeit und ihre Ergebnisse."_

### 3. `settings/`
Dieser Ordner enthält die Konfigurationsdateien zur Anpassung der Protokolle.

- **`acronyms_de.tex`**: Enthält vordefinierte deutsche Abkürzungen. Sie können nach Belieben eigene Abkürzungen hinzufügen.

- **`acronyms_eng.tex`**: Enthält vordefinierte englische Abkürzungen. Sie können nach Belieben eigene Abkürzungen hinzufügen.

- **`commands.tex`**: Diese Datei enthält benutzerdefinierte Befehle für Ihr LaTeX-Dokument.

- **`index.ist`**: Wenn Sie ein Indexverzeichnis in Ihr Protokoll aufnehmen möchten, können Sie die Einstellungen hier konfigurieren.

- **`packages.tex`**: Alle benötigten LaTeX-Pakete werden in dieser Datei geladen. Wenn Sie Overleaf verwenden, werden die Pakete automatisch geladen. Bei der Verwendung von MiKTeX oder anderen lokalen Umgebungen müssen möglicherweise fehlende Pakete manuell installiert werden.

- **`settings.tex`**: Diese Datei enthält die allgemeinen Einstellungen für die Protokolle, wie z.B. Seitengeometrie, Autoreninformationen, Farbanpassungen für Links und Formatierungen für Codeauflistungen. Wichtige Einstellungen:

  - Zeile 9: `\addbibresource{}` – Fügen Sie hier den Pfad zu Ihrer persönlichen Bibliografie-Datei hinzu. Stellen Sie sicher, dass Sie eine `.bib`-Datei für korrektes Zitieren einbinden.

- Tabellen-Ordner: Wenn nötig, können Sie einen separaten Ordner für Tabellen erstellen und diese in Ihrem Protokoll referenzieren.

## Nutzung

1. Klonen Sie dieses Repository auf Ihren lokalen Rechner oder laden Sie die Zip-Datei herunter. Wenn Sie Overleaf verwenden möchten, ist die Zip-Datei die bevorzugte Version, da Sie die Zip-Datei hochladen können.
2. Aktualisieren Sie die Dateien `settings.tex`, `acronyms_de.tex` und `acronyms_eng.tex` entsprechend den Anforderungen für Ihr spezifisches Experiment und Protokoll.
3. Fügen Sie die Abbildungen in die entsprechenden Unterordner im Verzeichnis `figures/` ein.
4. Schreiben Sie Ihre Protokolle im Ordner `protocolls/` unter Verwendung der LaTeX-Vorlagenstruktur.
5. Stellen Sie sicher, dass Ihre Bibliografiedatei in `settings.tex` korrekt eingefügt und referenziert ist.
