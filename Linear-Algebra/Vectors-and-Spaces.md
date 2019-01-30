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
    - Dot product of the vector with itself gives us its "Length". Dot product property is associative, commutative and distributive.
    - Cauchy-Schwarz inequality: The absolute value of the dot product of two non-zero vectors belonging to R<sup>n</sup> is less than or equal to the product of the two vectors length. The only time the inequality turns into an equality is when one of the vectors is a scalar multiple of the other.
    - Vector triangle inequality: The length of the sum of two vectors is less than the sum of lengths of the two vectors. If the two vectors are collinear (scalar multiple), the inequality turns into an equality.
    - Law of cosines (Broader Pythagoran theorem): For three sides of a triangle, A, B, C, and an angle theta between A and B, C<sup>2</sup> = A<sup>2</sup> + B<sup>2</sup> - 2ABcos(theta).
    - Relationship between dot product and cosine of the angle between two vectors. Notion of orthogonality for zero vector.
    - Equation of a plane in R<sup>3</sup>: Ax + By + Cz = D. A plane in R<sup>3</sup> can also be defined with a point and normal vecor.
    - Dot product gives you a scalar and can be defined in R<sup>n</sup> but cross product gives a vector and is only defined in R<sup>3</sup>.
    - Cross product of two vectors results in a vector orthogonal to the two vectors. Right hand rule can be used to determine the direction of the resulting vector. Relationship between cross product and sin of the angle between the two vectors.
    - Finding the distance of a point to a plane and the distance between two planes.

- [ ] Matrices for solving systems by elimination

- [ ] Null space and column space