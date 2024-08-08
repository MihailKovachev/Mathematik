> [!THEOREM] Satz: Lokales Extremum $\implies$ kritische Stelle
> Jede Stelle eines [lokalen Extremums](../../Funktionen/Extrema/Lokale%20Extrema.md) ist auch eine kritische Stelle.
> > [!PROOF]- Beweis
> > Sei $f$ eine Funktion mit einem lokalen Extremum im Punkt $x_0$. Wenn $f$ in $x_0$ nicht differenzierbar ist, dann sind wir fertig - $x_0$ ist nach Definition eine kritische Stelle.
> > 
> > Wenn aber $f$ im Punkt $x_0$ differenzierbar ist, müssen wir zeigen, dass $f'(x_0)=0$. Es gilt dann
> > 
> > $$\lim_{x\to x_0} \frac{f(x)-f(x_0)}{x-x_0} = \lim_{x\to x_0^{-}} \frac{f(x)-f(x_0)}{x-x_0} = \lim_{x\to x_0^{+}} \frac{f(x)-f(x_0)}{x-x_0} = f'(x_0)$$
> > 
> > Nehmen wir an, $f(x_0)$ ist ein lokales Maximum. Dann existiert ein $\varepsilon \gt 0$ mit $f(x)-f(x_0)\le 0$ für alle $x \in (x_0-\varepsilon; x_0+\varepsilon)$. Betrachten wir nun die einseitigen Grenzwerte. Bei $x\to x_0^-$ gilt immer $x- x_0\lt 0$ und zusammen mit $f(x)-f(x_0)\le 0$ ergibt sich
> > $$\lim_{x\to x_0^{-}} \frac{f(x)-f(x_0)}{x-x_0} \ge 0$$
> > Andererseits gilt immer $x-x_0\gt 0$ bei $x\to x_0^+$. Also
> > $$\lim_{x\to x_0^{-}} \frac{f(x)-f(x_0)}{x-x_0} \le 0$$
> > Da aber die beiden Grenzwerte gleich $f'(x_0)$ sind, bleibt nur die Möglichkeit, dass $f'(x_0) = 0$.
> > 
> > Ein analogischer Vorgang lässt sich ausführen, um dasselbe für ein lokales Minimum zu beweisen.

> [!THEOREM] Satz: Kriterium der zweiten Ableitung
> Sei $f: D \to\mathbb{R}$ eine [stetige](../../Grenzwerte%20von%20Funktionen/Stetigkeit/Stetigkeit.md) [Funktion](../../Funktionen/Funktion.md).
> 
> Eine [kritische Stelle](../../Funktionen/Extrema/Kritische%20Stellen.md) $x_0$ der Funktion $f$ ist Stelle eines [lokalen Minimums](../../Funktionen/Extrema/Lokale%20Extrema.md), wenn $f''(x_0) \gt 0$.
> 
> Eine kritische Stelle $x_0$ der Funktion $f$ ist Stelle eines [lokalen Maximums](../../Funktionen/Extrema/Lokale%20Extrema.md), wenn $f''(x_0) \lt 0$.
> 
> > [!WARNING] Warnung
> > Im Falle, dass $f''(x_0) = 0$, ist keine Aussage möglich.
> 
> > [!PROOF]- Beweis

> [!THEOREM] Satz: Kriterium des Vorzeichenwechels
> Sei $f: D \to \mathbb{R}$ eine stetige Funktion.
> 
> Eine kritische Stelle $x_0$ der Funktion $f$ ist Stelle eines lokalen Minimums, wenn ein $\varepsilon \gt 0$ existiert mit
> $$f'(x) \lt 0 \quad \forall x \in (x_0-\varepsilon; x_0)\qquad \text{und} \qquad f'(x) \gt 0 \quad \forall x\in (x_0; x_0+\varepsilon)$$
> 
> Eine kritische Stelle $x_0$ der Funktion $f$ ist Stelle eines lokalen Maximums, wenn ein $\varepsilon \gt 0$ existiert mit
> $$f'(x) \gt 0 \quad \forall x \in (x_0-\varepsilon; x_0)\qquad \text{und} \qquad f'(x) \lt 0 \quad \forall x\in (x_0; x_0+\varepsilon)$$
> > [!PROOF]- Beweis

> [!ALGORITHM] Algorithmus: Bestimmen der Extremstellen einer Funktion
> Voraussetzungen: Die Funktion $f: D \subseteq \mathbb{R} \to \mathbb{R}$ ist stetig.
> 1. Bestimme die kritischen Stellen von $f$, also alle $x_0, x_1,\cdots, x_n \in D$, wo $f'$ eine Nullstelle hat oder nicht existiert.
> 2. Überprüfe anhand der Kriterien, welche von $x_0, x_1,\cdots, x_n$ Stellen lokaler Extrema sind.
> 3. Bestimme die Extremwerte, also alle $f(x_i)$, wo $x_i$ Stelle eines lokalen Extremums ist.
> 4. Bestimme die folgenden Werte an den Randpunkten von $D$:
> 	- Falls $D = [a;b]$ mit $a,b\in\mathbb{R}$, so bestimme $f(a)$ und $f(b)$;
> 	- Falls $D = (a; b)$ mit $a, b \in \mathbb{R} \cup \{+\infty\}$