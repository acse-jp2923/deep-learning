

# BACKPROP!!!! WOOOOO

1. $$
   \delta^L_j = \frac{\partial C}{\partial a^L_j} \sigma'(z^L_j)
   $$

2. $$
   \delta^l = ((w^{l+1})^T \delta^{l+1}) \odot \sigma'(z^l)
   $$

3. $$
   \frac{\partial C}{\partial b^l_j} = \delta^l_j
   $$

5. $$
   \frac{\partial C}{\partial w^{l}_{jk}} = a^{l-1}_k \delta^l_j
   $$










$$
\delta^L_j = \frac{\partial C}{\partial a^L_j} \sigma'(z^L_j)
$$

NODE CHANGE RECOMMENDATION = RESPONSIBILITY * READINESS TO ADJUST

1. $$
   \delta^L_j
   $$

    The error at a node `j` on layer `L`

2. $$
   \frac{\partial C}{\partial a^L_j}
   $$

   measures how sensitive the cost is to a change in a particular activation. 

   When this derivative is high it means that changes in activation of a node have a high impact on cost. When its low it means the opposite (High implies far from 0, Low implies close to 0)
   
3. $$
   \sigma'(z^L_j)
   $$

   This is the derivative of the cost function at the point the our output is. When it is high (around 0 for sigmoid) the error recommendation will be larger, because the
   
   When it is really low it means that the activation function is relatively flat at that point, and it wont result





---


$$
\delta^l = ((w^{l+1})^T \delta^{l+1}) \odot \sigma'(z^l)
$$

1. $$
   \delta^l
   $$

   explaining....

2. $$
   ((w^{l+1})^T \delta^{l+1})
   $$

   explaining...

3. $$
   ((w^{l+1})^T \delta^{l+1})
   $$

   explaining...

4. $$
   \sigma'(z^l)
   $$

   explaining....



---

$$
\frac{\partial C}{\partial b^l_j} = \delta^l_j
$$

1. $$
   \frac{\partial C}{\partial b^l_j}
   $$

   expl..

2. $$
   \delta^l_j
   $$

   exp...

3. $$
   \frac{\partial C}{\partial b^l_j} = \delta^l_j
   $$





---


$$
\frac{\partial C}{\partial w^{l}_{jk}} = a^{l-1}_k \delta^l_j
$$

1. $$
   \frac{\partial C}{\partial w^{l}_{jk}}
   $$

   expla...

2. $$
   a^{l-1}_k 
   $$

   expla...

3. $$
   \delta^l_j
   $$

   exp...