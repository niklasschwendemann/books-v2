# Kommentare im Quelltext {#head}

<div class="description">Das Kommentieren von Quellcode ist leider ein Thema das stiefmütterlich behandelt wird. Den Nutzen von guten Kommentaren erkennt man häufig erst dann, wenn man versucht sich durch fremden Quelltext durchzuwuseln oder wenn man ein eigenes Programm nach langer Zeit wieder 'ausgräbt'. Kommentare werden vom Kompiler nicht ausgewertet und beeinflussen den Ablauf des Programms damit nicht. Text und Programmteile die auskommentiert sind, erkennt man daran, dass sie grau gefärbt sind.
</div>
<div class="line">
    <br>
    <br>
</div>



## Einzeilig
Einzeilige Kommentare finden sich oft im Quelltext. Sie dienen dazu bestimmte Befehle oder Konstrukte  zu erklären.
Ein einzeiliger Kommentar wird durch zwei `//`gekennzeichnet. 

```arduino
// Ich bin ein Kommentar
int led = 1;  // Die variable led bekommt den Wert 1
```
## Mehrzeilige Kommentare
Mehrzeilige Kommentare stehen oft zu Beginn eines Programms oder vor einer Methode. Sie beginnen mit `/*` und enden mit `*/`. Man kann sie außerdem dazu verwenden, Teile eines Programms auszukommentieren. Etwa wenn man einen Fehler hat und überprüfen möchte, in welchem Programmteil er liegt. 

```arduino
/*
 *
 * Ich bin ein mehrzeiliger Kommentar
 * Ich kann zum Beispiel beschreiben, welchen Zweck ein ganzes Programm 
 * oder eine einzelne Methode hat.
 * 
 * übrigens:
 * <- diese Sterne werden zwar automatisch erzeugt, sind aber nicht unbedingt notwendig.
 *
 */
```

## Wie viele Kommentare braucht ein Quellcode?
Das ist eine Frage, auf die es keine klare Antwort gibt. Es gibt Programmierer, die erwarten, dass jede Zeile Quelltext kommentiert wird. Dies ist bei unseren einfachen Programmen nicht notwendig. Grundsätzlich sollten mindestens folgende Programmteile kommentiert sein:

- Ein Kommentar zu Beginn, welcher den Zweck des Programms beschreibt.
- Jede Methode muss kommentiert sein und hier insbesondere die Eingabeparameter und eventuelle Rückgaben. 
- Mathematisch oder logisch anspruchsvolle Befehle oder besondere 'Kniffe' die sich der Programmierer überlegt hat.

<div class="box_info">
    <i class="fa fa-info fa-fw" aria-hidden="true" style="color: #42acf3;"></i>
   Wenn du dich weiter mit dem Thema beschäftigen möchstest, dann schau doch mal bei <a href="https://de.wikipedia.org/wiki/Javadoc">Wikipedia</a>
</div>
