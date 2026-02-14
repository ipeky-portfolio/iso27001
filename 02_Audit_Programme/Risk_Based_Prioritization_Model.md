# Risikobasiertes Audit-Priorisierungsmodell

Um ein effektives Audit-Programm für ein komplexes Unternehmen zu erstellen, nutze ich eine Risikomatrix, um **Audit-Schwerpunkte** zu setzen.

## 1. Risikofaktoren (Gewichtung)
Jeder Geschäftsbereich wird anhand dieser Faktoren bewertet:
* **A: Kritikalität der Daten (1-5):** Verarbeitung von personenbezogenen Daten (PII) oder Geschäftsgeheimnissen.
* **B: IT-Abhängigkeit (1-5):** Wie schnell entstehen finanzielle Schäden bei Systemausfall?
* **C: Änderungsrate (1-5):** Häufigkeit von Software-Releases oder Infrastrukturänderungen.
* **D: Historische Befunde (1-5):** Anzahl der Feststellungen im Vorjahr.

**Formel:** $Gesamtrisiko = (A+B+C) \times D$

## 2. Audit-Strategie
| Risikoscore | Einstufung | Audit-Umfang |
| :--- | :--- | :--- |
| **> 50** | Hoch | Vollaudit, inklusive technischer Tiefenprüfung (Penetration Test Report Review). |
| **25 - 50** | Mittel | Audit der Kernkontrollen (Annex A), Stichproben. |
| **< 25** | Niedrig | Dokumentenprüfung, Management-Interviews. |

## 3. Prioritäten für 2026
1.  **HR-Abteilung (Score 60):** Hoher PII-Anteil, neue Cloud-Software eingeführt.
2.  **IT-Infrastructure (Score 55):** Zentraler kritischer Prozess.
3.  **Marketing (Score 20):** Geringe IT-Abhängigkeit.
