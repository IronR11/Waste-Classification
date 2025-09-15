# ♻️ Waste Classification (CNN + Gradio)

A deep learning project that classifies waste into six categories:  
**Cardboard, Glass, Metal, Paper, Plastic, Trash**.  

The model was trained using **TensorFlow/Keras** in Google Colab and deployed via **Gradio** for interactive testing.  
Currently, the Gradio demo generates a **temporary public link** (since it runs in Colab).  

---

## 📊 Model Performance
- **Training Accuracy:** ~95%  
- **Validation Accuracy:** ~88%  
- Final Model: `waste_classification_final_model.h5`  

---

## 📂 Dataset
This project uses the [Garbage Classification Dataset](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification),  
which contains images in 6 classes: *Cardboard, Glass, Metal, Paper, Plastic, Trash*.  

### 🔽 How to Download

pip install kaggle
kaggle datasets download -d asdasdasasdas/garbage-classification
unzip garbage-classification.zip -d dataset

📂 Repository Structure

waste-classifier/
├── notebooks/
│   ├── Waste_Classification.ipynb
│   ├── Waste_Classification_Final_Model.ipynb
├── app.py                          # Gradio app
├── waste_classification_final_model.h5   # trained CNN model
├── requirements.txt
├── README.md

▶️ Running the App in Colab

Upload waste_classification_final_model.h5 and app.py into Colab.

Install dependencies:

pip install gradio tensorflow pillow
Run the app:

python app.py
You’ll see a temporary Gradio public link


🛠️ Tech Stack

Python
TensorFlow / Keras
NumPy
Pillow
Gradio (for deployment)
Google Colab (training & testing)

📜 License
MIT License


