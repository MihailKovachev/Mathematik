> [!TODO] Algorithmus: Lösen von linearen GDGL erster Ordnung
> Wir betrachten die [lineare GDGL erster Ordnung](Lineare%20GDGL%20erster%20Ordnung.md)
> $$\frac{\mathop{\mathrm{d}y}}{\mathop{\mathrm{d}x}}+p(x)y = g(x)$$
> 1. Bestimme einen **Integrationsfaktor** $\mu(x)$, indem du die folgende Gleichung löst:
> $$\frac{\mathop{\mathrm{d}\mu(x)}}{\mathop{\mathrm{d}x}} = p(x)\mu(x)$$
> - Dividiere durch $\mu(x)$;
> $$\frac{1}{\mu(x)}\frac{\mathop{\mathrm{d}\mu(x)}}{\mathop{\mathrm{d}x}} = p(x)$$
> - Integriere beide Seiten;
> $$\ln |\mu(x)| = \int p(x) \mathop{\mathrm{d}x} + k$$
> - Die Konstante $k$ darf man hier beliebig wählen, denn die Gleichung $\mu'(x)=\mu(x)p(x)$ hängt nicht von ihr ab. Also setze $k=0$, um die einfachste $\mu(x)$ zu erhalten.
> > [!IMPORTANT] Lösung für $\mu(x)$
> > $$\mu(x) = \mathrm{e}^{\int p(x) \mathop{\mathrm{d}x}}$$
> 
> 2. Multipliziere die ursprüngliche Differentialgleichung mit dem schon bestimmten Integrationsfaktor $\mu(x)$.
> $$\mu(x)\frac{\mathop{\mathrm{d}y}}{\mathop{\mathrm{d}x}}+p(x)\mu(x)y = \mu(x)g(x)$$
> 3. Wende die [Produktregel](../../../../Differentiation/Rechenregeln%20für%20Ableitungen.md) an, um die linke Seite als $(\mu(x)y)'$ darzustellen.
> - Da wir $\mu(x)$ so bestimmt haben, dass $\mu'(x) = p(x)\mu(x)$, gilt
> $$(\mu(x)y)' = \mu(x)y' + \mu'(x)y = \mu(x)y' + p(x)\mu(x)y$$
> - Daraus ergibt sich
> $$\frac{\mathop{\mathrm{d}}}{\mathop{\mathrm{d}x}}[\mu(x)y] = \mu(x)g(x)$$
> 4. Integriere beide Seiten
> $$\mu(x)y = \int \mu(x)g(x)\mathop{\mathrm{d}x} \mathop{+} c$$
> 5. Dividiere durch $\mu(x)$, um die Lösungen zu erhalten, wobei jedes $c\in\mathbb{R}$ eine Lösung ergibt.
> > [!IMPORTANT] Lösung für $y(x)$
> $$y(x) = \frac{1}{\mu (x)}\left(\int \mu(x)g(x)\mathop{\mathrm{d}x} \mathop{+} c\right)$$
> 
> > [!EXAMPLE]- Beispiel
