# CSE676-Project
## Detection of diabetic retinopathy using deep learning

Dataset: https://drive.google.com/file/d/1g9ZNuA8dgneI3453AGeQ-JaPz_0e-FLf/view?usp=sharing
The dataset we used for training is available on this location. We uploaded the dataset in the Google Drive and then imported it in Google Colab by mounting the Google Drive. 

Files description:
- DRdetection2.ipynb: Model training and result evaluation
- model_analysis: Computation of Quadratic Kappa Score and analysing saliency maps using final model
- final_model.h5: Saved final model

To run the python notebook code, follow these steps:
- Upload the dataset to Google Drive
- Open the given .ipynb notebook in Google Colab
- (For model_analysis.ipynb) Upload the saved model file final_model.h5
- Run the cells


### References
- Tensorflow tutorial on transfer learning and fine tuning. https://www.tensorflow.org/guide/keras/transfer_learning
- Quadratic Weighted Kappa functions https://github.com/benhamner/Metrics/blob/master/Python/ml_metrics/quadratic_weighted_kappa.py
- Saliency maps https://towardsdatascience.com/practical-guide-for-visualizing-cnns-using-saliency-maps-4d1c2e13aeca
