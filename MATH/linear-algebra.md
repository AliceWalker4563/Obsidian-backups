# Vectors

A _vector_ can be imagined as an arrow starting from the _origin_ (the point where the axes intersect). Alternatively, it can be defined as a list of numbers that describe the coordinates of where the arrow points.

There are two primary operations with vectors:

- **Vector addition** (or linear combination): Geometrically, we move an arrow (or create a parallel copy) so that its tail starts exactly where the head of the previous arrow ends, and then we draw a new vector from the start of the first arrow to the end of the second. Numerically, this means adding each corresponding pair of coordinates independently.
- **Scalar multiplication**: This involves extending a vector or compressing it. Because a number scales the vector, that number is called a _scalar_.

# Span And Basis

In an $xy$ (or any other) coordinate system, we can choose $\hat{i}$ and $\hat{j}$[^1] vectors (_basis vectors_), with one pointing right and the other pointing up. We can then treat every coordinate as a scalar that stretches or compresses those basis vectors. The resulting vector can be written as a linear combination, for example: $3\hat{i} - 5\hat{j}$.

The _basis_ of a vector space is a set of *linearly independent* vectors that span the full space.

The _span_ of two or more vectors is the set of all their possible linear combinations (every point that can be reached using vector addition and scalar multiplication). In 2D space, the span can be a plane, an infinite line (if the vectors point in the same or opposite directions), or a single point (if both are zero vectors).

A vector is _linearly independent_ if it adds a dimension to the span. If it does not, it is _linearly dependent_ (it lies within the existing span of the other vectors and can be expressed as a linear combination of them).

# Linear Transformations And Matrices

A _transformation_ is a function—an instruction that takes a vector as an input and produces a vector as an output. A transformation is _linear_ if lines remain lines (they stay parallel and evenly spaced without curving) and the origin remains in the same fixed place during the transformation.

To transform any vector in a space, we only need to know where the basis vectors $\hat{i}$ and $\hat{j}$ land. Therefore, any 2D linear transformation can be described completely by just four numbers. This forms a 2x2 _matrix_. The first column contains the coordinates of where $\hat{i}$ lands, and the second column contains the coordinates of where $\hat{j}$ lands.

**A matrix is a linear transformation of space.**

![[Drawing 2026-07-19 13.25.42.excalidraw 1.png]]

[^1]: Pronounced as i-hat and j-hat
