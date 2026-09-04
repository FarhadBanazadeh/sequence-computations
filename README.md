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
- [Repository Structure](#repository-structure)
- [Publication](#publication)
- [License](#license)

---

## Research Articles

This repository contains research articles and computational studies on ternary Collatz-type maps, related integer sequences, and their scaled families.

### 1. A Ternary $(4k \pm 1)/3$ Collatz-Type Map: Computational Verification up to $10^9$
This article studies the ternary $(4k \pm 1)/3$ Collatz-type map and presents a computational verification up to $10^9$.
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

The research develops through several related stages:
1. The original ternary $(4k \pm 1)/3$ map.
2. The scaled family associated with powers of $4$.
3. The general $(4n \pm 4^r)/3$ family for $r \ge 0$.
4. The independent ternary $(4k+1(2))/3$ dynamical map.

---

## Mathematical Formulation of the Map

The domain of admissible starting values is:
$$\mathcal{D} = \{ n \in \mathbb{N} : 3 \nmid n \}$$

For $n = 3k + 1$, the transformation before removing factors of $3$ is:
$$G(3k + 1) = 4k + 2$$

For $n = 3k + 2$, the transformation is:
$$G(3k + 2) = 4k + 3$$

Equivalently:
$$G(n) = \left\lfloor \frac{4n + 2}{3} \right\rfloor$$

Let the $3$-adic valuation be defined as:
$$v_3(m) = \max \{ k \ge 0 : 3^k \mid m \}$$

The compressed map is therefore:
$$T(n) = \frac{G(n)}{3^{v_3(G(n))}}$$

The computation uses the compressed ternary domain, with the eliminated state $3$ identified with $1$.

---

## Main Computational Results ($10^9$)

The computation was performed for every admissible starting value satisfying:
$$1 \le n \le 10^9, \quad 3 \nmid n$$

The number of admissible starting values is exactly **$666{,}666{,}667$**.

Every tested starting value reached one of the two observed cycles:

### Cycle $C_1$
* **Elements:** $C_1 = (1, 2)$
* **Basin Count:** $21{,}785{,}111$
* **Percentage:** $3.267766648366117\%$

### Cycle $C_7$
* **Elements:** $C_7 = (7, 10, 14, 19, 26, 35, 47)$
* **Basin Count:** $644{,}881{,}556$
* **Percentage:** $96.732233351633880\%$

### Basin Summary Table
| Attractor / Cycle | Basin Count | Percentage |
| :--- | :--- | :--- |
| **Cycle $C_1 = (1, 2)$** | $21{,}785{,}111$ | $3.26776665\%$ |
| **Cycle $C_7 = (7, 10, 14, 19, 26, 35, 47)$** | $644{,}881{,}556$ | $96.73223335\%$ |
| **Unknown / Unresolved Orbits** | $0$ | $0.00000000\%$ |
| **Total Verified** | **$666{,}666{,}667$** | **$100.00000000\%$** |

The two basin counts sum exactly to the total number of admissible starting values.

---

## Stopping-Time & Orbit Statistics

* **Total Number of Steps:** $42{,}759{,}887{,}447$
* **Mean Number of Steps:** $\approx 64.139831138430083$
* **Maximum Stopping Time:** $385$ steps
* **Starting Value Producing Maximum Stopping Time:** $n = 696{,}171{,}200$
* **Global Maximum Trajectory Value (Peak):**  
  $$134{,}701{,}251{,}885{,}711{,}310$$  
  *(produced by starting value $n = 920{,}435{,}228$)*
* **Total Factors of $3$ Removed:** $21{,}683{,}837{,}513$

---

## 📂 Repository Contents

This repository provides a complete bundle of research artifacts, source codes, datasets, and documentations:

| Category | File Types | Description |
| :--- | :--- | :--- |
| **Code & Algorithms** | `.py` | Python scripts for sequence computation and verification |
| **Datasets & Outputs** | `.json`, `.zip` | Raw sequence datasets and computational search outputs |
| **Manuscripts & Papers** | `.pdf` | Full-text preprint and compiled research papers |
| **Source Documents** | `.tex` | LaTeX source files for mathematical formulations |
| **Archival Data** | `.zip` | Compressed artifacts and release bundles |


## License
The research materials are released under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

The Zenodo records provide the official publication versions and persistent DOIs.
