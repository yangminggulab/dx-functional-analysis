## Overall Roadmap

Following MIT OpenCourseWare functional analysis, the main line includes normed spaces, completeness, linear functionals, the Hahn-Banach theorem, duality, operators, Lebesgue measure, Lp spaces, and Hilbert spaces. This repository currently focuses on metric spaces, normed spaces, and bounded linear operators.

```text
Functional Analysis = doing linear algebra and analysis in infinite-dimensional spaces
|
+-- The central problems
|   +-- How can functions be treated as points in a space?
|   |   +-- Use metrics, norms, and completeness to make function sets analyzable.
|   +-- How can limits be controlled in infinite-dimensional spaces?
|   |   +-- Use Banach spaces, contraction mappings, and compactness.
|   +-- How can linear transformations acting on functions be studied?
|       +-- Use bounded linear operators, linear functionals, dual spaces, and core theorems.
|
+-- Tool 1: metric spaces -> clarify distance and limits first
|   +-- Basic spaces and point-set language introduce neighborhoods, open/closed sets, closure
|   +-- Complete metric spaces make Cauchy sequences converge
|   +-- Contraction mapping principle proves existence and uniqueness by iteration
|   +-- Topological-space supplements generalize metric intuition
|
+-- Tool 2: normed linear spaces -> linear structure plus size
|   +-- Norms and linear spaces preserve addition, scalar multiplication, and length
|   +-- Convex sets prepare separation ideas such as Hahn-Banach
|   +-- Lp spaces organize functions by integrability
|   +-- Finite-dimensional normed spaces contrast finite and infinite dimensions
|
+-- Tool 3: bounded linear operators -> matrices in infinite dimensions
    +-- Bounded operators and functionals decide whether linear maps are continuous and controlled
    +-- Banach-Steinhaus theorem moves from pointwise boundedness to uniform control
    +-- Open mapping and closed graph theorems describe stability of linear operators
    +-- Hahn-Banach theorem extends functionals and opens the door to duality
```

# dx's Functional Analysis

## Preface

Functional analysis can feel as if it is floating higher and higher above the ground. Spaces, operators, functionals, weak convergence, dual spaces, and reflexivity can look abstract enough that definitions are readable while the subject still feels hard to hold.

The central goal of this book is to keep abstraction from floating away. Functional analysis reorganizes distance, norms, completeness, compactness, continuity, limits, function spaces, and linear structure into a larger framework.

## Why This Book Is Written This Way

If functional analysis is written only as a chain of increasingly abstract definitions, it loses its center. This book tries to attach each concept to the problem it solves.

Completeness guarantees limits. Contraction mappings produce fixed points. Boundedness is the right form of continuity for linear maps. Metric spaces, normed spaces, and topological spaces form a hierarchy rather than a pile of terms.

## What This Book Keeps

The first chapter starts with metric spaces, completeness, contraction mappings, and topological spaces. The second chapter develops normed linear spaces, convex sets, and Lp spaces. The third chapter studies bounded linear operators, Banach-Steinhaus, open mapping, closed graph, Hahn-Banach, reflexivity, and weak convergence.

The line of growth is upward: from distance, to linear space, to operators, to duality and weaker structures.

## Intended Readers

This book is for readers who feel that functional analysis is cloudy but suspect that there is a skeleton inside. It tries to separate objects, relations, and theorems so the structure can be seen.

## Repository Notes

- The main entry is `main.tex`.
- The chapter files cover metric spaces, normed linear spaces, and bounded linear operators.
- Exercises and supplementary materials are kept separately.
- For local compilation, running `xelatex main.tex` twice is usually enough.
