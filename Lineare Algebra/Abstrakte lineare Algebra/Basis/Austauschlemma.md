> [!THEOREM] Satz: Austauschlemma
> Sei $B$ eine [Basis](Basis.md) eines [endlich erzeugbaren](../Erzeugendensystem.md) [Vektorraums](../Abstrakter%20Vektorraum.md) $(V,K,+,\cdot)$. Zu jedem $\mathbf{u}\ne \mathbf{0}$ aus $V$ gibt es einen Vektor $\mathbf{v}\in B$ derart, dass $B\setminus \{\mathbf{v}\}\cup \{\mathbf{u}\}$ eine Basis von $(V, K,+,\cdot)$ ist.
> 
> Wir können also jedes $\mathbf{u}\in V$ mit einem Vektor aus $B$ austauschen und noch eine Basis erhalten.
> > [!NOTE] Wahl des Vektors aus der Basis
> > Als Vektor zu ersetzen kann jeder Vektor $\mathbf{v}\in B$ gewählt werden, vor dem ein Koeffizient $k\ne 0$ in der Basisdarstellung von $\mathbf{u}$ steht.
> 
> > [!PROOF]- Beweis
> > Da $B$ ein Erzeugendensystem ist, gibt es Vektoren $\mathbf{v}_1,\cdots,\mathbf{v}_n\in V$ mit
> > $$\mathbf{u} = k_1\mathbf{v}_1+\cdots+k_n\mathbf{v}_n$$
> > Aus $\mathbf{u}\ne \mathbf{0}$ folgt, dass mindestens ein $k_j \ne 0$ ist. Wir nennen den dazugehörigen Vektor $\mathbf{v}_j$ und definieren
> > $$B' \overset{\text{def}}{=} B\setminus \{\mathbf{v}_j\} \cup \{\mathbf{u}\}$$
> > Nun müssen wir zeigen, dass $B'$ eine Basis von $(V,K,+,\cdot)$ ist. Zunächst weisen wir nach, dass $B'$ ein Erzeugendensystem ist. Aus der Darstellung von $\mathbf{u}$ folgt
> > $$k_j\mathbf{v}_j = \mathbf{u}-\sum_{i\ne j}k_i\mathbf{v}_i$$
> > Da $k_j\ne 0$ ist, können wir beide Seiten durch $k_j$ dividieren.
> > $$\mathbf{v}_j = \frac{1}{k_j}\mathbf{u}-\sum_{i\ne j}\frac{k_i}{k_j}\mathbf{v}_i$$
> > Wir haben daher eine Darstellung von $\mathbf{v}_j$ durch die Vektoren aus $B'$ gefunden. Die Basis $B$ ist schon ein Erzeugendensystem, d.h. jeder Vektor aus $V$ lässt sich als Linearkombination der Vektoren $\mathbf{v}_1,\cdots,\mathbf{v}_j,\cdots,\mathbf{v}_n\in V$ darstellen. Wir können aber $\mathbf{v}_j$ immer durch die vorgenannte Darstellung $\frac{1}{k_j}\mathbf{u}-\sum_{i\ne j}\frac{k_i}{k_j}\mathbf{v}_i$ ersetzen und dann ließe sich jeder Vektor als Linearkombination der Vektoren $\mathbf{v}_1,\cdots,\mathbf{v}_{j-1},\mathbf{u},\mathbf{v}_{j+1},\cdots,\mathbf{v}_n$ darstellen. Es gilt deshalb, $B' = \{\mathbf{v}_1,\cdots,\mathbf{v}_{j-1},\mathbf{u},\mathbf{v}_{j+1},\cdots,\mathbf{v}_n\}$ ist ein Erzeugendensystem.
> > 
> > Nun zeigen wir, dass $B'$ linear unabhängig ist. Angenommen, $B'$ wäre linear abhängig. Dann gäbe es Skalare $h_1,\cdots,h_n$ mit
> > $$h_j\mathbf{u}+\sum_{i\ne j}h_i\mathbf{v}_i =\mathbf{0}$$
> > Wenn $h_j = 0$ wäre, müsste $\sum_{i\ne j}h_i\mathbf{v}_i = \mathbf{0}$ gelten, aber das hieße $h_1=h_2=\cdots=h_n=0$, denn die Vektoren $\mathbf{v}_1,\cdots,\mathbf{v}_n$ sind Teil der Basis $B$ und daher sind sie auch linear unabhängig. Dann wären alle $h_1,\cdots,h_j,\cdots,h_n = 0$, aber wir haben angenommen, dass mindestens einer dieser Koeffizienten ungleich Null ist. Deswegen muss $h_j \ne 0$ gelten. Also können wir durch $h_j$ dividieren, um zu erhalten
> > $$\mathbf{u}+\sum_{i\ne j}\frac{h_i}{h_j}\mathbf{v}_i = \mathbf{0}$$
> > Wir ersetzen $\mathbf{u}$ durch die entsprechende Basisdarstellung.
> > $$\sum_{i} k_i\mathbf{v}_i + \sum_{i\ne j}\frac{h_i}{h_j}\mathbf{v}_i = \mathbf{0} $$
> > Daraus folgt
> > $$k_j\mathbf{v}_j + \sum_{i\ne j} \left(k_i + \frac{h_i}{h_j}\right) \mathbf{v}_i = \mathbf{0}$$
> > Da dies eine Linearkombination von Vektoren aus der linear unabhängigen Basis $B$ ist, müssen alle Koeffiziente, inklusiv $k_j$, gleich Null sein. Das ist aber ein Widerspruch, denn wir haben $k_j \ne 0$ gewählt. Daher folgt, dass $B'$ linear unabhängig ist.