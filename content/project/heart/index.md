---
title: "Heart Disease Prediction Using Data Mining Techniques"
#date: 2019-08-26
#publishDate: 2019-09-30T15:05:54.055216Z
authors: ["Oyshee Saha Roy, Supriya Patel"]
#publication_types: [""]
featured: false
#publication: "Dalhousie University, Canada"
#tags: ["Computer networks", "Computer science", "Costs", "Internet", "Mobile computing", "Network address translation", "Network servers", "North America", "Protocols", "Web server"]
#url: "https://dalspace.library.dal.ca/handle/10222/76305"
---

- **Motivation:**

Heart disease is one of the leading cause of death in the world.Predicting Heart disease using patients databases can be compared to
the real-life application. It is not possible to determine which attributes have a higher impact on disease prediction. 
Therefore the already available dataset can be used for diagnosing. Over the years a significant amount of patient data has been
collected. Those data can be mined to find hidden patterns which can eventually help in decision making. Data mining is the process
of finding hidden patterns or relationships with large sets of data, and it also helps to predict outcomes based on that analysis.
Thus by building a heart disease prediction system using data mining technique can aid in early –detection or prevention of the disease. The accuracy of prediction depends on the selection of parameters to be used.
- **Objective:** 

The application scenario referred in this project is to predict heart disease using decision tree algorithms.
The study was conducted by Technique Jaymin Patel, Prof.TejalUpadhyay, Dr. Samir Patel Department of Computer Science and Engineering,
Nirma University, Gujarat, India. The primary objectives set for the study was to :
1. The prediction system should not have prior knowledge of the patient records.
2. The chosen system must be scalable to run against an extensive database with thousands of data.
Cleveland dataset from UCI repository has been used for the study.
It is available at http://archive.ics.uci.edu/ml/datasets/Heart+Disease.
The dataset has 76 attributes and 303 records. Only 13 attributes are used for the study and testing.
 
- **Algorithms:** 

The algorithm used in the project are:

1. Naïve Bayes Classifier

2. Random forest algorithm

3. J48 algorithm

- **Discussions:** 

By analyzing the experimental results, it is concluded that Naïve Bayes technique turned out to be the best classifier
for heart disease prediction because it contains more accuracy and least time taken to test model on test split up.
We can see that highest accuracy belongs to Random forest algorithm followed by Naïve Bayes algorithm and J48 algorithm respectively.
The best algorithm Random forest algorithm based on UCI data has the highest accuracy, i.e. 59.06%(weka) 58.06%(python),
while J48 algorithm has the lowest accuracy, i.e. 57.37 %.In conclusion, although we have received a better accuracy rate than
the referred paper, there is a need for combinational and more complex models to increase the accuracy of predicting the early
onset of heart disease.

- {{% staticref "files/heart.pdf" "newtab" %}}Link to full project{{% /staticref %}}

