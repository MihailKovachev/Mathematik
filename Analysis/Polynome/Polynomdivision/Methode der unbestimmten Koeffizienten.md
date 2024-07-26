> [!TODO] Algorithmus: Methode der unbestimmten Koeffizienten
> Wir haben zwei [Polynome](../Polynom.md) $A(x)$ und $B(x)$ mit $\deg (A) = n$ und $\deg (B) = m \le n$ und möchten $A(x)$ durch $B(x)$ [dividieren](../Polynom.md). Das heißt, wir wollen die zwei Polynome $Q(x)$ und $R(x)$ mit $\deg(Q) = n - m$ und $\deg(R) \lt m$ finden, so dass
> $$A(x) = B(x)Q(x) + R(x)$$
> 1. Wir wissen, dass $\deg (Q) = n-m$ ist, also können wir $Q(x)$ in folgender Weise aufschreiben:
> $$Q(x) = q_{n-m}x^{n-m}+q_{n-m-1}x^{n-m-1} + \cdots + q_1x + q_0$$
> 2. Da $\deg (R) \lt m$ ist, können wir in Analogie dazu annehmen, dass $\deg(R) = m-1$ ist, und $R(x)$ folgendermaßen darstellen:
> $$R(x) = r_{m-1}x^{m-1} + r_{m-2}x^{m-1} + \cdots + r_1x + r_0$$
> Sollte es sich herausstellen, dass unsere Annahme falsch ist, würden die Koeffizienten $r_i, i \gt \deg (R)$ einfach zu Null.
> 3. Wir schreiben dann alles in vollkommener Form
> $$A(x) = B(x)(q_{n-m}x^{n-m}+q_{n-m-1}x^{n-m-1} + \cdots + q_1x + q_0) + (r_{m-1}x^{m-1} + r_{m-2}x^{m-1} + \cdots + r_1x + r_0)$$
> 4. Wir multiplizieren $B(x)$ und $Q(x)$ aus und gruppieren dann die Potenzen von $x$, indem wir die Summe aller Koeffizienten der jeweiligen Potenz vor den Summanden schreiben. Wir erhalten etwas wie das Folgende
> $$A(x) = k_nx^n+\cdots+k_1x+k_0, $$
> wobei die Koeffizienten $k_i$ verschiedene Kombinationen von den Koeffizienten der Polynome $B(x), Q(x)$ und $R(x)$ repräsentieren.
> 5. Nun ersetzen wir $A(x)$ durch seine ganze Form:
> $$a_nx^n + \cdots + a_1x + a_0 = k_nx^n+\cdots+k_1x+k_0$$
> 6. Wir vergleichen jetzt die Koeffizienten vor den Potenzen von $x$ an beiden Seiten. Damit die linke Seite gleich der rechten ist, müssen alle $a_i = k_i$ sein. Somit erhalten wir ein Gleichungssystem:
> $$\begin{cases}a_n = k_n \\ a_{n-1}=k_{n-1} \\ \vdots \\ a_1 = k_1 \\ a_0 = k_0 \end{cases}$$
> Erinnern wir uns daran, dass hinter $k_n,\cdots,k_0$ Kombinationen der Koeffizienten $b, q, r$ von $B(x), Q(x), R(x)$ stecken. Die Koeffizienten von $A(x)$ und $B(x)$ wissen wir schon und jetzt können wir die von $Q(x)$ und $R(x)$ bestimmen, indem wir das Gleichungssystem lösen.
> 
> > [!EXAMPLE]- Beispiel
> > $$(4x^4-6x^3+2x-1) : (3x^2 - 5) = ?$$
> > Hier sind $A(x) = (4x^4-6x^3+2x-1)$ und $B(x) = (3x^2 - 5)$, also
> > $$(4x^4-6x^3+2x-1) = (3x^2 - 5)Q(x) + R(x)$$
> > Der Grad von $Q$ ist $\deg (A) - \deg (B) = 4 - 2 = 2$. Das heißt, $Q(x)$ hat die Form
> > $$Q(x) = q_2x^2 + q_1x + q_0$$
> > und wir wollen die Koeffizienten $q_2,q_1,q_0$ bestimmen. Der Grad von $R$ ist kleiner als der von $B$, also ist $\deg(R)$ höchstens $\deg(B) - 1 = 2 - 1 = 1$. Dann hat $R$ die Form
> > $$R(x) = r_1x + r_0$$
> > und wir wollen auch die Koeffizienten $r_1, r_0$ bestimmen. Schreiben wir das im Ganzen:
> > $$A(x) = B(x)Q(x) + R(x)$$
> > $$(4x^4-6x^3+2x-1) = (3x^2 - 5)(q_2x^2 + q_1x + q_0) + (r_1x + r_0)$$
> > Wir multiplizieren die rechte Seite aus und gruppieren die Summanden.
> > $$4x^4-6x^3+2x-1 = 3q_2x^4+3q_1x^3+3q_0x^2 - 5q_2x^2-5q_1x-5q_0 + r_1x + r_0$$
> > $$4x^4-6x^3+2x-1 = 3q_2x^4+3q_1x^3+(3q_0-5q_2)x^2+(-5q_1+r_1)x+(r_0-5q_0)$$
> > Jetzt erstellen wir das Gleichungssystem:
> > $$\begin{cases} 3q_2 = 4 \\ 3q_1 = -6\\ 3q_0 - 5q_2 = 0 \\ -5q_1+r_1 = 2\\ r_0 - 5q_0 = -1\end{cases}$$
> > Dies lässt sich leicht lösen.
> > $$\begin{cases}q_2 = \frac{4}{3} \\ q_1 = -2 \\ q_0 = \frac{20}{9} \\ r_1 = -8 \\ r_0 = \frac{91}{9}\end{cases}$$
> > Letztendlich erhalten wir das Ergebnis
> > $$(4x^4-6x^3+2x-1) = (3x^2 - 5)\left(\frac{4}{3}x^2-2x+\frac{20}{9}\right) + \left(-8x+\frac{91}{9}\right)$$