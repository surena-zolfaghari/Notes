





# Third video

Similarity of logestic regression, now assume we have one data with three features $x_{1},x_{2},x_{3}$, I can calculate a node with an activation function and then $\hat y$. Then I need to initialize $w$, $b$. I had not hidden layer. Now let's do with one hidden layer with four nodes.  
$$z_{1}^{[1]}= w_{1}^{[1]T} X+ b_{1}^{[1]}, \; a_{1}^{[1]} = \sigma(z_{1}^{[1]})$$$$z_{2}^{[1]} = w_{2}^{[1]T}X + b_{2}^{[1]}, \; a_{2}^{[1]} = \sigma(z_{2}^{[1]})$$$$z_{3}^{[1]} = w_{3}^{[1]T}X + b_{3}^{[1]}, \; a_{3}^{[1]} = \sigma(z_{3}^{[1]})$$
$$z_{4}^{[1]} = w_{4}^{[1]T}X + b_{4}^{[1]}, \; a_{4}^{[1]} = \sigma(z_{4}^{[1]})$$
Now **How to vectorizition?** 
It's just enough put $w_{1}^{T}$ on first row and so on. call this matrix $w^{[1]}$   