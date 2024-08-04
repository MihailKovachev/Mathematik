> [!DEFINITION] Definition: Das Newtonverfahren
> Das **Newtonverfahren** ist ein praktisches Verfahren zur näherungsweisen Bestimmung einer Lösung einer Gleichung vom Typ $f (x) = 0$ für eine [differenzierbare](../Ableitung%20und%20Differenzierbarkeit.md) [Funktion](../../Funktionen/Funktion.md) $f$.

> [!ALGORITHM] Algorithmus: Das eindimensionale Newtonverfahren
> Gegeben ist eine zweimal stetig differenzierbare Funktion $f: I \to \mathbb{R}$, für die wir eine Nullstelle $x^\ast \in I$ suchen.
> 1. Wir wählen eine Toleranzgrenze $\tau  \gt 0$.
> 2. Wir wählen ein beliebiges $x_0 \in I$, das bestenfalls in der Nähe von $x^\ast$ liegt.
> 3. Bestimme
> 	$$x_{i+1} = x_{i} - \frac{f(x_i)}{f'(x_i)}$$
> 	bis eines der folgenden Kriterien erfüllt wird:
> 	- $|x_{i+1}-x_{i}| \lt \tau$
> 	- $|f(x_{i+1})| \gt |f(x_i)|$