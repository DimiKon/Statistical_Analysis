# Statistical Tests and Data Analysis

The notebook explores quantitative data analysis with Python, focusing on statistical tests and visualizations. It covers data preparation, exploratory analysis, and various statistical techniques.
---

## Libraries Used

The following Python libraries are utilized:
- **`pandas`**: For data manipulation and analysis.
- **`matplotlib`** and **`seaborn`**: For data visualization.
- **`numpy`**: For numerical computations.
- **`scipy`**: For statistical tests.
- **`statsmodels`**: For advanced statistical modeling.

---

## Dataset Description

The dataset contains the following columns:
- **`groupid`**: Identifies the group each observation belongs to.
- **`er1`, `er2`, `er3`**: Numerical variables for analysis.
- **`score`**: A summary score for each observation.

### Example Dataset Structure
```python
data = {
    'groupid': [1, 2, 3, ...],
    'er1': [7, 30, 36, ...],
    'er2': [4, 26, 4, ...],
    'er3': [27, 24, 27, ...],
    'score': [144.6, 33.2, 86.6, ...]
}
df = pd.DataFrame(data)

---

## Statistical Tests

The following tests are conducted:

- **Bartlett's Test**: Checks homogeneity of variances across groups.
- **ANOVA**: Analyzes differences in means across multiple groups.
- **Normality Tests**: Verifies if data follows a normal distribution using methods like Shapiro-Wilk or Kolmogorov-Smirnov.


