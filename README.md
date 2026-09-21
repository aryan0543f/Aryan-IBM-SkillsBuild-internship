# Supermarket Sales Analysis

## IBM SkillsBuild Data Analytics with AI Academic Internship Program

**Program:** AICTE - IBM SkillsBuild Data Analytics with AI  
**Conducted by:** BharatCares  
**Author:** Aryan

---

## 📋 Project Overview

This project analyzes supermarket sales data to extract valuable insights about products, branches, categories, customer behavior, payment methods, and customer satisfaction ratings. The analysis aims to support data-driven business decisions for improving supermarket operations and profitability.

## 🎯 Problem Statement

The aim of this project is to analyze supermarket sales data and find useful information about:
- Product performance
- Branch effectiveness
- Category sales trends
- Customer payment preferences
- Customer type behavior (Members vs Normal)
- Customer satisfaction ratings

## 📊 Dataset

**Dataset Name:** Supermarket Sales Data  
**Dataset Link:** `supermarket_sales.csv` (included in project folder)

**Dataset Details:**
- **Total Records:** 1000 sales transactions
- **Format:** CSV (Comma Separated Values)

**Key Columns:**
- Invoice ID
- Branch (A, B, C)
- City
- Customer type (Member/Normal)
- Gender
- Product line (Category)
- Unit price
- Quantity
- Tax 5%
- Total
- Date
- Time
- Payment (Ewallet/Credit card/Cash)
- Rating
- Sales (Total amount)

## 🛠️ Technologies Used

- **Programming Language:** Python 3.8+
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Development Environment:** Jupyter Notebook
- **Version Control:** Git

### Python Libraries:
```
pandas
numpy
matplotlib
seaborn
jupyter
notebook
```

## 🚀 Setup and Installation

### Prerequisites
- Python 3.8 or higher installed
- pip (Python package installer)
- Jupyter Notebook or JupyterLab

### Installation Steps

1. **Clone or download the project files**
   ```bash
   # If using Git
   git clone <repository-url>
   cd supermarket-sales-analysis
   ```

2. **Install required dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Place the dataset**
   - Download the dataset CSV file
   - Place it in the project directory as `supermarket_sales.csv`

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

5. **Open and run the notebook**
   - Open `SupermarketSalesAnalysis.ipynb`
   - Run all cells sequentially (Cell → Run All)

## 📈 Analysis Steps

The project follows a structured data analysis workflow:

1. **Data Collection:** Load the CSV dataset
2. **Data Exploration:** Understand data structure and statistics
3. **Data Cleaning:** Check for missing values and duplicates
4. **Feature Engineering:** Calculate Sales = Quantity × Unit Price
5. **Data Analysis:** Group and summarize data using aggregations
6. **Visualization:** Create charts and graphs for insights
7. **Business Insights:** Derive actionable recommendations

## 🔍 Key Findings

### 1. Product Performance
- **Highest selling category:** Food and beverages
- **Total sales:** ₹56,144.84

### 2. Branch Performance
- **Best performing branch:** Branch C (Naypyitaw)
- **Total sales:** ₹110,568.71

### 3. Category Performance
- **Top selling category:** Food and beverages
- **Total sales:** ₹56,144.84

### 4. Payment Methods
- **Most popular method:** Ewallet
- **Total transactions:** 345 (34.5% of all transactions)

### 5. Customer Type Analysis
- **Member average transaction:** ₹327.79
- **Normal customer average transaction:** ₹318.12
- **Insight:** Members spend ₹9.67 more per transaction on average

### 6. Customer Satisfaction
- **Average rating:** 6.97 out of 10

## 💡 Business Recommendations

Based on the analysis, the following business decisions are recommended:

1. **Inventory Management**
   - Maintain higher stock levels for Food and beverages category
   - Monitor top-selling products to prevent stockouts
   - Optimize shelf space based on category performance

2. **Branch Strategy**
   - Study and replicate success factors from Branch C (Naypyitaw) to other branches
   - Allocate resources proportionally based on branch performance
   - Share best practices across all locations

3. **Payment Infrastructure**
   - Ensure robust Ewallet payment systems (most preferred method)
   - Continue supporting and promoting digital payments
   - Maintain backup payment options for reliability

4. **Customer Engagement**
   - Continue membership program - members spend slightly more per transaction
   - Design targeted marketing campaigns for both customer segments
   - Implement loyalty programs to retain high-value customers

5. **Service Quality**
   - Focus on customer service improvements to increase ratings above 7.0/10
   - Collect and act on customer feedback regularly
   - Address pain points identified through low ratings

## 📁 Project Structure

```
supermarket-sales-analysis/
│
├── SupermarketSalesAnalysis.ipynb    # Main Jupyter notebook with analysis
├── requirements.txt                  # Python dependencies
├── README.md                         # Project documentation (this file)
├── Aryan_ProjectReport.docx         # Detailed project report
├── supermarket_sales.csv            # Dataset (to be added)
└── Completion Certificate_SkillsBuild.pdf  # Internship certificate
```

## 📝 Usage

1. Ensure all dependencies are installed
2. Place your dataset CSV file in the project directory
3. Open the Jupyter notebook
4. Execute cells in order from top to bottom
5. Review generated visualizations and insights
6. Modify analysis parameters as needed

## 🎓 Learning Outcomes

This project demonstrates proficiency in:
- Data manipulation with Pandas
- Statistical analysis with NumPy
- Data visualization with Matplotlib and Seaborn
- Business intelligence and insight generation
- Professional documentation and reporting
- End-to-end data analytics workflow

## 👨‍💻 Author

**Aryan**  
IBM SkillsBuild Data Analytics with AI Academic Internship  
BharatCares - AICTE

## 📜 License

This project is part of the IBM SkillsBuild Academic Internship Program.

## 🙏 Acknowledgments

- **AICTE** for organizing the internship program
- **IBM SkillsBuild** for providing the platform and resources
- **BharatCares** for conducting and coordinating the program
- Instructors and mentors for guidance throughout the internship

---

## 📞 Contact

For questions or feedback regarding this project, please contact through the IBM SkillsBuild platform.

---

**Note:** This project was completed as part of the IBM SkillsBuild Data Analytics with AI Academic Internship Program in association with AICTE and conducted by BharatCares.
