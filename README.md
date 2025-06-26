# Vitiligo Detection Using Convolutional Neural Networks (CNN)

A deep learning-based project aimed at providing accurate, efficient, and accessible detection of vitiligo through skin image analysis using Convolutional Neural Networks (CNNs). The system integrates a user-friendly web interface allowing real-time skin image classification.

## 🧠 Project Overview

Vitiligo is a skin condition characterized by the loss of pigmentation, forming white patches on the skin. Early detection is crucial for better management and psychological well-being. This project leverages CNNs for automatic vitiligo detection, addressing challenges such as the lack of dermatological services in rural and underserved regions.

## 🎯 Objectives

* Develop a CNN model to classify images as **"Vitiligo"** or **"Healthy Skin"**.
* Build a web application for real-time image uploading and diagnosis.
* Ensure high accuracy, accessibility, and user privacy.
* Provide a scalable and cost-effective solution for early screening.

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS
* **Backend:** Python, Flask
* **Database:** SQLite
* **Libraries & Tools:** TensorFlow/Keras, OpenCV, NumPy, Pandas, Matplotlib, scikit-learn

## 🧬 Methodology

1. **Data Acquisition:** Collect a diverse dataset of vitiligo and non-vitiligo skin images.
2. **Preprocessing:** Resize, normalize, and augment images for training.
3. **Model Design:** Construct a CNN with convolutional, pooling, and fully connected layers.
4. **Training:** Train on a balanced dataset and validate with performance metrics.
5. **Deployment:** Integrate with a Flask web app and deploy for real-time diagnosis.

## 🔍 Features

* Secure **sign-up/login** system for personalized access.
* Real-time **image upload** and analysis.
* Predictive model outputting **“Vitiligo”** or **“Healthy Skin”**.
* Responsive and intuitive web interface.
* **Data privacy** maintained with no personal image storage.

## 🚀 How to Run the Project Locally

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-repo/vitiligo-detection-cnn.git
   cd vitiligo-detection-cnn
   ```

2. **Create Virtual Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the App**

   ```bash
   python app.py
   ```

5. Open `http://127.0.0.1:5000` in your browser.

## 📊 Model Performance Metrics

* **Accuracy:** \~95%
* **Precision & Recall:** Evaluated through standard image classification metrics
* **Real-time prediction latency:** Sub-second on standard hardware

## 📂 Project Structure

```
/vitiligo-detection-cnn
│
├── app.py                  # Flask backend
├── vitiligo_model.h5       # Trained CNN model
├── templates/              # HTML templates (login, upload, results)
├── static/uploads/         # Image uploads
├── users.db                # SQLite database
└── README.md
```

## 🧪 Example Use Case

1. A user logs in via the portal.
2. Uploads a skin image from their device.
3. The image is preprocessed and passed to the CNN model.
4. The result ("Vitiligo" or "Healthy Skin") is shown instantly.

## 💡 Future Enhancements

* Improve model performance with larger datasets.
* Add lesion segmentation and severity grading.
* Extend for other dermatological conditions.
* Host the web app on cloud for broader accessibility.

## 🤝 Contributors

* Nikitha N M
* Sirisha M
* Vineetha N
* Vinutha C M
  **Under the guidance of:** Mrs. Supriya Suresh, Assistant Professor, KSSEM

## 📜 License

This project is developed as part of an academic requirement and may be reused for educational and non-commercial purposes with attribution.

