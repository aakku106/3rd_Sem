# NM Final Preparation (Pass First, Then 30+)

## 1) Scope Used for This Plan

This plan is based only on the files you provided:

- syllabus.md
- 2075.md
- 2077.md
- 2078.md
- 2079.md
- 2080.md
- 2081.md
- modelset1.md
- modelSet2.md

Note: 2076 paper is not present in the folder, so this analysis uses the available 8 question sets (6 yearly papers + 2 model sets).

## 2) Objective and Exam Math

- Board theory full marks: 60
- Pass marks: 24
- Your safety target: 30
- Pattern in papers: Group A (attempt any 2, typically 10 marks each), Group B (attempt any 8, typically 5 marks each)

### Practical target for 30

- Group A target: 12 to 14 marks out of 20
- Group B target: 16 to 20 marks out of 40
- Total target: 28 to 34 (safe around 30)

This means you do not need full syllabus mastery first. You need reliable execution in repeated question types.

## 3) Most Repeated Topics (from 8 sets)

### Tier 1: Must Cover First (highest return)

1. Nonlinear equation root methods (Secant, Newton-Raphson, Bisection, Fixed Point, False Position)

- Appears in all 8 sets in either Group A or Group B.

1. Interpolation family (Lagrange, Newton forward/backward/divided, spline)

- Appears in almost every set as direct numerical problem or algorithm/program question.

1. Numerical integration (Simpson 1/3, Simpson 3/8, Trapezoidal, Romberg, Gaussian)

- Appears in all 8 sets.

1. ODE numerical methods (Euler, Heun, RK4, Taylor, shooting)

- Appears in all 8 sets.

1. PDE / Poisson / steady-state plate finite difference

- Appears in all 8 sets.

### Tier 2: Strongly Repeated (next priority)

1. Linear systems: Gauss elimination, Gauss-Jordan, pivoting, inverse by Gauss-Jordan

- Appears in most sets, often in Group A long question.

1. Regression / least squares curve fitting

- Appears in all 8 sets in short problems.

### Tier 3: If Time Remains

1. Matrix factorization (LU, Doolittle, Crout, Cholesky), eigenvalue/eigenvector
2. Numerical differentiation (three-point, tabulated differentiation)
3. Theory-only distinctions (ODE vs PDE, interpolation vs regression, direct vs iterative methods)

## 4) Exact Repeating Question Types You Should Practice

## A) Root finding (high confidence repeat)

Practice these first:

- 2075 Group A Q1 (Secant derivation + solve)
- 2077 Group A Q1 (Newton-Raphson derivation + solve)
- 2079 Group A Q1 (Secant method)
- 2080 Group A Q1 (Secant vs Newton-Raphson + solve)
- 2081 Group A Q1 (Newton-Raphson + solve)
- modelset1 Group A Q1 (Newton-Raphson)
- 2078 Group B Q4 (Half-interval/Bisection)
- 2078 Group B Q5 (Fixed-point)
- 2079 Group B Q4 (Bisection)
- 2079 Group B Q5 (Fixed-point)
- 2080 Group B Q4 (Half-interval theory)
- modelset1 Group B Q12 (False-position)
- modelSet2 Group B Q12 (Bisection)

## B) Interpolation and tables

- 2077 Group A Q2 (Lagrange algorithm/program)
- 2080 Group A Q2 (Newton divided difference algorithm/program)
- 2081 Group A Q3 (Lagrange algorithm/program)
- modelset1 Group A Q2 (Lagrange)
- modelSet2 Group A Q2 (Lagrange polynomial + estimate)
- 2077 Group B Q5 (Newton forward table)
- 2080 Group B Q5 (Newton backward table)
- 2081 Group B Q4 (Newton interpolation estimate)
- modelset1 Group B Q4 (forward table)
- modelSet2 Group B Q5 (divided difference missing term)
- 2079 Group A Q2 and 2081 Group B Q9 (cubic spline)

## C) Numerical integration

- 2075 Group B Q8 (Simpson 1/3)
- 2079 Group B Q8 (Simpson 1/3)
- 2081 Group B Q7 (Simpson 3/8)
- modelSet2 Group B Q10 (Simpson 3/8 tabulated)
- 2080 Group B Q9 (composite trapezoidal)
- 2075 Group B Q9, 2078 Group B Q9, modelset1 Group B Q11, modelSet2 Group B Q9 (Romberg)
- 2079 Group B Q9 (Gaussian integration)

## D) Linear systems and matrix methods

- 2077 Group A Q3 (Gaussian elimination + pivoting + comparison)
- 2079 Group A Q3 (pivoting + Gaussian elimination algorithm/program)
- 2080 Group A Q3 (Gauss-Jordan + inverse)
- modelSet2 Section A Q1 (Gauss elimination vs Gauss-Jordan + solve)
- 2081 Group A Q2 (Jacobi vs Gauss-Seidel + solve)
- 2079 Group B Q10 and 2075 Group B Q10 (Gauss-Seidel solve)
- 2081 Group B Q8 (Gauss-Jordan solve)

## E) ODE methods

- 2077 Group B Q10, modelSet2 Section A Q3, modelset1 Group B Q6 (Euler)
- 2079 Group B Q6 and 2080 Group B Q12 and modelSet2 Group B Q4 (Heun algorithm/program)
- 2079 Group B Q11, 2081 Group B Q11, 2075 Group B Q11 (RK4)
- 2080 Group B Q10 (Taylor method)
- 2075 Group A Q3, 2077 Group B Q12, modelset1 Group B Q10 (shooting)

