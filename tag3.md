# Tag 3 – [04.06.2026]

## Was habe ich heute gelernt?
`git log --oneline` zeigt alle Commits kompakt an.
Jeder Commit hat einen eindeutigen Hash (z.B. abc1234).
Mit `git diff` sieht man was sich seit dem letzten
Commit verändert hat.

## Welches Problem bin ich begegnet?
Ich habe vergessen `git add` zu machen und direkt
`git commit` ausgeführt – nichts wurde gespeichert.

## Wie habe ich es gelöst?
`git status` hat gezeigt dass die Datei "untracked"
war. Danach `git add tag3.md` und nochmal committed.