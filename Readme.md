# Git für kleine Teams
Dies ist eine kleine Befehlsreferenz mit Grundlegenden Git Befehlen

## touch [Dateiname]
Legt eine leere Datei an

## nano [Dateiname]
nano ist ein einfacher Texteditor

## git init
Legt ein leeres Repository an


## git add [Dateiname]
Fügt eine Datei / Änderung aus den Arbeitsverzeichniß in den aktuelle Commit hinzu

## git commit [-a] -m "Nachricht"
Das Commit abschließen und mit einer Nachricht versehen
-a übernimmt alle Änderungen (kann anstelle von git add benutzt werden) - Übernummt aber nur Änderungen von Dateien die sich bereits im Repository befinden.

## git remote add [name] [URL]
Ein Remote Repository mit [name] und [url] hinzufügen

## git push [-u [name]] [branch]
Alle Commits des aktuellen Branches auf das Remote Repository spiegeln

-u Alle Commits des [branch] in das Remote Repository [name] spiegeln. 

## git clone [URL]
Ein bestehendes Repository auf den eigenen Computer spiegeln

## git pull
Alle Änderungen aus dem Remote Repository kopieren.

## git checkout [-b] [name]
Git checkout wechselt den aktiven Branch. 
-b Erstellt den Branch neu mit [name] äquivalent zu
git branch [name]
git checkout [name]

## git merge [name]
Einen Branch mit dem aktuellen verschmelzen
