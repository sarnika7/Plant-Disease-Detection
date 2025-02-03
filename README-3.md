# Plant-disease-detection
This project develops an AI model using deep learning to accurately detect and classify plant diseases from leaf images, offering an efficient and practical tool for farmers and agricultural professionals.

# Technologies:
Python: Core language for implementing the AI model.
OpenCV: For image preprocessing.
TensorFlow/Keras:
  CNN: For feature extraction and classification.
  VGG16: Pre-trained for efficient feature extraction.
  Attention Mechanisms: Highlights key image areas.
Node.js: Enables a robust backend API for processing requests and interacting with the trained AI model.
React.js: Provides an intuitive and user-friendly web interface for user interaction.
Dataset: The PlantVillage dataset with 54,309 images across 38 plant diseases affecting 14 crops, split into 80% training and 20% validation data.

# Workflow:
User Input: Upload leaf images via a React-based web interface.
Preprocessing: Resize and enhance images with OpenCV (Python).
Modeling:
  CNN with VGG16: For feature extraction and classification.
  Attention Mechanisms: For precision enhancement.
Backend Processing: Requests sent to the Node.js backend are processed using Python scripts for model inference.
Output: Real-time disease detection results displayed through the React frontend.
This system enhances accuracy in plant disease detection, benefiting agricultural stakeholders significantly.

# Expected Outcome: 
The final application will feature a React-based web interface where users can upload images of plant leaves. Once an image is uploaded, it will be sent to the Node.js backend, which will invoke Python-based AI model scripts for analysis. The trained deep learning model will determine if the leaf is healthy or shows signs of disease. If a disease is detected, the system will identify the specific issue and deliver the results instantly, along with helpful insights. Designed for speed and simplicity, the application will provide users with quick, reliable feedback to support decision-making.

# Resultant Web Application Overview
Backend Framework: The app is built using Node.js, providing a robust and scalable backend to handle API requests and communicate with Python-based AI model scripts.
Frontend Framework: The user interface is developed using React.js, ensuring a seamless and user-friendly experience.
Image Upload: Users can upload an image of a plant through the web interface.
Model Prediction: The backend invokes Python scripts to preprocess the image and use a pre-trained AI model for predicting plant diseases.
Response: The backend returns a JSON response containing the predicted class of the plant disease and any associated insights.
