---
layout: page
title: Correlação
permalink: prob-est/correlacao
---

Assim como a covariância, o coeficiente de correlação é um número que quantifica as relações lineares entre duas variáveis.
Entretanto, o coeficiente de correlação é uma medida normalizada no intervalo [-1, 1], independendo da escala de cada variável.

- Quando o valor do coeficiente se aproxima de 1, significa que as variáveis possuem uma forte relação linear positiva.
- Quando o valor do coeficiente se aproxima de -1, significa que as variáveis possuem uma forte relação linear negativa.
- O valor 0 do coeficiente representa a inexistência de correlação entre as variáveis


## Coeficiênte de correlação de Pearson

$$ corr(X, Y) = \frac{cov(X, Y)}{\sigma _X \sigma _Y} $$

onde $$\sigma _X$$ é o desvio padrão de $$X$$ e $$cov(X, Y)$$ é a covariância entre as variáveis $$X$$ e $$Y$$.

# Ver também
- [Covariância]({{ site.github.url }}{% link _prob-est/covariancia.md %})

# Referências
- [Weisstein, Eric W. "Statistical Correlation." From MathWorld--A Wolfram Web Resource](http://mathworld.wolfram.com/StatisticalCorrelation.html)
- [Statistics 101: Understanding Correlation](https://www.youtube.com/watch?v=4EXNedimDMs)
