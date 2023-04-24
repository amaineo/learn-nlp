---
title: Hidden Markov Model
date: '2021-01-01'
type: book
weight: 20

---
{{< math >}}

$$ \delta_j = \underset{k}{\operatorname{max}} {P (path_k({t}_j^s))} $$

{{< /math >}}

{{< math >}}
$$
\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}
$$
{{< /math >}}
