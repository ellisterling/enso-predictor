# Predicting ENSO Phases
### Abstract
This project aims to assess the predictability of ENSO phases. To accomplish this, I will develop a Logistic Regression model that classifies the future ENSO phase as either El Nino, La Nina, or Neutral. Success evaluation for this project will depend on a few factors. One, it may not be possible to create an accurate classifier for this problem without analyzing the atmospheric processes that contribute to it. I will begin by assessing if the model can successfully classify a current phase, and if I can achieve reasonable accuracy with that, then I will modify the algorithm to predict 6 months in the future. I will consider this project a success if I can achieve greater than 50 percent accuracy since weather patterns are notoriusly not well understood and difficult to simulate.

### Motivation and Question
NOAA has readily available weather and ocean data, and I wanted to use this data to create a predictive algorithm. ENSO, since it is a large-scale circulation that has relatively strict definitions, seemed like a good candidate to attempt to predict. One of my scientific questions is honestly if machine learning can accurately predict ENSO conditions without a climate model's assistance. Another is how accurate can we make this model. If the model is moderately successful, it could be used to predict ENSO phases and therefore could help prepare communities whose weather is drastically affected by these conditions (e.g. the Indian Monsoon).

### Deliverables
This project's deliverables will consist of the typical Python code and Jupyter Notebook with data visualizations. Additionally, depending on the accuracy of the model, it could include an essay or short reflection about accuracy and future possible integrations/algorithms that could be included.

##### Full Success:
If the project is successful and we are able to predict ENSO conditions most of the time, the deliverable would consist of the source code and a Jupyter notebook with visualizations and some explanation.

##### Partial Success:
If I cannot get the model to predict ENSO conditions 6 months in the future, but can get it to recognize current ENSO conditions, the deliverables would be similar to the full success deliverables but would likely include an essay or short reflection on why the model didn't work and how it could be improved in the future/integrated with other software such as climate models.