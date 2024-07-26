> [!IMPORTANT] Satz: Cauchy-Kriterium
> Eine reelle [Folge](../../Folge.md) ist genau dann [konvergent](Konvergenz.md), wenn es zu jedem $\varepsilon \gt 0$ ein $N \in \mathbb{N}$ derart gibt, dass
> $$|a_n - a_m| \lt \varepsilon \qquad \forall m,n \ge N$$
> > [!CHECK]- Beweis
> > Wir müssen beide Richtungen beweisen.
> > 
> > Zunächst sei $(a_n)_{n\in\mathbb{N}}$ eine gegen $L$ konvergente reelle Folge. Dann existiert zu jedem $\frac{\varepsilon}{2} \gt 0$ ein $N \in \mathbb{N}$ derart, dass
> > $$|a_n - L| \lt \frac{\varepsilon}{2}, \forall n \ge N$$
> > Daraus folgt
> > $$|a_n - a_m| = |a_n - L + L - a_m| \le |a_n - L| + |L - a_m| \lt \frac{\varepsilon}{2} + \frac{\varepsilon}{2} = \varepsilon$$
> > Dieses gilt für jede $n,m \gt N$, also ist $(a_n)_{n\to\infty}$ eine Cauchy-Folge.
> > 
> > Umgekehrt: sei $(a_n)_{n\in\mathbb{N}}$ eine Cauchy-Folge. Dann gibt es zu jedem $\varepsilon \gt 0$ ein $N \in \mathbb{N}$ derart, dass
> > $$|a_n - a_m| \lt \varepsilon, \forall m,n \ge N$$
> > Wir beweisen jetzt, dass $(a_n)_{n\in\mathbb{N}}$ beschränkt ist. Wir wählen $\varepsilon = 1$ und den davon abhängigen Index $N(\varepsilon)$. Für alle $n\ge N$ gilt dann
> > $$|a_n| = |a_n - a_N + a_N| \le |a_n - a_N| + |a_N| \lt 1 + |a_N|$$
> > Daraus folgt
> > $$|a_n| \le \max \{|a_1|,\cdots,|a_{N-1}|,|a_{N}| + 1\} \lt \infty$$
> > Die Folge ist also beschränkt. Laut des Bolzano-Weierstraß Satzes hat sie dann mindestens einen Häufungspunkt $L$, also zumindest eine Teilfolge $(a_{n_k})_{n\in\mathbb{N}}$ mit $\displaystyle\lim_{k\to\infty} a_{n_k} = L$. Nun zeigen wir, dass sogar die ganze Folge $(a_n)_{n\in\mathbb{N}}$ gegen $L$ konvergiert. Nach Definition der Konvergenz der Teilfolge existiert zu jedem $\varepsilon \gt 0$ ein $K \in \mathbb{N}$ mit
> > $$|a_{n_k} - L| \lt \frac{\varepsilon}{2}, \forall k\ge K$$
> > Da die Folge eine Cauchy-Folge ist, gibt es ein $N\in\mathbb{N}$ mit
> > $$|a_n - a_m| \lt \frac{\varepsilon}{2}, \forall n,m \ge N$$
> > Insgesamt ergibt sich
> > $$|a_n - L| = |a_n - a_{n_k} + a_{n_k} - L| \le |a_n-a_{n_k}| + |a_{n_k} - L| \lt \frac{\varepsilon}{2} + \frac{\varepsilon}{2} = \varepsilon$$
> > für alle $n\ge \max \{K, N\}$. Die ganze Folge ist also gegen $L$ konvergent.
>
> > [!DANGER] Definition: Cauchy-Folgen
> > Folgen, für die das obige erfüllt ist, nennt man **Cauchy-Folgen**.
