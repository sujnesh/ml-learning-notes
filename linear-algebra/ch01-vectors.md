# Chapter 1: Vectors — What Even Are They?

## What is a Vector?

A vector is an arrow in space defined by its **direction** and **magnitude** (length). In linear algebra, we almost always root vectors at the **origin** (0, 0).

A vector is described by its **coordinates** — an ordered list of numbers that tells you how far to move along each axis.

```
v = [3, 2]  →  move 3 along x-axis, 2 along y-axis
```

In 2D, a vector has 2 components. In 3D, it has 3. In general, a vector in n-dimensional space has n components.

## Vector Addition

To add two vectors, add their corresponding components:

```
[a1, a2] + [b1, b2] = [a1 + b1, a2 + b2]
```

**Geometrically**: place the tail of the second vector at the tip of the first. The result points from the origin to the new tip.

```
[1, 2] + [3, -1] = [4, 1]
```

## Scalar Multiplication

Multiply each component of a vector by a number (called a **scalar**):

```
c * [a1, a2] = [c * a1, c * a2]
```

- **c > 1** → stretches the vector (longer)
- **0 < c < 1** → shrinks the vector (shorter)
- **c < 0** → flips the direction and scales

```
3 * [2, 1] = [6, 3]      # stretched
-1 * [2, 1] = [-2, -1]   # flipped
```

This process of scaling is why numbers in this context are called **scalars** — they scale vectors.

## Key Takeaway

Vectors are the fundamental building blocks of linear algebra. Everything that follows — transformations, matrices, eigenvalues — is built on operations over vectors.
