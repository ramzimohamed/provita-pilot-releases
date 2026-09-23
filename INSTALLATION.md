# ProVita ERP Pilot 0.1.3

Für Macs mit Apple-Chip (M1 oder neuer) und macOS 14 oder neuer. Dies ist der ProVita-Pilot, noch kein vollständiger Ersatz aller HERO-Funktionen.

**Geprüfter Stand 24.09.2026:** Der echte Update-Test 0.1.2 → 0.1.3 ist auf unserem Mac bestanden: Download, Signaturprüfung, Installation, automatischer Neustart, erneute Anmeldung, Kontaktliste und Kontakt-Detail. Die App zeigt Version 0.1.3 und „Alles aktuell“. Das korrigierte Updatearchiv liegt ausschließlich unter `repack-2e9130af`; App und DMG sind unverändert. Das historische Archiv unter `/0.1.3/aarch64/` nicht verwenden. Installation auf Michas eigenem Mac ist noch nicht geprüft.

## Einmal installieren

1. Für den vereinbarten Test die [Mac-Programmdatei herunterladen](https://provita-updates.noctive.de/ProVita%20ERP%20Pilot_0.1.3_aarch64.dmg).
2. Die heruntergeladene DMG öffnen und **ProVita ERP Pilot** in **Programme** ziehen.
3. Die App aus **Programme** starten. Zugangsdaten erhältst du getrennt von Ramzi; für die Anmeldung wird eine Internetverbindung benötigt.

Eine vorhandene ProVita-Installation nicht löschen oder ungeprüft ersetzen. Wenn bereits eine Version installiert ist, zunächst Ramzi informieren beziehungsweise den freigegebenen Aktualisierungsweg verwenden.

## Spätere Aktualisierungen

Im Programm **„Nach Aktualisierung suchen“** wählen. Bei einer angebotenen Version folgen **„Herunterladen“**, **„Jetzt installieren“** und **„Jetzt neu starten“**. Vor der Installation laufende Arbeit abschließen. Die App prüft und installiert nicht ungefragt im Hintergrund.

Der beschriebene Weg wurde mit 0.1.2 → 0.1.3 tatsächlich geprüft. Wer 0.1.3 neu installiert, sieht zunächst „Alles aktuell“. Nach einem Neustart ist eine erneute Anmeldung erforderlich. Spätere Versionen müssen jeweils gebaut, geprüft, signiert und veröffentlicht werden; bloße Codeänderungen erscheinen nicht automatisch beim Empfänger.

## Testumfang und Erreichbarkeit

Diese Fassung enthält Anmeldung, lesende Bestandsansichten mit synthetischen Testdaten und den Aktualisierungsweg. Anlegen, Ändern, Buchen und Planen sind nicht enthalten; ebenso wenig die übrigen noch nicht verfügbaren Fachmodule. Keine echten Kundendaten eingeben. Es ist kein vollständiger HERO-Ersatz und keine Freigabe für den Kundenbetrieb.

Die getrennte ProVita-Testumgebung ist seit **24.09.2026 ohne feste Abschaltfrist** eingerichtet. Datenbank, API und Verbindung sind nach einem kontrollierten Neustart der ProVita-Umgebung selbstständig gestartet; der Datenabruf in der App wurde danach geprüft. Wartungen oder Störungen können die Erreichbarkeit weiterhin unterbrechen. Der Download-/Updatekanal bleibt unabhängig davon bestehen. Die Zugangsdaten werden separat und nicht öffentlich übergeben.

## Falls etwas nicht klappt

Die genaue Meldung oder ein Bildschirmfoto an Ramzi senden. Keine macOS-Schutzfunktionen abschalten und keine unbekannten Terminalbefehle ausführen. Passwörter gehören nicht ins Bildschirmfoto.
