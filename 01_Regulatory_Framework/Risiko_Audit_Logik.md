# Methodik: Risikobasierte Audit-Priorisierung

## Zielsetzung
Ein Audit nach ISO 27001 ist kein reiner Compliance-Check. Es muss sicherstellen, dass die Sicherheitskontrollen dort wirken, wo die höchsten Risiken für die Vertraulichkeit, Integrität und Verfügbarkeit von Informationen bestehen.

## Vorgehensweise
Ich priorisiere Audit-Aktivitäten basierend auf folgenden Faktoren:

| Faktor | Beschreibung | Auswirkung auf Audit |
| :--- | :--- | :--- |
| **Geschäftskritische Prozesse** | Prozesse mit hohem Einfluss auf den Umsatz oder die Reputation. | Tiefenprüfung (Full Scope) |
| **Asset-Wert** | IT-Systeme mit personenbezogenen Daten oder geistigem Eigentum. | Fokus auf technische Kontrollen |
| **Änderungshistorie** | Systeme/Prozesse, die kürzlich stark verändert wurden. | Erhöhte Stichprobenanzahl |
| **Vergangene Befunde** | Bereiche mit bekannten Schwächen in vorherigen Audits. | Nachverfolgung der Korrekturmaßnahmen |

## Beispielanwendung (Cloud-Service-Provider)
Statt alle Server gleich zu behandeln, konzentriert sich das Audit auf:
1.  Die **Mandantentrennung** in der Cloud-Architektur.
2.  Den **Zugangsschutz** der Administratoren (IAM).
3.  Die **Sicherheit der Lieferkette** (Drittanbieter von Speicherplatz).
