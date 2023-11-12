# Face Recognition - Gender Classification
This repository is used to fulfill the first assignment - Face Recognition from Indonesia AI Bootcamp

## Repository Structure
🔗 Result Team:
- [Slide](https://github.com/dikhaarianda/Gender-FaceRecognition/blob/master/ResultTeam/Slide%20Presentation_CV-1.pdf)
- [GoogleLeNet](https://github.com/dikhaarianda/Gender-FaceRecognition/blob/master/ResultTeam/Model-GoogleLeNet.ipynb)
- [ResNet](https://github.com/dikhaarianda/Gender-FaceRecognition/blob/master/ResultTeam/Model-ResNet.ipynb)
- [VGG](https://github.com/dikhaarianda/Gender-FaceRecognition/blob/master/ResultTeam/Model-VGG.ipynb)

🔗 Self Experiment:
- [Data-Preparation](https://github.com/dikhaarianda/Gender-FaceRecognition/blob/master/DataPreparation.ipynb)
- [Model-Experiment](https://github.com/dikhaarianda/Gender-FaceRecognition/blob/master/Model_Experiment.ipynb)
- [Model-Fix](https://github.com/dikhaarianda/Gender-FaceRecognition/blob/master/Model_Fix.ipynb)

## Report Self-Experiment
*Architecture: **Pytorch VGG-16***

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

### Conclusion
This project demonstrates the effectiveness of the PyTorch VGG-16 architecture in gender classification, even in the presence of an imbalanced dataset. Further improvements and fine-tuning can be explored for enhanced performance.
