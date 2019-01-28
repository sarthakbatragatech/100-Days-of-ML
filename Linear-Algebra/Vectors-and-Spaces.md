### Vectors and spaces
- [x] Vectors
    - An entity with both magnitude and direction. Velocity is a vector while speed is a scalar.
    - When referencing to R<sup>n</sup>, one is talking about all real valued n-tuples.
    - Concept behind "collinear vectors" and parametric representation of lines.

- [x] Linear combinations and spans
    - Span of n vectors v<sub>1</sub>, v<sub>2</sub>, ..... , v<sub>n</sub> is a set of all vectors in R<sup>n</sup> that can be represented by a linear combination of the n vectors.
    - span(v<sub>1</sub>, v<sub>2</sub>, ..... , v<sub>n</sub>) = { c<sub>1</sub>v<sub>1</sub> + c<sub>2</sub>v<sub>2</sub> +, ..... , + c<sub>n</sub>v<sub>n</sub> | c<sub>i</sub> belongs to R for 1 <= i <= n }

- [x] Linear dependence and independence
    - A set of vectors are linearly dependent if one of the vector(s) in the set can be represented by some combination of the other vector(s) in the set. Basically, that vector is not adding a new dimension or contributing to the span of the vectors that can represent it.
    - Formally, a set S = {v<sub>1</sub>, v<sub>2</sub>, ..... , v<sub>n</sub>} is linearly dependent if and only if c<sub>1</sub>v<sub>1</sub> + c<sub>2</sub>v<sub>2</sub> + , ..... , + c<sub>n</sub>v<sub>n</sub> = 0, for some c<sub>i</sub>'s where not all of them are zero. Essentially, at least one c<sub>i</sub> is non-zero.
    - Linear independence implies the only solution to c<sub>1</sub>v<sub>1</sub> + c<sub>2</sub>v<sub>2</sub> + , ..... , + c<sub>n</sub>v<sub>n</sub> = 0 is when all c<sub>i</sub>'s are equal to zero.
    - To summarize things in a beautiful manner, if span of n vectors is R<sup>n</sup>, the set of vectors are linearly independent.

- [x] Subspaces and the basis for a subspace
    - For a set of vectors V to be a subspace of R<sup>n</sup>, V should be a subset of R<sup>n</sup> containing the zero vector and must be closed under multiplication (if any vector x in V is multiplied by some real scalar, we are still in the same set V) and closed under addition (for vectors a and b in V, a + b should also be in V).
    - Once again, to put things eloquently, the span of n vector(s) is a subspace of R<sup>n</sup>.
    - A set of vectors S forms the basis of a subspace V if it is linearly independent and spans V. Think of it as the 'minimum' set of vectors whose span makes the subspace V.
    - So if you have a basis for some subspace, any member of the subspace can be uniquely determined by a unique combination of the vectors that form the basis.

- [x] Vector dot and cross products
    - 

- [ ] Matrices for solving systems by elimination

- [ ] Null space and column space