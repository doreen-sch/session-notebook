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

wenn bspw. bei GitHub direkt main und branch gemerged wurden:

- direkt über den Button löschen, weil...

1. wir arbeiten nie auf alten Versionen / Branches
2. kein Branchfriedhof: auch veraltete lokale Branches löschen
3. stay up to date: Merge anschließend über Terminal pullen

danach lokal:

1. alten Branch löschen
2. alten Branch aufrufen
3. git branch -d [name]
4. git pull zum updaten mit GitHub
