# OHVL · Open Headset Voice Lab

Von **VoltexModz / NekoZDevTeam** · By **VoltexModz / NekoZDevTeam**

Hier veröffentlichen wir Downloads und Informationen zum Projekt. Der aktuelle
Download ist **OHVL Diagnostics 0.3.2**, ein Development-Teststand für Geräteberichte.
Voice Lab, Audio-Modifikationen und der Flasher sind **nicht** enthalten.
Der Anwendungsquellcode bleibt privat. Ältere Diagnoseversionen bleiben unter Releases verfügbar.

## Diagnoseprogramm herunterladen

**[OHVL Diagnostics 0.3.2 — Testerpaket für Windows x64](https://github.com/VoltexModz/OHVL/releases/download/diagnostics-0.3.2/OHVL-Diagnostics-0.3.2-Testerpaket.zip)**

[Release und Hinweise](https://github.com/VoltexModz/OHVL/releases/tag/diagnostics-0.3.2)
· [SHA-256-Prüfsumme](https://github.com/VoltexModz/OHVL/releases/download/diagnostics-0.3.2/OHVL-Diagnostics-0.3.2-Testerpaket.zip.sha256)

Bitte das **Testerpaket.zip** herunterladen. GitHubs automatisch angebotene
„Source code“-Archive enthalten nur die Dateien dieses Download-Repositories,
nicht das Programm und nicht dessen Quellcode.

### Wozu ist das gut?

Mit freiwilligen Geräteberichten wollen wir Unterschiede zwischen Headset-Modellen
und Hardwarevarianten besser verstehen. Diagnostics erfasst ausgewählte USB-/HID-
Merkmale und freiwillige Angaben. Es flasht keine Firmware, ersetzt keine Ansagen,
verändert keine Einstellungen und führt keinen Reset aus.

Bekannte Anschlüsse werden zuerst gesucht. Alternativ führt ein Assistent durch
das Anstecken: USB-Ausgangsstand erfassen, dann nur das Headset verbinden. Mehrere
Headsets lassen sich nacheinander prüfen. Andere Geräte werden dadurch nicht
automatisch als kompatibel oder als Sena bestätigt.

Die bestätigte Versionsabfrage verwendet belegte Produkt-/Protokollzuordnungen
und passende HID-Merkmale. Das gemeldete 50S-Profil ist in 0.3.2 berücksichtigt.
Unbekannte Antwortformate bleiben unbestätigt; USB-Revisionen sind keine
Firmwareversionen. Nicht belegte Befehle werden nicht ausprobiert.

### So testest du

1. Das gesamte ZIP in einen Ordner entpacken. Nicht direkt im ZIP starten.
2. `START-HERE.html` öffnen: bebilderte Anleitung auf Deutsch und Englisch, offline nutzbar.
3. Sena Manager, OpenSena und Voice Lab schließen. Ein USB-Datenkabel verwenden.
4. `app/OHVL.Diagnostics.exe` starten und dem Assistenten folgen. Eine separate .NET-Installation ist nicht nötig.
5. Nur bekannte Angaben ergänzen. Nichts zerlegen, keine Seriennummer eintragen.
6. Bericht ansehen und speichern. Die neue JSON-Datei oder Berichts-ZIP über euren
   vereinbarten privaten Kontakt an VoltexModz / NekoZDevTeam schicken.

Bitte **keine Diagnoseberichte öffentlich hochladen**. Auch ein Fehlerbericht hilft;
bei Problemen lässt sich erneut suchen und der bisherige Bericht behalten.
Keine Firmware, Audioaufnahmen oder kompletten Projektordner mitschicken.
Es erfolgt kein automatischer Upload.

### Teststand und Sicherheit

Dies ist ein öffentliches **Pre-release / Development**, keine allgemeine
Kompatibilitätszusage. **43 statisch belegte Produktkennungen sind nicht 43 getestete
Modelle.** Ein eingesandter 0.3.2-Bericht zeigt eine erfolgreiche 30K-Versionsabfrage;
die echte 50S-Abfrage und weitere Varianten müssen noch getestet werden. Weitere
Manager-Protokolle sind nicht vollständig umgesetzt. Ein Diagnosebericht ist
**keine Freigabe zum Modden oder Flashen**.

Das Programm ist nicht digital signiert. Bei Sicherheitswarnungen nachfragen und
deren Wortlaut ohne persönliche Daten an den vereinbarten Kontakt schicken.
Schutzsoftware nicht abschalten. Eine SHA-256-Prüfsumme ersetzt keine Codesignatur
oder Sicherheitsgarantie.

Persönliche Kennungen und lokale Pfade werden im vorgesehenen Export ausgeschlossen;
eigene Eingaben, Zeitangaben und Hardwarekombinationen können trotzdem zuordenbar
sein. Daher den Bericht vor dem Teilen prüfen. **Diagnostics bleibt offline:**
keine Telemetrie, Aktivierung, Fernabschaltung oder automatischen Uploads.

## English

This public repository distributes **OHVL Diagnostics only**. The current download
is **0.3.2**, a development pre-release for voluntary device reports. The Voice Lab
editor, audio modifications, firmware flasher and application source code are not included.

Download the **Testerpaket.zip** above, extract the whole archive and open
`START-HERE.html`. The app and illustrated guide support English and German.
Close other headset managers, use a USB data cable and run `app/OHVL.Diagnostics.exe`
on Windows x64. Several headsets can be checked in sequence; no separate .NET setup is needed.

Version queries use manager-evidenced product/protocol mappings and matching HID
capabilities, including the reported 50S profile. Unknown response formats remain
unconfirmed. 43 mapped product IDs are not 43 hardware-tested models. A submitted
0.3.2 report shows a successful 30K read; a real 50S read test is still pending.
Other transports are not fully implemented. Detection is not modding or flash approval.

Diagnostics does not flash firmware, change settings or reset devices. It remains
offline: no activation, telemetry, remote shutdown or automatic uploads. Preview
and save the report, then send its JSON or report ZIP through your agreed private
contact with VoltexModz / NekoZDevTeam. **Do not post reports publicly.** Error reports
help too. Reports are data-minimized, not guaranteed anonymous.

The executable is unsigned. Ask about warnings and do not disable security software.
GitHub's automatic “Source code” downloads contain repository documentation, not
the app or its source. Previous diagnostics releases remain available.

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
