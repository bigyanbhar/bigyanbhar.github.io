---
layout: default
title: Bigyan Bhar
mathjax: true
---

# Top heading

hello world

## Code
```python
import itertools
print("Hello world")
```

## Equations

<div>
$$
\begin{align}
{ROAS} _ {t+1} & = { {ROAS} _ {t} } \\
\\
\implies \left. \frac{ {impr} \times {CTR} \times {CVR} \times {ASP} }{ {revenue} } \right|_{t+1} & = \left. \frac{ {impr} \times {CTR} \times {CVR} \times {ASP} }{ {revenue} } \right|_{t} \\
\\
\implies \left. \frac{ {ForecastQuantity} \times {ASP} }{ \alpha \times {RP} } \right|_{t+1} & = \left. \frac{ {ForecastQuantity} \times {ASP} }{ \alpha \times {RP} } \right|_{t} \\
\\
\implies {RP}_{t+1} & = \frac{ {ForecastQuantity}_{t+1} \times {ASP}_{t+1} }{ {ForecastQuantity}_t \times {ASP}_t } \times {RP}_{t} \\
\\
\implies {RP}_{t+1} & = \frac{ {ForecastQuantity}_{t+1} }{ {ForecastQuantity}_t } \times {RP}_{t}
\end{align}
$$
</div>

<div>
$$
\begin{align}
{ROAS} _ {t+1} & = { {ROAS} _ {t} } \\
\\
\implies \left. \frac{ {impr} \times {CTR} \times {CVR} \times {ASP} }{ {revenue} } \right|_{t+1} & = \left. \frac{ {impr} \times {CTR} \times {CVR} \times {ASP} }{ {revenue} } \right|_{t} \\
\\
\implies \left. \frac{ {ForecastQuantity} \times {ASP} }{ \alpha \times {RP} } \right|_{t+1} & = \left. \frac{ {ForecastQuantity} \times {ASP} }{ \alpha \times {RP} } \right|_{t} \\
\\
\implies {RP}_{t+1} & = \frac{ {ForecastQuantity}_{t+1} \times {ASP}_{t+1} }{ {ForecastQuantity}_t \times {ASP}_t } \times {RP}_{t} \\
\\
\implies {RP}_{t+1} & = \frac{ {ForecastQuantity}_{t+1} }{ {ForecastQuantity}_t } \times {RP}_{t}
\end{align}
$$
</div>

## Latex
Inline equation like $e=mc^2$ or $\sqrt{100}=10$ or $\sqrt[3]{1000}=10$.

$$ \rho_{t+1} = \rho_{t} + \delta $$

$$ {RP}^{t+1}_{seasonal} = \alpha \times \beta \times {RP}^{t+1} $$

$\beta=10$

$$ \alpha = 
    \frac{1}{C} \times 
        \sum_{a \in {ASIN}(q,k)}{
            \left(
                \frac{
                    {SalesForecast}^{t+1}_{a}
                }{
                    {SalesForecast}^{t}_{a}
                }
            \right)

            \left(
                10 \times {Conversion}^{t}_{a} + 
                {Clicks}^{t}_{a}
            \right)
        }
$$