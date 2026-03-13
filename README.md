# Schleifen
Schleifen gehören zu den wichtigsten Elementen beim Programmieren. In dieser Aufgabe verwenden wir die beiden wichtigsten Arten: For-Schleifen (auch als Zählschleife bekannt) und While-Schleifen (Schleifen mit Bedingung).

## Videos
Für jede Aufgabe ist bereits eine Methode vorbereitet. Bearbeite die Aufgaben immer in der richtigen Methode, sonst findet Artemis deine Bearbeitung nicht! In den meisten Fällen haben die Methoden Parameter, deren Werte erst beim Ausführen festgelegt werden. Wenn du da noch nicht ganz fit bist, hilft dieser [Teil von Jonas Keils Video zu Methoden](https://youtu.be/bvGepmcDqD0?t=382) (die Wiedergabe beginnt automatisch bei 6:22 Min.) weiter.

Zu While- und For-Schleifen helfen die folgenden Videos von Jonas Keil:
- [While-Schleifen](https://youtu.be/mcm84hlxXo8).
- [For-Schleifen](https://www.youtube.com/watch?v=CoEKIbc8B0k).

---

## Aufgaben


- 1: 0 bis 9
- 2: 0 bis limit
- 3: Rückwärts Start bis Ende
- 4: Quadratzahl Strings
- 5: Fibonacci-Zahlen 

[task][Aufgabe 1: Zählen von 5 bis zum Parameter (1,5 BE)](testAufgabe1_lineCount1,testAufgabe1_exactMatch1,testAufgabe1_lineCount2,testAufgabe1_exactMatch2,testAufgabe1_lineCount3,testAufgabe1_exactMatch3)
Gib alle ganzen Zahlen von 5 bis einschließlich dem Wert des Parameters `limit` in jeweils einer eigenen Zeile auf der Konsole aus.

Beispielsweise für den Aufruf `Aufgaben.aufgabe1(11);` wäre die Ausgabe:
```java
5
6
7
8
9
10
11
```

[task][Aufgabe 2: Quadratzahlenliste (2 BE)](testAufgabe2_exactMatch1,testAufgabe2_lineCount1,testAufgabe2_exactMatch2,testAufgabe2_lineCount2,testAufgabe2_exactMatch3,testAufgabe2_lineCount3)
Gib bei 0 beginnend so viele aufeinanderfolgende Quadratzahlen wie im Parameter `limit` angegeben in jeweils einer eigenen Zeile auf der Konsole aus. Achte hierbei genau auf die Formatierung der Ausgabe!

Beispielsweise für den Aufruf `Aufgaben.aufgabe2(4);` wäre die Ausgabe:
```java
0 * 0 = 0
1 * 1 = 1
2 * 2 = 4
3 * 3 = 9
```


Löse nun folgende Aufgaben mit einer For-Schleife:
 
[task][Aufgabe 3: Countdown (1,5 BE)](testAufgabe3_exactMatch1,testAufgabe3_lineCount1,testAufgabe3_exactMatch2,testAufgabe3_lineCount2,testAufgabe3_exactMatch3,testAufgabe3_lineCount3)
Schreibe ein Programm, dass vom Parameter `start` <ins>rückwärts</ins> bis einschließlich zum Parameter `ende` zählt und jede Zahl in einer eigenen Konsolenzeile ausgibt. Überlege dir hierbei auch, was dein Programm tun soll, wenn `start < ende`.

Beispielsweise für den Aufruf `Aufgaben.aufgabe3(5,-1);` wäre die Ausgabe:
```java
5
4
3
2
1
0
-1
```
[task][Aufgabe 4: Nochmal von 5 zählen (1,5 BE)](testAufgabe4_exactMatch1,testAufgabe4_lineCount1,testAufgabe4_exactMatch2,testAufgabe4_lineCount2,testAufgabe4_exactMatch3,testAufgabe4_lineCount3)
Gib alle ganzen Zahlen von 5 bis <ins>ausschließlich</ins> dem Wert des Parameters `limit` (also nur alles was kleiner ist) in jeweils einer eigenen Zeile auf der Konsole aus. Vergleiche deinen Code auch mit `aufgabe1` und suche Gemeinsamkeiten.

Beispielsweise für den Aufruf `Aufgaben.aufgabe4(11);` wäre die Ausgabe:
```java
5
6
7
8
9
10
```

## Freie Schleifenwahl
Du kennst jetzt for- und while-Schleifen und ihre Vor- und Nachteile. Löse die folgende Aufgabe immer jeweils mit der Schleife, die dir geeigneter erscheint:

[task][Aufgabe 5: Fibonacci Zahlen (Bonus: 2,5 BE)](testAufgabe5_exactMatch1,testAufgabe5_exactMatch2,testAufgabe5_exactMatch3)
Schreibe ein Programm, das die ersten `limit`
[Fibonacci-Zahlen](https://en.wikipedia.org/wiki/Fibonacci_number) in jeweils einer eigenen Zeile auf der Konsole ausgibt. 

Beispielsweise sähe für den Aufruf `Aufgaben.aufgabe5(9);` die Ausgabe folgendermaßen aus:
```java
1
1
2
3
5
8
13
21
34
```
*Tipp: Papier und Stift helfen beim Vorstellen der Zahlenreihenfolge und den aktuellen Werten von Variablen.*


[task][Aufgabe 6: Zahlenfolge (3 BE)](testAufgabe6_exactMatch,testAufgabe6_lineCount)
Gib die ersten 30 Elemente dieser folgenden Zahlenfolge in jeweils einer eigenen Zeile auf der Konsole aus. Das dreißigste Element ist 465, die drei Punkte stehen für im Beispiel ausgelassenen Elemente (die in eurem Programm aber natürlich ausgegeben werden müssen).
```java
1
3
6
10
15
21
28
36
...
465
```
Tipp: Schau dir an, nach welchem System sich die Abstände zwischen den aufeinanderfolgenden Zahlen verändern.

[task][Aufgabe 7 (Bonus: 2 BE)](testAufgabe7_exactMatch1,testAufgabe7_exactMatch2,testAufgabe7_exactMatch3) 
Gib alle Zahlen der unten stehenden Zahlenfolge in jeweils einer eigenen Zeile aus, solange der Betrag nicht größer als der Wert des Parameters `limit` ist.

Für den Aufruf `Aufgaben.aufgabe7(64)` sähe die Ausgabe beispielsweise so aus:
```java
1
-2
4
-8
16
-32
64
```
Tipp: Schau dir an, nach welchem System aufeinanderfolgende Zahlen zusammenhängen. Evtl. hilft dir eine der vorherigen Aufgaben dabei.
