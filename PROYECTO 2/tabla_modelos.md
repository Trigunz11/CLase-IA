| Modelo | Hiperparámetros óptimos |
|---|---|
| KNN | `{"clf__n_neighbors": 3, "clf__p": 1, "clf__weights": "distance"}` |
| RandomForest | `{"clf__max_depth": null, "clf__min_samples_leaf": 1, "clf__min_samples_split": 2, "clf__n_estimators": 200}` |
| SVM (rbf/halving) | `{"clf__C": 10, "clf__class_weight": null, "clf__gamma": 0.001}` |
| LogReg | `{"clf__C": 1, "clf__solver": "lbfgs"}` |
| DecisionTree | `{"clf__max_depth": null, "clf__min_samples_leaf": 1, "clf__min_samples_split": 2}` |
| GaussianNB | `{"clf__var_smoothing": 1e-07}` |
