# 🛍️ Mall Customer Segmentation & Spending Analysis

### Turning Customer Data into Smart Business Decisions with Machine Learning

<p align="center">
  <strong>Python | Exploratory Data Analysis | Unsupervised Machine Learning | Customer Analytics</strong>
</p>

---

## 🌟 About the Project

Every customer has different shopping habits, spending patterns, and preferences. Understanding these differences helps businesses make better decisions.

**Mall Customer Segmentation** is a Data Science project that analyzes customer data and applies unsupervised Machine Learning techniques to identify groups of similar customers.

The project explores different clustering algorithms, visualizes customer patterns, and translates the analysis into practical business recommendations.

🎯 **My goal:** To transform raw customer data into meaningful insights that can help businesses understand their customers and improve marketing strategies.

## 🎯 Project Objectives

- 🔍 Explore and understand the customer dataset through Exploratory Data Analysis (EDA).
- 🧹 Prepare the data and scale numerical features for clustering.
- 🤖 Apply and compare three clustering algorithms.
- 📊 Visualize customer groups using dimensionality-reduction techniques.
- 💡 Interpret customer segments and identify useful business opportunities.
- 📈 Develop data-driven recommendations for customer engagement and marketing.

## 🧰 Technologies & Tools

| Technology | Purpose |
|---|---|
| 🐍 Python | Data analysis and model development |
| 🐼 Pandas | Data manipulation and analysis |
| 🔢 NumPy | Numerical computations |
| 📊 Matplotlib | Data visualization |
| 🎨 Seaborn | Statistical visualization |
| 🤖 Scikit-learn | Clustering, scaling, PCA, t-SNE and evaluation |
| 🌳 SciPy | Hierarchical clustering and dendrograms |
| 📓 Google Colab | Coding, experimentation and documentation |

## 🧠 Machine Learning Algorithms

### 1. K-Means Clustering
Groups customers into a predefined number of clusters based on their similarities.

**What I explored:**
- Selecting the number of clusters using the Elbow Method.
- Evaluating cluster quality using the Silhouette Score.
- Visualizing and interpreting the resulting customer groups.

### 2. Hierarchical Clustering
Builds a hierarchy of similar customers and helps explore how individual observations form larger groups.

**What I explored:**
- Understanding customer similarities.
- Using a dendrogram to investigate cluster structure.
- Comparing the clustering results with K-Means.

### 3. DBSCAN Clustering
Identifies dense groups of customers and can detect observations that do not belong to a dense cluster.

**What I explored:**
- Experimenting with `eps` and `min_samples`.
- Identifying clusters and potential noise points.
- Understanding how density-based clustering differs from other methods.

## 📉 Dimensionality Reduction & Visualization

### 🔹 Principal Component Analysis (PCA)
PCA transforms numerical features into principal components, helping summarize data variation and visualize customer patterns in fewer dimensions.

### 🔹 t-SNE
t-SNE creates a lower-dimensional representation of the data to help explore local similarities and possible group structures.

These visualizations support the analysis, but the plots alone do not prove that customer segments are meaningful.

## 📊 Cluster Analysis & Business Insights

The project examines the characteristics of the identified customer groups and considers how businesses might use these insights.

Potential business applications include:

- 💎 **Customer Retention:** Develop loyalty programs for valuable, frequent-spending customers.
- 🎯 **Targeted Marketing:** Design campaigns suited to different customer groups.
- 🛍️ **Personalized Offers:** Explore promotions based on customer spending patterns.
- 💰 **Budget-Friendly Strategies:** Consider value offers for price-conscious customers.
- 📈 **Business Growth:** Use customer patterns to guide future marketing experiments.

*The final segment descriptions and recommendations should be based on the actual cluster profiles and model results generated in the notebook.*

## 📁 Project Structure

```text
Mall-Customer-Segmentation/
│
├── Mall_Customer_Spending_Analysis_and_Customer_Segmentation.ipynb
├── requirements.txt
├── README.md
├── visualizations.pdf
│
└── visualizations/
    ├── Individual chart images
    └── Clustering and analysis plots
```

## 🚀 How to Run the Project

### Option 1: Google Colab

1. Download or upload the Jupyter Notebook to Google Drive.
2. Open the notebook using Google Colab.
3. Load the mall customer dataset.
4. Run the cells sequentially.
5. Review the charts, clustering results, and business insights.

### Option 2: Run Locally

**Step 1:** Clone or download this repository.

**Step 2:** Install the required Python libraries.

```bash
pip install -r requirements.txt
```

**Step 3:** Launch Jupyter Notebook.

```bash
jupyter notebook
```

**Step 4:** Open the project notebook, verify the dataset path, and run the cells.

## 📌 Project Deliverables

- ✅ Jupyter Notebook containing code and available outputs.
- ✅ K-Means, Hierarchical Clustering, and DBSCAN analysis.
- ✅ PCA and t-SNE dimensionality-reduction analysis.
- ✅ Customer cluster interpretation and business recommendations.
- ✅ `requirements.txt` for project dependencies.
- ✅ `visualizations.pdf` and individual visualization images.
- ✅ This project documentation in `README.md`.

## 📚 Key Learning Outcomes

Through this project, I explored how to:

- Prepare and scale data for distance-based algorithms.
- Apply different unsupervised Machine Learning techniques.
- Compare clustering approaches and evaluate their limitations.
- Visualize high-dimensional data using PCA and t-SNE.
- Connect technical analysis with practical business questions.

## 🔮 Future Improvements

- Evaluate additional clustering configurations and features.
- Improve cluster validation and compare model performance.
- Develop an interactive customer segmentation dashboard.
- Explore additional customer attributes to improve business insights.

## 👨‍💻 About Me

I am a Computer Science and Data Science graduate who is building practical skills in Python, Data Analysis, and Machine Learning.

I enjoy learning through hands-on projects, solving problems step by step, and understanding how data can support real-world decisions.

**My career goal is to grow as a Data Science professional and become a strong problem solver.**

🔗 **GitHub:** https://github.com/HARISHRAJ-R-07

💬 **Feedback and suggestions are welcome!**

---

<p align="center">
  <strong>Learn • Analyze • Experiment • Improve</strong>
  <br/>
  <em>Turning data into insights, one project at a time. 🚀</em>
</p>
