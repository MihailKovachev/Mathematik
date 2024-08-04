> [!ALGORITHM] Algorithmus: Lösen von homogenen linearen GDGL mit konstanten Koeffizienten
> Wir betrachten die [homogene lineare GDGL mit konstanten Koeffizienten](Homogene%20lineare%20GDGL%20mit%20konstanten%20Koeffizienten.md)
> $$a_n y^{(n)}(x) + a_{n-1} y^{(n-1)}(x) + \cdots + a_1 y'(x) + a_0 y(x) = 0$$
> 
> 1. Notiere das [charakteristische Polynom](Charakteristisches%20Polynom.md) $p(\lambda)$ der Differentialgleichung.
> $$p(\lambda) = a_n\lambda^n + a_{n-1}\lambda^{n-1}+\cdots + a_1\lambda + a_0$$
> 2. Bestimme die verschiedenen [Nullstellen](../../../../Polynome/Nullstellen/Nullstelle.md) $\lambda_1,\cdots,\lambda_q$ ($q\le n$) des charakteristischen Polynoms.
> 3. Bestimme $n$ [linear unabhängige](../../../../../../Lineare%20Algebra/Abstrakte%20lineare%20Algebra/Lineare%20Unabhängigkeit.md) Lösungen der Differentialgleichung nach [diesem Satz](Nullstellen%20des%20charakteristischen%20Polynoms.md).
> - Aus jeder $m_r$-fachen reellen Nullstelle $\lambda_r$, ergeben sich $m_r$ linear unabhängige Lösungen
> $$y_{\lambda_r,1}(x) = \mathrm{e}^{\lambda_r x} \qquad y_{\lambda_r,2}(x) = x\mathrm{e}^{\lambda_r x} \qquad \cdots \qquad y_{\lambda_r,m_r}(x) = x^{m_r-1}\mathrm{e}^{\lambda_r x}$$
> - Aus jeder $m_k$-fachen komplexen Nullstelle $\lambda_k = a+\mathrm{i}b$, ergeben sich $2m_k$ linear unabhängige Lösungen (man ignoriert dabei die [komplex konjugierte](../../../../../../Komplexe%20Zahlen/komplexe%20Konjugation/Komplexe%20Konjugation.md) Nullstelle $\overline{\lambda_k}$, denn sie ergibt dieselben Lösungen wie $\lambda_k$).
> $$\begin{align}&y_{\lambda_k,0}(x) = \mathrm{e}^{ax}\cos(bx) \qquad y_{\lambda_k,1}(x) = x\mathrm{e}^{ax}\cos(bx) \qquad \cdots \qquad y_{\lambda_k,m_{k-1}}(x) = x^{m_k-1} \mathrm{e}^{ax}\cos(bx) \\ &y_{\lambda_k,m_k}(x) = \mathrm{e}^{ax}\sin(bx) \qquad y_{\lambda_k,m_k+1}(x) = x\mathrm{e}^{ax}\sin(bx) \qquad \cdots \qquad y_{\lambda_k,2m_k}(x) = x^{m_k-1} \mathrm{e}^{ax}\sin(bx)\end{align}$$
> - Dieses Verfahren ergibt genau $n$ linear unabhängige Lösungen der Differentialgleichung.
> 4. Nach dem [Superpositionsprinzip](Superpositionsprinzip.md) können sich alle Lösungen der Differentialgleichung als [Linearkombination](../../../../../../Lineare%20Algebra/Abstrakte%20lineare%20Algebra/Linearkombination.md) der im Schritt 3 erhalten Lösungen darstellen.
> 
> > [!EXAMPLE]- Beispiel