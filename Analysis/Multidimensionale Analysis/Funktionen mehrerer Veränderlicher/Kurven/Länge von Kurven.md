>[!DEFINITION] Definition: Länge einer Kurve
>Die **Länge** einer [stetig differenzierbaren](Differentiation/Ableitung%20von%20Kurvenparametrisierungen.md) [Kurve](Kurve.md) $\mathbf{r}: [a;b]\to\mathbb{R}$ nennt man das [bestimmte Integral](../../../Eindimensionale%20Analysis/Integration/Bestimmte%20Integrale/Bestimmtes%20(Riemann-)Integral.md) der [Länge](../../../../Lineare%20Algebra/Vektoren%20als%20Matrizen/Reelle%20Vektoren/Länge.md) ihres [Tangentenvektors](Differentiation/Ableitung%20von%20Kurvenparametrisierungen.md):
>$$\displaystyle \int_a^b ||\dot{\mathbf{r}}(t)||\mathop{\mathrm{d}t}$$

>[!DEFINITION] Definition: Bogenlängenfunktion
>Die **Bogenlängenfunktion** $s_{\mathbf{r}}:[a;b]\to\mathbb{R}$ einer [Kurvenparametrisierung](Kurve.md) $\mathbf{r}:[a;b]\to\mathbb{R}^n$ ordnet jedem $t\in[a;b]$ die Länge der Kurve von $\mathbf{r}(a)$ bis $\mathbf{r}(t)$ zu.
>$$s_\mathbf{r}(t)=\int\limits_a^t ||\dot{\mathbf{r}}(\tau)||\mathop{\mathrm{d}\tau}$$