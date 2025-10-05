## AI-based-tomato-plant-disease
This project is an AI-powered system designed to detect and classify tomato plant diseases from leaf images using a Hybrid Convolutional Neural Network (CNN) architecture.
The model aims to assist farmers and researchers in early disease identification to improve crop yield and reduce losses.

## Key Features
> Hybrid CNN architecture for high-accuracy disease classification
> Supports multiple tomato leaf disease categories
> Detailed model evaluation metrics (accuracy, precision, recall)
> Built with TensorFlow, Keras, and OpenCV
> A step toward smart agriculture using AI

## Technologies Used
>Python
>TensorFlow / Keras
>NumPy, Pandas, Matplotlib
>OpenCV
>Google Colab / Jupyter Notebook


## Dataset
The dataset used consists of tomato leaf images divided into multiple disease categories (e.g., Early Blight, Late Blight, Leaf Mold, etc.) and healthy leaves.
You can use the PlantVillage Dataset (Tomato subset) available publicly on Kaggle.
Example:
Kaggle - Tomato Leaf Disease Dataset


## Model Architecture
The Hybrid CNN combines multiple convolutional layers, pooling, and dropout for better generalization.
The model uses ReLU activation, Adam optimizer, and categorical cross-entropy loss for multi-class classification.

Pipeline:
>Load and preprocess image dataset
>Train CNN model
>Evaluate performance
>Predict disease class from test images

## Installation & Setup
>Clone the repository
git clone https://github.com/your-username/AI-Based-Tomato-Plant-Disease-Detection-Using-Hybrid-CNNs.git
cd AI-Based-Tomato-Plant-Disease-Detection-Using-Hybrid-CNNs

>Install dependencies
pip install -r requirements.txt

>Run the model
python main.py


## Results
Metric	Value
Accuracy->	~95%
Precision->	~93%
Recall->	~94%
F1-Score->	~93%


## Future Enhancements
Integrate with mobile app or web dashboard for farmers
Real-time disease detection via camera
Expand to more crops (potato, maize, rice)


## Author
Priya Rani
4th-year Computer Science Engineering Student (Data Science Minor)
📍 Lovely Professional University, Punjab
    Passionate about AI, Data Science, and real-world innovation in agriculture.
    Email: priya212255@gmail.com  

## License
>This project is open-source under the MIT License.
>Feel free to use, modify, and share with credit.
