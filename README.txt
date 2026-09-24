# Vokabeltrainer – Installation auf GitHub Pages

Lade **alle vier Dateien** (`index.html`, `manifest.webmanifest`, `icon.png`, `apple-touch-icon.png`) in die oberste Ebene deines bestehenden GitHub-Pages-Repositories hoch. Ersetze dabei die bisherige `index.html`.

Danach kurz warten, die Pages-Seite in Safari neu laden und die alte Home-Bildschirm-Verknüpfung löschen und erneut über **Teilen → Zum Home-Bildschirm** hinzufügen.

Wichtig zur ersten Version:
- Listen, Profile, Einstellungen und Statistik werden lokal im Browser gespeichert.
- Export/Import erzeugt bzw. liest ein JSON-Backup.
- Sprachabfrage nutzt die vom Browser angebotene Web-Spracherkennung. Auf iOS muss das auf dem konkreten Gerät getestet werden.
- Vibration funktioniert nur, wenn der Browser die Vibration API unterstützt; iOS unterstützt sie typischerweise nicht.
- Der Foto-Import enthält bereits die Aufnahme-/Dateiauswahl, aber noch keine automatische OCR. Auf iPhone/iPad kann Text zunächst mit Apples Live Text aus einem Foto kopiert und in die Masseneingabe eingefügt werden.
