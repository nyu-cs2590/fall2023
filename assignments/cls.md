**Please not the index here is different from the original question statement!**


For that formulation, we can just change the underindex to j to prevent confusion with the index of the token.

$$X_i$$ is a token in the sentence and $$i$$ is the index of the token in the sentence, $$i \in \{1, \ldots, n\}$$.

$$
P(X_i|Y=y) \sim \text{category}\left(\theta_{w_j, y}\right)
$$

while $$j$$ is the index of the token in the vocabulary, $$j \in \{1, \ldots, m\}$$.

In the question statement, we give


$$P(X_i|Y=y) = p\left(x_1, \ldots, x_m\right)=\prod_{j=1}^m \theta_j^{\mathbb{1}\{x_i=j\}} = \theta_{w_j, y}$$

We notice there is $$i$$ in the equation, which is the result of independence assumption. And only the term with $$x_i$$ is not 1. 

