# Bools

In Python gibt es einen Datentyp für Wahrheitswerte. Dieser hat zwei Zustände:
wahr und falsch, dargestellt als `True` und `False`.

Diese Wahrheitswerte können auch als an/aus oder ja/nein angesehen werden.

Beispiel:

```py
mein_bool = True
```

## Verarbeitung

Bools kann man durch verschiedene Operatoren verarbeiten.

Um das Gegenteil eines Bools zu erhalten, benutzt man den `not` Operator:

```py
mein_bool = not True # entspricht False
```

Um zu überprüfen, ob mindestens einer von zwei Bools `True` ist, benutzt man den `or`
Operator:

```py
mein_bool = False or True # entspricht True
```

Der `and` Operator wird benutzt, um zu überprüfen, ob zwei Bools `True` sind:

```py
mein_bool = True and False # entspricht False
```

Um herauszufinden, ob genau einer von zwei Bools `True` ist, benutzt man den `^`
Operator:

```py
mein_bool = True ^ True # entspricht False
```
