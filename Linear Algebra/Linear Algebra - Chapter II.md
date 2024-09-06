#linear_algebra 
# Multiplication
### Meaning
1. multiple inputs
2. composition
>$g \circ f$ means:  $g$ after $f$   or   $g(f(\,))$
### Properties
1. **NO** commutative
2. $(AC)^{T} = C^TA^T$
3. associative: different order of calculation could lead to various amout of calculation


>**Trace**: 
>$A: m\times m,\,\, Trace(A) = a_{11}+a_{22}+a_{33}+...+a_{mm}$  



# Inverse
>**Invertible Matrix Theorem**：
>1. Square matrix
>2. (Takes matrix as a FUNCTION) This function is ***one-to-one*** or ***onto***.

1. $(A^T)^{-1} = (A^{-1})^T$ (the inverse of transpose, and it also indicates *the order of transpose and inverse doesn't matter*.)
2. $(AB)^{-1} = B^{-1}A^{-1}$, for more matrices, $(A_1A_2...A_k)^{-1} = (A_k)^{-1}...(A_2)^{-1}(A_1)^{-1}$
### Elementary Matrix
>Def.
>Elementary Matrix multiply a matrix = do **elementary row operation** on the matrix.

**Find a desired Elementary Matrix**
apply the desired elementary row operation on **identity matrix.**
### Find Inverse Matrix
Let $A$ be an $n\times n$ matrix. Transform $[A\,\,\,I_n]$ into its $[ R\,\,\, B ]\,$.
If $R\,=\,I_n\,$, $B\,=\,A^{-1}$. 
If not, $A$ is not invertible.
