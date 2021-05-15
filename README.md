# ---Machine-Learning-with-Python-Project
Project is based on predicting the loan status of different loan customers based on historical data and other external factors using different machine learning algorithms.

In the notebook, I worked on a loan dataset and built different predictive alogorithms.

I loaded a dataset using Pandas library, applied the following algorithms, and selected the best one for this specific dataset by accuracy evaluation methods.



Dataset

Unnamed: 0	Unnamed: 0.1	loan_status	Principal	terms	effective_date	due_date	age	education	Gender	
0	0	0	PAIDOFF	1000	30	9/8/16	10/7/16	45	High School or Below	male
1	2	2	PAIDOFF	1000	30	9/8/16	10/7/16	33	Bechalor	female
2	3	3	PAIDOFF	1000	15	9/8/16	9/22/2016	27	college	male
3	4	4	PAIDOFF	1000	30	9/9/16	10/8/16	28	college	female
4	6	6	PAIDOFF	1000	30	9/9/16	10/8/16	29	college	male![image](https://user-images.githubusercontent.com/32384910/118344256-a4284800-b570-11eb-9605-440b7c0ee5a7.png)




Algorithms Used

| Algorithm          | Jaccard | F1-score | LogLoss |
|--------------------|---------|----------|---------|
| KNN                |0.67     |0.63      | NA      |
| Decision Tree      |0.72     |0.74      | NA      |
| SVM                |0.80     |0.76      | NA      |
| LogisticRegression |0.74     |0.66      |0.57     |
