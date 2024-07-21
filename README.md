# Retail_Sales_Analysis
This is the final project from the TechPro Academy Data Science stream

Files:
  1. Retail_Sales_Analysis.ipynb : The python file with all the code, plots and comments in english
  2. Retail_Sales_Analysis_presentation.pptx : The powerpoint of the presentation
  3. Retail_Sales_Analysis_greek.pdf  : PDF file with the analysis and conclusions in greek language without the code
  4. Retail_Sales_Analysis_dataset.csv : The dataset in a csv format
--------------

Running the Notebook in Google Colab
  1.	Open Google Colab: Go to https://colab.research.google.com/.
  2.	Upload the Notebook:
  3.	Click on "File" -> "Upload notebook" and select "Retail_Sales_Analysis.ipynb" from your local machine.
  4.	Alternatively, you can upload the entire project directory (including "Retail_Sales_Analysis.ipynb") to your Google Drive and open the notebook directly from there.
  5.  Don't forget to also upload the csv file in your google drive and change the path in the upload section of the code 
--------------

Objective

Conduct a comprehensive data analysis project on a fictional retail company's sales data,
focusing on foundational data science skills and project management.
--------------

Project Description

Use the dummy dataset provided in the accompanying CSV file for your analysis(Retail_Sales_Analysis_dataset.csv).
--------------

Analysis Goals

  • Data cleaning and preparation.
  
  • Descriptive statistics: Calculate basic statistics like mean, median, mode, and
    standard deviation to understand sales trends, customer demographics, and product
    performance. Analyze patterns like average sales per product category, age
    distribution of customers, and typical product ratings.
    
  • Data visualization: Utilize Python libraries (like Matplotlib, Seaborn) or PowerBI to
    create visualizations that highlight sales trends, customer demographics, and product
    performance. You are strongly encouraged to use both methods of visualization,
    using a non-enterprise solution and an enterprise solution.
    
  • Inferential statistics: Conduct simple hypothesis testing to draw conclusions from the
    data. Test if average sales differ significantly between product categories. Test also if
    average sales differ significantly between regions.
    
--------------

Advanced Components

  • Predictive modeling: Build a linear regression model to predict sales amounts based
    on factors like product category, customer demographics, and product ratings.
    
  • Advanced statistical analysis: Apply more complex statistical methods, like multivariable regression analysis to understand how various factors jointly influence sales.
  
  • Advanced statistical analysis: Apply clustering methods to identify distinct customer
    segments.
    
--------------

Methods Used

    •	Data Manipulation,Cleaning (pandas,numpy)
    •	Data Visualization(seaborn,matplotlib)
    •	Manchine Learning(Linear Regression)
    •	Clustering(Kmeans)
    •	ANOVA
    
--------------

DATA

  The dataset includes the following:

  • SalesDate (date in YYYY-MM-DD format)
  
  • ProductCategory (Categorical variable – {Clothing, Electronics, Home Appliances} –
    text)
    
  • SalesAmount (numeric in $)
  
  • CustomerAge (Categorical variable – text)
  
  • CustomerGender (Categorical variable – {Male, Female, Non-binary} – text)
  
  • CustomerLocation (Categorical variable – {Japan, Australia, India, USA, UK, Canada}
    – text)
    
  • ProductRatings (Categorical variable – {1 = low to 5 = high rating} – text)
  
--------------
Results

  • All our findings  from statistical analysis, ANOVA, Liner Regression, Clustering, suggests that our data have much variation, and all categories behave in a way that makes it difficult to predict purchase behavior based solely on customer demographics or product category. We were unable to successfully categorize customers based on their purchase characteristics.


