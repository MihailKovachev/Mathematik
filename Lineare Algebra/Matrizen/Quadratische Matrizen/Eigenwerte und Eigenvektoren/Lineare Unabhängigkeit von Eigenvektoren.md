> [!THEOREM] Satz: Lineare Unabhängigkeit von Eigenvektoren
> Sind $\vec{e}_1,\cdots,\vec{e}_r\in K^n$ [Eigenvektoren](Eigenvektor.md) zu jeweils den verschiedenen [Eigenwerten](Eigenwert.md) $\lambda_1,\cdots,\lambda_r$ einer [quadratischen Matrix](../Quadratische%20Matrix.md) $M\in K^{n\times n}$, so sind $\vec{e}_1,\cdots,\vec{e}_r$ linear unabhängig.
> 
> Das heißt, [Eigenvektoren](Eigenvektor.md) aus verschiedenen [Eigenräumen](Eigenraum.md) einer [Matrix](../Quadratische%20Matrix.md) sind [linear unabhängig](../../../Abstrakte%20lineare%20Algebra/Lineare%20Unabhängigkeit.md).
> > [!PROOF]- Beweis
> > Eine kleine Bemerkung - die [Anzahl der verschiedenen Eigenwerte](Anzahl%20der%20Eigenwerte.md) von $M\in K^{n\times n}$ ist höchstens $n$, weshalb $r\le n$ gilt.
> > 
> > Der Beweis ist per Induktion.
> > 
> > Induktionsanfang: Der Fall $r=1$ ist trivial, denn $\{\vec{e}_1\}$ ist linear unabhängig.
> > 
> > Induktionsschritt: Angenommen, für $p \le n - 1$ wäre $\{\vec{e}_1,\cdots,\vec{e}_p\}$ linear unabhängig. Dann gilt
> > $$k_1\vec{e}_1+\cdots +k_p\vec{e}_p = \vec{0} \implies k_1=\cdots=k_p=0$$
> > Wir betrachten nun die folgende Gleichung, die wir (a) nennen.
> > $$k_1\vec{e}_1+\cdots +k_p\vec{e}_p + k_{p+1}\vec{e}_{p+1}= \vec{0}$$
> > Multipliziere beide Seiten mit $M$.
> > $$M(k_1\vec{e}_1)+\cdots +M(k_p\vec{e}_p) + M(k_{p+1}\vec{e}_{p+1})= M\vec{0}$$
> > $$k_1(M\vec{e}_1)+\cdots +k_p(M\vec{e}_p) + k_{p+1}(M\vec{e}_{p+1})= M\vec{0}$$
> > $$k_1\lambda_1\vec{e}_1+\cdots +k_p\lambda_p\vec{e}_p + k_{p+1}\lambda_{p+1}\vec{e}_{p+1}= \vec{0}$$
> > Diese nennen wir Gleichung (b).
> > 
> > Wir multiplizieren (a) mit $\lambda_{p+1}$, um Gleichung (c) zu erhalten.
> > $$k_1\lambda_{p+1}\vec{e}_1+\cdots +k_p\lambda_{p+1}\vec{e}_p + k_{p+1}\lambda_{p+1}\vec{e}_{p+1}= \vec{0}$$
> > Nun betrachten wir (b) - (c).
> > $$k_1(\lambda_1-\lambda_{p+1})\vec{e}_1 + \cdots +k_p(\lambda_p-\lambda_{p+1})\vec{e}_p =\vec{0}$$
> > Da die Vektoren $\vec{e}_1,\cdots,\vec{e}_p$ linear unabhängig sind, muss $k_i(\lambda_i - \lambda_{p+1}) = 0$ für alle $i=1,\cdots,p$ gelten. Da die Eigenwerte verschieden sein sollen, kann auf keinen Fall $(\lambda_i - \lambda_{p+1})=0$ gelten. Dann müssen $k_1,\cdots,k_p$ alle gleich Null sein.
> > 
> > Aus (a) folgt daher
> > $$k_{p+1}\vec{e}_{p+1}=\vec{0}$$
> > Da Eigenvektoren laut Definition nicht $\vec{0}$ sind, bleibt nur, dass $k_{p+1}=0$ ist. Damit haben wir 
> > $$k_1\vec{e}_1+\cdots +k_p\vec{e}_p + k_{p+1}\vec{e}_{p+1}= \vec{0} \implies k_1=\cdots=k_p=k_{p+1}=0$$
> > bewiesen, was heißt, $\{\vec{e}_1,\cdots,\vec{e}_p,\vec{e}_{p+1}\}$ sind linear unabhängig.