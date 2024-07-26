> [!IMPORTANT] Satz: Transformation des Nullvektors
> Für jede [lineare Transformation](Lineare%20Transformation.md) $T: V \to W$ gilt
> $$T (\mathbf{0}_V) = \mathbf{0}_W,$$
> wo $\mathbf{0}_V$ und $\mathbf{0}_W$ die [Nullvektoren](../Abstrakter%20Vektorraum.md) jeweils aus $V$ und $W$ sind.
> > [!CHECK]- Beweis
> > 

> [!IMPORTANT] Satz: Linearität der Verkettung
> Die [Verkettung](../../../Mengenlehre/Abbildungen/Verkettung.md) $g\circ f: V\to W$ von zwei [linearen Transformationen](Lineare%20Transformation.md) $f: V\to U$ und $g: U\to W$ ist auch eine lineare Transformation.
> > [!CHECK]- Beweis
> > $$\begin{align}g\circ f(\lambda \mathbf{u} +\mu\mathbf{v}) &= g(f(\lambda \mathbf{u} +\mu\mathbf{v}))\\ &= g(\lambda f(\mathbf{u}) + \mu f(\mathbf{v})) \\ &= g(\lambda f(\mathbf{u})) + g(\mu f(\mathbf{v})) \\ &= \lambda g(f(\mathbf{u})) +\mu g(f(\mathbf{v}))\\ &= \lambda g\circ f(\mathbf{u})+\mu g\circ f (\mathbf{v})\end{align}$$

> [!IMPORTANT] Satz: Linearität der Umkehrtransformation
> Ist $f$ eine [bijektive](../../../Mengenlehre/Abbildungen/Injektivität,%20Surjektivität%20und%20Bijektivität.md) [lineare Transformation](Lineare%20Transformation.md), so ist auch die [Umkehrabbildung](../../../Mengenlehre/Abbildungen/Umkehrabbildung.md) $f^{-1}$ eine bijektive lineare Transformation.
> > [!CHECK]- Beweis