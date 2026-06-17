🍽️ Zomato Data Analysis Using Python
Python Pandas Jupyter License Status

Exploratory Data Analysis (EDA) on Zomato restaurant data to uncover dining trends, customer preferences, and actionable business insights.

📊 Notebook Walkthrough · 📁 Dataset · 📸 Visualizations · 🚀 Quick Start

📌 Table of Contents
Project Overview
Objectives
Dataset Information
Technologies Used
Project Workflow
Sample Output Visualizations
Key Insights
Project Structure
How to Run the Project
Skills Demonstrated
Future Enhancements
Author
📖 Project Overview
This project performs end-to-end Exploratory Data Analysis (EDA) on a Zomato restaurant dataset containing 148 restaurants across multiple dining categories. Through data cleaning, feature engineering, and rich visualizations, the analysis surfaces patterns in customer behavior, restaurant performance, and the factors that drive ratings and popularity.

🎯 Objectives
Analyze restaurant ratings and understand what drives customer satisfaction.
Measure the impact of online ordering and table booking on restaurant popularity.
Identify trends across restaurant types (Buffet, Cafes, Dining, Other).
Visualize key business metrics through clear, actionable charts.
Generate recommendations for restaurant owners and food delivery platforms.
📂 Dataset Information
File: Zomato-data.csv  |  Records: 148 restaurants  |  Features: 7

Column	Type	Description
name	String	Restaurant name
online_order	Yes / No	Whether online ordering is available
book_table	Yes / No	Whether table booking is available
rate	Float	Customer rating out of 5 (cleaned from "4.1/5" format)
votes	Integer	Total number of customer votes
approx_cost(for two people)	Integer	Estimated cost for two people (₹100 – ₹950)
listed_in(type)	Categorical	Restaurant category — Buffet, Cafes, Dining, Other
🛠️ Technologies Used
Tool	Purpose
Python 3.8+	Core programming language
Pandas	Data loading, cleaning & manipulation
NumPy	Numerical operations
Matplotlib	Base charting and layout control
Seaborn	Statistical visualizations
Jupyter Notebook	Interactive analysis environment
📊 Project Workflow
1. 📥 Data Collection
Imported the Zomato CSV dataset using Pandas.
2. 🧹 Data Cleaning
Parsed the rate column from "4.1/5" string format into a clean float using a custom handleRate() function.
Identified and handled missing/null values with .isnull().sum().
Reviewed column data types and structure using .info().
3. 🔍 Exploratory Data Analysis (EDA)
Analysis	Visualization
Restaurant type distribution	Count Plot
Total votes by restaurant type	Line Plot
Restaurant with the highest votes	Programmatic lookup
Online order availability	Count Plot
Rating frequency distribution	Histogram
Approximate cost for two people	Count Plot
Online order vs. restaurant rating	Box Plot
Restaurant type × online order cross-tab	Heatmap
4. 💡 Insights Generation
Identified customer behavior patterns across restaurant categories.
Measured how online ordering correlates with ratings and vote counts.
Derived business recommendations from EDA findings.
📸 Sample Output Visualizations
Online Order Distribution
	Rating Distribution

Table Booking Distribution
	Votes Distribution

📈 Key Insights
#	Insight
⭐	Most restaurants are rated between 3.5 and 4.2 / 5, indicating moderate-to-high overall satisfaction.
📱	Restaurants with online ordering show higher median ratings compared to those without.
📅	Table booking is concentrated in Dining category restaurants, which also tend to attract higher votes.
💰	The most common spend bracket is ₹300 – ₹800 for two people, pointing to a mid-range market preference.
🏆	A single restaurant holds the highest votes, suggesting strong brand loyalty or viral popularity.
🍽️	Dining dominates both in restaurant count and aggregate vote share across all categories.
📁 Project Structure
Zomato-Data-Analysis-Using-Python/
│
├── 📓 Zomato_Data_Analysis.ipynb       # Main Jupyter analysis notebook
├── 📄 Zomato-data.csv                  # Dataset — 148 restaurants, 7 features
├── 📋 requirements.txt                 # Python dependencies
├── 📖 README.md                        # Project documentation
├── 📜 LICENSE                          # MIT License
├── 🙈 .gitignore                       # Git ignore rules
├── 🤝 CONTRIBUTING.md                  # Contribution guidelines
│
└── 📸 Zomato-Output-Images/
    ├── online_order_distribution.png
    ├── rating_distribution.png
    ├── table_booking_distribution.png
    └── votes_distribution.png
🚀 How to Run the Project
Prerequisites
Python 3.8 or higher
pip
Step-by-Step
# 1. Clone the repository
git clone https://github.com/ayaanpasha007/Zomato-Data-Analysis-Using-Python.git
cd Zomato-Data-Analysis-Using-Python

# 2. (Recommended) Create a virtual environment
python -m venv venv
source venv/bin/activate        # macOS / Linux
# venv\Scripts\activate         # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch Jupyter Notebook
jupyter notebook

# 5. Open and run the analysis
#    → Zomato_Data_Analysis.ipynb
#    → Kernel > Restart & Run All
⚠️ Local path fix: The notebook was originally developed in Google Colab.
Update Cell 1 from:

dataframe = pd.read_csv("/content/Zomato-data-.csv")
to:

dataframe = pd.read_csv("Zomato-data.csv")
💼 Skills Demonstrated
Data Cleaning & Wrangling
Exploratory Data Analysis (EDA)
Statistical Analysis
Data Visualization (Matplotlib & Seaborn)
Business Insights Generation
Python Programming
Jupyter Notebook Development
🔮 Future Enhancements
 Interactive dashboard using Power BI or Tableau
 Machine Learning model to predict restaurant ratings
 Customer segmentation using clustering algorithms
 Sentiment analysis on customer reviews
 Integration with live Zomato API data
👨‍💻 Author
Ayaan Pasha
Data Analyst Aspirant | Python · SQL · Excel · Power BI


Made with ❤️ using Python & Jupyter Notebook

⭐ If you found this project useful, please star the repository! ⭐
