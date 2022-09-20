# Aussageformen
Eine Aussageform ist ein sprachliches Gebilde, das mindestens eine [[Variablen|Variable]] enthält und nach geeigneter Ersetzung in eine (wahre oder falsche) [[Aussagen|Aussage]] übergeht. Eine solche Ersetzung wird Belegung der Variablen genannt.

bsp.: *3+x = 5*
Werden erst dann zu [[Aussagen]] wenn die vorkommenden [[Variablen]] mit (zulässigen) Werten belegt werden. Dazu gehört ein **zulässiger Grundbereich** der Vorgegeben werden muss (z.B. x€N #TODO(Zeichen erstezten).

Wie [[Aussagen]] kann man Aussageformen miteinander Verknüpfen ([[Aussageverknüpfungen]]) und man erhält neue Aussageformen.

## Quantoren
Außer der Belegung der [[Variablen]] mit Werten gibt es noch andere Möglichkeiten aus einer [[Aussageform]] eine [[Aussagen|Aussage]] zu machen. (Ein Grundbereich *M* muss vorgegeben sein.)
"Für alle *x* (aus *M*) gilt *A(x)*"
"Für alle *x*€*N* gilt 3+x=5" -> falsche Aussage #TODO(Formatierung von Gleichungen festlegen)

Allquantor #TODO(Recherche und Gleichung oben überarbeiten)
Existensquantor #TODO(Recherche + Symbol) "Es existiert mindestens ein x (aus M) mit A(x)"

(EXIST x €*N*) (3 + x = 1) *falsch*
(EXIST x €N) (3 + x = 1) *true*

"Es existiert höchstens ein x mit A(x)""
(ALL x)(ALL y) (A(x) ^ A(y) => x < y)

"Es gibt höchstens ein x mit A(x)"
((EXIST ! x) A(x) == ((EXIST x) A(x)) ^((ALL x) (ALL y) A(x) ^ A(y) => x = y #TODO(Formatting)

## #Übung
- Verdächtige: Achim (A), Bertram (B), Christin (C)
- Der/Die Täter sind in der Gruppe der Verdächtigen zu finden
- Wenn A und B nicht beide Beteiligt waren, dann hat C auch nicht mitgemacht.
- Wenn B schuldig ist oder wenn C unschuldig ist kann A nicht der Täter sein

A|B|C|möglich
---|---|---|---
W|W|W|2, 3
W|W|F|3
W|F|W|2
F|W|W|2
F|W|F|wahr
F|F|F|1
(A AND B and C) ^ (NOT (A ^ B) => NOT C) ^((B AND NOT C) => NOT A)
Ergebnis: NOT A, B, NOT C