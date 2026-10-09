# Picnic Trinkgeld-Tracker

Android-App zur Erfassung und Auswertung von Trinkgeldern und Schichten im Picnic-Lieferalltag. Dieses Repository stellt die APK zum Download bereit; es enthält nicht den Quellcode der App.

## Download

Aktueller Download-Stand: v1.10.0

[Picnic-Trinkgeld-Tracker.apk herunterladen](https://github.com/david-g927/trinkgeld-tracker-releases/raw/refs/heads/main/Picnic-Trinkgeld-Tracker.apk)

Der Link führt direkt zur APK-Datei auf dem Branch `main`. Die Datei wird bei neuen Versionen ersetzt.

## Funktionsumfang

- Trinkgeld-Auswertung: Analysen nach Postleitzahl, Straße, Wochentag und Schicht sowie Trenddarstellungen über Wochen, Monate und Halbjahre.
- Interaktive Analysen: Detailansichten der zugehörigen Schichten beim Antippen einer Auswertung.
- Schicht-Erfassung: Unterstützung für Liefer-, Innendienst- und HubHelp-Schichten. HubHelp-Stunden werden bei den Trinkgeld-Kennzahlen gesondert behandelt.
- Schicht-Erinnerungen: Benachrichtigung nach sechs Stunden und Unterstützung beim Schichtabschluss anhand hinterlegter Schichtvorlagen.
- Feierabend-Check: Übersicht zum erfassten Bargeld-Trinkgeld am Ende einer Tour.
- Standort-Unterstützung: Rückgriff auf den letzten bekannten Standort bei fehlendem GPS-Signal und Hinweis auf veraltete Standortdaten. Hintergrund-Ortung wird mit entsprechender Berechtigung unterstützt.
- Datenverwaltung: CSV-Import, CSV-Export sowie vollständige JSON-Backups und Wiederherstellung.
- In-App-Updater: Funktion zur Erkennung und zum Download neuer App-Versionen.

Diese Übersicht beschreibt den dokumentierten Funktionsumfang. Sie ist kein versionsspezifisches Änderungsprotokoll für v1.10.0.

## Installation auf Android

1. Lade die APK über den Download-Link auf dein Android-Gerät herunter.
2. Öffne `Picnic-Trinkgeld-Tracker.apk` über die Downloads oder deinen Dateimanager.
3. Falls Android danach fragt, erlaube deinem Browser oder Dateimanager die Installation unbekannter Apps. Erteile diese Berechtigung nur für eine Quelle, der du vertraust.
4. Tippe auf „Installieren“ und öffne anschließend die App.
5. Die Erlaubnis zur Installation unbekannter Apps kannst du danach wieder deaktivieren.

Die Bezeichnungen der Android-Menüs können je nach Gerät und Android-Version abweichen.

## Vorhandene Installation aktualisieren

1. Erstelle vor dem Update ein JSON-Backup über die Daten- und Backup-Verwaltung der App.
2. Lade die aktuelle APK herunter und öffne sie.
3. Wähle „Aktualisieren“, sofern Android die Datei als Update der installierten App erkennt.

Deinstalliere die bestehende App nicht vorsorglich. Sichere deine Daten, bevor du eine Neuinstallation oder Fehlerbehebung durchführst.

## Berechtigungen

Für die beschriebenen Standort- und Erinnerungsfunktionen können entsprechende Android-Berechtigungen erforderlich sein:

- Standort: zur Erfassung von Koordinaten.
- Hintergrund-Standort: für die Standort-Erfassung bei gesperrtem Bildschirm, sofern du diese Funktion nutzen möchtest.
- Benachrichtigungen: für Schicht-Erinnerungen.

## Versionen und Veröffentlichungen

Der aktuelle Download wird direkt als APK in diesem Repository bereitgestellt. Zum Zeitpunkt dieser README-Überarbeitung sind keine GitHub-Releases veröffentlicht.

Die [Commit-Historie](https://github.com/david-g927/trinkgeld-tracker-releases/commits/main/) dokumentiert die bisherigen Datei-Updates.

## Fehler melden und Feedback geben

[Fehler oder Verbesserungsvorschlag melden](https://github.com/david-g927/trinkgeld-tracker-releases/issues/new)

Bitte gib dabei die App-Version, deine Android-Version, das Gerätemodell und die Schritte zum Nachstellen an. Füge gegebenenfalls einen Screenshot ohne persönliche Daten hinzu. Veröffentliche keine Backups, genauen Standortdaten oder anderen sensiblen Informationen.
