# Face Recognition - Gender Classification
*architecture: **Pytorch VGG-16***


## Report:
- Dataset Count:

    ![Dataset](https://github.com/dikhaarianda/FaceRecognition-VGG16/blob/master/assets/DatsetCount.png)
    ```
    Dataset total: 5.000
    Split dataset: 
        Train: 4.000 | Test: 500 | Validation: 500 
    
    note: Dataset is Imbalance!
    ```

- Training and Validation:

    ![Chart](https://github.com/dikhaarianda/FaceRecognition-VGG16/blob/master/assets/Chart_TrainingValidate.png)
    ```
    Epoch: 10
    Batch Size: 32
    Total Runtime   : ±20 min

    Training Loss   : 0.0002
    Validation Loss	: 0.1037

    Training Accuracy	: 100%
    Validation Accuracy	: 98.60%
    ```

- Classification Report:

    ![Report](https://github.com/dikhaarianda/FaceRecognition-VGG16/blob/master/assets/ClassificationReport.png)
    ```
    note: Because the data is imbalanced, the F1-Score is used as a reference
    ```

- Confusion Matrix:

    ![confusion](https://github.com/dikhaarianda/FaceRecognition-VGG16/blob/master/assets/ConfusionMatrix.png)
    ```
    Correct:
        Male: 195 | Female: 295
    ```

## Conclusion:
This project demonstrates the effectiveness of the PyTorch VGG-16 architecture in gender classification, even in the presence of an imbalanced dataset. Further improvements and fine-tuning can be explored for enhanced performance.
