# Clone the repository
git clone https://github.com/Abdullah22200/SentimentAnalysisAI.git

# Navigate to the project directory
cd SentimentAnalysisAI

# Install dependencies (ensure you have requirements.txt)
pip install -r requirements.txt
# Create a virtual environment (recommended)
python -m venv venv

# Activate the virtual environment
# For Windows:
venv\Scripts\activate
# For Linux/Mac:
source venv/bin/activate
# Import and use the prediction function
from model import predict_sentiment

# Example usage
print(predict_sentiment("This movie is amazing!"))  # Output: Positive
# Example training command (adjust dataset path)
python train.py --dataset dataset.csv
# Update the repository (pull latest changes)
git pull origin main

# Check Python version
python --version

# Check TensorFlow installation
python -c "import tensorflow as tf; print(tf.__version__)"
tensorflow>=2.10
pandas
numpy
