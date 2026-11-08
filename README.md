# Placement Predictor: ML Lifecycle

A small end-to-end machine learning project that predicts whether a student
will be placed from their CGPA and IQ. It is built to show the flow of an ML
pipeline, from problem to live app.

**Live demo:** [Placement Predictor: ML Lifecycle](https://placement-predictor-iota-navy.vercel.app/)

![Placement Predictor screenshot](screenshot.png)

## ML lifecycle
A typical ML project follows these stages:

1. Frame the problem
2. Data gathering
3. Preprocessing
4. EDA
5. Feature extraction, scaling and selection
6. Model training and evaluation
7. Testing
8. Model deployment
9. Optimize

This is a small practice project with a mini dataset (100 rows), built to show the
flow of an ML pipeline from start to finish. So I applied only the essential steps
for this data: framing, data gathering, basic preprocessing and EDA, scaling,
training, evaluation, testing and deployment. Heavier stages such as feature
selection and optimization (tuning, cross-validation, model comparison) are not
needed at this scale and are listed as future improvements.

## Tech
Python, scikit-learn (logistic regression, StandardScaler), pandas, Vercel

## Results
- 100 students, 2 features (CGPA, IQ)
- Logistic regression, about 90% accuracy on a 10-row test set (a very small test set, so treat it as a rough guide)

## Source code
All code lives in my main learning repo:

- Web app (frontend + API + saved model):
  [3_Placement_Predictor_ML_LifeCycle/Webpage_Files](https://github.com/MKS-24/ML-Machine-Learning-/tree/main/3_Placement_Predictor_ML_LifeCycle/Webpage_Files)
- Notebook:
  [3_Placement_Predictor_ML_LifeCycle.ipynb](https://github.com/MKS-24/ML-Machine-Learning-/blob/main/3_Placement_Predictor_ML_LifeCycle/3_Placement_Predictor_ML_LifeCycle.ipynb)

## Author
Muhammad Khuzaima Siddiqui

- Portfolio: [my-port-folio-dusky-chi.vercel.app](https://my-port-folio-dusky-chi.vercel.app/)
- GitHub: [MKS-24](https://github.com/MKS-24)
