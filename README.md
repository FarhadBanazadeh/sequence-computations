## Sequence Computations 

## Contents  

1. Research Articles
2. Research Chain
3. Author
4. Repository Structure
5. Mathematical Form of the New Map
6. Main Computational Result
7. Reproducibility
8. License

## Research Articles 

This repository contains research articles and computational studies on ternary Collatz-type maps, related integer sequences, and their scaled families.

### A Ternary (4k±1)/3 Collatz-Type Map: Computational Verification up to 10⁹  

This article studies the ternary $(4k\pm1)/3$ Collatz-type map and presents a computational verification up to $10^9$.

Zenodo: [10.5281/zenodo.22195651](https://doi.org/10.5281/zenodo.22195651)

GitHub repository: [Sequence Computations](https://github.com/FarhadBanazadeh/sequence-computations)

### Related Scaled-Family Work  

This work studies the scaled family associated with the ternary $(4k\pm1)/3$ map and the corresponding domains based on powers of $4$.

Zenodo: [10.5281/zenodo.22195652](https://doi.org/10.5281/zenodo.22195652)

### A Ternary (4k±1)/3 Collatz-Type Map and Its (4n±4^r)/3 Scaled Family  

This work gives a general formulation of the scaled family

$(4n\pm4^r)/3$

for $r\geq0$.

Zenodo: [10.5281/zenodo.22228200](https://doi.org/10.5281/zenodo.22228200)

### Ternary (4k+1(2))/3 Collatz-Type Map  

This independent article studies a different ternary Collatz-type map.

For every positive integer not divisible by $3$, the transformation uses either $4k+1$ or $4k+2$ so that the result is divisible by $3$.

The map can be written as

$$
G(n)=\left\lfloor\frac{4n+2}{3}\right\rfloor.
$$

After this step, all factors of $3$ are removed.

The study includes:

* theoretical analysis,
* Haar measure and $3$-adic considerations,
* the distribution of the $3$-adic valuation,
* average multiplicative contraction,
* algebraic analysis of cycles,
* stopping-time analysis,
* numerical examples,
* computational verification up to $10^9$.

Two cycles were found in the complete computation:

$C_1=(1,2)$

and

$C_7=(7,10,14,19,26,35,47)$.

Zenodo: [10.5281/zenodo.22279137](https://doi.org/10.5281/zenodo.22279137)

GitHub repository: [Sequence Computations](https://github.com/FarhadBanazadeh/sequence-computations)

## Research Chain  

The research develops through several related stages:

1. The original ternary $(4k\pm1)/3$ map.
2. The scaled family associated with powers of $4$.
3. The general $(4n\pm4^r)/3$ family.
4. The independent ternary $(4k+1(2))/3$ map.

## Author  

Farhad Banazadeh

ORCID: [0009-0004-7023-0298](https://orcid.org/0009-0004-7023-0298)

Email: [fn.bana@hotmail.com](mailto:fn.bana@hotmail.com)

## Repository Structure 

The repository contains research articles, LaTeX source files, computational programs, data, and supplementary materials.

### Article 1

* [PDF — Ternary (4k±1)/3 Collatz-Type Map](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Ternary_4k_pm_1_over_3_Collatz_Map.pdf)
* [LaTeX Source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Ternary_4k_pm_1_over_3_Collatz_Map.tex)
* [Data and Code ZIP](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Ternary_4k_pm_1_over_3_Collatz_Map_Data_and_Code.zip)
* [Zenodo DOI — 10.5281/zenodo.22195651](https://doi.org/10.5281/zenodo.22195651)

### Article 2

The related scaled-family work is available through its Zenodo record.

* [Zenodo DOI — 10.5281/zenodo.22195652](https://doi.org/10.5281/zenodo.22195652)

### Article 3

* [PDF — Scaled Family](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Banazadeh_Ternary_4k_pm_1_over_3_Scaled_Family.pdf)
* [LaTeX Source — General Family](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Banazadeh_Ternary_4k_pm_1_over_3_Scaled_Family_General.tex)
* [Final ZIP — Scaled Family](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/Banazadeh_Ternary_4k_pm_1_over_3_Scaled_Family_FINAL.zip)
* [Zenodo DOI — 10.5281/zenodo.22228200](https://doi.org/10.5281/zenodo.22228200)

### Article 4

* [PDF — A Ternary (4k+1(2))/3 Collatz-Type Map](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/A_Ternary_4k1_2_over_3_Collatz_Type_Map.pdf)
* [LaTeX Source](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/A_Ternary_4k1_2_over_3_Collatz_Type_Map.tex)
* [Supplementary ZIP — Data, Code, and Supporting Materials](https://github.com/FarhadBanazadeh/sequence-computations/blob/main/A_Ternary_4k1_2_over_3_Collatz_Type_Map_Supplementary.zip)
* [Zenodo DOI — 10.5281/zenodo.22279137](https://doi.org/10.5281/zenodo.22279137)

The supplementary ZIP contains the computational source code, data, and supporting documentation.

## Mathematical Form of the New Map  

The domain is

$$
D=\{n\in\mathbb{N}:3\nmid n\}.
$$

For

$$
n=3p+1,
$$

the transformation before removing factors of $3$ is

$$
G(3p+1)=4p+2.
$$

For

$$
n=3p+2,
$$

the transformation is

$$
G(3p+2)=4p+3.
$$

Equivalently,

$$
G(n)=\left\lfloor\frac{4n+2}{3}\right\rfloor.
$$

Let

$$
v_3(m)=\max\{r\geq0:3^r\mid m\}.
$$

The compressed map is therefore

$$
T(n)=\frac{G(n)}{3^{v_3(G(n))}}.
$$

The computation uses the compressed ternary domain, with the eliminated state $3$ identified with $1$.

## Main Computational Result  

The computation was performed for every admissible starting value satisfying

$$
1\leq n\leq10^9,\qquad 3\nmid n.
$$

The number of admissible starting values is

$$
666,666,667.
$$

Every tested starting value reached one of the two observed cycles.

### Cycle $C_1$  

The first cycle is

$$
C_1=(1,2).
$$

Number of starting values reaching $C_1$:

21,785,111

Percentage:

3.267766648366117%

### Cycle $C_7$  

The second cycle is

$$
C_7=(7,10,14,19,26,35,47).
$$

Number of starting values reaching $C_7$:

644,881,556

Percentage:

96.732233351633880%

### Unknown Or Unresolved Orbits  

Unknown:

0

The two basin counts sum exactly to the total number of admissible starting values.

### Stopping-Time Statistics  

Total number of steps:

42,759,887,447

Mean number of steps:

64.139831138430083

Maximum stopping time:

385

Starting value producing the maximum stopping time:

696,171,200

### Global Peak  

The largest value reached anywhere during the computation was

134,701,251,885,711,310.

The starting value producing this global peak was

920,435,228.

The global peak occurred at step

115.

### Factors of 3 Removed  

Total number of removed factors of $3$:

21,683,837,513

Maximum number of factors of $3$ removed in a single step:

19.

## Reproducibility  

The computational source code and supporting data are included in the supplementary materials.

The main C program can be compiled with:

`cc -O3 -std=c11 ternary_collatz.c -o ternary_collatz`

and executed with:

`./ternary_collatz`

The supplementary ZIP contains the source code, computational data, and supporting documentation used for the study.

## Publication  

The official publication record for the new article is available on Zenodo:

[10.5281/zenodo.22279137](https://doi.org/10.5281/zenodo.22279137)

The article was published on September 3, 2026.

## License  

The research materials are released under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

The Zenodo records provide the official publication versions and persistent DOIs.
