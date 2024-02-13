# Brain-Tumor-Diagnosis

<img width="310" alt="235309204-68caaa9a-f47b-4b2e-8f53-aca277099d80" src="https://github.com/Armin-Abdollahi/Brain-Tumor-Diagnosis/assets/103449830/d2cbfe7e-4746-4d7e-893a-0a6badf8e837">


## Dataset Link

https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection


## Dataset Description

The dataset has 253 samples, which are divided into two classes with tumor and non-tumor. The number of people with brain tumor is 155 and people with non-tumor is 98.




## A summary of the CNN model

![Screenshot (831)](https://github.com/Armin-Abdollahi/Brain-Tumor-Diagnosis/assets/103449830/c6ebbc2b-931b-4b72-9679-c20d8f88c870)

## Training

![Screenshot (832)](https://github.com/Armin-Abdollahi/Brain-Tumor-Diagnosis/assets/103449830/6a3ba16e-8b99-4042-b09e-4e7b14583a55)


- The optimizer is set to Adam.
- The loss function is set to binary cross-entropy, which is used for binary classification problems.
- The evaluation criterion is set to accuracy, which is used to measure the performance of the model during training and testing.
- The batch_size parameter specifies the number of samples per gradient update.
- The epochs parameter specifies the number of iterations in the entire training dataset.
- The validation_data parameter specifies the validation data used during training.
- The model is trained for 22 epochs, which means it is repeated 22 times on the entire training dataset.
- During training, the performance of the model is evaluated based on the validation data. This helps prevent overfitting and ensures that the model generalizes well to new data.










## Results
| Accuracy | Loss |
| --- | --- |
| ![Screenshot (830)](https://github.com/Armin-Abdollahi/Brain-Tumor-Diagnosis/assets/103449830/c088f578-a18e-4dae-8de1-bf5bfebd30a3) | ![Screenshot (829)](https://github.com/Armin-Abdollahi/Brain-Tumor-Diagnosis/assets/103449830/449973e5-7171-45d3-a542-de38f92c60e6) |
