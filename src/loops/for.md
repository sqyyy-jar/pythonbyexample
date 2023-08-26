# For-Schleifen

For-Schleifen in Python führen Code für zum Beispiel alle Elemente einer Liste aus:

```py
for x in [1, 2, 3]:
    print(x)
```

Bei jedem Durchlauf nimmt `x` den nächsten Wert in der Liste an.

Daher schreibt dieser Code `1`, `2` und `3` nacheinander.

## Die Range-Funktion

Um Code zum Beispiel 15 mal auszuführen, kann man die `range` Funktion benutzen:

```py
for x in range(15):
    print(x)
```

In diesem Beispiel nimmt `x` die Werte von `0` bis `14` an.

Um die Werte von zum Beispiel `5` bis `10` anzunehmen, kann man einen Start festlegen:

```py
for x in range(5, 11):
    print(x)
```

Beachte hierbei, dass das Ende immer exklusiv ist, also endet die Schleife nach `10`,
anstatt nach `11`.
