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



### Aufgabe 1: Zählen bis nicht ganz 200
<!---
[task][Aufgabe 1](Aufgabe1_ZeilenAnzahl,Aufgabe1_Inhalt)
-->
Gib alle ganzen Zahlen im Intervall `[ 0 ; 200 [` jeweils in einer eigenen Zeile auf der Konsole aus.

Die ersten Zeilen der Aufgabe sehen so aus:
```java
0
1
2
3
4
...
```



### Aufgabe 2: Zählen bis zum Parameter
<!---
[task][Aufgabe 2](Aufgabe2_ZeilenAnzahl,Aufgabe2_Inhalt)
-->
Gib alle ganzen Zahlen von 0 bis einschließlich des Wertes des Parameters `limit` in jeweils einer eigenen Zeile auf der Konsole aus.

Beispielsweise für den Aufruf `Main.aufgabe2(5);` wäre die Ausgabe:
```java
0
1
2
3
4
5
```

### Aufgabe 3: Countdown
<!---
[task][Aufgabe 3](Aufgabe3_ZeilenAnzahl,Aufgabe3_Inhalt)
-->
Schreibe ein Programm, das vom Parameter `start` <ins>rückwärts</ins> bis einschließlich des Parameters `ende` zählt und jede Zahl in einer eigenen Konsolenzeile ausgibt. Überlege dir hierbei auch, was dein Programm tun soll, wenn `start < ende`.

Beispielsweise für den Aufruf `Main.aufgabe3(5,-1);` wäre die Ausgabe:
```java
5
4
3
2
1
0
-1
```


### Aufgabe 4: Quadratzahlen
<!---
[task][Aufgabe 4](Aufgabe4_ZeilenAnzahl,Aufgabe4_Inhalt)
-->
Gib bei 0 beginnend so viele aufeinanderfolgende Quadratzahlen wie im Parameter `limit` angegeben in jeweils einer eigenen Zeile auf der Konsole aus. Achte dabei genau auf die Formatierung der Ausgabe wie im Beispiel! (Leerzeichen sind optional)

Beispielsweise für den Aufruf `Main.aufgabe4(4);` wäre die Ausgabe:
```java
0 * 0 = 0
1 * 1 = 1
2 * 2 = 4
3 * 3 = 9
```


### Aufgabe 5: Fibonacci
<!---
[task][Aufgabe 5](Aufgabe5_ZeilenAnzahl,Aufgabe5_Inhalt)
-->

Schreibe ein Programm, das die ersten `limit`
[Fibonacci-Zahlen](https://en.wikipedia.org/wiki/Fibonacci_number) jeweils in einer eigenen Zeile auf der Konsole ausgibt. 

Beispielsweise sähe für den Aufruf `Main.aufgabe5(9);` die Ausgabe folgendermaßen aus:
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
*Tipp: Papier und Stift helfen beim Vorstellen der Zahlenreihenfolge und der aktuellen Werte von Variablen.*
