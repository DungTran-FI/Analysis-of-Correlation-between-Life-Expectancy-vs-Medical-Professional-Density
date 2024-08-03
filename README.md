# Unveiling the Correlation: Does Having Many Healthcare Providers Really Extend Life Expectancy?

## The complete analysis and all related work are documented in the following files:
  - [Analysis of Correlation between Life Expectancy vs Medical Professional Density.ipynb](https://github.com/DungTran-FI/Analysis-of-Correlation-between-Life-Expectancy-vs-Medical-Professional-Density/blob/main/Analysis%20of%20Correlation%20between%20Life%20Expectancy%20vs%20Medical%20Professional%20Density.ipynb)
  - [Presentation - Life Expectancy vs Medical Professional Density.pptx]([path/to/Presentation_-_Life_Expectancy_vs_Medical_Professional_Density.pptx](https://github.com/DungTran-FI/Analysis-of-Correlation-between-Life-Expectancy-vs-Medical-Professional-Density/blob/main/Presentation%20-%20Life%20Expectancy%20vs%20Medical%20Professional%20Density.pptx))

## <u>1. Introduction</u>

### <u>Background</u>

**Healthcare accessibility and quality** are crucial in enhancing the **well-being** and **longevity** of populations. Existing research underscores the pivotal role of **healthcare providers**—such as **medical doctors** and **pharmacists**—in delivering timely and effective care. However, the direct correlation between the **density** of these providers and **life expectancy** is an area still ripe for exploration.

This project leverages data from the **World Health Statistics 2020**, covering healthcare provider distribution and life expectancy metrics from **1990 to 2019**. The dataset includes information on the number of **pharmacists** and **medical doctors** per 10,000 population, along with **healthy life expectancy at birth**. Our analysis aims to uncover patterns and insights into how the density of healthcare providers influences life expectancy.

The outcomes of this study could inform **policymakers** and **healthcare planners** about the importance of investing in **healthcare infrastructure** and personnel, ultimately contributing to the optimization of healthcare resources to improve global life quality and longevity.

### <u>Objective & Research Questions</u>

The primary aim of this project is to explore the **correlation** between the **density** of healthcare providers (pharmacists and medical doctors) and **life expectancy**. We seek to determine if a higher number of healthcare providers per capita correlates with increased life expectancy.

To address this, the project is structured around two main objectives and their respective questions:

**Objective 1**: Provide an overview of **Life Expectancy by Gender and Continent** for the years 2000, 2010, and 2015.

- Do **females** or **males** tend to have higher life expectancy?
- Which **continent** or **country within each continent** has the highest and lowest life expectancy?

**Objective 2**: Investigate the potential **relationship** between **Medical Professional Density** and **Life Expectancy**.

- Is there any correlation between the density of medical professionals and life expectancy?

## <u>2. Dataset Description</u>

The analysis utilizes three comprehensive datasets from the **World Health Statistics 2020**. These datasets detail:

- The distribution of **healthcare providers** (medical doctors and pharmacists) per 10,000 population.
- Metrics on **life expectancy** across various regions and time periods (1990-2019).

For more information about the dataset, you can access it here: [World Health Statistics 2020 | Complete | Geo-Analysis](https://www.kaggle.com/datasets/world-health-statistics-2020).

## <u>3. Data Preprocessing</u>

Before analysis, the datasets were cleaned and preprocessed to ensure **accuracy** and **consistency**. This included handling missing values, standardizing formats, and merging datasets to align with research objectives.

## <u>4. Data Analysis and Visualization</u>

**4.1. Overview of Life Expectancy (Periods: 2000, 2010, 2015)**

We examined average life expectancy for the years **2000**, **2010**, and **2015**. The data shows a general increase in life expectancy over these years, with 2015 marking the highest average. The analysis delves into how **healthcare provider density** may correlate with these trends.

**4.2. Life Expectancy by Continent (Periods: 2000, 2010, 2015)**

We assessed life expectancy across different **continents** and compared the data from 2000, 2010, and 2015.

**4.3. Healthcare and Life Expectancy Disparities**

- **Countries with Highest/Lowest Life Expectancy by Continent**: Identified top and bottom countries in terms of life expectancy.
- **Countries with Highest/Lowest Medical Professional Density by Continent**: Highlighted countries with the highest and lowest density of medical professionals.
- **Relationship between Life Expectancy and Medical Professional Density**: Analyzed the correlation between these variables.

## <u>5. Conclusion</u>

### <u>Findings from the Analysis</u>

- **Countries with the highest medical professional density** do not always exhibit the highest life expectancy.
- In **Europe**, a clearer positive correlation between medical professional density and life expectancy was observed.
- The relationship between medical professional density and life expectancy is complex and influenced by various factors including:
  - **Quality of healthcare systems**
  - **Healthcare infrastructure**
  - **Socioeconomic factors** (income, education, employment opportunities, social support)
  - **Lifestyle choices** (nutrition, diet)
  - **Environmental conditions** (air and water quality)

### <u>Research Questions Revisited</u>

**Objective 1: Life Expectancy by Gender and Continent**

- Do females or males tend to have higher life expectancy? **Female life expectancy** is generally higher.
- Which continent or country by continent has the highest/lowest life expectancy? Detailed answers are provided in the analysis sections.

**Objective 2: Relationship Between Medical Professional Density and Life Expectancy**

- Is there any correlation between these two variables? The correlation is nuanced and influenced by various factors.

## <u>Limitations</u>

- **Data Quality**: Variations in data reporting and completeness across countries.
- **External Factors**: Other influencing factors beyond healthcare provider density were not exhaustively explored.
- **Temporal Changes**: Changes in healthcare policies or global events may impact the results.

## <u>Future Work</u>

Further research could explore additional factors influencing life expectancy and refine the analysis by incorporating more granular data or considering more recent developments in healthcare systems.

## <u>References</u>

- [World Health Statistics 2020](https://www.who.int/data/gho/publications/world-health-statistics)
- [Data Sources and Methodology](https://www.who.int/healthinfo/global_burden_disease/en/)
