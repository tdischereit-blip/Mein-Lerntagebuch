# Tag 7 – [08.06.2026]

## Was habe ich heute gelernt?
GitHub Actions führt automatisch Code aus wenn man
pusht. Eine YAML-Datei in .github/workflows/ reicht.
Das grüne Häkchen beim Commit bedeutet: alle Checks
bestanden.

## Welches Problem bin ich begegnet?
Die YAML-Datei hatte einen Einrückungsfehler –
GitHub Actions hat den Workflow nicht erkannt.

## Wie habe ich es gelöst?
YAML ist sehr empfindlich bei Leerzeichen. Mit einem
Online-YAML-Validator den Fehler gefunden und
2 Leerzeichen statt Tab verwendet.