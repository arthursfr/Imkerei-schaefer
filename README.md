# Imkerei Schäfer – Rechnungsprogramm 🍯

Kleines, kostenloses Rechnungsprogramm für Honigverkäufe. Es funktioniert komplett im Browser – ohne Server, Anmeldung oder externe Abhängigkeiten.

## Benutzung

1. `index.html` in einem Browser öffnen oder die Website über GitHub Pages aufrufen.
2. Absender- und Kundendaten, Rechnungsnummer, Honigsorten, Mengen und Preise eintragen.
3. Auf **Rechnung als PDF speichern** klicken und im Druckdialog **Als PDF speichern** wählen.
4. Rechnungen selbst sicher archivieren.

## GitHub Pages

1. Neues öffentliches Repository auf GitHub anlegen, zum Beispiel `imkerei-schaefer`.
2. Die Dateien `index.html`, `style.css`, `script.js` und `README.md` direkt in das Repository hochladen.
3. Unter **Settings → Pages → Build and deployment → Deploy from a branch** den Branch `main` und Ordner `/ (root)` auswählen und speichern.
4. Nach der Veröffentlichung ist die Website normalerweise unter `https://DEIN-BENUTZERNAME.github.io/imkerei-schaefer/` erreichbar.

## Hinweise

- Absenderdaten und die letzte verwendete Rechnungsnummer werden lokal im Browser über `localStorage` gespeichert, **nicht online synchronisiert**. Ein anderer Browser oder ein anderes Gerät führt gegebenenfalls dieselbe Rechnungsnummer nochmals – bitte vor dem Ausstellen kontrollieren.
- Die Anwendung übernimmt keine rechtliche oder steuerliche Prüfung. Die Steuerbefreiung nach § 19 UStG ist derzeit voreingestellt und muss für die Imkerei tatsächlich zutreffen.
- Das Liefer-/Leistungsdatum wird als identisch mit dem Rechnungsdatum ausgewiesen. Verwende diese Vorlage nur, wenn das tatsächlich stimmt, oder ändere den Hinweis im Code.
- Keine personenbezogenen echten Kundendaten oder vertraulichen Steuernummern direkt in die öffentlich zugänglichen Quelldateien schreiben.
- Ein PDF-Druck ist keine strukturierte elektronische Rechnung (z. B. XRechnung).

## Projektdateien

- `index.html` – Oberfläche und Rechnungs-Vorschau
- `style.css` – Gestaltung und Drucklayout
- `script.js` – Eingaben, Berechnung, lokale Speicherung und PDF-Druck
