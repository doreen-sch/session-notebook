# Git & Github

- **q** - "Quit" nach Ordner- oder Dateiabfrage, neues Fenster öffnete sich

## Branches

- **git branch** - Liste lokaler Branches
- **git branch -a** - Liste aller Branches inkl. versteckter Dateien (wie ls -a)
- rot angezeigte Branches: befinden sich upstream bei GitHub, nicht lokal

### Brancherstellung

- **git switch -c [name]** - Kombination aus git branch [name] und git switch [name]
- **git branch [name]** - Erstellung eines neuen Branches
- **git switch [name]** - Switch zu neuem Branch

### GitHub

wenn bspw. bei GitHub main und branch gemerged wurden, dort den Branch löschen, weil...

- wir arbeiten nie auf alten Versionen / Branches
- kein Branchfriedhof: auch veraltete lokale Branches löschen
- stay up to date: Merge anschließend über Terminal pullen
