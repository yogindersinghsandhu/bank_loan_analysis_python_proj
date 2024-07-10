# Bank Loan Analysis

## Project Overview

This project aims to analyze a dataset of bank loan applications to uncover meaningful insights and relationships between various variables. By exploring these relationships, we can better understand the factors that influence loan applications and approvals.

## Directory Structure

- `data/`: Contains the dataset used for analysis.
- `analysis/`: Contains the Python scripts used for data analysis.

## Insights

### Positive Correlations

1. **CNT_CHILDREN and CNT_FAM_MEMBERS**: 
   - **Correlation**: 0.89
   - **Insight**: There's a strong positive correlation between the number of children and the number of family members, indicating that larger families typically have more children.

2. **AMT_ANNUITY and AMT_CREDIT**: 
   - **Correlation**: 0.75
   - **Insight**: The correlation between the annuity amount and credit amount suggests that higher loan amounts generally have higher annuity payments.

3. **AGE_IN_YEARS and EMPLOYMENT_YEARS**: 
   - **Correlation**: 0.59
   - **Insight**: Indicates a strong positive relationship between a person's age and their years of employment, which is expected as older individuals have had more time to accumulate work experience.

### Negative Correlations with AGE_IN_YEARS

1. **AGE_IN_YEARS and CNT_CHILDREN**: 
   - **Correlation**: -0.25
   - **Insight**: Suggests that older individuals tend to have fewer dependent children.

2. **AGE_IN_YEARS and CNT_FAM_MEMBERS**: 
   - **Correlation**: -0.2
   - **Insight**: Indicates that older age groups might have smaller family sizes.

### Weak or Insignificant Correlations

- Variables like **AMT_INCOME_TOTAL** show very low correlation with other variables like **AGE_IN_YEARS**, **EMPLOYMENT_YEARS**, and **AMT_CREDIT**, indicating that total income does not significantly affect these aspects within the dataset.

## Usage

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/bank-loan-analysis.git
    cd bank-loan-analysis
    ```

2. **Install Dependencies**:
    Ensure you have the necessary Python packages installed. You can install them using:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Analysis**:
    Navigate to the `analysis` folder and execute the Python script:
    ```bash
    cd analysis
    python analyze.py
    ```

## Conclusion

This correlation matrix is useful for identifying which variables are related and could help in building models to predict payment difficulties or to understand the demographic and financial backgrounds of individuals facing such difficulties. The shades of blue and green in the correlation matrix represent the strength and direction of the correlation, with darker blues indicating stronger positive correlations and darker greens indicating stronger negative correlations.

Feel free to explore the data and scripts to gain deeper insights into the loan application data!

---

For any questions or contributions, please feel free to open an issue or submit a pull request.

**Author**: Yoginder singh sandhu
**Email**: yogindersingh0803@gmail.com
