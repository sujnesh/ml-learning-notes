# Chapters 3-4: Linear Transformations and Matrix Multiplication

## Core Insight

A matrix **is** a transformation. Specifically, the columns of a matrix tell you where the basis vectors land after the transformation.

```
| a  b |    →    î lands at [a, c]
| c  d |    →    ĵ lands at [b, d]
```

To transform any vector, you just take the linear combination of these new basis positions:

```
| a  b |   | x |     | ax + by |
| c  d | * | y |  =  | cx + dy |
```

You're saying: "x amount of the new î, plus y amount of the new ĵ."

## Matrix Multiplication = Composition

Multiplying two matrices is applying one transformation after another.

```
M2 * M1 = "first apply M1, then apply M2"
```

Read right to left — same as function composition: f(g(x)).

## Why This Matters

Every matrix operation in ML — weight matrices in neural networks, attention matrices in transformers — is a transformation of the input space. Understanding this geometrically makes everything downstream more intuitive.
