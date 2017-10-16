---
layout: page
title: Covariância
permalink: prob-est/covariancia
---

Covariância faz parte de uma família de medidas estatísticas usadas para analisar as relações lineares entre duas variáveis.

É uma medida descritiva da associação linear entre duas variáveis.
- Um valor **positivo** indica uma relação linear direta ou **crescente**
- Um valor **negativo** indica uma relação linear **decrescente**
- Quando as variáveis não aparentam ter uma relação linear a covariância é próxima ou igual a 0

![text]({{ site.github.url }}{% link assets/images/covariancia_01.svg %})

## Definição
Covariância amostral:

$$ s_{xy} = \frac{\sum{(x_i - \overline{x})(y_i - \overline{y})}}{n-1} $$

onde $$x_i$$ é o valor de $$x$$ na amostra $$_i$$, $$\overline{x}$$ é o valor médio de $$x$$, $$y_i$$ é o valor de $$y$$ na amostra $$_i$$, $$\overline{y}$$ é o valor médio de $$y$$, e $$n$$ o tamanho da amostra.


## Matriz de covariância
É uma matriz simétrica em que o elemento na posição i, j da matriz é a correlação entre as variáveis aleatórias i e j. Para os elementos da diagonal principal, a covariância de uma variável aleatória com ela mesma é simplesmente a variância dessa variável.

### Exemplo
Sendo $$x_1$$, $$x_2$$, $$x_3$$, $$x_4$$ diferentes variáveis aleatórias,

|         |      $$x_1$$     |      $$x_2$$     |      $$x_3$$     |      $$x_4$$     |
|:-------:|:----------------:|:----------------:|:----------------:|:----------------:|
| $$x_1$$ |   $$var(x_1)$$   | $$cov(x_1,x_2)$$ | $$cov(x_1,x_3)$$ | $$cov(x_1,x_4)$$ |
| $$x_2$$ | $$cov(x_2,x_1)$$ |   $$var(x_2)$$   | $$cov(x_2,x_3)$$ | $$cov(x_2,x_4)$$ |
| $$x_3$$ | $$cov(x_3,x_1)$$ | $$cov(x_3,x_2)$$ |   $$var(x_3)$$   | $$cov(x_3,x_4)$$ |
| $$x_4$$ | $$cov(x_4,x_1)$$ | $$cov(x_4,x_2)$$ | $$cov(x_4,x_3)$$ |   $$var(x_4)$$   |

# Ver também
- [Correlação]({{ site.github.url }}{% link _prob-est/correlacao.md %})
