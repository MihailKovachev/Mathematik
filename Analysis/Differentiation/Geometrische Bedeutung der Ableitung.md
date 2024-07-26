---
Related:
- "[[Ableitung und Differenzierbarkeit]]"
---

> [!INFO] Geometrische Bedeutung der Ableitung
> Betrachten wir eine Kurve $f$.
> ![Geometric derivative](Resources/Geometric%20derivative.jpg)
> Durch jede zwei Punkte $P_0(x_0; f(x_0))$ und $P(x_0+\Delta x; f(x_0+\Delta x))$ der Kurve lässt sich eine Sekante konstruieren, deren Steigung folgendermaßen berechnet werden kann:
> $$\frac{\Delta y}{\Delta x} = \frac{f(x_0+\Delta x) - f(x_0)}{\Delta x}$$
> 
> Diese Sekannte macht mit der $x$-Achse einen Winkel $\varphi$, für den gilt
> $$\tan \varphi = \frac{\Delta y}{\Delta x}$$
> 
> Wenn wir $\Delta x$ gegen Null laufen lassen, also wenn wir den Punkt $P$ der Kurve entlang dem Punkt $P_0$ annähern, wird die Sekannte zu einer immer besseren Approximation der *Tangente* im Punkt $P_0$. Dies wird durch den Limes ausgedrückt:
> $$\lim_{\Delta x\to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0}\frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}$$
> Das heißt auch, der Winkel $\varphi$ wird zu einer immer besseren Approximation des Winkels $\alpha$, den die Tangente in $P_0$ mit der $x$-Achse macht. Dann gilt
> $$\tan \alpha = \lim_{\Delta x \to 0} \tan \varphi = \lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0}\frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} = f'(x_0)$$
> Die Ableitung im Punkt $P_0(x_0; f(x_0))$ ist also der Tangens des Winkels, den die Tangente zu $f$ in $P_0$ mit der $x$-Achse macht.
