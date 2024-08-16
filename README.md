# Montgomery County 911 Emergency Call Analysis
Analysis of 911 emergency call data from Montgomery County, Pennsylvania, to optimize resource allocation and improve public safety.

## Project Overview
This project analyzes 911 emergency call data from Montgomery County, PA, to identify patterns and trends in emergency services. The goal is to optimize resource allocation, improve response times, and enhance overall public safety through data-driven insights.

## Project Structure
Montgomery-County-911-Emergency-Call-Analysis/
├── Data/
│   └── MontcoAlert.csv         # 911 call data from Montgomery County
├── 911_Call_Analysis.ipynb     # Jupyter Notebook with analysis
└── README.md                   # Project overview and instructions

## Installation and Setup
To run the analysis, you need to have Python installed along with the necessary libraries. You can set up your environment by following these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Montgomery-County-911-Emergency-Call-Analysis.git
   cd Montgomery-County-911-Emergency-Call-Analysis
   
2. **Install required libraries**:
You can install the necessary libraries by running:
   ```bash
   pip install pandas numpy matplotlib seaborn folium

3. **Run the Jupyter Notebook**:
Start the Jupyter Notebook by executing:
   ```bash
   jupyter notebook 911_Call_Analysis.ipynb


## Data Description
MontcoAlert.csv: Contains 911 call data from Montgomery County, PA. The dataset includes information on call types, zip codes, timestamps, and the corresponding emergency services (EMS, Fire, Traffic).

## Analysis Overview
In the Jupyter Notebook, the 911 call data is analyzed to identify high-demand areas and peak times for emergency services. The notebook includes:
Data cleaning and preprocessing.
Exploratory Data Analysis (EDA) to uncover trends.
Time-based analysis (hourly, daily, monthly patterns).
Geographic analysis (zip code and township-based).
Department-specific analysis (EMS, Fire, Traffic).

## Key Findings
The top 5 zip codes with the most 911 calls are 19401, 19464, 19403, 19446, and 19406.
EMS calls are the most frequent, followed by traffic and fire-related calls.
Friday has the highest call volume, while weekends show a decrease in calls.
EMS calls peak between 10 AM and 1 PM, while police and fire calls peak around 5 PM.

## Future Work
Integrate additional data sources for more comprehensive analysis.
Develop predictive models for forecasting emergency call volumes.
Create interactive dashboards for real-time monitoring of emergency services.

## Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
This project was completed as part of the Capstone Design course in the Data Science Department. Special thanks to Professor Park Sangsung for guidance and support.
