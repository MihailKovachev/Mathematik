---
Related:
  - "[[../Folge|Folge]]"
  - "[[Konvergenz/Konvergenz|Konvergenz]]"
---

> [!ALGORITHM] Algorithmus: Bestimmen des Grenzwertes einer rekursiven Folge
> Sei $(a_n)_{n\in\mathbb{N}}$ eine reelle, rekursiv definierte Folge, z. B.
> $$a_1 = a, a_2 = a', a_{n+1} = \mu a_n - \lambda a_{n-1}^2$$
> 
> Wenn $a_n$ gegen $L \in \mathbb{R}$ konvergiert, dann gilt
> 
> $$\lim_{n\to\infty} a_{n+1} = \lim_{n\to\infty} a_n = \lim_{n\to\infty} a_{n-1} = L$$
> 
> Im Grenzübergang wird daraus die sogenannte *Fixpunktgleichung*
> 
> $$L = \mu L - \lambda L^2$$
> 
> Der Algorithmus lautet dann:
> 
> 1. Zeige, dass $a_n$ konvergent ist (z. B. durch Monotonie und Beschränktheit).
> 2. Stelle die Fixpunktgleichung auf, indem du in der Rekursionsvorschrift $a_{n+1},a_n,a_{n-1}$ durch $L$ ersetzt.
> 3. Löse die Fixpunktgleichung, um die möglichen Werte für $L$ zu bestimmen.
> 4. Überprüfe, welche Werte für $L$ nicht in Frage kommen und welcher Wert übrigbleibt. Das ist der Grenzwert von $(a_n)_{n\in\mathbb{N}}$.
> 
> > [!NOTE] Nachweisen der Divergenz
> > Dieser Vorgang kann teilweise auch zum Nachweisen von Divergenz angewendet werden. Wenn die Fixpunktgleichung keine Lösung in $\mathbb{R}$ hat, dann hat die Folge auch keinen Grenzwert.