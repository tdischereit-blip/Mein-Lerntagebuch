# Tag 4 – [05.06.2026]

## Was habe ich heute gelernt?
Was ein Branch ist: eine parallele Version des Projekts.
`git checkout -b feature/zusammenfassung` erstellt
einen neuen Branch und wechselt direkt hinein.
`git branch` zeigt alle vorhandenen Branches.

## Welches Problem bin ich begegnet?
Ich habe den Branch lokal erstellt aber er war
auf GitHub nicht sichtbar.

## Wie habe ich es gelöst?
`git push origin feature/zusammenfassung` – man muss
den Branch-Namen beim ersten Push explizit angeben.