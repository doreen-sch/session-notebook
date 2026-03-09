<h1>Branch</h1>

git branch. -> Liste lokaler Branches
git branch -a -> Liste aller Brnaches inkl. versteckter Dateien (wie ls -a)
-> rot angezeigte Branches: befinden sich upstream bei GitHub, nicht lokal

<h2>Brancherstellung</h2>
git switch -c [name] -> Kombination aus git branch [name] und git switch [name]
git branch [name]    -> Erstellung eines neuen Branches
git switch [name]    -> Switch zu neuem Branch

<h2>GitHub</h2>
wenn bspw. bei GitHub main und branch gemerged wurden, dort den Branch löschen
-> wir arbeiten nie auf alten Versionen / Branches
-> auch lokal alte Branches löschen, um Branch-Friedhof zu vermeiden
-> Merge anschließend über terminal pullen, um auf allen Plattformen uptodate zu bleiben
