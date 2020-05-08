# Statistical Hypothesis

## Hypothesis Testing (Two Samples)

* **Notations**

  ![Notations](images/Notations.png)

* **To test**
  * H₀: μ₁ = μ₂ H₁: μ₁ ≠ μ₂
  * H₀: μ₁ = μ₂ H₁: μ₁ > μ₂
  * H₀: μ₁ = μ₂ H₁: μ₁ < μ₂

## Testing Strategy

  ![Testing Strategy 2](images/TestingStrategy2.png)

### Method 1

* Check assumptions from above Strategy table.
* Use N(0,1) to obtain critical value/ p-value.

### Method 2

* Check assumptions from above Strategy table.
* Use N(0,1) to obtain critical value/ p-value.

### Method 3 (t test for two independent samples assuming equal variances)

* **Assumptions**
  * σ₁ and σ₂ both  are unknown
  * Both populations are normal
  * sample sizes n₁ and n₂ are small
  * Unknown σ₁ and σ₂ are assumed to be equal

* **Test Statistic**

  ![Test Stat 5](images/TestStat5.png)

* Use t(n₁+n₂-2) distribution for critical value/ p-value.

## Method 4 (t test for two independent samples assuming unequal variances)

* **Assumptions**
  * σ₁ and σ₂ both  are unknown
  * Both populations are normal
  * sample sizes n₁ and n₂ are small
  * Unknown σ₁ and σ₂ are assumed to be unequal

* **Test Statistic**

  ![Test Stat 6](images/TestStat6.png)

* Use t(f) distribution for critical value/ p-value.

  ![F Value](images/fValue.png)

## Method 5 (paired)

* **Assumptions**
  * Observations are paired
  * Both populations are normal

* **Test Statistic**

  ![Test Stat 7](images/TestStat7.png)

* Use t(n-1) distribution for critical value/ p-value.

## Hypothesis Testing for Differences of Variances

* **Notations**

  ![Notations2](images/Notations2.png)

* **To test**
  * H₀: σ₁² = σ₂²   H₁: σ₁² ≠  σ₂²
  * H₀: σ₁² = σ₂²   H₁: σ₁² > σ₂²
  * H₀: σ₁² = σ₂²   H₁: σ₁² < σ₂²

* **Assumptions**
  * Both populations are normal

* **Test Statistic**

  ![Test Stat 8](images/TestStat8.png)

* For critical values, use Snedecor’s F distribution with degree of freedom (n1−1,n2−1).

### Two Tail Test

  ![Two Tail Variance](images/TwoTailVar.png)

### Right Tail Test

  ![Right Tail Variance](images/RightTailVar.png)

### Left Tail Test

  ![Left Tail Variance](images/LeftTailVar.png)

* The F critical value is found from the F table
* There are two appropriate degrees of freedom: numerator and denominator.
* In the F table,
  * numerator degrees of freedom determine the column (denoted as n₁  or ν1 usually)
  * denominator degrees of freedom determine the row (denoted as n₂  or ν2 usually)
* Also, note that:

  ![F Value Alpha](images/FValueAlpha.png)

## Hypothesis Testing for Differences of Proportions

* **Notations**

  ![Notations 3](images/Notations3.png)

* **To test**
  * H₀: π₁  = π₂ H₁: π₁ ≠ π₂
  * H₀: π₁ = π₂ H₁: π₁ > π₂
  * H₀: π₁ = π₂ H₁: π₁ < π₂

* **Assumptions**
  * Large samples (n₁, n₂ ≥ 30)

* **Test Statistic**

  ![Test Stat 9](images/TestStat9.png)

* Use N(0,1) to obtain critical value/ p-value.
* In most of the problems, 𝝅 is not known, so we use the estimate of 𝝅, given by :

  ![Pi Estimate](images/piestimate.png)

## Summary of Testing Strategies

  ![Test Summary](images/TestSummary.png)

  ![Test Summary2](images/TestSummary2.png)
