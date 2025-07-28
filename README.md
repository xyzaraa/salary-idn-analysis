# Indonesian Salary by Region Analysis
## Project Description
This project analyzes salary data across various regions in Indonesia from 1997 to 2022. It aims to understand regional salary disparities, identify top and bottom-performing regions in terms of average salary, and observe overall salary trends and distribution.

## Data Source
The analysis is based on the dataset Indonesian Salary by Region (1997-2022).csv, which contains average salary information for different Indonesian provinces over the specified period.

## Analysis Steps
1. **Data Loading and Initial Inspection**
The dataset was loaded using pandas. Initial checks were performed to understand its structure, data types, and identify any missing or duplicate values.

2. **Data Cleaning**
The 'INDONESIA' entry in the REGION column was removed to focus specifically on provincial-level data.

3. **Regional Average Salary Analysis (1997-2022):**

- Top 5 Regions with Highest Average Salary: Identified and visualized the regions with the highest overall average salaries across the entire 1997-2022 period.

- Top 5 Regions with Fewest Average Salary: Identified and visualized the regions with the lowest overall average salaries across the entire 1997-2022 period.

4. **Overall Average Salary Trend (2000-2022)**
A line plot was generated to visualize how the national average salary has changed year-on-year from 2000 to 2022.

5. **Recent Regional Average Salary (2020-2022)**
The analysis was narrowed down to a more recent period to observe current regional salary conditions. A bar chart was created to display average salaries per region for 2020-2022.

6. **Salary Distribution**
A histogram was generated to show the overall distribution of salary figures across the entire dataset.

## Key Findings
### Long-Term Average Salary (1997-2022):

- Highest: Kalimantan Utara showed the highest average salary over this extended period, followed by Papua Barat and DKI Jakarta. This could be attributed to the significant high-paying natural resource sectors in Kalimantan (e.g., mining, oil & gas) and a relatively smaller population, where substantial cumulative earnings over two decades could elevate the average.

- Lowest: Nusa Tenggara Timur, DI Yogyakarta, Sulawesi Tengah, Nusa Tenggara Barat, and Sulawesi Selatan consistently recorded the lowest average salaries, generally above Rp 100,000.

### Recent Average Salary (2020-2022):

- **Highest:** In the more recent period, DKI Jakarta emerged as the region with the highest average salary, reflecting its status as the capital and primary economic center with higher wage standards and living costs.

### Salary Distribution:
The overall salary distribution is right-skewed, indicating that the majority of salary figures are concentrated at the lower end of the spectrum, with a decreasing frequency as salary levels increase. A small number of high earners contribute to the extended right tail of the distribution.

## Visualizations
The analysis utilizes several types of visualizations to present insights:

- Bar charts for comparing average salaries across regions.

- Line plots for illustrating salary trends over time.

- Histograms for showing the distribution of salary values.

## How to Run
To explore this analysis, you can open the salary-analysis.ipynb Jupyter Notebook in a compatible environment (e.g., Jupyter Lab, Google Colab). Ensure you have the Indonesian Salary by Region (1997-2022).csv file in the same directory as the notebook. The notebook contains executable Python code cells that will reproduce the analysis and visualizations.
