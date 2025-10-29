# Abschlussprojekt PowerBI: 🚨 Notfallanalyse: Erpressungsversuch durch angeblichen Datenleak

![Startseite der Präsentation: Notfallsitzung des Bankvorstandes](img/screenshot0.png)

## 📋 Dringliche Agenda

- Situation: Erpressungsdrohung mit angeblichem Datenleak unserer Kundendaten
- Auftrag: Ad-hoc-Analyse zur Validität der vorgelegten Daten
- Methodik: Forensische Datenanalyse in PowerBI
- Ergebnis: 20 eindeutige Beweise für Datenfälschung
- Empfehlung: Strategie zur Abwehr der Erpressung-

## 🎯 Kernaussage

Der vorgelegte Datensatz ist eine Fälschung - ich habe 20 eindeutige Beweise identifiziert, die zeigen, dass es sich um synthetische Mockdaten handelt, nicht um einen echten Datenleak unserer Systeme.
![Seite 14 des Ad-hoc-Berichts: 14 Beweise für Fälschung des Datensatzes](img/screenshot1.png)

## 🔍 Beweiskategorien für die Fälschung

1. PCI-DSS Compliance-Verstöße als Fälschungsindikator

- CVV-Codes im Klartext gespeichert → unrealistisch für echte Bankdaten
- Unverschlüsselte Kreditkartennummern → würde sofort entdeckt werden
- Fehlende Zugriffskontrollen dokumentiert → technisch unmöglich

2. Zeitliche Anomalien

- Transaktionslücken täglich 22-03 Uhr CST → typisches Skript-Muster
- Keine 24/7-Aktivität wie bei echten Banktransaktionen
- Perfekte periodische Muster → mathematisch zu regelmäßig

3. Datenstruktur-Beweise

- Ungewöhnliche Datenhierarchien und -beziehungen
- Inkonsistenzen in den Datenattributen

![KPIs aus dem Datensatz](img/screenshot2.png)

4. FICO-Score Anomalien

- Auffälligkeiten im Scoring-Modell:
- Statistisch unmögliche Verteilung: Keine natürliche Streuung
- Perfekte Korrelationen: Keine realen Ausreißer
- Vorhersagbare Muster: Algorithmisch generiert, nicht organisch gewachsen
- Gewichtung der analysierten Faktoren:
- Zahlungshistorie (35%) - Zu perfekte lineare Abhängigkeiten
- Kreditauslastung (30%) - Mathematisch ideale Verteilungen
- Kreditkontohistorie (15%) - Fehlende realistische Altersverteilung
- Kreditmix (10%) - Stereotype Kombinationen
- Neue Kreditanfragen (10%) - Gleichmäßige statt burstartige Muster

5. Geographische Inkonsistenzen

- CST/UTC-Zeitzonenkonflikte bei internationalen Transaktionen
- Fehlende lokale Besonderheiten im Zahlungsverhalten
- Uniforme Verteilungen über verschiedene Regionen
- Übermäßige Ähnlichkeiten zwischen den Transaktionen

![Suchseite zur vollständigen Aufklärung des Datensatzes](img/screenshot3.png)

## Forensische Analyse-Ergebnisse

18 Beweise im Detail:

1. Klartext-CVV Codes (PCI-DSS Verstoß #1)

2. Unverschlüsselte Kartennummern (PCI-DSS Verstoß #2)

3. Regelmäßige Transaktionslücken (22-03 Uhr Pattern)

4. Fiktive Namensgenerierung (erkennbare Algorithmen)

5. Perfekte FICO-Score-Verteilung (statistisch unmöglich)

6. Fehlende Datenbank-Konsistenz (keine Referential Integrity)

7. Vorhersagbare Betragsmuster (mathematische Sequenzen)

8. Zeitzonen-Inkonsistenzen (CST/UTC Konflikte)

9. Fehlende Transaktionsgebühren (unrealistisch für Bankdaten)

10. Uniforme Kreditlimits (keine individuelle Risikobewertung)

11. Synthetische Adressgenerierung (erkennbare Muster)

12. Fehlende historische Daten (keine echte Zeitreihe)

13. Perfekte Datenqualität (keine echten Dirty Data)

14. Algorithmische Kundenalter (gleichmäßige Verteilung)

15. Fehlende System-Metadaten (keine Audit-Trails)

16. Vorhersagbare Kontonummern (sequenzielle Generierung)

17. Uniformes Zahlungsverhalten (keine kulturellen Unterschiede)

18. Fehlende Saisonalität (keine echten Marktmuster)

19. Mathematisch ideale Korrelationen (keine realen Unsicherheiten)

Reproduzierbare "Zufalls"muster (deterministische Generierung)
![Analyseseite: Angeblich geleakte Kundendaten und Zusammenhänge](img/screenshot4.png)

## 🛡️ Datenmodell & Analyse-Architektur

![Diagramme: Fälschungsmuster im Datensatz](img/screenshot5.png)

Forensisches Datenmodell:

- Zentrale Fälschungs-Indikatoren-Tabelle → systematische Beweisführung
- Verknüpfte Entitäten: Transaktionen, Kunden, Karten → umfassende Analyse
- Transaktions-Anomalie-Erkennung → Pattern-Analyse
- Zeitreihen-Forensik → Identifikation synthetischer Muster

Statistische Abweichungsanalyse → Nachweis künstlicher Generierung

## 💡 Handlungsempfehlung

Sofortmaßnahmen:

- Erpresser konfrontieren mit den 20 Fälschungsbeweisen
- Strafanzeige stellen wegen versuchter Erpressung
- Interne Kommunikation zur Beruhigung der Stakeholder
- Security-Review trotzdem durchführen (Best Practice)

Langfristig:

- Implementierung erweiterter Datenforensik-Tools
- Regelmäßige Penetration-Tests
- Mitarbeiter-Sensibilisierung für Social Engineering

Fazit: Die forensische PowerBI-Analyse beweist eindeutig, dass es sich um synthetische Mockdaten handelt. Unser Banksystem war nicht kompromittiert. Die Erpressungsdrohung kann mit Datenkompetenz abgewehrt werden.
