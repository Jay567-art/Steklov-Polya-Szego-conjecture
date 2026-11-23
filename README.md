# Steklov Polygon Inequalities

We prove the **polygonal Weinstock-type conjecture** for every integer $N\ge3$. Among all simple planar polygons of positive area with at most $N$ sides and a given perimeter, the regular $N$-gon uniquely maximizes the first positive Steklov eigenvalue, up to congruence.

Write $P(\Omega)$ for the perimeter of $\Omega$, let $\sigma_1(\Omega)$ be its first positive Steklov eigenvalue, and set $J(\Omega)=P(\Omega)\,\sigma_1(\Omega)$. If $R_N$ is a regular $N$-gon, the scale-invariant form of the theorem is

$$
J(\Omega)\le J(R_N),
$$

with equality precisely when $\Omega$ is similar to $R_N$. The theorem covers convex and nonconvex polygons. Each maximal straight segment of the boundary counts as one side.

## Papers

### Triangles ($N=3$)

**The Sharp Steklov Inequality for Triangles and Its Linear Stability**  
Zhuo Cheng and Yi'an Zhang

The equilateral triangle $E$ is the unique maximizer up to similarity. The length $\ell_{\max}(T)$ of the longest side also controls how far any triangle $T$ falls below the maximum. For universal constants $c,C>0$,

$$
c\,d(T)\le 1-\frac{J(T)}{J(E)}\le C\,d(T),
\qquad d(T)=\frac{3\ell_{\max}(T)}{P(T)}-1.
$$

The proof transplants a first eigenfunction of $E$ by an affine map that sends one edge to a longest side of $T$.

[PDF](N3_Triangle.pdf) · [LaTeX source](N3_Triangle.tex)

### Quadrilaterals ($N=4$)

**A Sharp Steklov Inequality for Quadrilaterals by Interpolation Along a Diagonal**  
Zhuo Cheng and Yi'an Zhang

The square alone attains the sharp value $8\tau\tanh\tau$, where $\tau\in(0,\pi/2)$ solves $\tan\tau\,\tanh\tau=1$. Every concave quadrilateral satisfies the stricter bound $J(Q)<3\sqrt{3}$. For convex quadrilaterals near the square, interpolation along a diagonal gives a lower bound on the deficit that is linear in the affine distortion of the associated parallelogram and quadratic in the distance between the diagonal midpoints.

[PDF](N4_Quadrilateral.pdf) · [LaTeX source](N4_Quadrilateral.tex)

### N≥5.**polygonal Weinstock-type conjecture**

Theorem 6.1 proves the inequality and its equality case for every $N\ge5$. For pentagons, the proof gives sharp quadratic stability in the convex case and a uniform gap below the regular pentagon in the nonconvex case. For $N\ge6$, trial functions on a fan of triangles handle the convex case, while a bound in terms of the number of strictly convex corners handles the nonconvex case. The proof uses finite rational and integer certificates.

[Combined paper (PDF)](N%E2%89%A55.polygonal%20Weinstock-type%20conjecture.pdf)

## Version history

The commit history records revisions to each paper.
