# Sequence Computations

Code and research documentation for computing integer sequences, dynamical systems, and ternary Collatz-type maps.

---

## Contents
- [Research Articles](#research-articles)
- [Research Chain](#research-chain)
- [Mathematical Formulation of the Map](#mathematical-formulation-of-the-map)
- [Main Computational Results ($10^9$)](#main-computational-results-109)
- [Stopping-Time & Orbit Statistics](#stopping-time--orbit-statistics)
- [Reproducibility & Source Code](#reproducibility--source-code)
- [Author & Contact](#author--contact)
- [License](#license)

---

## Research Articles

This repository contains research articles and computational studies on ternary Collatz-type maps, related integer sequences, and their scaled families.

### 1. A Ternary $(4k \pm 1)/3$ Collatz-Type Map: Computational Verification up to $10^9$
This article studies the ternary $(4k \pm 1)/3$ Collatz-type map and presents computational verification up to $10^9$.
* **Zenodo DOI:** [10.5281/zenodo.22195651](https://doi.org/10.5281/zenodo.22195651)

### 2. Related Scaled-Family Work
This work studies the scaled family associated with the ternary $(4k \pm 1)/3$ map and the corresponding domains based on powers of $4$.
* **Zenodo DOI:** [10.5281/zenodo.22195652](https://doi.org/10.5281/zenodo.22195652)

### 3. A Ternary $(4k \pm 1)/3$ Collatz-Type Map and Its $(4n \pm 4^r)/3$ Scaled Family
This work provides a general formulation of the scaled family:
$$\frac{4n \pm 4^r}{3} \quad \text{for } r \ge 0$$
* **Zenodo DOI:** [10.5281/zenodo.22228200](https://doi.org/10.5281/zenodo.22228200)

### 4. A Ternary $(4k+1(2))/3$ Collatz-Type Map
An independent study on the compressed ternary map defined on integers not divisible by $3$. For every positive integer $n \not\equiv 0 \pmod 3$, the transformation selects $4n+1$ or $4n+2$ such that the result is divisible by $3$, followed by complete removal of factors of $3$.
* **Zenodo DOI:** [10.5281/zenodo.22279137](https://doi.org/10.5281/zenodo.22279137)

---

## Research Chain

The research progresses systematically through four connected stages:
1. The original ternary $(4k \pm 1)/3$ map.
2. The scaled family associated with powers of $4$.
3. The general $(4n \pm 4^r)/3$ family for $r \ge 0$.
4. The independent ternary $(4k+1(2))/3$ dynamical map.

---

## Mathematical Formulation of the Map

Let the domain of admissible starting values be:
$$\mathcal{D} = \{ n \in \mathbb{N} : 3 \nmid n \}$$

The intermediate generator $G(n)$ is defined as:
* For $n = 3k + 1$: $G(3k+1) = 4k + 2$
* For $n = 3k + 2$: $G(3k+2) = 4k + 3$

Equivalently:
$$G(n) = \left\lfloor \frac{4n + 2}{3} \right\rfloor$$

Let $v_3(m) = \max \{ k \ge 0 : 3^k \mid m \}$ denote the standard $3$-adic valuation. The fully compressed Collatz-type map $T: \mathcal{D} \to \mathcal{D}$ is defined by:
$$T(n) = \frac{G(n)}{3^{v_3(G(n))}}$$

---

## Main Computational Results ($10^9$)

Exhaustive verification was conducted for all admissible starting values $n \le 10^9$ ($3 \nmid n$), representing exactly **$666,666,667$** integers.

Every tested starting value enters one of two distinct non-trivial limit cycles:
* **Cycle $C_1$ (Length 2):** $(1, 2)$
* **Cycle $C_7$ (Length 7):** $(7, 10, 14, 19, 26, 35, 47)$

### Basin Partition
| Attractor / Cycle | Basin Count | Percentage |
| :--- | :--- | :--- |
| **Cycle $C_1 = (1, 2)$** | $21,785,111$ | $3.26776665\%$ |
| **Cycle $C_7 = (7, 10, 14, 19, 26, 35, 47)$** | $644,881,556$ | $96.73223335\%$ |
| **Divergent / Unresolved Orbits** | $0$ | $0.00000000\%$ |
| **Total Verified** | **$666,666,667$** | **$100.00000000\%$** |

---

## Stopping-Time & Orbit Statistics

* **Total Steps Computed:** $42,759,887,447$
* **Mean Stopping Time:** $\approx 64.1398$ steps
* **Maximum Stopping Time:** $385$ steps (produced by $n = 696,171,200$)
* **Global Maximum Trajectory Value (Peak):**  
  $$134,701,251,885,711,310$$  
  *(produced by starting value $n = 920,435,228$)*
* **Total Factors of $3$ Removed:** $21,683,837,513$

---

## Reproducibility & Source Code

The computational verification was carried out using standard optimized C routines.

### Compilation:
```bash
cc -O3 -std=c11 ternary_collatz.c -o ternary_collatz


## Publication  

The official publication record for the new article is available on Zenodo:

[10.5281/zenodo.22279137](https://doi.org/10.5281/zenodo.22279137)

The article was published on September 3, 2026.

## License  

The research materials are released under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

The Zenodo records provide the official publication versions and persistent DOIs.
