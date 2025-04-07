#  Willkommen auf meinem GitHub-Profil!👋

Hi, ich bin Sivanajani und ich studiere **Medizininformatik (B.Sc.)** an der FHNW und begeistere mich für die Schnittstelle zwischen **IT, Medizin und Organisation**.  
Mein Fokus liegt auf dem Frontend, aber auch das Backend und systemnahe Themen interessieren mich sehr.

---

## 🚀 Tech Stack & Interessen

- **Sprachen:** Python · Java · JavaScript · TypeScript · Google Apps Script · Kotlin · C · C++
- **Frameworks:** React · Spring Boot · Node.js · Vite
- **Infrastruktur & Server:** Docker · Apache · PostgreSQL · Orthanc (Open-Source PACS für DICOM, PACS-Integration)
- **DevOps & CI/CD:** GitHub Actions · CI/CD Workflows
- **Monitoring & Logging:** Prometheus · Grafana · Netdata · cAdvisor
- **Data Science & Analytics:**  Datenanalyse · Datenvisualisierung · NumPy · Pandas · Jupyter · Vision Transformer (ViT) · Klassifikation · Modelloptimierung · Medizindatensätze (z. B. Parkinson)
- **Security & Auth:** Keycloak (SSO, OAuth2)

---

## 💼 Projekte & Erfahrungen

### 🔬 HistoApp – Webapplikation zur Verwaltung histologischer Gewebeproben
HistoApp ist eine webbasierte Anwendung zur Anzeige, Verwaltung, Annotation und Kommentierung von Bildern histologischer Gewebeproben. Sie wurde im Rahmen eines Hochschulprojekts entwickelt und kombiniert moderne Webtechnologien.  

🔧 Tech Stack:
- **Frontend**: React · TypeScript · Vite · Material UI · Axios · React Router
- **Backend**: Spring Boot · Kotlin · RESTful API
- **Datenbank**: H2 (Kommentare & Tags)
- **Containerisierung**: Docker · Docker Compose
- **Monitoring**: Prometheus · Grafana

📌 Features:
- Anzeige & Verwaltung von Gewebebildern
- Tagging- und Kommentarfunktion für einzelne Bildinstanzen
- REST-Schnittstellen zur Datenverwaltung
- Monitoring der Systemleistung mit Prometheus & Grafana
- Containerisierte Entwicklungs- & Produktionsumgebung

---

### 🧾 Anamnese-Formular – Automatisierte Analyse medizinischer PDFs
Dieses Projekt dient der automatisierten Analyse und Verarbeitung medizinischer Anamnese-Formulare. Ziel ist es, Inhalte aus PDF-Dokumenten zu extrahieren, Checkboxen auszuwerten und mit einem definierten Satzkatalog abzugleichen. Ich durfte dieses bestehende Projekt übernehmen, weiterentwickeln und optimieren – mit Fokus auf Genauigkeit, Strukturierung und Erweiterbarkeit der Analysefunktionen.

🔧 Tech Stack:
- Python · Tesseract OCR · OpenCV · Pandas · CSV
- PDF & Bildverarbeitung · Texterkennung · Datenmatching

📌 Features:
- 📄 PDF-Konvertierung: Umwandlung von PDF-Dokumenten in hochauflösende Bilder
- 🧹 Bildvorverarbeitung: Binarisierung & Entzerrung zur Verbesserung der OCR-Ergebnisse
- 🔍 Texterkennung (OCR): Extraktion von Text und Metadaten mithilfe von Tesseract
- ☑️ Checkbox-Verarbeitung: Analyse von „Ja/Nein“-Markierungen inklusive Outlier-Filterung
- 📊 Satzabgleich: Matching der erkannten Inhalte mit einem vordefinierten Satzkatalog
- 📤 Ergebnisausgabe: Export der Resultate in strukturierte CSV-Dateien

---
### 🤖 Emotionserkennung mit Vision Transformer (ViT)

In diesem Projekt wurde das **vortrainierte Google ViT-Base-Patch16-224 Modell** eingesetzt, um Emotionen anhand von Bildern zu klassifizieren.  
Der Klassifikationskopf wurde für sieben Emotionen neu trainiert, wobei moderne Deep-Learning-Techniken zur Optimierung und Stabilisierung des Trainingsprozesses verwendet wurden.

**🔧 Tech Stack & Methoden:**  
- Vision Transformer (ViT) · PyTorch · Hugging Face Transformers  
- Datenaugmentation · Normalisierung · Early Stopping  
- Adam-Optimizer mit Weight Decay · Cross-Entropy-Loss · Learning Rate Scheduler

