# Multi Layer Perceptron

This in an implementation of a MLP from scratch. This neural network is designed with 2 layers, including one hidden layer and used to perform binary classification. Technical details are available in the notebook. 

To code this MLP, I based myself on the course given by Geoffroy Peeters, professor at Télécom Paris. Concerning alternatives to gradient descent, they are based of courses given by Rémi Flamary, professor at Ecole Polytechique.

### Overview of the MLP
$$ 
\begin{align*}
&\text{Input : }\mathbf{x}  \\
&\text{Layer[1]:} \quad \mathbf{x} W^{[1]} + b^{[1]} \rightarrow z^{[1]} \rightarrow g^{[1]}(z^{[1]}) \rightarrow a^{[1]} \\
&\text{Layer[2]:} \quad a^{[1]} W^{[2]} + b^{[2]} \rightarrow z^{[2]} \rightarrow g^{[2]}(z^{[2]}) \rightarrow a^{[2]} \\
&\text{Loss:} \quad \mathcal{L}(\hat{y} = a^{[2]}, y)
\end{align*}
$$ 






