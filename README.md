# Boston Crime Analytics

A comprehensive data analytics project examining crime patterns, shooting incidents, and public employee earnings in Boston from 2015 to 2021. This project was developed as part of the W200 Data Science course and provides insights into crime trends, geographic distributions, and correlations with public spending.

## 📊 Project Overview

This repository contains data analytics and visualizations exploring:
- **Crime Incidents**: Analysis of over 500,000+ crime reports from 2015-2020
- **Shooting Data**: Detailed examination of shooting incidents from 2015-2021
- **Employee Earnings**: Boston public employee compensation analysis
- **Spending Analysis**: Correlation between public spending and crime patterns

### Key Objectives
- Identify crime trends and patterns across Boston districts
- Analyze temporal patterns (yearly, monthly, hourly trends)
- Examine geographic distribution of crimes
- Investigate relationship between public spending and crime rates
- Provide actionable insights for policy makers and law enforcement

## 📁 Repository Structure

```
Boston_crime-analytics/
│
├── Boston Incidents Reported 2015 to 2020.ipynb    # Main crime analysis notebook
├── Boston_Shooting_Data_2015-2021.ipynb            # Shooting incidents analysis
├── Project_2_Emp_Ern_analysis.ipynb                # Employee earnings analysis
├── Project_2_Spend_Analysis_Final.ipynb            # Public spending analysis
│
├── Boston_Crime_Data/                               # Crime datasets
│   ├── combined_2015-2020_allcrime_Boston.csv      # Consolidated crime data
│   ├── crime_Boston_2015.csv through 2020.csv      # Yearly crime data
│   ├── Boston_Allshooting_2015-2021.csv            # Shooting incidents data
│   ├── Crime_data_csv_combine.ipynb                # Data consolidation notebook
│   ├── rmscrimeincidentfieldexplanation.xlsx       # Field descriptions
│   └── rmsoffensecodes.xlsx                        # Offense code reference
│
├── Boston_all_employee_earnings/                   # Employee earnings datasets
│   ├── employee-earnings-combined2015-2020.csv     # Consolidated earnings data
│   ├── employee-earnings-report-2015-2020.csv      # Yearly reports
│   └── Combine_all_employee_earnings_Boston_Spending.ipynb
│
├── Boston Map/                                      # Geographic shapefiles
│   └── Police_Districts.*                          # Boston police district boundaries
│
├── W200_Project2_Report.pdf                        # Final project report
├── W200_Proj_2_Presentation.pdf                    # Project presentation slides
└── W200_Project_2.docx                             # Project documentation
```

## 📓 Notebooks Description

### 1. Boston Incidents Reported 2015 to 2020
**Main crime analysis notebook** covering:
- Data loading and cleaning of 500,000+ crime incidents
- Exploratory data analysis (EDA) of crime patterns
- Temporal analysis (yearly, monthly, daily, hourly trends)
- District-wise crime distribution
- Crime category analysis
- Shooting incident identification and analysis
- Geographic visualization using police district maps

### 2. Boston Shooting Data 2015-2021
Specialized analysis of shooting incidents including:
- Shooting data preprocessing and cleaning
- Trend analysis over 6 years
- Geographic hotspot identification
- Temporal patterns of shooting incidents
- Correlation with overall crime data

### 3. Project_2_Emp_Ern_analysis
Employee earnings analysis featuring:
- Boston public employee compensation data (2015-2020)
- Salary trends and distributions
- Department-wise earnings analysis
- Overtime and additional compensation patterns

### 4. Project_2_Spend_Analysis_Final
Comprehensive spending analysis examining:
- Public spending patterns over time
- Correlation between spending and crime rates
- Employee compensation breakdown (regular, overtime, details, etc.)
- Department-level spending analysis
- Statistical analysis of spending trends

## 🔍 Data Sources

The project utilizes publicly available data from:
- **Boston Police Department**: Crime incident reports via [Boston.gov Open Data](https://data.boston.gov/)
- **City of Boston**: Employee earnings records and public spending data
- **Boston GIS**: Police district boundary shapefiles for geographic analysis

### Data Coverage
- **Crime Data**: 500,000+ incidents from 2015-2020
- **Shooting Data**: Comprehensive records from 2015-2021
- **Employee Data**: Public employee earnings from 2015-2020

## 🛠️ Requirements

### Python Environment
- Python 3.7+
- Jupyter Notebook / JupyterLab

### Required Libraries
```python
pandas              # Data manipulation and analysis
numpy               # Numerical computing
matplotlib          # Data visualization
seaborn             # Statistical data visualization
geopandas           # Geographic data handling
folium              # Interactive map visualization
shapely             # Geometric operations
scipy               # Scientific computing
statsmodels         # Statistical modeling
```

## 📦 Installation

1. **Clone the repository**
```bash
git clone https://github.com/arunnath011/Boston_crime-analytics.git
cd Boston_crime-analytics
```

2. **Create a virtual environment (recommended)**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install required packages**
```bash
pip install pandas numpy matplotlib seaborn jupyter geopandas folium shapely scipy statsmodels
```

## 🚀 Usage

1. **Start Jupyter Notebook**
```bash
jupyter notebook
```

2. **Open any of the analysis notebooks**:
   - `Boston Incidents Reported 2015 to 2020.ipynb` - Start here for crime analysis
   - `Boston_Shooting_Data_2015-2021.ipynb` - For shooting-specific analysis
   - `Project_2_Emp_Ern_analysis.ipynb` - For employee earnings analysis
   - `Project_2_Spend_Analysis_Final.ipynb` - For spending correlation analysis

3. **Run the cells sequentially** to reproduce the analysis

## 📈 Key Features & Analyses

### Crime Pattern Analysis
- ✅ Temporal trends (yearly, seasonal, daily patterns)
- ✅ Geographic distribution across Boston districts
- ✅ Crime category breakdown and trends
- ✅ Hourly patterns (peak crime hours)
- ✅ Day-of-week analysis

### Shooting Incident Analysis
- ✅ Year-over-year shooting trends
- ✅ Geographic hotspot identification
- ✅ Temporal patterns of shootings
- ✅ Correlation with general crime patterns

### Public Spending Analysis
- ✅ Employee compensation trends
- ✅ Department-level spending breakdown
- ✅ Overtime and special detail analysis
- ✅ Correlation with crime rates

### Visualizations
- 📊 Interactive time series plots
- 🗺️ Geographic heat maps
- 📉 Statistical distribution charts
- 🎯 Correlation matrices

## 📄 Project Reports

The repository includes comprehensive project deliverables:
- **W200_Project2_Report.pdf**: Detailed 8-page report with findings and methodology
- **W200_Proj_2_Presentation.pdf**: 12-page presentation slides
- **W200_Project_2.docx**: Project documentation

## 🎯 Key Findings

Based on the analyses performed, the project reveals:
- Crime patterns show distinct temporal and geographic variations
- Certain districts have consistently higher crime rates
- Shooting incidents show specific hotspot patterns
- Public spending correlates with crime prevention effectiveness
- Seasonal and time-of-day factors significantly influence crime rates

## 🤝 Contributing

This is an academic project, but suggestions and improvements are welcome:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new analysis'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📝 License

This project is available for educational and research purposes. Please cite appropriately if using this work.

## 👥 Acknowledgments

- **Data Source**: City of Boston Open Data Portal
- **Course**: UC Berkeley W200 Data Science
- **Tools**: Python, Jupyter, Pandas, GeoPandas, Matplotlib

## 📧 Contact

For questions or collaborations, please open an issue in this repository.

---

*This project demonstrates data science techniques applied to real-world urban data, providing insights for public safety and policy decision-making.*