**📌 Highlights:**  
- Nutzung eines vortrainierten ViT-Modells zur Extraktion relevanter Bildmerkmale mittels Self-Attention  
- Anpassung des Klassifikationskopfs auf sieben Emotionsklassen  
- Anwendung von Datenaugmentation zur Verbesserung der Robustheit  
- Regulierung der Modellkomplexität durch Weight Decay  
- Stabilisierung des Trainings durch Early Stopping & Lernraten-Scheduling  
- Analyse von Overfitting anhand von Trainings- vs. Testgenauigkeit

---
### 🧠 Parkinson-Datensatzanalyse – Sprachdatenanalyse & Visualisierung zur Vorhersage klinischer Scores

In diesem Data-Science-Projekt wurde ein Datensatz mit **5'875 Stimmmessungen von 42 Parkinson-Patienten** im Frühstadium analysiert.  
Ziel war es, Sprachparameter wie **Jitter**, **Shimmer**, **HNR**, **NHR** etc. im Zusammenhang mit der **UPDRS-Skala** (Unified Parkinson’s Disease Rating Scale) zu untersuchen und visuell darzustellen.

Ich war verantwortlich für das **Preprocessing, die Analyse und die Visualisierung** der Daten und konnte dabei wertvolle Erfahrungen im Umgang mit realen, medizinischen Datensätzen sammeln.

**🔧 Tech Stack & Methoden:**  
- Python · Pandas · NumPy · Matplotlib · Seaborn  
- CSV-Parsing · Plausibilitätsprüfungen · Feature Engineering  
- Visualisierung (Violin Plots, Boxplots, Heatmaps, Histogramme, Scatterplots)

**📌 Highlights:**  
- Überprüfung & Bereinigung der Daten (NaNs, Duplikate, inkonsistente Werte)  
- Umwandlung und Kategorisierung von Merkmalen (z. B. Geschlecht, Probanden-ID)  
- Feature Engineering inkl. Interaktionsvariablen wie `motor_UPDRS * Jitter(%)`  
- Erstellung statistischer Visualisierungen zur Analyse geschlechtsspezifischer Unterschiede  
- Berechnung und Darstellung von Korrelationen zwischen klinischen Scores und Sprachmerkmalen

**📊 Ziel:**  
Die Ergebnisse liefern erste Hinweise darauf, dass Sprachveränderungen zur Vorhersage des **Parkinson-Verlaufs** genutzt werden können – z. B. über nicht-lineare Regressionsmodelle oder Klassifikatoren.

---

### 🌌 Region Growing zur Stern-Segmentierung (Bildverarbeitung mit Python)

In diesem Projekt wurde eine **Bildverarbeitungsroutine** entwickelt, um segmentierte Objekte (Blobs) in einem Bild automatisch zu labeln.  
Ziel war es, mithilfe des **Region-Growing-Algorithmus** (Flood-Fill) einzelne Sterne im Bild `stars.png` zu erkennen, zu beschriften und individuell darzustellen.

**🔧 Tech Stack & Methoden:**  
- Python · NumPy · Matplotlib · Scikit-Image  
- Flood-Fill (Region Growing) · Segmentierung · Labeling · Visualisierung

**📌 Features:**  
- Einlesen & Umwandlung von RGB-Bildern in Graustufen  
- Automatische Schwellenwertbildung zur Binarisierung  
- Anwendung von `skimage.segmentation.flood()` zur Objekterkennung  
- Labeling einzelner Blobs (Sterne) mit eindeutigen Werten  
- Visualisierung aller Objekte mit Farbzuordnung (`nipy_spectral`)  
- Einzelmasken pro Segment (Stern) zur Weiterverarbeitung oder Analyse

**🖼️ Ergebnis:**  
- Jeder erkannte Stern wird eindeutig gelabelt und kann individuell dargestellt oder analysiert werden  

---

## 📫 Kontakt & mehr

📍 Basel, Schweiz  
📧 Kontakt auf Anfrage  
<!-- 🌐 [Portfolio (in Entwicklung)](https://github.com/sivanajani/portfolio)  --> 
---

🌱 **Aktuell:**  
Ich arbeite an meiner Bachelor-Thesis und erweitere kontinuierlich meine Kenntnisse in **Webentwicklung**, **DevOps** und **Data Science**. Ich freue mich über spannende Kontakte oder neue Herausforderungen!

---


<!--
## Hi there 👋
Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
