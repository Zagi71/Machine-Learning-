# Vision Trransformers 
# TransferLearning.ipynb has the code used to this project 

Model:
For this project, we utilized a pre-trained Vision Transformer (ViT) model for transfer learning. The
specific architecture used is ViT-B_16, which is a variant of the Vision Transformer model with 16 layers.
We modified the head of the pre-trained ViT model to adapt it for a specific classification task, replacing
the original head with a linear layer with an output size of 100 classes.
Environment:
To run the model, the following Python libraries are required:
PyTorch
TorchVision
tqdm
PIL
Usage:
To run the model and perform inference on new images, follow these step-by-step instructions:
1. Load Pre-trained Model Weights:
a. The pre-trained model weights can be obtained from the provided link.
b. Save the downloaded model weights file ("pretrained_vit_weights.pth") to your local
directory.
2. Load Pre-trained Model:
3. Ensure you have the required Python libraries installed.
4. Load the pre-trained ViT model architecture and modify the head for classification using the
provided code.
5. Load Image for Prediction:
6. Choose an image that you want to classify.
7. Ensure the image is in a supported format (e.g., JPEG, PNG).
8. Store the path to the image for later use.
9. Preprocess the image using the provided preprocessing function.
10. Load the pre-trained model weights using the saved model weights file.
11. Pass the preprocessed image through the model to obtain predictions.
12. Display Results:
13. The model will output the predicted class index and probabilities for the given image.
14. Interpret the results to understand the predicted class and confidence levels.
15. Weight:
16. The pre-trained model weights can be downloaded from the following link:
https://drive.google.com/file/d/1GZh2r7P2q62TZJ9USb-2jHbpQOm7uaIf/view?usp=drive_link
Team Contributions
In this project we were two teammates (Zarghaam Abbas , Abdullah Saeed). We distributed the
work in 4 categories
1) Data Preprocessing
2) Model selection, initialization and loss function selection
3) Optimization selection, training loop, Evaluation
4) Fine tuning and regularization

   This concludes the report for the transfer learning project. For any further inquiries or assistance, please
feel free to contact me via email.
