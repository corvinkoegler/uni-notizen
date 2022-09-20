# Mengen

## **Erkärung**: Cantor naive Mengendefinition

"Unter einer Menge *M* verstehen wir eine Zusammenfassung von wohldefinierten Objekten *m* unserer Anschaung oder unseres Denkens, welche die Elemente von *M* genannt werden zu einem einheitlichen Ganzen"
	(Georg Cantor (1845 - 1918))

## Schreibweise
- *m€M* (*m* ist ein Element von *M*)
- *m NOT€ M* (*m* ist kein Element von *M*)
- für Mengen mit (wenigen) endlich vielen Elementen: *M*{*m1, m2, m3*}
- allgemein mittels Eigenschaft *E(m)* (Aussageform) *A = {m | E(m)}* bzw *A = {m€M | E(m)}* = *{m | m€M ^ E (m)}*
	- *B' = {p€N | 2 >= p ^ p <= 12 ^ p Primzahl}**
- leere Menge {} o/ #TODO(Symbol erstzen) = {x | x != x}
- Einmenge *A = {a}* oder *A = {x | x = a}*
- Zweimenge *A = {a, b}* oder *A = {x | x = a OR x = b}* #TODO(Zeichen ersetzen)
- *|A|* oder *#A* Anzahl der Elemente in A (wenn *A* endlich)
- Andere: Natürliche Zahlen *N*, Reele Zahlen *Z*
- Teilmengen *A* c *B* #TODO *A* ist Teilmenge von *B*, *B* ist Obermenge von *A*. Ist *B* eine Teilmenge von *C* ist auch *A* eine Teilmenge von *C*. Ist *A* eine Teilmenge von *B* und *B* eine Teilmenge von *A*, gilt *A = B*. Wenn *B !c A* ist *A* eine echte Teilmenge von B

## Problem
**Man darf nicht alle möglichen Zusammenfassungen bilden!**
Bsp.: Bernhard Russel *R = {M | M ist Menge ^ M NOT€ M}*
*R € R <=> R NOT€ R* (Wiederspruch)

**Ausgang** Axiomatischer Aufbau der Mengenlehre.

## Beispiel für ein Axiom
- **Existenzaxiom**: Zwei Mengen *A* und *B* sind genau dann gleich wenn sie dieselben Elemente haben. *A=B <=> (Vx)(x€A <=> x€B)*
	- *B = B'*
		- {1, 2, 3} == {2, 3, 1, 2, 3, 1}