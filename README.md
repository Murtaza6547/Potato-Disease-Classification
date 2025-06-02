🥔 Potato Disease Classification using CNN – Summary
🔍 Objective:
To build a deep learning model using CNNs to automatically classify potato leaf diseases from images. Common disease classes include:

Early Blight

Late Blight

Healthy

📁 Dataset:
Sourced from PlantVillage Dataset (often via Kaggle)

Contains labeled images of potato leaves

Classes: Potato___Early_blight, Potato___Late_blight, Potato___healthy

🧠 Model Architecture:
Typically a Convolutional Neural Network (CNN) with:

Convolutional Layers

ReLU Activation

MaxPooling Layers

Fully Connected Layers

Dropout (optional)

Softmax Output (for classification)

🧪 Training:
Images resized (e.g., 128x128 or 224x224)

Normalized pixel values

Train-test split (commonly 80-20)

Optimizer: Adam

Loss function: Categorical Crossentropy

Accuracy as evaluation metric

📊 Results:
Accuracy between 95–99% on test data (depending on data size and model tuning)

Confusion matrix and classification report often used for performance evaluation
