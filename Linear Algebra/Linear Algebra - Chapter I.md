#linear_algebra
### Linear system
1. What's a **system**?
	a system has **input and output**.
2. <mark style="background: #FFB86CA6;">Two properties of linear system</mark>
	a. Preserving Multiplication
	b. Preserving Addition
### System of Linear Equations
>**Note:**
   Linear system = system of linear equations
### Matrix
identity matrix $I_m = I_{m\times m}$

# Solutions
**consistent** → a system of equations has *at least one solution*
***inconsistent** → no solution* 
### Linear Combination
i.e. weighted sum
⇒ every column vector(vector set) multiplies a scalar.

### Span
1. for a vertor set $S = \{u_1, u_2,..., u_k\}$, $span\, S = \{c_1u_1+c_2u_2+...+c_ku_k\,|\,for\, all\, c_1, c_2,...,c_k\}$
2. If a vector set $V = span\,S$, then *S is a generating set for V*.
3. $AX = b$ ⇔ $b \in span\,S$  (S is the columns of A)
4. If $span\,S = R^2$, every $b$ has solution.

### Dependent & Independent
>Definition of **Dependent**:
>for a vertor set $\{u_1, u_2,...,u_k\}$, there exists $c_1u_1+c_2u_2+...+c_ku_k = 0$ and at least one $c_i$ is *non-zero*.
1. Dependent ⇔ the set has useless vector (有人在耍廢)
2. (If *has solutions* →) *dependent* → *infinite* solutions.

### Rank & Nullity
>**Definition** of Rank:
>The maximum number of *independent* columns.
>**Definition** of Nullity:
>$N - Rank$ ($N$ is the total number of columns in the matrix)

Rank = number of non-zero rows
Nullity $\neq$ number of zero rows

independent ⇔ Rank = N
dependent ⇔ Rank $<$ N

rank $\leq min(m, n)$  (given a $m\times n$ matrix)


### Conclusion
![[Pasted image 20240621143856.png]]

### How to Find Solutions
- **Equivalent**: two solution sets are identical.
- Augmented Matrix
- Elementary Row Operation
- Reduced Form Echelon Form(RREF)

### RREF

>**Column Correspondence Theorem**:
>column之間的承諾，by doing ERO on a matrix, the correspondence between two columns won't change.

**Check Independent**
a vector set is independent ⇔ its RREF is a set of standard vertors