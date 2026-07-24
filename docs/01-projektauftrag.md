# Projektauftrag – Georg-Dashboard

## Ausgangslage

Ein Mitarbeiter bearbeitet für den VAB-Verbund umfangreiche Abrechnungen von Verkehrsunternehmen und wirkt gleichzeitig an zahlreichen Ausschreibungs- und Vergabeverfahren mit.

Die derzeitigen Arbeitsabläufe verteilen sich voraussichtlich auf verschiedene Dateien, E-Mails, Dokumentenablagen, Fristenlisten und persönliche Wiedervorlagen. Dadurch entstehen hoher manueller Aufwand, Medienbrüche und das Risiko, dass Fristen oder offene Rückmeldungen übersehen werden.

## Projektziel

Mit dem Georg-Dashboard soll eine zentrale browserbasierte Arbeitsoberfläche entstehen, die den Mitarbeiter bei seinen täglichen Aufgaben unterstützt und wiederkehrende Verwaltungsarbeiten reduziert.

## Geplante Hauptbereiche

- Startdashboard mit offenen Aufgaben und Warnungen
- Abrechnung von Verkehrsunternehmen
- Verwaltung von Verkehrsverträgen
- Ausschreibungs- und Vergabeverfahren
- Aufgaben, Fristen und Wiedervorlagen
- Dokumente und Kommunikation
- spätere Auswertungen über Qlik

## Technische Grundrichtung

- Ubuntu Server
- Docker Compose
- Python-Webanwendung
- PostgreSQL-Datenbank
- GitHub für Quellcode und Dokumentation
- zentrale browserbasierte Benutzeroberfläche
- Qlik ausschließlich für Auswertungen

## Projektgrundsatz

Die Anwendung soll für den Benutzer als einheitliches Fachverfahren erscheinen. Andere Dienste dürfen im Hintergrund unterstützen, sollen aber nicht als getrennte Arbeitsoberflächen sichtbar sein.

## Erste Projektphase

Vor der Programmierung werden gemeinsam mit dem zuständigen Mitarbeiter die tatsächlichen Arbeitsabläufe aufgenommen.

Dabei werden insbesondere ermittelt:

- regelmäßig durchgeführte Tätigkeiten
- verwendete Dateien und Datenquellen
- benötigte Prüfschritte
- wiederkehrende Fristen
- häufige Rückfragen
- bestehende Vorlagen
- mögliche Automatisierungen
- notwendige Berechtigungen
- vertrauliche Daten und Dokumente

## Abgrenzung der ersten Pilotversion

Die erste Pilotversion soll noch keine vollständige Vergabe- oder Finanzsoftware ersetzen.

Sie soll zunächst:

- Vorgänge zentral darstellen
- Aufgaben und Fristen überwachen
- Verträge strukturiert erfassen
- Abrechnungsprüfungen unterstützen
- Ausschreibungen übersichtlich abbilden
- Dokumente den jeweiligen Vorgängen zuordnen
- Bearbeitungsschritte nachvollziehbar dokumentieren
