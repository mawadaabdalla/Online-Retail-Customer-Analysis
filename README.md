# 🛒 Online Retail Dataset Analysis (RFM & Clustering) 🚀

This project analyzes an **Online Retail Dataset** containing customer purchase information. Using **RFM (Recency, Frequency, Monetary)** analysis and **K-Means clustering**, we segment customers into meaningful groups and visualize the results to uncover actionable insights. 📊

---

## 🚀 Key Features
- **📂 Dataset Exploration**: Explore customer purchase data, including invoices, stock codes, quantities, and more.
- **📊 RFM Analysis**:
  - **Recency**: How recently a customer made a purchase.
  - **Frequency**: How often they purchase.
  - **Monetary**: How much they spend.
- **🤖 K-Means Clustering**: Segment customers based on RFM values.
- **📈 Visualizations**: Create graphs to showcase customer segments and trends.

---

## 🛠️ How to Use
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/online-retail-analysis.git
   cd online-retail-analysis
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the Notebook**:
   Launch Jupyter Notebook and open `online_retail_analysis.ipynb`.

4. **Run the Analysis**:
   Execute the cells in the notebook to perform RFM analysis, clustering, and visualization.

5. **Explore Results**:
   View customer segments and insights directly in the notebook. 🎉

---

## 🔍 Methodology
1. **📥 Data Loading**: Load the Online Retail Dataset.
2. **🧹 Data Cleaning**:
   - Handle missing values (e.g., `CustomerID`).
   - Remove duplicates and invalid entries.
3. **📊 RFM Analysis**:
   - **Recency**: Calculate the number of days since the last purchase for each customer.
   - **Frequency**: Count the number of purchases per customer.
   - **Monetary**: Sum the total spending per customer.
4. **🤖 K-Means Clustering**:
   - Normalize RFM values.
   - Apply K-Means clustering to segment customers into groups.
   - Order clusters so that the most recent, frequent, and high-spending customers have higher values.
5. **📈 Visualizations**:
   - Create scatter plots, bar charts, and heatmaps to visualize customer segments.
   - Highlight key insights, such as high-value customers or at-risk customers.

---

## 📌 Results
- **📊 RFM Scores**: Recency, Frequency, and Monetary values for each customer.
- **🤖 Customer Segments**: Clusters of customers based on RFM analysis.
- **📈 Visualizations**: Graphs showcasing customer segments and trends.

---

## 🤝 Contributing
Contributions are welcome! 🎉  
1. Fork the repo.  
2. Create a branch.  
3. Submit a pull request with your changes.  

---

## 📜 License
MIT License. See [LICENSE](LICENSE) for details.

