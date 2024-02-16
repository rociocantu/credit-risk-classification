## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model **1**, Logistic Regression **using raw data**:
  * Balanced Accuracy Score 0.9520479254722232

  *     Confusion Matrix results
            True positive:  18663   
            False positive: 56
            True negative:  563
            False negative: 102

  *                      precision   recall  f1-score   support

           0                1.00      0.99      1.00     18765
           1                0.85      0.91      0.88       619

            accuracy                            0.99     19384
            macro avg       0.92      0.95      0.94     19384
            weighted avg    0.99      0.99      0.99     19384


* Machine Learning Model **2**, Logistic Regression **using raw data and Random Oversampling**:

  * Balanced Accuracy Score 0.9936781215845847

  *     Confusion Matrix results
            True positive:  18649  
            False positive: 4
            True negative:  615
            False negative: 116

  *                      precision   recall  f1-score   support

           0                1.00      0.99      1.00     18765
           1                0.84      0.99      0.91       619

            accuracy                            0.99     19384
            macro avg       0.92      0.99      0.95     19384
            weighted avg    0.99      0.99      0.99     19384

* Machine Learning Model **3**, Logistic Regression **using scaled data and Random Oversampling**:

  * Balanced Accuracy Score 0.9889115309798473

  *     Confusion Matrix results
            True positive:  18652  
            False positive: 10
            True negative:  609
            False negative: 113

  *                      precision   recall  f1-score   support

           0                1.00      0.99      1.00     18765
           1                0.84      0.98      0.91       619

            accuracy                            0.99     19384
            macro avg       0.92      0.99      0.95     19384
            weighted avg    0.99      0.99      0.99     19384

* Machine Learning Model **4**, Logistic Regression **using scaled data and Random Oversampling**:

  * Balanced Accuracy Score 0.9934383134311076

  *     Confusion Matrix results
            True positive:  18640  
            False positive: 4
            True negative:  615
            False negative: 125

  *                      precision   recall  f1-score   support

           0                1.00      0.99      1.00     18765
           1                0.83      0.99      0.91       619

            accuracy                            0.99     19384
            macro avg       0.92      0.99      0.95     19384
            weighted avg    0.99      0.99      0.99     19384
