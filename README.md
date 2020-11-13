# Machine learning-based prediction of 6 months post-operative Karnofsky Performance Status in glioblastoma patients: capturing the real-life interaction of multiple clinical and oncological factors

**ABSTRACT**

**Background and aim**
Ability to thrive following invasive and intensive treatment is an important parameter to assess in patients with high-grade glioma (HGG), particularly in those with glioblastoma multiforme (GBM), given its dismal prognosis. The Karnofsky Performance Status scale (KPS) is currently used to identify those patients suitable for post-operative radio-chemotherapy: predicting KPS time-trend over a longer timespan can lead to better patient counseling and tailored clinical decision-making. Aim of the present study is to investigate whether machine learning (ML)-based models can reliably predict patients’ KPS status 6-months after surgery.

**Methods**
A cohort of 416 patients undergoing surgery for a histopathologically confirmed GBM were collected from a multicentric database and split into a training and hold-out test set in an 80/20 ratio. Worsening of KPS at 6 months post-surgery (compared with pre-operative KPS score) occurred in 138 patients (33.2%). Relevant pre-, intra- and immediately post-operative variables were selected by a recursive features selection algorithm (BORUTA) and used to build two ML-based predictive models.

**Results**
A Random Forest Classifier and a Random Forest Regressor were trained to predict 6 months post-operative KPS status as a categorical (worsening vs stable/improving) and continuous variables; they achieved, respectively, an area under the curve (AUC) of 0.81 (95% CI: 0.76; 0.84) and a mean absolute error (MAE) of 4.4 (95% CI: 4.0; 4.7). Leveraging the predictive value resulting from the combination of independent variables, the RF classifier outperformed conventional statistics in successfully identifying those patients more likely to experience a worsening KPS 6 months after surgery (AUC improvement of +21%).

**Conclusions**
A robust ML-based prediction model that identifies patients at high risk for worsening of KPS 6 months after surgery was successfully trained and internally validated. Considerable effort remains to improve the interpretation of the results and to clarify the limitations that may arise when these predictions are employed in a patient-centered care context.

<p align="center">
  <img width="1400" height="800" src="https://github.com/valerio-mc/ML-6months-KPS-GBM/blob/master/Fig1.png">
</p>
