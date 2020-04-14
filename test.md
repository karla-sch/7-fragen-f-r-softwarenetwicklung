## 7 Fragen in 7 Minuten


**1. Der Befehl `git pull` realisiert zwei Schritte:**

[( )] `git branch` und `git merge`
[(X)] `git fetch` und `git merge`
[[?]] Der kombinierte Befehl bezieht sich auf die Interaktion mit dem Remote-Repository und dessen ggf. vor dem aktuellen lokalen Repository liegenden Versionen.
***********************************************************************

                                {{1}}
Mit `git pull` werden die aktuellen Änderungen des Branches, die auf dem Remote-Repository
liegen abgerufen und in das lokale Repository mit `git merge` übernommen.

***********************************************************************

**2. Exklusives Bearbeiten (Sequentialisierung): Kreuze in der richtigen Reihenfolge an!** 

[[1.] [2.] [3.]]
[( )  (X)  ( ) ]       Modify 
[(X)  ( )  ( ) ]       Lock 
[( )  ( )  (X) ]       Unlock 
***********************************************************************

Bei der Sequentialisierung handelt es sich um die pessimistische Versionsverwaltung, bei der einzelne Dateien vor einer Änderung durch den Benutzer gesperrt und nach Abschluss selbiger wieder freigegeben werden. 

***********************************************************************


**3. Kollaboratives Arbeiten mit Mischen: Kreuze in der richtigen Reihenfolge an!** 

[[1.] [2.] [3.]]
[(X)  ( )  ( ) ]       Copy 
[( )  ( )  (X) ]       Merge  
[( )  (X)  ( ) ]       Modify 
***********************************************************************

Hierbei handelt es sich um die optimistische Versionsverwaltung, bei der gleichzeitige Änderungen durch mehrere Benutzer an einer Datei möglich sind, da diese Änderungen anschließend automatisch oder manuell zusammengeführt werde (*Merge*). 

***********************************************************************


**4. Vervollständige die Definition:** 

Ein Paar von Änderung aus Dokument 1 bzw. Dokument 2 gegenüber einem Ausgangsdokument kann unverträglich sein, wenn die Abbildung beider Änderungen in einem gemeinsamen Dokument nicht möglich ist. In diesem Fall spricht man von einem [[Konflikt]]. 

**5. Kreuze die zugehörige Definition an! **

[[2-Wege-Mischen] [3-Wege-Mischen]]
[       ( )              (X)      ]       Mischen von Dokumenten gemeinsamen Ursprungs 
[       (X)              ( )      ]       Mischen unabhängiger Dokumente 
[[?]] Beim 2-Wege-Mischen ist die Erzeugung eines neuen Dokuments das Ziel, während beim 3-Wege-Mischen eine weiterentwickelte Version des ursprünglichen Dokuments entstehen soll. Übertrage dieses Wissen auf die Ausgangsdokumente um die richtigen Definitionen zuordnen zu können. 
***********************************************************************

Beim *2-Wege-Mischen* werden die gemeinsamen Komponenten und die individuellen Teilmengen voneinander unabhängiger Dokumente vereint. 
Beim *3-Wege-Mischen* werden (möglichst) alle Änderungen am Ursprungsdokument in eine weiterentwickelte Version des selbigen integriert. 

***********************************************************************


**6. Welche Form der Versionsverwaltung findet noch heute in manchen Büroanwendungen (bspw. *Word*) Verwendung?** 
[( )] Verteilte Versionsverwaltung 
[( )] Zentrale Versionsverwaltung 
[(X)] Lokale Versionsverwaltung 
[[?]] Die genannten Anwendungen speichern die Versionen eines Dokuments in der Datei des Dokuments selbst - dabei handelt es sich um eine `?`Speicherung. 
