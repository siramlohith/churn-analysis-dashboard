# churn-analysis-dashboard
An interactive churn analysis dashboard leveraging regression analysis in Python and visualization in Power BI to uncover key drivers of customer churn and support data-driven decision making.
// Customer Segmentation Using K-Means (Telecom Data)

> Overview
This project applies K-Means clustering to segment telecom customers based on usage behavior and service interaction patterns.

> Business Objective
- Identify high-value customers  
- Detect churn-risk segments  
- Enable targeted marketing strategies  

> Dataset
- Telecom dataset (`churn-bigml-80.csv`)  
- Features: call minutes, customer service calls, voicemail usage  

> Tech Stack
Python | Pandas | Scikit-learn | Matplotlib  

> Approach
- Data cleaning and preprocessing  
- Feature scaling using StandardScaler  
- Elbow Method to find optimal clusters  
- K-Means clustering (k = 4)  

^^ Customer Segments

> Cluster 0 – Low Value**
- Low usage, low engagement  
- Action: Re-engagement campaigns  

> Cluster 1 – High Value**
- High usage, stable  
- Action: Retention & upselling  

> Cluster 2 – At Risk**
- High support calls  
- Action: Improve service & retain  

> Cluster 3 – Premium Users**
- High international usage  
- Action: Offer premium plans  

> Outcome
- Identified 4 customer segments  
- Highlighted revenue and churn-risk groups  

> Future Improvements
- Add churn prediction model  
- Build Power BI dashboard  

> Author
- Lohith
