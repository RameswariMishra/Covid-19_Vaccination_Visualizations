# Covid-19_Vaccination_Visualizations
Effect of COVID-19 Vaccination: A Comparative Data Visualization Study
## Project Overview:

This project presents a comparative data visualization analysis to evaluate the impact of COVID-19 vaccination on infection rates and death rates across three U.S. states: Alabama, Missouri, and New York.

The analysis focuses on pre- and post-vaccination periods, the emergence of new variants, and the effect of booster doses, using publicly available COVID-19 statistics to inform public-health decisions.

The visual evidence demonstrates a clear reduction in COVID-19 death rates and infection severity following widespread vaccination adoption. 

## Objectives:

- Analyze COVID-19 death rates before and after vaccination rollout

- Compare infection trends across states with varying vaccination coverage

- Evaluate the impact of booster doses during new variant waves

- Communicate insights through clear, policy-friendly visualizations

## Analytical Approach

### Data Collection
- Public COVID-19 datasets aggregated by state and time period

- Vaccination rates, infection counts, and death counts
### Data Processing
- Monthly aggregation of cases and deaths

- Normalization by population (rates per 100K where applicable)

- Time-based segmentation (pre-vaccination, post-vaccination, booster phase)
### Visualization Strategy
- Line charts showing monthly trends

- Side-by-side state comparisons

- Annotated vaccination milestones and variant periods

## Key Insights & Findings

- Significant decline in COVID-19 death rates observed after vaccination rollout in 2021 across all three states

- States with higher vaccination coverage (e.g., New York) showed lower and more stable death rates

- Despite the emergence of Omicron and new variants, booster doses contributed to controlling mortality trends in 2022

- Infection rates dropped from ~4000 to under 500 cases per 100K population after vaccination expansion 

## Tools & Technologies

- Python

- Pandas & NumPy – data manipulation

- Matplotlib & Seaborn – visualization

- Jupyter Notebook – exploratory analysis

- PDF Infographics – public-facing insights
  
## 📁 Repository Structure

covid-vaccination-visualization/
├── notebooks/ # Jupyter notebooks for analysis and visualization
├── reports/ # Summary reports and infographics
├── README.md
├── requirements.txt
└── .gitignore

## 🚀 How to Run the Project

### 1. Clone the repository
   git clone https://github.com/your-username/covid-vaccination-visualization.git

### 2. Install dependencies
   pip install -r requirements.txt

### 3. Launch Jupyter Notebook. Open the file and run
  jupyter notebook
  notebooks/Effect_of_COVID_19_Vaccination_Data_Visualization.ipynb

## 📌 Impact & Relevance

- Supports **data-driven public health communication** by translating complex COVID-19 trends into clear, accessible visual insights.
- Designed as a **social awareness and decision-support analysis**, helping individuals and communities understand the real-world impact of vaccination and booster programs.
- Demonstrates **policy-relevant data visualization skills**, suitable for informing public health discussions and evidence-based decision-making.
- Highlights the **importance of vaccination and booster adoption** through comparative, state-level analysis.
- Well-suited for **healthcare analytics, epidemiology, and data visualization portfolios**.
  
## ⚠️ Limitations & Future Work

### Limitations
- The analysis relies on **aggregated, state-level public health data**, which limits the ability to capture individual-level vaccination outcomes.
- Individual vaccination records (e.g., age, comorbidities, exact vaccination status per person) were **not available due to privacy and data access constraints**.
- Potential confounding factors such as healthcare access, socioeconomic conditions, testing availability, and reporting delays were not explicitly modeled.
- Observational trends indicate associations rather than direct causal relationships between vaccination and outcomes.

### Future Improvements
- Incorporate **individual-level or stratified vaccination datasets** (where ethically and legally permissible), such as age-group or risk-category vaccination data.
- Integrate additional public datasets, including:
  - **CDC vaccination coverage by demographic group**
  - **Hospitalization and ICU admission rates**
  - **County-level socioeconomic indicators (income, rural vs urban)**
- Apply **statistical modeling or causal inference techniques** to better quantify the impact of vaccination and booster doses.
- Extend the visualization into **interactive dashboards** (e.g., Plotly or Power BI) for enhanced public engagement and policymaker use.
- Expand the analysis to include **additional states or international comparisons** for broader generalizability.
