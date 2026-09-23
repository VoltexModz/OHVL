# OHVL · Open Headset Voice Lab

Von **VoltexModz / NekoZDevTeam** · By **VoltexModz / NekoZDevTeam**

Hier veröffentlichen wir Downloads und Informationen zum Projekt. Derzeit gibt es
hier ausschließlich **OHVL Diagnostics 0.3.0**, einen Development-Teststand für
Geräteberichte. Voice Lab, Audio-Modifikationen und der Flasher sind **nicht** in
diesem Download enthalten. Der Anwendungsquellcode bleibt privat.

## Diagnoseprogramm herunterladen

**[OHVL Diagnostics 0.3.0 — Testerpaket für Windows x64](https://github.com/VoltexModz/OHVL/releases/download/diagnostics-0.3.0/OHVL-Diagnostics-0.3.0-Testerpaket.zip)**

[Release und Hinweise](https://github.com/VoltexModz/OHVL/releases/tag/diagnostics-0.3.0)
· [SHA-256-Prüfsumme](https://github.com/VoltexModz/OHVL/releases/download/diagnostics-0.3.0/OHVL-Diagnostics-0.3.0-Testerpaket.zip.sha256)

Bitte das **Testerpaket.zip** herunterladen. GitHubs automatisch angebotene
„Source code“-Archive enthalten nur die Dateien dieses Download-Repositories,
nicht das Programm und nicht dessen Quellcode.

### Wozu ist das gut?

Mit freiwilligen Geräteberichten wollen wir Unterschiede zwischen Headset-Modellen
und Hardwarevarianten besser verstehen. Diagnostics sammelt ausgewählte USB- und
HID-Merkmale sowie deine freiwilligen Angaben. Es flasht keine Firmware, ersetzt
keine Ansagen und verändert keine Geräteeinstellungen.

Bekannte Anschlüsse werden zuerst automatisch gesucht. Sonst hilft ein Assistent:
erst den USB-Ausgangsstand erfassen, dann nur das Headset auf Aufforderung anstecken.
Mehrere Headsets lassen sich nacheinander prüfen. Andere Geräte werden dadurch
nicht automatisch als kompatibel oder als Sena erkannt.

Eine automatische Firmwareabfrage gibt es nur für ein eng geprüftes 30K-Profil und
erst nach Bestätigung. Beim 50S und unbekannten Profilen werden keine unbekannten
Herstellerbefehle ausprobiert. Eine fehlende Firmwareangabe darf leer bleiben.
Ein Diagnosebericht ist **keine Freigabe zum Modden oder Flashen**.

### So testest du

1. Das gesamte ZIP in einen Ordner entpacken. Nicht direkt im ZIP starten.
2. `START-HERE.html` öffnen: bebilderte Anleitung auf Deutsch und Englisch, offline nutzbar.
3. Sena Manager, OpenSena und Voice Lab schließen. Ein USB-Datenkabel bereithalten.
4. `app/OHVL.Diagnostics.exe` starten und dem Assistenten folgen. Eine separate .NET-Installation ist nicht nötig.
5. Nur bekannte Angaben ergänzen. Nichts zerlegen, keine Seriennummer eintragen.
6. Den Bericht ansehen, speichern und die neu erstellte JSON-Datei oder Berichts-ZIP
   über euren vereinbarten privaten Kontakt an VoltexModz / NekoZDevTeam schicken.

Bitte **keine Diagnoseberichte in öffentliche Issues hochladen**. Auch ein Fehlerbericht
oder „nicht erkannt“ hilft. Keine Firmware, Audioaufnahmen oder kompletten Projektordner
mitschicken. Es erfolgt kein automatischer Upload.

### Teststand und Sicherheit

Dies ist ein öffentliches **Pre-release / Development** zur Erprobung auf weiteren
Geräten, keine allgemeine Kompatibilitätszusage. Softwaretests wurden durchgeführt;
die Hardwareabnahme genau dieser Version 0.3.0 steht noch aus.

Das Programm ist noch nicht digital signiert. Bei einer Sicherheitswarnung bitte
deren Wortlaut ohne persönliche Daten an den vereinbarten Kontakt schicken und
nachfragen. Schutzsoftware nicht abschalten. Eine SHA-256-Prüfsumme ersetzt keine
Codesignatur oder Sicherheitsgarantie.

Berichte enthalten ausgewählte Gerätedaten und deine Eingaben. Persönliche Kennungen
und lokale Pfade werden im vorgesehenen Export ausgeschlossen; Zeitangaben und
Hardwarekombinationen können trotzdem zuordenbar sein. Daher vor dem Teilen prüfen.
Es gibt keine Telemetrie, Aktivierung oder Fernabschaltung in diesem Paket.

## English

This public repository currently distributes **OHVL Diagnostics 0.3.0 only**, a
development pre-release for voluntary device reports. The Voice Lab editor, audio
modifications, firmware flasher and application source code are not included.

Download the **Testerpaket.zip** above, extract the whole archive, and open
`START-HERE.html`. The illustrated guide and app support German and English.
Close other headset managers and run `app/OHVL.Diagnostics.exe` on Windows x64.
Use a USB data cable and follow the wizard. You can check several headsets in order.

Diagnostics does not flash firmware or change settings. Automatic version reading
is limited to a checked 30K profile after confirmation. For 50S and unknown profiles,
leave unknown version fields blank; the USB report is still useful. Detection does
not establish modding or flashing compatibility.

Preview and save the report, then send only the newly generated JSON or report ZIP
through your agreed private contact with VoltexModz / NekoZDevTeam. **Do not post
device reports in public issues.** No automatic uploads, telemetry, activation or
remote shutdown are included. Reports are data-minimized, not guaranteed anonymous.

This exact version still needs real-device acceptance. The executable is unsigned;
ask about security warnings and do not disable security software. GitHub's automatic
“Source code” downloads contain repository documentation, not the app or its source.

## Lizenz / License

Die Anwendung ist kostenlos und Closed Source. Für projekteigene Anwendungsteile
gilt die mitgelieferte **NekoZDevTeam Freeware License 1.0** (`app/LICENSE`).
Lizenzhinweise der mitgelieferten .NET-Komponenten liegen unter `app/licenses`.
Ein öffentliches Download-Repository ist keine Open-Source-Freigabe der Anwendung.

The application is free of charge and closed source under the bundled
**NekoZDevTeam Freeware License 1.0**. Third-party runtime notices remain applicable.

Unabhängiges Communityprojekt, nicht von Sena herausgegeben oder autorisiert.
Sena und Modellnamen dienen nur der Zuordnung und Kompatibilitätsbeschreibung.
No manufacturer firmware, original voice recordings or vendor tools are bundled.
