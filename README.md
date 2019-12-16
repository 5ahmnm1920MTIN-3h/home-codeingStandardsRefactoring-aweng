# home-codeingStandardsRefactoring-aweng

# Was ist Refactoring Definition in eigenen Worten?

Refactoring dient dazu den Code zu verbessern. Man säubert den Code nachdem er geschrieben ist, um ihn damit er für sich selbst oder andere verständlicher und einfach zu lesen ist.  

# Welche Vorteile/Nachteile birgt Refactoring?
Vorteile
Der Code ist einfacher zu lesen.
Der Code ist verständlicher.
Der Code ist einfacher wieder verwendbar.

Nachteile
Mehr Zeitaufwand, für keine sichtbaren Verbesserungen am Endprodukt
eventuelle Fehler, verursacht durch refactoring.


# Was sind die Refactoring-Schritte?
1) Man definiert einen Testcase
2) Man stellt sicher das der Code funktioniert. Ist das der Fall commited man den Code um im Notfall später darauf zurück greifen zu können.
3) Man ändert einen kleinen Teil des Codes um ihn zu verbessern.
4) Man tested ob der Code noch immer funktioner.
5) Man commited und schreibt in die commit message die Änderung, um am Ende nachvollziehn zu können was man gemacht hat.
6) Man geht den Code bis zum Ende, nach dem selben Prinzip (Schritte 3-5), bis zum Ende durch. 


# Prinzipien von guten Code?
DRY - Don’t Repeat Yourself
Ist ein Prinzip das besagt, dass man Code-Wiederholungen  vermeiden soll.

KISS - Keep it Simple, Stupid
Die Grundaussage dieses Prinzip ist, dass wenn es mehrere Varianten für das selbe Ergebnis gibt, sollte man die einfachste verwenden. 

YAGNI - You Ain’t Gonna Need It
Dieses Prinzip dient dazu, dass man überprüft ob man den Code wirklich für die Funktionalität benötigt, also nicht notwendige Extras sollten entfernt werden.

SoC - Separation of Concerns
Unter diesem Prinzip versteht man, dass verschiedene Aufgaben einer Anwendung in Teillösungen umgesetzt werden.

Principle of least Astonishment
Dieses Prinzip besagt, dass eine Benutzerschnittstelle so ausgelegt werden sollte, dass der Benutzer möglichst wenige Überraschungen erlebt. Dass man z.B. Variablen, Klassen, Methoden zu benennt das deren Funktion beschrieben wird.


Single Responsibility Principle
Dieses Prinzip besagt, dass Klassen nur für eine Sache zuständig sein sollten und nicht mehrere Funktionen erfüllen.



# Was versteht man unter Code Smell?
Unter einem Code-Smell versteht man einen Code, welcher schlecht strukturiert ist und schwer verständlich ist. Durch einen Code-Smell können sich schnell Fehler einschleichen.
Zum Beispiel: zu lange Methoden, Magical Strings, Magical Values

# Recherche von 10 Code Smells die Eure Projekt betreffen können, inkl. Beschreibung und Beispiel.
Kommentare
Man sollte zu viele Kommentare veremeiden, da diese nur eine Unterstützung sein sollten.

Nichtssagende Namen
Sowohl Variablen, als auch Klassen sollten so benannt werden, dass man davon die Funktion ablesen kann

Doppelter Code
Man sollte vermeiden, dass ein Code zweimal vorkommt.

Lange Methode
Man sollte zu lange Methoden, aufgrund der Verständlichkeit und Übersichtlichekeit vermeiden.

Kurze Namen
Man sollte Variablen, Klassen oder Methoden mit einen beschreibenden Namen bennenen und nicht nur mit einzelnen Buchstaben.

Lange Namen
Jedoch sollten, Variablen, Klassen oder Methoden auch keine  viel zu lange Namen haben.

Tiefe Verschaftelungen
Man sollte Verschachtelungen vermeiden, da diese den Code unverständlich und unlesbar machen.

Leerzeilen
Zu viele Leerzeilen sollten gelöscht werden, um den unnötigen Verbrauch von Zeile zu vermeiden.

Unbenutzter Code
Man sollte vermeiden unbenutzten Code im Projekt zu haben, da dieser den Code unverständlicher macht,nur unnötig verlängert und Speicher verbraucht.

Falsche Klammern
Es passiert schnell, dass man die Klammern im Code falsch setzt oder vergisst. Dies kann zu einem fehlerhaften Code führen und sollte auf alle Fälle vermieden werden.

