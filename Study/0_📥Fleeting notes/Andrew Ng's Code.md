# Week 2 
## Vectorization

```
import numpy as np 

a = np.array([1,2,3,4])

print("a")

import time

a = np.random.rand(1000000)
b = np.random.ramd(1000000)
tic = time.time()
c = np.dot(a,b)
toc = time.time()
print("Vectorized version:" + str(1000*(toc-tic)) + "ms")

```
## More Vectorization Examples
He introduced some example you can see in his presentaion.




# in practice assignment 
Instructions: x could now be either a real number, a vector, or a matrix. The data structures we use in numpy to represent these shapes (vectors, matrices...) are called numpy arrays. You don't need to know more for now.