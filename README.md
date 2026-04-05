# Global Superstore Sales Analysis using Python 📊

Is project mein maine 50,000+ orders ka sales data analyze kiya hai. Isme Data Cleaning se lekar Advanced Visualization tak ke saare steps Python (Pandas & Seaborn) ke zariye kiye gaye hain.

## 🛠️ Tools & Libraries Used
- **Language:** Python
- **IDE:** Jupyter Notebook
- **Libraries:** Pandas (Data Manipulation), Matplotlib & Seaborn (Visualization)

## 🔍 Key Analysis Steps
1. **Data Cleaning:** - 'Postal Code' column mein 80% missing values thi, jinhe humne `fillna(0)` se handle kiya.
   - Duplicate rows ko remove kiya gaya.
2. **Exploratory Data Analysis (EDA):**
   - Category aur Region ke hisab se Sales aur Profit ka breakdown.
   - Scientific notation (`e+06`) ko readable format mein convert kiya.
3. **Visualizations:**
   - **Bar Chart:** Sabse zyada bikne wali categories (Technology leads).
   - **Line Chart:** Monthly Sales Trends dikhane ke liye.
   - **Heatmap:** Correlation check karne ke liye (Discount vs Profit).
   - **Scatter Plot:** Sales aur Profit ka relation dekhne ke liye.

## 💡 Top Insights
- **Technology** category sabse zyada Sales generate kar rahi hai.
- **Tables** aur **Supplies** sub-categories mein heavy loss dikha raha hai.
- **Discount** aur **Profit** ke beech negative correlation hai, matlab zyada discount profit kam kar raha hai.

## 🚀 How to Run
1. Download karein `Global_Superstore.csv` aur `Analysis.ipynb`.
2. Jupyter Notebook open karke saare cells run karein.
