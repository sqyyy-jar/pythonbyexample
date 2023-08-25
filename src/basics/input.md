# Eingaben vom Benutzer
Oft brauchen wir auch Eingaben vom Benutzer. Das geht mit dem Schlüsselwort `input()`. Dies braucht wieder
Klammern. 

Innerhalb dieser Klammern kann man einen Prefix angeben. Das bedeutet, wie geben an, was vor der Eingabe
stehen soll.

**Die input-Funktion hat als Rückgabewert eine Zeichenkette(deine Eingabe)**

Dies sieht dann so aus:
```python
input("Bitte gebe deinen Namen ein: ")
```
Wir bekommen in diesem Fall eine Aufforderung unseren namen einzugeben. Dieser wird jedoch nicht gespeichert.

## Namen abfragen und ausgeben
Um einen `input` Wert zu speichern brauchen wir wieder [Variablen](variables.md). Wir schreiben also:
```python
name = input("Gebe deinen Namen ein: ")
```
Jetzt können wir diesen Namen einfach ausgeben:
```python
name = input("Gebe deinen Namen ein: ")
print(name)
```
Außerdem hat man die möglichkeit in [Funktionen](hello_world.md) andere Funktionen mit Rückgabewerten zu verwenden.
Das sieht dann so aus:
```python
print(input("Gebe deinen Namen ein: "))
```
