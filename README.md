# Diabetic-Nephropathy-Risk-Prediction
Machine learning in healthcare aids the humans to process huge and complex medical datasets and then analyse them into clinical insights, leading to increased patient satisfaction. In this project, I tried to implement functionalities of machine learning in healthcare in a single system. Instead of diagnosis, when a disease prediction is implemented using certain machine learning predictive algorithms then healthcare can be made smart. Some cases can occur when early diagnosis of a disease is not within reach. Hence disease prediction can be effectively implemented. As widely said “Prevention is better than cure”, prediction of diseases and epidemic outbreak would lead to an early prevention of an occurrence of a disease. In addition, an automated medical diagnosing system would be useful if the symptoms are ambiguous because including large datasets to the currently known symptoms may illuminate the case. This project mainly focusses on the development of a system or say an immediate medical provision which would incorporate the symptoms collected from multisensory devices and other medical data and store them into a healthcare dataset. This dataset would then be analysed using Linear regression model, Logistic Regression Model, Decision Tree Model and K-Means (Clustering) Model machine learning algorithms to deliver results with maximum accuracy.

Diagnosis of a disease is based on a doctor’s knowledge and experience. But under some circumstances the prediction can be wrong which leads to incorrect treatment to the patient. Hence to confirm if the diagnosis is right, it would be useful if there could be a tool which uses data from several patients to diagnose the disease and its probability of occurrence.

In this project, diseases such as diabetes, kidney diseases, (also can be extended to - breast cancer, cervical cancer, heart disease, hepatitis, liver disorders, lung diseases, Parkinson’s disease, skin diseases, thyroid and vertebral column diseases) are automated for diagnosis. The datasets are downloaded/created, pre-processed and patterns of disease are analysed using several machine learning algorithms. Among the different machine learning algorithms implemented in the tool, the best algorithm is to be selected for diagnosing the disease as per the patient dataset analysis, i.e. based on analysed prediction accuracy.

Machines surpass humans in many tasks, such as playing chess (or more recently Go) or predicting the weather. Even if the machine is as good as a human or a bit worse at a task, there remain great advantages in terms of speed, reproducibility and scaling. A once implemented machine learning model can complete a task much faster than humans, reliably delivers consistent results and can be copied infinitely. Replicating a machine learning model on another machine is fast and cheap. The training of a human for a task can take decades (especially when they are young) and is very costly. A major disadvantage of using machine learning is that insights about the data and the task the machine solves is hidden in increasingly complex models. You need millions of numbers to describe a deep neural network, and there is no way to understand the model in its entirety.

<hr>

[We have collected some of the raw data from healthcare related online sources](https://github.com/AllanSasi/Diabetic-Nephropathy-Risk-Prediction/blob/main/proj-data.csv)

After that we have selected few models for checking the accuracy. We have used four models namely:-
+ Linear regression model
+ Logistic Regression Model
+ Decision Tree Model
+ K-Means (Clustering) Model

<p align="center">
  <img width="460" height="300" src="gif.gif">

<table border="2" cellpadding="4" cellspacing="0">
  <thead>
    <tr>
      <th align="left">
        Disease / Algorithm
      </th>
      <th align="center">
        Linear Regression
      </th>
      <th align="center">
        Logistic Regression
      </th>
      <th align="center">
        Decision Tree
      </th>
      <th align="center">
        K-Means (Clustering)
      </th>
    </tr>
  </thead>
  <tbody>
    <tr valign="top">
      <td>
        Diabetes
      </td>
      <td align="center">
        88.65
      </td>
      <td align="center">
        0.538
      </td>
      <td align="center">
        0.9
      </td>
      <td align="center">
        0.42
      </td>
    </tr>
    <tr valign="top">
      <td>
        Kidney
      </td>
      <td align="center">
        90.78
      </td>
      <td align="center">
        0.923
      </td>
      <td align="center">
        0.3
      </td>
      <td align="center">
        0.06
      </td>
    </tr>
  </tbody>
</table>
</p>

Logistic Regression Model is a good one as accuracy calculated was near about 0.5384 and 0.9230 which is higher than the other models.
On the other hand, for the automated diagnosis to happen on a large and reliable scale, we would need large amounts of medical data for each patient across geographies for all diseases. This feat could involve huge amounts of data collection, data entry, and data storage efforts.
