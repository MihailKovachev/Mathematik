>[!DEFINITION] Definition: Divergenz
>Sei $\boldsymbol{v}: D\subseteq \mathbb{R}^n\to\mathbb{R}^n$ ein [Vektorfeld](Vektorfeld.md) mit [Komponentenfunktionen](../../Reelle%20Funktion%20mehrerer%20Veränderlicher.md) $v_1,\cdots,v_n$.
>
>Die **Divergenz** von $\boldsymbol{v}$ ist das [Skalarfeld](../../Skalarfelder/Skalarfeld.md)
>$$\sum_{i=1}^n \partial_i v_i$$
>
>>[!NOTE] Bezeichnung
>>$$\nabla \cdot \boldsymbol{v} \\ \qquad \mathop{\operatorname{div}}\boldsymbol {v}$$
>
>>[!DEFINITION] Definition: Quelle und Senke
>> Die Divergenz von $\boldsymbol{v}$ in einem bestimmten $\vec{x}\in D$ ist die reelle Zahl $\nabla\cdot \boldsymbol{v}(\vec{x}) = \sum_{i=1}^n \partial_i v_i (\vec{x})$.
>>
>>Falls $\nabla\cdot\boldsymbol{v}(\vec{x}) \lt 0$, so heißt $\vec{x}$ **Senke**.
>>
>>Falls $\nabla\cdot\boldsymbol{v}(\vec{x}) = 0$, so heißt $\vec{x}$ **quellenfrei**.
>>
>>Falls $\nabla\cdot\boldsymbol{v}(\vec{x}) \gt 0$, so heißt $\vec{x}$ **Quelle**.