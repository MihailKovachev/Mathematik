> [!DANGER] Definition: Bernoulli'sche Differentialgleichung
> Eine **Bernoulli'sche Differentialgleichung** ist eine [gewöhnliche Differentialgleichung](Gewöhnliche%20Differentialgleichung.md) der Form
> $$y'(x) + p(x)y(x) = g(x)y(x)^\alpha,$$
> wobei $\alpha\in\mathbb{R}\setminus \{0,1\}$.

> [!TODO] Algorithmus: Lösen einer Bernoulli'schen Differentialgleichung
> Wir lösen die Bernoulli'sche Differentialgleichung
> $$y'(x) + p(x)y(x) = g(x)y(x)^\alpha \qquad \alpha\in\mathbb{R}\setminus \{0,1\}$$
> 1. Setze $z(x) = y(x)^{1-\alpha}$:
> - Laut der [Kettentregel](../../Differentiation/Rechenregeln%20für%20Ableitungen.md) für [Ableitungen](../../Differentiation/Ableitung%20und%20Differenzierbarkeit.md) gilt
> $$z'(x) = (1-\alpha)y(x)^{-\alpha}\cdot y'(x)$$
> - Daraus ergibt sich
> $$y'(x)=\frac{1}{1-\alpha}z'(x)y(x)^\alpha$$
> 
> 2. Ersetze $y'$ in der Bernoulli'schen Gleichung durch das obige Ergebnis:
> $$\frac{1}{1-\alpha}z'(x)y(x)^\alpha + p(x)y(x) = g(x)y(x)^\alpha$$
> 3. Dividiere durch $y(x)^\alpha$:
> $$\frac{1}{1-\alpha}z'(x) + p(x)y(x)^{1-\alpha} = g(x)$$
> 4. Ersetze $y(x)^{1-\alpha}$ durch $z(x)$:
> $$\frac{1}{1-\alpha}z'(x) + p(x)z(x) = g(x)$$
> 5. [Löse die resultierende lineare GDGL](Lineare%20GDGL/Lineare%20GDGL%20erster%20Ordnung/Lösen%20von%20linearen%20GDGL%20erster%20Ordnung.md) für $z(x)$ und erhalte die Lösung für $y(x)$ durch Rücksubstitution.
> 
> > [!EXAMPLE]- Beispiel