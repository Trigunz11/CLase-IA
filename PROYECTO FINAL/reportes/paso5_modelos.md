| Modelo | Accuracy CV (5-fold) | Hiperparámetros óptimos |
|---|---:|---|
| RandomForest | 0.9966 | `{"clf__max_depth": 40, "clf__min_samples_leaf": 1, "clf__min_samples_split": 2, "clf__n_estimators": 400}` |
| KNN | 0.9954 | `{"clf__n_neighbors": 3, "clf__p": 1, "clf__weights": "distance"}` |
| SVM (rbf) | 0.9940 | `{"clf__C": 10, "clf__gamma": 0.001}` |
| LogReg | 0.9933 | `{"clf__C": 1.0, "clf__solver": "lbfgs"}` |
| DecisionTree | 0.9720 | `{"clf__max_depth": null, "clf__min_samples_leaf": 1, "clf__min_samples_split": 2}` |
| GaussianNB | 0.5830 | `{"clf__var_smoothing": 1e-07}` |
