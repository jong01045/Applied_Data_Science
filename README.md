---

# MSc Data Science – Applied Data Science Projects

This repository contains two main projects completed during my MSc Data Science program under the module **Applied Data Science**. The work is organized into two folders: **Semester 1** and **Semester 2**.

## Table of Contents
1. [Semester 1: Traffic Data Collection & Analysis](#semester-1-traffic-data-collection--analysis)
2. [Semester 2: Tesco Sales Data Analysis](#semester-2-tesco-sales-data-analysis)
3. [Getting Started](#getting-started)
4. [Repository Structure](#repository-structure)
5. [Contributions and Contact](#contributions-and-contact)

---

## Semester 1: Traffic Data Collection & Analysis

During Semester 1, we collected traffic data near the entrance of the University of Bath. The goal was to **gather, clean, and analyze** real-world data to gain insights into local traffic patterns.

### Key Objectives
- **Data Collection**: We manually gathered traffic data (vehicle counts, vehicle types, timestamps, etc.) and consolidated them into CSV files.
- **Data Cleaning**: Used Python and Pandas to merge CSVs from different peers, handle missing values, and standardize column formats.
- **Analysis**:  
  - Explored overall traffic flow.
  - Focused on the **number of electric cars** compared to 2022 data to highlight trends in **sustainable transport** adoption.

### Methods & Tools
- **Python**: Data cleaning, exploration, and analysis.
- **Pandas**: Data manipulation and merging.
- **Matplotlib/Seaborn** (if used): Basic data visualization.

### Findings
- Electric car usage showed notable year-over-year growth (placeholder for exact details).
- Potential to encourage more eco-friendly transportation methods by showcasing real data on adoption rates.

### Image Placeholder
*(Include a screenshot, chart, or photograph related to traffic data collection or results.)*

```md
![Semester 1 Traffic Analysis](images/semester1-image.png)
```

---

## Semester 2: Tesco Sales Data Analysis

In Semester 2, I performed a **data analysis on Tesco sales data**, integrating government demographic data to explore how socio-economic factors might influence purchasing trends.

### Key Objectives
- **Data Overview**: Provide a general audience-friendly overview of the Tesco sales dataset.
- **Critical Insights**: Create visualizations highlighting key trends in product categories, seasonal fluctuations, or promotional impacts.
- **Demographic Integration**:  
  - Merged government demographic data (such as average income per area).
  - Investigated possible correlations between income levels and sales volume/trends.

### Methods & Tools
- **Data Wrangling**: Python (Pandas) to clean and combine multiple datasets. Since the data was collected by numerous of individuals, it was all over the place. This cleaning process was the heaviest duty for the whole task.
- **Visualization**: Used libraries like Matplotlib, Seaborn, or Plotly for interactive or publication-quality charts.
- **Presentation**: Created a final presentation deck and **executive summary** to communicate findings.

### Highlights
- Identified a positive correlation between income and certain premium product sales.
- Seasonal promotions appear more effective in higher-income areas (placeholder for insights).

### **Extra analysis**
- **Bayesian Hierarchical Regression**: Employs PyMC3 to build a hierarchical model, accounting for differences across geographic areas (wards, local authorities). This model estimates how factors like diet, demographic attributes, and population density influence diabetes prevalence, providing a more nuanced, location-specific understanding of potential risk factors.

### Image Placeholder
*(Include a screenshot of a plot, chart, or your presentation slides relevant to the Tesco analysis.)*

```md
![Semester 2 Tesco Analysis](path/to/semester2-image.png)
```

---

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YourUsername/YourRepoName.git
   ```
2. **Install dependencies** (if any specific libraries are required beyond standard Python data science packages):
   ```bash
   pip install -r requirements.txt
   ```
3. **Navigate to each folder** (`Semester 1` or `Semester 2`) to view Jupyter notebooks (`.ipynb`) or scripts with the analysis steps.

---

## Repository Structure

```
YourRepoName/
│
├── Semester 1/
│   ├── Sub 1+2/     # Manually collected our version of CSV
│   ├── Sub 3/       # Analysis for the entire course's CSVs
│   ├── csv_data/    # All CSV data provided
│   └── CM50266_Coursework_2023S1_Specification.pdf  # CW specification
│
├── Semester 2/
│   ├── Graphs/                     # All graphs used in the presentation
│   ├── PurchaseDatasets/           # Tesco Sales data throughout different geographical areas
│   └── Presentation/   
│       └── ...      # PowerPoint or PDF with final presentation and executive summary
│   └── Bayesian regression Analysis (Extra).py
│   └── CM50266_S2_2324_CourseworkSpec.pdf
│
├── README.md        # This file
└── requirements.txt # If applicable
```

---

## Contributions and Contact

- **Author**: Jungho Park  
- **Email**: [jungho.career@gmail.com](mailto:jungho.career@gmail.com)  
- **LinkedIn**: [Linkedin](https://www.linkedin.com/in/jungho-park-2bb5a4198/)

If you wish to contribute, feel free to fork this repository and submit a pull request. Feedback and suggestions are always welcome!

---

**Thank you for exploring my Applied Data Science projects!**
