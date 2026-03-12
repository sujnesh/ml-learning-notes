# Chapter 7: Inverse Matrices, Rank, Column Space, and Null Space

## Rank

The **rank** of a matrix is the number of dimensions in the output after the transformation.

- A 3x3 matrix with **rank 3** → full rank, no dimension lost (3D → 3D)
- A 3x3 matrix with **rank 2** → squished 3D down to a 2D plane
- A 3x3 matrix with **rank 1** → squished everything onto a line

If rank < number of columns → dimensions were lost → determinant is 0.

## Column Space

The **column space** is the set of all possible outputs of the transformation — i.e., the span of the matrix's columns.

- Rank = dimension of the column space

## Null Space (Kernel)

The **null space** is the set of all vectors that land on the origin after the transformation.

- If rank is full → only the zero vector maps to zero (null space = {0})
- If dimensions were lost → a whole line or plane of vectors gets squished to zero

## Inverse Matrices

If a transformation doesn't lose any dimensions (det ≠ 0), you can **reverse** it:

```
A * A⁻¹ = I   (identity matrix — the "do nothing" transformation)
```

If det = 0, no inverse exists — you can't unsquish a pancake back into a cube.
