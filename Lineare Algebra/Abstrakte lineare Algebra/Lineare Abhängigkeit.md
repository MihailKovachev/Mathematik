> [!DANGER] Definition: Lineare Abhängigkeit
> Die Vektoren $\mathbf{v}_1,\mathbf{v}_2,\cdots$ des [abstrakten Vektorraums](Abstrakter%20Vektorraum.md) $(V, K, +,\cdot)$ heißen **linear abhängig**, falls sie nicht [linear unabhängig](Lineare%20Unabhängigkeit.md) sind, d.h. es gibt $k_1, k_2,\cdots\in K$ mit mindestens einem $k_i\ne 0$ und
> $$k_1\mathbf{v}_1+k_2\mathbf{v}_2+\cdots = \mathbf{0}$$

> [!IMPORTANT] Satz: Lineare Abhängigkeit $\implies$ Linearkombination
> Sind $\{\mathbf{v}_1,\cdots,\mathbf{v}_n\}$ ($n\ge 2$) linear abhängige Vektoren, dann besteht mindestens ein Vektor $\mathbf{v}_i \in \{\mathbf{v}_1,\cdots,\mathbf{v}_n\}$, der sich als [Linearkombination](Linearkombination.md) der anderen darstellen lässt:
> $$\mathbf{v}_i = \sum_{j\ne i} k_j \mathbf{v}_j$$
> > [!CHECK]- Beweis
> > Nach Definition der linearen Abhängigkeit, gibt es $h_1,\cdots,h_n$ mit
> > $$h_1\mathbf{v}_1+\cdots+h_n\mathbf{v}_n = \mathbf{0}$$
> > so, dass mindestens einer der Koeffizienten $h_i$ nicht Null ist. Dann folgt
> > $$h_i \mathbf{v}_i = -h_1\mathbf{v}_1+\cdots -h_{i-1}\mathbf{v}_{i-1}-h_{i+1}\mathbf{v}_{i+1}+\cdots+-h_n\mathbf{v}_n$$
> > Da $h_i \ne 0$, können wir beide Seiten durch $h_i$ dividieren. Dann gilt
> > $$\mathbf{v}_i = k_1\mathbf{v}_1+\cdots +k_{i-1}\mathbf{v}_{i-1}+k_{i+1}\mathbf{v}_{i+1}+\cdots+k_n\mathbf{v}_n$$
> > mit $k_j = -\frac{h_j}{h_i}$