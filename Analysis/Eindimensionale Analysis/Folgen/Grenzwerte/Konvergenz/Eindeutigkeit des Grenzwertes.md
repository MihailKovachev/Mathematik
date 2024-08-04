> [!THEOREM] Satz: Eindeutigkeit des Grenzwertes
> Jede [konvergente](Konvergenz.md) [Folge](../../Folge.md) besitzt nur einen [Grenzwert](Konvergenz.md).
> > [!PROOF]- Beweis
> > Seien $L_1, L_2$ zwei Grenzwerte der Folge $(a_n)_{n\in\mathbb{N}}$. Dann existiert für jedes $\varepsilon \gt 0$ ein $N_1 \in \mathbb{N}$ mit der Eigenschaft, dass
> > $$|a_n - L_1| \lt \frac{\varepsilon}{2}$$
> > für alle $n \ge N_1$ gilt (Da nach Definition $\varepsilon$ jede Zahl sein darf, können wir $\varepsilon$ durch $\frac{\varepsilon}{2}$ ersetzen). In Analogie dazu gibt es ein $N_2\in\mathbb{N}$ mit der Eigenschaft, dass
> > $$|a_n - L_2| \lt \frac{\varepsilon}{2}$$
> > für alle $n\gt N_2$ gilt.
> > Betrachten wir nun $|L_1 - L_2|$. Es gilt
> > $$|L_1 - L_2| = |L_1 - a_n + a_n - L_2|\le |L_1-a_n|+|a_n-L_2| \lt \frac{\varepsilon}{2} + \frac{\varepsilon}{2} = \varepsilon, \forall n \gt \max \{N_1, N_2\}$$
> > Dieses muss für alle $\varepsilon \gt 0$ gelten, also ist $|L_1 - L_2|$ kleiner als jede positive Zahl und da es nicht negativ sein darf, bleibt nur, dass $|L_1 - L_2| = 0$ ist. Das heißt, $L_1 = L_2$.