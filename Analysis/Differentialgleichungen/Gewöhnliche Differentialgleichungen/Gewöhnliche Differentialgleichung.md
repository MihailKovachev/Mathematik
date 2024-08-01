> [!DEFINITION] Definition: Gewöhnliche Differentialgleichung
> Eine **gewöhnliche Differentialgleichung** (kurz **GDGL** oder **ODE**) ist eine [Differentialgleichung](../Differentialgleichung.md), die nur [Ableitungen](../../Differentiation/Ableitung%20und%20Differenzierbarkeit.md) in einer Variable enthält:
> $$F\left(x,y,\frac{\mathop{\mathrm{d}y}}{\mathop{\mathrm{d}x}}, \frac{\mathop{\mathrm{d}^2y}}{\mathop{\mathrm{d}x^2}},\cdots, \frac{\mathop{\mathrm{d}^ny}}{\mathop{\mathrm{d}x^n}}\right) = 0$$
> > [!DEFINITION] Definition: Lösung der GDGL
> > Eine [Funktion](../../Funktionen/Funktion.md) $y: I\subseteq \mathbb{R}\to\mathbb{R}$ heißt **Lösung** der GDGL **auf dem Intervall** $I$, falls für alle $x\in I$ gilt:
> > $$F\left(x,y(x),y'(x),y''(x),\cdots, y^{(n)}(x)\right) = 0$$

> [!DEFINITION] Definition: Explizite GDGL
> Eine gewöhnliche Differentialgleichung heißt **explizit**, falls sie sich in der folgenden Form darstellen lässt:
> $$\frac{\mathop{\mathrm{d}^ny}}{\mathop{\mathrm{d}x^n}}=f\left(x,y,\frac{\mathop{\mathrm{d}y}}{\mathop{\mathrm{d}x}}, \frac{\mathop{\mathrm{d}^2y}}{\mathop{\mathrm{d}x^2}},\cdots, \frac{\mathop{\mathrm{d}^{n-1}y}}{\mathop{\mathrm{d}x^{n-1}}}\right)$$