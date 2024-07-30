> [!DANGER] Definition: Homogene DGL
> Eine **homogene Differentialgleichung** ist eine [gewöhnliche Differentialgleichung](Gewöhnliche%20Differentialgleichung.md) der Form
> $$y'(x) = f\left(\frac{y(x)}{x}\right)$$

> [!TODO] Algorithmus: Lösen einer homogenen Differentialgleichung
> Wir lösen die [homogene Differentialgleichung](Homogene%20DGL.md)
> $$y'(x) = f\left(\frac{y(x)}{x}\right)$$
> 1. Setze $z(x) = \frac{y(x)}{x}$
> - Daraus ergibt sich:
> $$y(x) = x\cdot z(x)$$
> - Laut der [Produktregel](../../Differentiation/Rechenregeln%20für%20Ableitungen.md) für [Ableitungen](../../Differentiation/Ableitung%20und%20Differenzierbarkeit.md) gilt
> $$y'(x) = z(x) + x\cdot z'(x)$$
> 
> 2. Forme die Gleichung um, um eine [trennbare GDGL erster Ordnung](Trennbare%20GDGL/Trennbare%20GDGL%20erster%20Ordnung.md) zu erhalten:
> $$z' = \frac{1}{x}\left(f(z)-z\right)$$
> - Wandele die separierbare Gleichung in Standardform um.
> $$\frac{1}{f(z)-z}\frac{\mathop{\mathrm{d}z}}{\mathop{\mathrm{d}x}} = \frac{1}{x}$$
> 3. [Löse](Trennbare%20GDGL/Lösen%20von%20trennbaren%20GDGL%20erster%20Ordnung.md) die trennbare Differentialgleichung durch Integration der beiden Seiten:
> $$\int \frac{1}{f(z)-z}\mathop{\mathrm{d}z} = \int \frac{1}{x}\mathop{\mathrm{d}x} \mathop{+} c$$
> - Die Lösung der ursprünglichen Differentialgleichung erhält man durch Rücksubstitution von $z$.
> 
> > [!EXAMPLE]- Beispiel