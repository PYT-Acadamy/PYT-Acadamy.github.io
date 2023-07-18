---
title: PYT-Academy Self hosted Server Projekt
date: 2023-07-18 12:00:00 +0100
categories: [Server, Projekt]
tags: [open-source, selfhoted, server]
author: david
---

# Gesprächpunkte

1. [Cloud-Speicher](#cloud-speicher-software)
Wir haben die Absicht, einen Cloud-Speicher für unseren Verein einzurichten. Angesichts unserer Anforderungen und Nutzungsvolumens, haben wir vorläufig eine Speichergröße von 250 bis 500GB ins Auge gefasst. Details zur Umsetzung müssen noch geklärt werden.

2. E-Mail-Server
Wir planen, einen E-Mail-Server für unseren Verein aufzusetzen. Die Einzelheiten dazu wurden während des Gesprächs nicht weiter ausgeführt und bedürfen weiterer Diskussion und Planung.

3. Passwortmanagement
Wir haben die Idee eines Passwortmanagement-Systems in Betracht gezogen. Allerdings sind die Details zu dieser Anwendung noch unklar und müssen noch erörtert werden.


## Zeitrahmen
Wir haben einen Zeitrahmen von etwa 3 Monaten zur Einrichtung und Inbetriebnahme des Servers anvisiert. Wir sind eine kleine Gruppe von vier Personen und wollen den Server zuerst nur für uns nutzen. Wenn der Betrieb stabil ist, beabsichtigen wir, unsere Dienste auch in Paraguay anzubieten.

## Ziel
Unser Hauptziel ist es nicht, Gewinn zu erzielen, sondern das Projekt als Lern- und Übungsmöglichkeit zu sehen. Wir möchten jedoch auch unsere Dienste einer kleinen Gruppe anbieten und so unsere Vereinskasse für weitere Projekte und Investitionen aufbessern.

## Besonderheiten:
Wir haben darüber diskutiert, uns durch bestimmte Alleinstellungsmerkmale von großen Unternehmen abzuheben. Diese sind: hohe Sicherheit, persönlicher Kontakt und exzellenter Service.

## Cloud

Die Auswahl der richtigen Cloud-Speicher-Software für einen Server kann eine herausfordernde Aufgabe sein. Wir haben uns verschiedene Optionen angesehen und möchten in diesem Artikel ownCloud, Nextcloud, Pydio und Seafile vergleichen. Hier sind unsere Notizen zu den jeweiligen Lösungen:

### ownCloud
ownCloud scheint auf den ersten Blick eine gute Wahl zu sein. Es handelt sich um eine Open-Source-Software mit einer aktiven Community, die kontinuierlich daran arbeitet. Ein großer Pluspunkt ist, dass ownCloud den Datenschutzvorschriften, wie der GDPR (General Data Protection Regulation) und der LGPD (Lei Geral de Proteção de Dados), entspricht. Die Software bietet auch die Möglichkeit zur Aktivierung von 2FA (Two-Factor Authentication) und MFA (Multi-Factor Authentication) für zusätzliche Sicherheit. Allerdings könnte ownCloud mehr Informationen über die Funktionalitäten ihrer Software bereitstellen, da ihre Werbung hauptsächlich oberflächlich ist und nicht ins Detail geht.

### Nextcloud
Nextcloud ist ähnlich wie ownCloud, da es ebenfalls als Open-Source-Lösung mit einer aktiven Community entwickelt wird. Nextcloud wirbt mit einem ansprechenden Design und einer Vielzahl von Features. Jedoch liegt uns die Sicherheit besonders am Herzen, und in dieser Hinsicht bietet Nextcloud nicht viel Neues im Vergleich zu ownCloud.

### Pydio
Pydio hebt sich von den vorherigen Lösungen ab, indem es bereits auf den ersten Blick mit seiner Sicherheit, Skalierbarkeit, Open-Source-Natur und den Self-Hosting-Möglichkeiten wirbt. Pydio gibt uns außerdem detailliertere Einblicke in die Funktionsweise ihrer Software. Auf ihrer Webseite konnten wir feststellen, dass Pydio eine breite Palette von Geräten unterstützt, darunter Windows, MacOS, Linux, Android, iPads und iPhones. Die Sicherheit hat für Pydio einen hohen Stellenwert.

### Seafile
Zuletzt haben wir uns Seafile angesehen. Diese Lösung ähnelt Pydio, bietet jedoch zusätzliche Möglichkeiten beim Download. Seafile unterstützt auch ältere Geräte wie Windows 7 und ältere Macs. Interessanterweise kann Seafile auch vollständig über die Kommandozeile unter Linux gesteuert werden, falls dies gewünscht ist. Für Android-Nutzer gibt es die Möglichkeit, Seafile sowohl aus dem Google Play Store als auch von F-Droid herunterzuladen. Selbstverständlich werden auch iPad- und iPhone-Geräte unterstützt.

### Abschließende Gedanken
Bei der Auswahl einer Cloud-Speicher-Software für Ihren Server ist es wichtig, Ihre Anforderungen an Sicherheit, Funktionalität und Kompatibilität mit verschiedenen Geräten zu berücksichtigen. OwnCloud und Nextcloud sind solide Optionen mit einer aktiven Community, während Pydio mit einem Schwerpunkt auf Sicherheit und Einblick in die Funktionsweise hervorsticht. Seafile bietet zusätzliche Möglichkeiten beim Download und unterstützt eine Vielzahl von Geräten.

| Plattform | ownCloud | Nextcloud | Seafile | Pydio |
|:--------------|:----------------------------|:----------------------------|:----------------------------|----------------------------:|
| Open Source? | Ja | Ja | Ja | Ja |
| Lizenz | AGPLv3 | AGPLv3 | AGPLv3 | AGPLv3 |
| Community | Aktive und engagierte Community | Aktive und engagierte Community | Aktive Community | Aktive Community |
| Verschlüsselung | Server-seitig | Server-seitig | Datei-basiert | Datei-basiert |
