# Testmodul: Zugangskontrolle (Access Control)

**Referenz:** ISO 27001:2022 Annex A 5.15, 5.16, 5.18

## 1. Testschritte
1.  **Richtlinienprüfung:** Besteht eine klare Berechtigungsrichtlinie (RBAC - Role Based Access Control)?
2.  **User Provisioning:** Prüfung des Onboarding-Prozesses für 3 Beispiel-Mitarbeiter.
3.  **Rechte-Audit:** Abgleich der Berechtigungen eines Administrators mit der Jobbeschreibung.
4.  **De-Provisioning:** Prüfung, ob Zugänge von 3 ausgeschiedenen Mitarbeitern innerhalb von 24h gesperrt wurden.

## 2. Erwartete Evidenz
* Active Directory Export (Gruppenmitgliedschaften).
* Ticketsystem-Auszüge (Zugangsanträge).
* Protokoll der Quartals-Rezension der Rechte durch Abteilungsleiter.

## 3. Mögliche Abweichungen (Nonconformities)
* **Minor:** Ein Mitarbeiter hat Rechte, die nicht mehr benötigt werden.
* **Major:** Kein Nachweis über die Sperrung von Accounts nach Austritt gefunden.
