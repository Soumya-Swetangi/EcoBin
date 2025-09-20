♻️ EcoBin – AI Waste Classifier

EcoBin is an AI-powered waste classification system that helps identify Hazardous, Organic, and Recyclable waste using deep learning.
Built with TensorFlow for model training and Streamlit for an interactive web interface.

🚀 Features

✅ Classifies waste into 3 categories: Hazardous, Organic, Recyclable

✅ Uses MobileNetV2 (Transfer Learning) for high accuracy

✅ Streamlit UI with image upload, predictions & confidence graph

✅ Handles class imbalance with class weights

✅ Early stopping to prevent overfitting

✅ Lightweight and easy to deploy



⚙️ Installation

Clone the repo

git clone https://github.com/your-username/EcoBin.git
cd EcoBin


Create a virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows


Install dependencies

pip install -r requirements.txt

📊 Training the Model




Run training:

python model.py


The trained model will be saved as:

waste_classifier.h5

🖥️ Running the Streamlit App
streamlit run app.py


Upload an image of waste

View prediction & confidence bar chart

📌 Example Output

Prediction: 🗑️ Organic Waste

Confidence Chart:

Class	Confidence
Hazardous	0.12
Organic	0.85 ✅
Recyclable	0.03
🔮 Future Improvements

📷 Add real-time webcam support for live detection

🌐 Deploy on Streamlit Cloud / Hugging Face Spaces

📈 Show training history (accuracy/loss plots) in UI

🗂️ Expand dataset for better generalization

🤝 Contributing

Pull requests are welcome! For major changes, open an issue first to discuss what you’d like to change.

📜 License

This project is licensed under the MIT License.
