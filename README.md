# Customer Segmentation (Mall Customers)

## Dataset
- [Mall Customers - Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- 200 customers, 5 features


### Objective
Segment 200 mall customers into meaningful groups based on **Annual Income** and **Spending Score** using **Unsupervised Learning**.


## Key Findings
- **5 natural clusters** using `Annual Income` + `Spending Score`
- **Young customers (25 yrs) with low income but high spending** → **Target for promotions**
- **VIPs**: High income + high spending
- **Age negatively correlated with spending** (younger = spend more)

## Methods
- **K-Means (k=5)**: Elbow Method
- **DBSCAN**: Found 5 clusters + 15 noise points
- **Scaling**: StandardScaler
- **Visualization**: Histograms, Scatter, Correlation, Bar charts

