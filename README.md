The image classification model is constructed using Convolutional Neural Networks (CNNs). The architecture entails three convolutional layers paired with max-pooling layers. Additionally, a dropout layer with a dropout rate of 0.2 is incorporated, where 20% of input units are omitted during training. After this, dense layers are added, two utilizing the Rectified Linear Unit (ReLU) activation function, while the final layer employs the softmax activation function for multiclass classification. To evaluate the model, the sparse categorical crossentropy loss function, accuracy metric, and Adam optimizer are employed.

Training Process:
Data Loading and Preprocessing:
The dataset comprising images of celebrities (e.g., Lionel Messi, Maria Sharapova, etc.) is loaded and resized to a standardized dimension of (128, 128) pixels.
Subsequently, the dataset is segregated into training and testing subsets.
Model Architecture:
The CNN model architecture encompasses convolutional layers, max-pooling layers, a dropout layer, and dense layers.
The model is compiled with the Adam optimizer and sparse categorical crossentropy loss function.
Training:
The model is trained over 20 epochs, utilizing a batch size of 32, utilizing the training dataset.
Training metrics such as accuracy and loss are tracked during the training process.
Evaluation:
Accuracy and Loss Calculation:
During the evaluation phase, accuracy and loss metrics are computed and visualized through graphs.
Model Prediction:
Testing and Predictions:
The trained model is utilized to predict labels for the test dataset.
Predictions and actual labels are stored within a CSV file for further analysis.
Critical Findings:
Accuracy Improvement Insights:
Adjusting learning rates, dropout rates, or modifying the model architecture has shown potential improvements in accuracy.
Experimentation with hyperparameters and architectural modifications could lead to enhanced model performance and increased accuracy on unseen data.
