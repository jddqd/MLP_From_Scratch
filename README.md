# Multi Layer Perceptron

Work In Progress

This in an implementation of a MLP from scratch. This neural network is designed with 2 layers, including one hidden layer and used to perform binary classification. Technical details are available in the notebook. 

Reference : 

IA-306 "Deep Learning I" course by Geoffroy Peeters, Alasdair Newson (Telecom Paris, IP-Paris)

Adam: A Method for Stochastic Optimization (Kingma, Diederik and Ba, Jimmy), In International Conference on Learning Representations (ICLR), 2015.



### Overview of the MLP
$$ 
\begin{align*}
&\text{Input : }\mathbf{x}  \\
&\text{Layer[1]:} \quad \mathbf{x} W^{[1]} + b^{[1]} \rightarrow z^{[1]} \rightarrow g^{[1]}(z^{[1]}) \rightarrow a^{[1]} \\
&\text{Layer[2]:} \quad a^{[1]} W^{[2]} + b^{[2]} \rightarrow z^{[2]} \rightarrow g^{[2]}(z^{[2]}) \rightarrow a^{[2]} \\
&\text{Loss:} \quad \mathcal{L}(\hat{y} = a^{[2]}, y)
\end{align*}
$$ 






