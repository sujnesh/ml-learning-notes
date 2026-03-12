# Chapter 6: The Determinant

## What It Is

The determinant measures **how much a transformation scales area** (in 2D) or **volume** (in 3D).

```
det = 1   →  area unchanged
det = 3   →  area tripled
det = 0.5 →  area halved
det = 0   →  everything squished to a lower dimension (line or point)
```

## Sign = Orientation

- **Positive determinant** → orientation preserved (space not "flipped")
- **Negative determinant** → orientation reversed (like flipping a sheet of paper)

Think of it as: if î is to the right of ĵ before the transformation and still is after, the sign is positive. If they swap sides, it's negative.

## det = 0 Is Special

A zero determinant means the transformation **collapses** a dimension — 2D squished to a line, 3D squished to a plane or line. This means:

- The matrix is **not invertible** (you can't undo the squish)
- Columns are **linearly dependent**

## Formula (2x2)

```
| a  b |
| c  d |  →  det = ad - bc
```
