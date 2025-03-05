# Air-Pollution-and-Public-Health-Analysis
**Yoatam Gebremicael**

This project investigates the relationship between air pollution and public health using data from the World Bank's WDI dataset. The objective is to analyze air quality trends, assess pollution-related mortality rates, and evaluate the effectiveness of environmental policies in mitigating health risks.

## Research Questions

### Main Questions:
1. Are air pollution levels improving or worsening over time across different regions?
2. How does air pollution impact public health, particularly mortality rates?
3. Are government policies effective in reducing air pollution and its health effects?

### Sub-questions:
- What are the long-term trends in air quality indicators across different countries?
- Is there a statistically significant correlation between air pollution and mortality rates?
- Have policy interventions led to measurable improvements in air quality and public health outcomes?

## Dataset
- **Dataset Source:** World Bank (WDI)
- **Files Used:** `WDIData.csv`, `WDISeries.csv`
- **Data Cleaning:** Removed missing values, standardized air pollution indicators
- **Key Variables:** Air pollution levels (PM2.5, CO2 emissions), mortality rates, policy measures

## Methods
1. **Data Cleaning and Preprocessing:**
   - Handled missing values and standardized air quality indicators.
   - Merged datasets to align pollution data with health outcomes.
   
2. **Exploratory Data Analysis (EDA):**
   - Visualized trends in air pollution levels across different regions.
   - Examined variations in pollution-related mortality rates over time.
   
3. **Statistical Analysis and Modeling:**
   - Performed correlation analysis to assess the relationship between pollution and health outcomes.
   - Applied regression modeling to evaluate policy effectiveness.

## Main Results
- **Trends in Air Pollution:** Some regions show declining air pollution levels, while others still face worsening conditions.
- **Health Impact:** Higher air pollution levels correlate with increased mortality rates, indicating a strong public health risk.
- **Policy Effectiveness:** Some environmental policies have led to measurable improvements in air quality and reduced health risks.

## Conclusion
The study highlights the urgent need for effective air pollution control policies to mitigate its health impacts. While some regions have made progress, others continue to face significant environmental and public health challenges.

## Limitations
- **Data Availability:** Some countries lack comprehensive pollution and health data.
- **Causality:** Correlation does not imply causation; other factors may influence mortality rates.
- **Policy Impact:** The effectiveness of specific policies requires further in-depth study.

## How to Replicate
### Prerequisites
- Python 3.x
- Required Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`

### Steps to Run the Analysis
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/air-pollution-analysis.git
   cd air-pollution-analysis
   ```
2. Install dependencies:
   ```sh
   pip install pandas numpy matplotlib seaborn statsmodels
   ```
3. Run the Jupyter Notebook to reproduce the analysis.