## F) PDE / Poisson / plate

- 2075 Group B Q12
- 2079 Group B Q12
- 2080 Group B Q11
- 2081 Group B Q12
- modelSet2 Group B Q11
- 2077 Group B Q11 and modelset1 Group B Q7 and 2078 Group B Q12 (plate temperature finite difference form)

## 5) Pass-First 4-Day Plan (30 target)

Assumption: around 8 to 10 focused study hours per day.

## Day 1: Root finding + Interpolation basics + one long-question method

Goal: Secure Group A confidence and one reliable Group B block.

1. Root finding core (4 hours)

- Practice: Newton-Raphson, Secant, Bisection
- Drill from: 2081 A1, 2080 A1, 2079 B4, modelSet2 B12
- Output: solve at least 5 full roots with stopping criteria and iteration table format.

1. Interpolation core (3 hours)

- Lagrange direct formula and Newton divided differences
- Drill from: modelSet2 A2, 2081 A3, 2080 A2, modelSet2 B5
- Output: one-page formula sheet + one complete solved table.

1. Group A long answer writing practice (2 hours)

- Write one full 10-mark solution for root method derivation and one for interpolation algorithm.

## Day 2: Linear systems + Regression + matrix factorization

Goal: Build another Group A option and 1 to 2 short-answer options.

1. Linear systems (4 hours)

- Gauss elimination with pivoting and Gauss-Jordan procedure
- Drill from: 2077 A3, 2080 A3, 2081 B8, modelSet2 A1
- Output: clean elimination workflow with row operation notation.

1. Iterative methods (1.5 hours)

- Jacobi and Gauss-Seidel iteration rules and convergence check
- Drill from: 2081 A2, 2079 B10

1. Regression and least squares (2.5 hours)

- Linear and quadratic fitting normal equations
- Drill from: 2081 B5, 2080 B6, modelSet2 B6

1. Matrix factorization quick coverage (1.5 to 2 hours)

- LU/Doolittle/Cholesky pattern
- Drill from: 2075 A2, 2080 B7, modelSet2 B8

## Day 3: Integration + ODE methods

Goal: Maximize Group B scoring reliability.

1. Numerical integration (4 hours)

- Simpson 1/3 and 3/8 (including composite), Trapezoidal, Romberg
- Drill from: 2079 B8, 2081 B7, modelSet2 B10, 2080 B9, modelSet2 B9

1. ODE methods (4 hours)

- Euler, Heun, RK4, Taylor method format
- Drill from: 2077 B10, 2079 B6, 2081 B11, 2080 B10, modelSet2 B4

1. One timed mini test (1.5 hours)

- 1 integration + 1 ODE + 1 regression (simulate Group B speed)

## Day 4: PDE + Revision + Full strategy execution

Goal: Lock pass marks and push to 30+.

1. PDE finite difference (3 hours)

- Poisson/plate setup, boundary handling, interior node equation solving
- Drill from: 2081 B12, 2080 B11, modelSet2 B11, 2077 B11

1. High-frequency revision (3 hours)

- Root finding, interpolation, Gauss-Jordan, Simpson, RK4 quick rerun.

1. Full paper simulation (3 hours)

- Pick 2 Group A and 8 Group B from mixed past papers under time limit.
- Check only method errors and arithmetic slips.

1. Final 60-minute formula and template revision

- Keep one short sheet for each: root methods, interpolation, integration, linear systems, ODE, PDE.

## 6) Pass-Mark Safe Attempt Strategy in Exam Hall

1. Group A selection rule

- Choose the 2 questions from:
  - Root finding derivation/solve
  - Interpolation algorithm/program
  - Gauss elimination/Gauss-Jordan solve

1. Group B selection rule

- First answer the 5 topics you practiced deeply:
  - integration
  - ODE
  - regression
  - interpolation table question
  - Poisson/plate
- Then complete remaining required answers with partial-credit structure: formula, substitution, 1-2 iterations, final expression.

1. Time control (3 hours)

- First 70 minutes: both Group A answers
- Next 100 minutes: 8 Group B answers
- Final 10 minutes: check sign errors, copied values, boundary conditions

## 7) Non-Negotiable Practice Set for 4 Days

If you can solve only a limited set, do these first (highest utility):

- 2081 Group A Q1
- 2080 Group A Q3
- 2081 Group A Q3
- 2079 Group B Q8
- modelSet2 Group B Q10
- modelSet2 Group B Q9
- 2081 Group B Q11
- 2079 Group B Q6
- 2081 Group B Q12
- 2079 Group B Q10
- 2081 Group B Q5
- modelSet2 Group B Q6

## 8) Minimum Formula Checklist (must memorize)

1. Newton-Raphson update formula
2. Secant update formula
3. Bisection stopping criterion and sign test
4. Lagrange interpolation polynomial form
5. Newton divided difference recursive formula
6. Simpson 1/3 and 3/8 composite formulas
7. Trapezoidal composite formula
8. Romberg table relation
9. Euler, Heun predictor-corrector, RK4 k1-k4 scheme
10. Finite difference form for Poisson equation interior node
11. Normal equations for linear/quadratic least squares
12. Gauss-Jordan row-operation end condition

## 9) If Time Is Left After Pass-Level Readiness

Use remaining time for score boost:

- eigenvalue by power method (modelSet2 B7)
- Cholesky/Crout derivation depth
- cubic spline full derivation (2081 B9, 2079 A2)
- numerical differentiation question type (2081 B6, 2077 B8, 2080 B8)

This sequence improves chances of crossing 30 while still protecting pass marks first.
