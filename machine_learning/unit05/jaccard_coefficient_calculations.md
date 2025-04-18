# Jaccard Coefficient Calculations

The table shows the pathological test results for three individuals.

| Name | Gender | Fever | Cough | Test-1 | Test-2 | Test-3 | Test-4 |
|------|--------|-------|-------|--------|--------|--------|--------|
| Jack | M      | Y     | N     | P      | N      | N      | A      |
| Mary | F      | Y     | N     | P      | A      | P      | N      |
| Jim  | M      | Y     | P     | N      | N      | N      | A      |


Converting the asymmetric variables to binary values: 

| Name | Gender | Fever | Cough | Test-1 | Test-2 | Test-3 | Test-4 |
|------|--------|-------|-------|--------|--------|--------|--------|
| Jack | M      |   1   |   0   |   1    |   0    |   0    |   0    |
| Mary | F      |   1   |   0   |   1    |   0    |   1    |   0    |
| Jim  | M      |   1   |   1   |   0    |   0    |   0    |   0    |


#### Jaccard Similarity Formula

The Jaccard Similarity between two sets \( A \) and \( B \) is given by:

$$
Jaccard = \frac{f_{01} + f_{10}}{f_{01} + f_{10} + f_{11}}
$$


### Pair 1: Jack vs Mary

**Feature values for Jack and Mary:**

| Feature  | Jack | Mary |
|----------|------|------|
| Fever    | 1    | 1    |
| Cough    | 0    | 0    |
| Test-1   | 1    | 1    |
| Test-2   | 0    | 0    |
| Test-3   | 0    | 1    |
| Test-4   | 0    | 0    |


**Jaccard coefficient for Jack & Mary:**

$$
Jaccard(Jack, Mary) = \frac{f_{01} + f_{10}}{f_{01} + f_{10} + f_{11}} = \frac{1 + 0}{1 + 0 + 2} = \frac{1}{3} = 0.33
$$

---

### Pair 2: Jack vs Jim

**Feature values for Jack and Jim:**

| Feature  | Jack | Jim  |
|----------|------|------|
| Fever    | 1    | 1    |
| Cough    | 0    | 1    |
| Test-1   | 1    | 0    |
| Test-2   | 0    | 0    |
| Test-3   | 0    | 0    |
| Test-4   | 0    | 0    |


**Jaccard coefficient for Jack & Jim:**

$$
Jaccard(Jack, Jim) = \frac{f_{01} + f_{10}}{f_{01} + f_{10} + f_{11}} = \frac{1 + 1}{1 + 1 + 1} = \frac{2}{3} = 0.67
$$
---

### Pair 3: Jim vs Mary

**Feature values for Jim and Mary:**

| Feature  | Jim  | Mary |
|----------|------|------|
| Fever    | 1    | 1    |
| Cough    | 1    | 0    |
| Test-1   | 0    | 1    |
| Test-2   | 0    | 0    |
| Test-3   | 0    | 1    |
| Test-4   | 0    | 0    |


**Jaccard coefficient for Jim & Mary:**

$$
Jaccard(Jim, Mary) = \frac{f_{01} + f_{10}}{f_{01} + f_{10} + f_{11}} = \frac{2 + 1}{2 + 1 + 1} = \frac{3}{4} = 0.75
$$

---

### Final Results

| Pair         | Jaccard Coefficient |
|--------------|---------------------|
| Jack & Mary  | 0.33                |
| Jack & Jim   | 0.67                |
| Jim & Mary   | 0.75                |

[Back to Machine Learning](/machine_learning/)


<script type="text/javascript" id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>