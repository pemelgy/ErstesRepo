# AI Job-Markt 2024/2025 - Datengetriebene, globale Analyse der Einflussfaktoren auf Gehalt, Jobpotenziale sowie Sklill-Anforderungen mit Prognosen mittels Machine-Learning 

Dieses Projekt liefert einen Überblick über den globalen AI-Job Markt und zeigt wichtige und wissenswerte Erkenntnisse insbesondere hinsichtlich der Gehaltspotenziale und deren Einflussfaktoren.

## Ziel des Projekts

- Erkenntnisse über die Einflussfaktoren auf Gehalt und Jobpotenziale
- geeignet für alle Jobsuchenden in diesem Job-Markt

## Inhalte des Repos

Dieses Repository enthält:
- Hauptdateien: Datenbereinigung_AI_Job_vacancies_2025.py, EDA_AI_Jobs_2024_2025.py, 
  Präsentation Job_AI_Markt.pdf


## Verwendete Technologien

- Programmiersprache: z.B. Python / JupyterNotebook
- Bibliotheken: z.B. pandas, matplotlib, seaborn
- Sonstiges: Tableau, Power BI, Excel, Power Query

## Anmerkungen für den Leser

- dieses Projekt wurde mit mir und meiner Projektpartnerin Naoual durchgeführt wobei wir 
  mit unterschiedlichem Kenntnisstand in dieses Projekt gestartet sind
- wir haben das Projekt in der Mitte geteilt um gleiche Aufteilung des Arbeitsaufwandes zu 
  erreichen 
- in dieser Projektpräsentation verzichte ich auf den Machine-Learning - Teil, weil ich zur 
  Projektabgabe noch nicht über die notwendigen Kenntnisse über dieses Thema verfügt habe sondern nur meine Projektpartnerin Naoual
- ich habe mich auf die Analyse sowie Visualisierung in Python und Tableau konzentriert und die 
  Power-Point Präsentation erstellt 
- nach ersten Schritten zur explorativen Datenanalyse in Python habe ich mich dazu entschieden die 
  Analyse in Tableau fortzusetzen 
- um die Verteilung der Job-Skills auf die einzelnen Datensätze zu ermitteln haben wir die Tabelle mit
  Power Query bearbeitet so dass ein neues Arbeitsblatt in der Excel-Datei entstanden ist mit nur drei Spalten job_id, required_skills und einer Indexspalte. Somit konnten über eine One-to-Many-Beziehung in Power Query die required_skills anhand der job_id auf die einzelnen Datensätze verteilt werden
- auf Grund des sehr großen Datenumfangs mit rund 19000 Zeilen habe ich darauf verzichtet den Datensatz
  in GitHub zu laden
- die Quelle der Ursprungsdateien war Kaggle, leider ist der Datensatz aktuell dort nicht mehr 
  verfügbar

## empfohlene Vorgehensweise für den Leser

- Datenbereinigung_AI_Job_vacancies_2025.py zeigt die Datenvorbereitung in Python
- EDA_AI_Jobs_2024_2025.py liefert einen Überblick über die ersten Schritte der explorativen  
  Datenanalyse in Python
- den einfachsten Einstieg in das Projekt liefert die Präsentation Job_AI_Markt.pdf mit Screenshots 
  vorwiegend aus Tableau
