# Lab 07 — Model Evaluation
## Group 4 — Reflection Journal

**Course:** ITAI 1371 — Introduction to Machine Learning  
**Lab:** Module 07 — Better Model Evaluation  
**Group:** Group 4

---

### Member 1 — Patrick Rostand Gandjouon Tchassem

**Reflection:**

This lab helped me understand that accuracy alone is not enough to decide whether a machine learning model is good. In our previous lab, we focused more on training models and getting predictions. In this lab, I learned how to evaluate those predictions and understand the mistakes the model makes.

One thing that stood out to me was the confusion matrix. Our model correctly predicted 90 passengers who died and 54 who survived, but it also made 35 incorrect predictions. This helped me see why precision and recall are important. For example, our model had 73% recall for passengers who survived, meaning it missed some of the actual survivors. I now understand that the type of mistake matters depending on the problem we are trying to solve.

I also learned why cross-validation is useful. Our model had about 80% accuracy on the test data, while the average cross-validation score was 78.68%. Seeing these results helped me understand that one train-test split does not always tell the whole story. Cross-validation gives us a better idea of how consistently a model performs on different parts of the data. Overall, this lab improved my understanding of model evaluation and showed me why checking errors is just as important as training the model.

---

### Member 2 — Saimi Manasiya.

In this lab, I learned how to evaluate a machine learning model using different evaluation techniques instead of depending only on accuracy. I worked with a Logistic Regression model using the Titanic dataset to predict whether passengers survived. I learned how to create and interpret a confusion matrix, which helps identify correct and incorrect predictions, including true positives, true negatives, false positives, and false negatives. I also learned about precision, recall, and the F1-score and understood how these metrics help us measure the performance of a classification model in different ways. Additionally, I practiced generating a classification report and performing five-fold cross-validation to check how consistently the model performs on different parts of the dataset. The average cross-validation score was 78.68%. Overall, this lab improved my understanding of model evaluation and taught me why it is important to use multiple evaluation methods to understand a machine learning model's reliability and performance.



---

### Member 3 — Kenneth Kouokam

For Module 07, my focus is interpreting the classification report and understanding what its scores
mean. The main lesson I take from this lab is that a single accuracy number can hide important
differences in a model's predictions. About 80% accuracy sounds encouraging, but it does not explain
which passengers the model identifies well or which mistakes it makes. Looking at each class
separately gives me a more useful way to judge the results.

The difference between precision and recall becomes clearer when I connect the formulas to the
group's reported confusion matrix. The model predicts survival for 69 passengers, and 54 of those
predictions are correct, giving precision of about 78%. However, there are 74 actual survivors, and
the model identifies only 54 of them, giving recall of about 73%. These percentages answer different
questions. Precision asks how often a survival prediction is correct, while recall asks how many of the
actual survivors the model finds.

The 20 missed survivors help explain why accuracy alone is not enough. Those passengers are false
negatives when survival is the positive class. The 15 passengers predicted to survive who actually
died are false positives. Both errors reduce performance, but they describe different weaknesses.
Comparing the two classes also shows that recall is higher for passengers who died, at about 86%.
This means that the overall score does not represent equal performance for both groups, even
though it summarizes all of their predictions together.

F1-score adds another useful perspective because it combines precision and recall using their
harmonic mean. For survivors, the score is about 76%, which reflects both the incorrect survival
predictions and the survivors the model misses. I also see why support belongs in the report: the test
set contains 105 passengers who died and 74 survivors. Knowing those counts gives the
percentages context and reminds me to look at how many examples each score represents.

This lab connects to Module 06 by extending the question from how accurate a classifier is to what
kinds of errors it makes. It also raises a question I would want to explore: could we identify more
survivors without creating too many incorrect survival predictions? The answer would require further
testing rather than assuming one metric tells the whole story. My takeaway is to explain the numbers
in terms of actual predictions and to consider which errors matter for the problem. A useful evaluation
should make both the model's strengths and its limitations understandable.



---

### Member 4 — [Enter Your Full Name]

**Reflection:**



---

### Member 5 — [Enter Your Full Name]

**Reflection:**



---

