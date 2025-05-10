Bollywood Celebrity Predictor is an AI-powered application designed to identify which Bollywood celebrity a user most closely resembles. The project leverages advanced deep learning techniques, using VGGFace (ResNet50) for feature extraction and MTCNN for accurate face detection. By comparing user-uploaded images with a pre-trained database of Bollywood celebrity images, the system calculates cosine similarity to determine the closest match.

The application is built with Streamlit, offering a simple and interactive user interface. Users can upload their images, and the system automatically detects their faces, extracts facial features, and matches them against a celebrity database. The project is optimized for speed and accuracy, making it suitable for real-time deployment on cloud platforms.

🚀 Key Features:
Accurate Face Detection: Utilizes MTCNN for precise face recognition in user images.

Deep Learning-Powered Feature Extraction: Uses VGGFace (ResNet50) for robust and high-dimensional feature representation.

Cosine Similarity Matching: Compares user facial features with celebrity features for accurate identification.

User-Friendly Interface: Streamlit provides a clean and interactive interface for image upload and result display.

Scalable: Can be extended with more celebrity images for broader recognition.

Secure and Private: User images are processed locally, ensuring privacy.

🌐 Use Cases:
Entertainment apps (celebrity look-alike filters).

Social media engagement (shareable results).

Educational demonstrations of face recognition and deep learning.

🔧 Tech Stack:
Deep Learning: VGGFace (ResNet50), MTCNN

Frontend: Streamlit

Backend: Python (TensorFlow, Keras, OpenCV, NumPy, Scikit-Learn)

Deployment: Local or cloud-based (Heroku, AWS, Streamlit Cloud)

