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







[task][Aufgabe 1: Zählen von 5 bis zum Parameter (1,5 BE)]()
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

[task][Aufgabe 2: Quadratzahlenliste (2 BE)]()
Gib bei 0 beginnend so viele aufeinanderfolgende Quadratzahlen wie im Parameter `limit` angegeben in jeweils einer eigenen Zeile auf der Konsole aus. Achte hierbei genau auf die Formatierung der Ausgabe!

Beispielsweise für den Aufruf `Aufgaben.aufgabe2(4);` wäre die Ausgabe:
```java
0 * 0 = 0
1 * 1 = 1
2 * 2 = 4
3 * 3 = 9
```


[task][Aufgabe 3: Countdown (1,5 BE)]()
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
