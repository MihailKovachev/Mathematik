> [!DANGER] Definition: Abstrakter Vektorraum
> Ein **abstrakter** $K$-**Vektorraum** $(V, K, +,\cdot)$ oder **abstrakter Vektorraum über den [Körper](../../Mengenlehre/Körper/Körper.md)** $K$ ist eine nichtleere Menge $V$ und ein Körper $K$, die mit einer **Vektoraddition** $+: V \times V \to V$ und einer **Multiplikation mit Skalaren** $\cdot : V \times K \to V$ ausgerüstet sind, die die folgenden Eigenschaften besitzen.
> - Kommutativität: $\mathbf{u} + \mathbf{v} = \mathbf{v} + \mathbf{u} \qquad \forall \mathbf{u},\mathbf{v} \in V$
> - Assoziativität I: $\mathbf{u} + (\mathbf{v} + \mathbf{w}) = (\mathbf{u} + \mathbf{v}) + \mathbf{w} \qquad \forall \mathbf{u},\mathbf{v}, \mathbf{w} \in V$
> - Assoziativität II: $(\lambda\mu)\mathbf{u} = \lambda(\mu\mathbf{u}) \qquad \forall \lambda,\mu\in K, \forall \mathbf{u} \in V$
> - Distributivität I: $\lambda (\mathbf{u} + \mathbf{v}) = \lambda\mathbf{u}+\lambda\mathbf{v} \qquad \forall \mathbf{u},\mathbf{v} \in V, \forall \lambda \in K$
> - Distributivität II: $(\lambda + \mu)\mathbf{v} = \lambda\mathbf{v}+\mu\mathbf{v} \qquad \forall \lambda,\mu \in K, \forall \mathbf{v}\in V$
> - Existenz eines Nullelements: Es besteht ein $\mathbf{0} \in V$ mit $\mathbf{v} + \mathbf{0} = \mathbf{v} \qquad \forall \mathbf{v} \in V$
> - Existenz eines Identitätselements: Es besteht ein $1 \in K$ mit $1\cdot \mathbf{u} = \mathbf{u} \qquad \forall \mathbf{u}\in V$
> - Existenz eines inversen Vektors: Für jedes $\mathbf{v} \in V$ gibt es ein $-\mathbf{v} \in V$ mit $\mathbf{v} + (-\mathbf{v}) = \mathbf{0}$
> 
> Die Elemente aus $V$ nennt man **Vektoren**. 
> 
> Den Vektor $\mathbf{0}$ nennt man **Nullvektor**.
> > [!DANGER] Definition: Reeller Vektorraum
> > Der Vektorraum $(V,K,+,\cdot)$ heißt **reell**, falls $K = \mathbb{R}$.
> 
> > [!DANGER] Definition: Komplexer Vektorraum
> > Der Vektorraum $(V,K,+,\cdot)$ heißt **komplex**, falls $K = \mathbb{C}$.