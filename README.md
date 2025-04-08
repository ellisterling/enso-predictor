# Predicting ENSO Phases
### Abstract
This project aims to assess the predictability of ENSO phases. To accomplish this, I will develop a Logistic Regression model that classifies the future ENSO phase as either El Nino, La Nina, or Neutral. Success evaluation for this project will depend on a few factors. One, it may not be possible to create an accurate classifier for this problem without analyzing the atmospheric processes that contribute to it. I will begin by assessing if the model can successfully classify a current phase, and if I can achieve reasonable accuracy with that, then I will modify the algorithm to predict 6 months in the future. I will consider this project a success if I can achieve greater than 50 percent accuracy since weather patterns are notoriusly not well understood and difficult to simulate.

### Motivation and Question
NOAA has readily available weather and ocean data, and I wanted to use this data to create a predictive algorithm. ENSO, since it is a large-scale circulation that has relatively strict definitions, seemed like a good candidate to attempt to predict. One of my scientific questions is honestly if machine learning can accurately predict ENSO conditions without a climate model's assistance. Another is how accurate can we make this model. If the model is moderately successful, it could be used to predict ENSO phases and therefore could help prepare communities whose weather is drastically affected by these conditions (e.g. the Indian Monsoon).

### Deliverables
This project's deliverables will consist of the typical Python code and Jupyter Notebook with data visualizations. Additionally, depending on the accuracy of the model, it could include an essay or short reflection about accuracy and future possible integrations/algorithms that could be included.

##### Full Success:
If the project is successful and we are able to predict ENSO conditions most of the time, the deliverable would consist of the source code and a Jupyter notebook with visualizations and some explanation. This deliverable should include evidence that the model can predict ENSO phases with visualizations included.

##### Partial Success:
If I cannot get the model to predict ENSO conditions 6 months in the future, but can get it to recognize current ENSO conditions, the deliverables would be similar to the full success deliverables but would likely include an essay or short reflection on why the model didn't work and how it could be improved in the future/integrated with other software such as climate models.

### Resources Required
Data is the main resource required here. For this project, we could use NOAA’s Global Marine Dataset in conjunction with Global Precipitation and possibly atmospheric/cloud data from the NOAA Weather Radar dataset. All those datasets can be found [here](https://www.ncdc.noaa.gov/cdo-web/datasets). For our y_train, we could extrapolate El Nino/La Nina/Neutral years from the [Oceanic Nino Index data](https://psl.noaa.gov/data/correlation/oni.data) and the [Southern Oscillation Index data](https://climatedataguide.ucar.edu/climate-data/southern-oscillation-indices-signal-noise-and-tahitidarwin-slp-soi), which gives us data on ENSO conditions back to 1866.

### Learning Goals
In this project, I think one of my main goals is surrounding data processing and cleaning. This project will involve combining multiple datasets, none of which are likely to be optimized for this kind of use. I am excited to explore the process of cleaning up the raw data into something that resembles some of the data we have worked with in this class so far! I am also excited to work through logistic regression with a dataset that might not yield a super high accuracy. I will also get practice implementing logistic regression beyond the blog post that I will do.

### Risk Statement
This is a pretty risky project in terms of scope. Although ENSO is a relatively well known pattern, weather patterns in general are difficult to predict and not very well understood. Also, without implementing some sort of climate model, it may be difficult to identify future ENSO phases based on just the pure data. It is possible that there is not enough of a pattern to the data to identify future ENSO phases. However, there should be enough of a pattern to identify current ENSO phases, so that will be a backup deliverable.

### Ethics Statement
People that have the potential to benefit from this project include scientists studying ENSO as well as people who live in regions where the weather differs drastically based on the ENSO phase such as India (whose monsoon season is determined by ENSO). Potential harm could come from this project in that if it is wrong, and its results are used to prepare for weather conditions, that people could be unprepared for the unexpected phase.

I don't know that the world would be a definitively better place because of this algorithm, but I do think that it would have a positive effect on ENSO research and would add to the applications of machine learning in Earth and Atmospheric Science. This is assuming that ENSO is predictable based on patterns in ocean and weather data. Additionally, it is assuming that this classification algorithm would be better than the highly detailed climate models that simulate atmospheric conditions and circulations. Finally, it assumes that global warming will not alter the patterns of ENSO enough to modify how it would be predicted.

### Tentative Timeline

##### Three-week check in:
At the three-week check in, I will aim to have consolidated the data into one clean dataframe that will be simple to implement Logistic Regression on. I will have been able to do some exploratory plotting, and will have hopefully begun implementing Logistic Regression so that I can get to the point where my model can identify current ENSO conditions.

##### Six-week check in:
At this point, I will have implemented a model that attempts to classify ENSO conditions six months in the future. If this model does not have high accuracy, I will have implemented a model that can successfully classify current ENSO conditions.