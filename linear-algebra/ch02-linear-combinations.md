# Chapter 2: Linear Combinations, Span, and Basis Vectors

## Basis Vectors

The two default basis vectors in 2D are:

```
î = [1, 0]   (unit vector along x-axis)
ĵ = [0, 1]   (unit vector along y-axis)
```

Every 2D vector is just a **linear combination** of these two:

```
[3, 2] = 3î + 2ĵ = 3[1, 0] + 2[0, 1]
```

## Linear Combination

A linear combination is scaling vectors and adding them together:

```
a * v + b * w
```

where `a` and `b` are scalars, and `v` and `w` are vectors.

## Span

The **span** of a set of vectors is the set of all points reachable by their linear combinations.

- Span of one vector → a **line**
- Span of two non-parallel vectors → the entire **2D plane**
- If two vectors are parallel (linearly dependent), their span collapses to a line

## Linear Dependence

Vectors are **linearly dependent** if one can be expressed as a combination of the others (i.e., it adds no new dimension to the span).

Vectors are **linearly independent** if each one adds a new direction to the span.
