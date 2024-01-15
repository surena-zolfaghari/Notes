

The vectors you are referring to essentially represent quantum states. The inner product between two quantum states gives you the overlap between the two states. Put differently, it tells us how much of one state is contained in the other.

For example, consider two possible quantum states $|\Psi_1\rangle$ and $|\Psi_2\rangle$. For example, once they are represented in real space, they can be something like $\langle x|\Psi_1\rangle=\sin(x)$, $\langle x|\Psi_2\rangle=\sin(2x)$. If you take the inner product between them the two states $|\Psi_1\rangle$,$|\Psi_2\rangle$ which is simply an integral over the real space if we choose to project them on the real space as we did above, we get zero. This is because the functions $\sin(x), \sin(2x)$ do not have any overlap in the sense that they can independently contribute in describing a function in real space.

To make it more concrete, we can represent a function $f(x)$ as a sum of the functions $\sin(nx)$, where $\sin(nx)$and $\sin(mx)$ are orthogonal (zero inner product) for $n\neq m$. In the language of vector calculus, these functions form an orthogonal (which can also be made orthonormal with the appropriate normalization) basis for functions $f(x)$. 

To exactly find the sum of the functions of the basis that describes an arbitrary function, one goes through the process of Fourier decomposition, but this is a topic for another time!

In the previous example, then, $\langle \Psi_1|\Psi_2\rangle=0$, and the two quantum states have zero inner product, so no overlap. If we had a third quantum state, say

|ϕ⟩=35|ψ1⟩+45|ψ2⟩

then its inner product with either |ψ1⟩
or |ψ2⟩ would not be zero. It obviously has overlap with both these states since it contains these states!