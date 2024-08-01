> [!DEFINITION] Definition: Anfangswertproblem (AWP)
> Ein **Anfangswertproblem** (kurz **AWP**) ist eine [explizite gewöhnliche Differentialgleichung](Gewöhnliche%20Differentialgleichung.md)
> $$\frac{\mathop{\mathrm{d}^ny}}{\mathop{\mathrm{d}x^n}}=f\left(x,y,\frac{\mathop{\mathrm{d}y}}{\mathop{\mathrm{d}x}}, \frac{\mathop{\mathrm{d}^2y}}{\mathop{\mathrm{d}x^2}},\cdots, \frac{\mathop{\mathrm{d}^{n-1}y}}{\mathop{\mathrm{d}x^{n-1}}}\right)$$
> mit $n$ **Anfangsbedingungen** 
> $$y(x_0) = y_0, y'(x_0)=y_1, y''(x_0)=y_2,\cdots, y^{(n-1)}(x_0)=y_{n-1},$$
> wobei die Werte $x_0,y_0,y_1,\cdots,y_{n-1}$ vorgegeben sind.
> > [!DEFINITION] Definition: Lokale Lösbarkeit
> > Ein Anfangswertproblem heißt **lokal lösbar**, falls ein $\varepsilon \gt 0$ existiert, sodass auf $I = (x_0-\varepsilon;x_0+\varepsilon)$ eine [Lösung](Gewöhnliche%20Differentialgleichung.md) $y:I\to\mathbb{R}$  der GDGL besteht, die auch den Anfangsbedingungen für $x_0$ genügt. 
> > 
> > So eine [Funktion](../../Funktionen/Funktion.md) $y(x)$ heißt **lokale Lösung** des AWP.
> 
> > [!QUOTE] Erklärung zur Definition
> > Der Begriff des Anfangswertproblems stammt von der Analysis physikalischer Systeme. Dabei wird die Entwicklungs eines oder mehrerer physikalischer Vorgänge im Laufe der Zeit durch Differentialgleichungen dargestellt und der Anfangszustand wird durch die Anfangsbedingungen repräsentiert.

