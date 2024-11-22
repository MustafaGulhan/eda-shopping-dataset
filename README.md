# EDA and Visualizing Shopping Dataset
## Project Overview
This project, completed as part of the Aygaz Data Processing Bootcamp, focuses on exploratory data analysis (EDA) and visualizing trends within an online shopping dataset. The workflow involves preprocessing data, handling missing values, and creating meaningful visualizations to extract insights.

Kaggle: https://www.kaggle.com/code/mustafagulhan/eda-and-visualizing-shopping-dataset
## Features
- Cleaning and preparing the dataset for analysis.
- Adding and handling random missing values.
- Implementing data visualizations using popular Python libraries such as "Matplotlib" and "Seaborn".
- Exploratory analysis of patterns in online shopping behavior.

## Getting Started
### Prerequisites
Make sure the following Python libraries are installed:
- pandas
- numpy
- seaborn
- matplotlib
- scipy
- scikit-learn

Install them using pip: 
```
pip install pandas numpy seaborn matplotlib scipy scikit-learn
```
Dataset
The dataset used in this project is loaded from a CSV file:
```
/kaggle/input/online-shopping-dataset/file.csv
```
Ensure the file path is correctly set before running the notebook.

# Structure
1. Dataset Preparation:

    - Load and inspect the dataset.
    - Clean and preprocess the data for analysis.
2. Handling Missing Data:

    - Introduce random missing values.
    - Handle missing data using statistical methods (e.g., median imputation).
3. Exploratory Data Analysis:

    - Generate visualizations for trends and patterns.
    - Analyze correlations and distributions.

# Conclusion and Recommendations / Sonuç ve Öneriler
### EN
In this analysis aimed at improving the performance of the e-commerce platform and analyzing customer behavior, customer spending, delivery fees, coupon usage, and shopping behaviors are considered. Analyzing monthly spending and delivery fees allows for the development of strategies such as free delivery during periods of high delivery charges. City-based analysis aims to increase sales in low-performing areas through special discounts. Spending analysis by gender helps in creating customized campaigns for specific customer groups. Customer value analysis can increase loyalty for high-spending customers through loyalty programs. Additionally, analyzing the effect of coupon usage on sales helps assess the effectiveness of promotional strategies, which can be applied to broader audiences. These analyses provide effective strategies to improve customer experience while increasing the company's revenue.

In e-commerce analysis, the Decision Tree algorithm is appropriate due to its simplicity, interpretability, and speed. Unlike algorithms that rely on linear relationships, such as Logistic Regression, decision trees can model both linear and nonlinear relationships. While more complex algorithms like Random Forest or XGBoost offer higher accuracy, they require more computational power and have lower interpretability. Decision trees work with both categorical and numerical data without the need for preprocessing and provide easily understandable visualizations for managers. These features make them ideal for quick and effective analysis with the current dataset.

### TR
E-ticaret platformunun performansını artırmak ve müşteri davranışlarını analiz etmek için yapılan bu analizde, müşteri harcamaları, teslimat ücretleri, kupon kullanımı ve alışveriş davranışları ele alınmaktadır. Aylık harcama ve teslimat ücretlerinin analizi, yüksek teslimat ücretlerinin olduğu dönemlerde ücretsiz teslimat gibi stratejiler geliştirilmesine olanak tanır. Şehir bazındaki analizler, düşük performans gösteren bölgelerde özel indirimler ile satışları artırmayı hedefler. Cinsiyet bazında yapılan harcama analizleri, belirli müşteri grupları için özelleştirilmiş kampanyalar oluşturulmasına yardımcı olur. Müşteri değeri analizi, sadakat programlarıyla yüksek harcama yapan müşterilerin bağlılığını artırabilir. Ayrıca, kupon kullanımının satışlar üzerindeki etkisi, promosyon stratejilerinin etkinliğini değerlendirerek daha geniş kitlelere uygulanabilir. Bu analizler, şirketin gelirini artırırken, müşteri deneyimini iyileştirmeye yönelik etkili stratejiler sunar.

E-ticaret analizinde Karar Ağacı algoritması basitliği, açıklanabilirliği ve hızından dolayı mantıklıdır. Logistic Regression gibi doğrusal ilişkilere bağlı algoritmalar yerine, karar ağaçları hem doğrusal hem de doğrusal olmayan ilişkileri modelleyebilir. Random Forest veya XGBoost gibi daha karmaşık algoritmalar yüksek doğruluk sunabilir ancak daha fazla hesaplama gücü gerektirir ve açıklanabilirlikleri düşüktür. Karar ağacı, hem kategorik hem de sayısal verilerle ön işleme gerek kalmadan çalışabilir ve yöneticiler için kolayca anlaşılabilir görselleştirmeler sunar. Bu özellikler, mevcut veri setinizde hızlı ve etkili analizler için idealdir.

# How to Run
1. Clone the repository:
```
git clone <repository_url>
```
2. Navigate to the project directory:
```
cd <project_directory>
```
3. Run the Jupyter Notebook:
```
jupyter notebook eda-and-visualizing-shopping-dataset.ipynb
```

# Acknowledgments
This project was developed together with [Büşra Nur KÜÇÜK](https://www.kaggle.com/branurkk). Thank you for being a great teammate! [Github](https://github.com/busrakck)
