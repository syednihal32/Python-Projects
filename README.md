CIFAR-10 Image Classification Using CNN
Overview
This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify images from the CIFAR-10 dataset. The CIFAR-10 dataset contains 60,000 color images classified into 10 categories:

🚀 Classes:

Airplane ✈️
Automobile 🚗
Bird 🐦
Cat 🐱
Deer 🦌
Dog 🐶
Frog 🐸
Horse 🐴
Ship 🚢
Truck 🚛
Dataset Details
Dataset: CIFAR-10
Total Images: 60,000
Training Images: 50,000
Testing Images: 10,000
Image Size: 32x32 pixels (RGB)
Number of Classes: 10
Project Workflow
Load and preprocess the dataset (normalize pixel values).
Visualize sample images from the dataset.
Build a CNN model with convolutional and dense layers.
Compile and train the model using the Adam optimizer.
Evaluate performance on the test set.
Visualize training results (accuracy & loss graphs).
Model Architecture
The CNN consists of:
✅ 3 Convolutional layers with ReLU activation
✅ Max-Pooling layers to reduce dimensions
✅ Flatten layer to transform features into a vector
✅ Fully connected Dense layers for classification

Results
📊 Final Test Accuracy: ~71.39% 🎯

📈 The accuracy improves over training epochs, but some overfitting is observed. Further improvements can be made with data augmentation and dropout layers.

Installation & Setup
Clone the repository
bash
Copy
Edit
git clone https://github.com/your-username/cifar10-cnn.git
cd cifar10-cnn
Install dependencies
bash
Copy
Edit
pip install tensorflow matplotlib
Run the script
bash
Copy
Edit
python cifar10_cnn.py
Future Improvements
🔹 Use data augmentation to improve generalization.
🔹 Add batch normalization to stabilize training.
🔹 Implement dropout layers to prevent overfitting.
🔹 Fine-tune the CNN architecture for better accuracy.

Contributing
Feel free to fork this repository, open issues, or submit pull requests to enhance the project!

License
📜 This project is licensed under the MIT License.
