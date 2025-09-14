

### Evaluation Metrics
---------

| Model           | Vectorizer      |Regularizer    | Lambda    |Accuracy        | Precision       |   Recall        | F1 Score        | AUC-ROC         |
|:-----------------:|:-----------------:|:-----------------:|:-----------------:|:-----------------:|:-----------------:|:-----------------:|:-----------------:|:-----------------:|
| Logistic Regression    | CountVector     | None     | --- | 94.2  |  81  | 72   |  76    | 0.91  |
| Logistic Regression     | CountVector      | L2     | 1 | 95.9  | 88  | 78   | 83     | 0.94  | 
| Logistic Regression     | CountVector      | L1     | 1 | ***96.4***  | 91  | 79   | ***85***     | ***0.95***  | 
| Logistic Regression     | TfidfVector      | None     | --- | 94.2  | 92  |  59  | 72     | 0.94 |
| Logistic Regression     | TfidfVector      | L2     | 1 | 93.9  | 91  | 57   | 70    | 0.93  | 
| Logistic Regression     | TfidfVector      | L1     | 1 | 93.9  | 96  | 54   | 69     | ***0.95***  | 
| Naive Bayes    | CountVector      | None     | --- | 95.9  | 80  | ***90***   | ***85***     | ---  |
| Naive Bayes    | TfidfVector      | None     | --- | 96  | ***99***  | 69   | 81     | ---  |

---------
