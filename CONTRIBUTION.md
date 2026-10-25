# Lab 07 — Model Evaluation
## Group 4 — Individual Contributions

**Course:** ITAI 1371 — Introduction to Machine Learning  
**Lab:** Module 07 — Better Model Evaluation  
**Group:** Group 4

---

### Member 1 — Patrick Rostand Gandjouon Tchassem

**Contribution:**

For this lab, I worked on completing the Google Colab notebook using the Titanic dataset. I worked through the logistic regression setup and model evaluation tasks, including generating the confusion matrix, classification report, and five-fold cross-validation results.

I reviewed the model's performance and checked the outputs to better understand its predictions. The confusion matrix showed 90 true negatives, 54 true positives, 15 false positives, and 20 false negatives. I also reviewed the classification report, which showed 80% accuracy, and the cross-validation results, which showed an average score of 78.68%.

I worked on the three knowledge-check questions about precision, recall, and cross-validation. I also prepared the notebook PDF with the code and outputs visible and helped organize the reflection and contribution Markdown files so each group member could add their own work.

---

### Member 2 — Saimi Manasiya

My contribution to this lab was working on the different steps involved in evaluating the Logistic Regression model using the Titanic dataset. I reviewed the dataset preparation process, including converting the gender values into numerical format, filling missing age values with the median, selecting the required features, and splitting the data into training and testing sets. I worked on generating the confusion matrix and understanding how it compares the actual results with the model's predictions. I also practiced using the classification report to examine precision, recall, F1-score, and overall accuracy for both the died and survived classes. Furthermore, I worked on understanding five-fold cross-validation and how calculating the average score and standard deviation helps evaluate the consistency of a model. I also reviewed the knowledge-check questions related to precision, recall, and cross-validation. Through these activities, I strengthened my Python and machine learning skills and gained a better understanding of how to evaluate classification models and interpret their results.



---

### Member 3 — Kenneth Kouokam

My contribution to Module 07 focuses on interpreting the classification metrics and explaining what
they show about the Logistic Regression model. Using the confusion-matrix counts shared by the
group, my analysis compares the Died and Survived classes instead of relying only on overall
accuracy. For survival predictions, precision is about 78%, recall is about 73%, and the F1-score is
about 76%. For the Died class, these values are about 82%, 86%, and 84%. The class supports are
74 survivors and 105 passengers who died, showing how many actual examples belong to each
class.

My interpretation connects these scores to the mistakes behind them. The model correctly identifies
54 of the 74 survivors but misses 20, which explains why survival recall is lower than the overall
accuracy of about 80%. It also predicts survival for 15 passengers who actually died, reducing
survival precision. This comparison shows that the model identifies passengers who died more
consistently than survivors on this test set. My section contributes an explanation of these differences
and why precision, recall, and F1-score give the group more information than accuracy alone.



---

### Member 4 — Anavictoria Cavazos

My personal contribution to this assignment was to independently work on the google colab and make sure I understood in depth how it
all makes sense and functions in machine learning. I started by going through each individual task and analyzing the reason for its use
or purpose. For instance, after I completed task 1 I understood how to read and input the confusion_matrix as well as the heatmap to 
properly see which parts were true positive and which were true negative. 

As I worked through the lab I was then able to notice the connection between splitting the data and then using that to create a cross 
validation to properly understand how good the model really is. Overall, this assignment help me get a better learning on how to apply
these concepts as I develop or work with other models in the future.



---

### Member 5 — Hashim Sayed Hoosini

My contribution to this lab assignment was working independently on Lab 7 due to a schedule conflict with the rest of the team; however, I consistently followed up and communicated with them through the group chat. I worked on the Lab 7 Google Colab notebook, ran the code according to the instructions, and ensured that I understood the context in depth. Through this lab, I learned that a single metric like accuracy can be misleading, and that it is best practice to evaluate a machine learning model using other robust evaluation techniques. I gained hands-on experience using the confusion matrix, recall, F1-score, precision, and cross-validation. I also learned that in real-world projects, deploying a model based purely on an accuracy score can be incredibly costly if the minority class is heavily misclassified.



---

