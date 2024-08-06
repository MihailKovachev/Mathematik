> [!ALGORITHM] Algorithmus: Das eindimensionale Newtonverfahren
> Wir wollen eine Lösung $x^\ast$ der Gleichung
> $$f(x)=0$$
> approximieren, wobei $f:I\to\mathbb{R}$ eine zweimal [stetig differenzierbare](../Höhere%20Ableitungen.md) [Funktion](../../Funktionen/Funktion.md) ist.
>  
> 1. Wir wählen eine Toleranzgrenze $\tau  \gt 0$.
> 2. Wir wählen ein beliebiges $x_0 \in I$, das bestenfalls in der Nähe von $x^\ast$ liegt.
> 3. Bestimme
> 	$$x_{i+1} = x_{i} - \frac{f(x_i)}{f'(x_i)}$$
> 	bis eines der folgenden Kriterien erfüllt wird:
> 	- $|x_{i+1}-x_{i}| \lt \tau$
> 	- $|f(x_{i+1})| \gt |f(x_i)|$