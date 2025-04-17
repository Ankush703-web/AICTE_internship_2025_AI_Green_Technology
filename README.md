# 🔥 Forest Fire Detection Using Deep Learning

This project implements a Convolutional Neural Network (CNN) to detect forest fires from image data. Leveraging deep learning techniques, it classifies images into **Fire** and **No Fire** categories to aid early wildfire detection and disaster response systems.

---

## 📁 Dataset

The dataset used for this project is sourced from Kaggle:

🔗 [The Wildfire Dataset on Kaggle](https://www.kaggle.com/datasets/elmadafri/the-wildfire-dataset)

It contains two main classes:
- `Fire`
- `No Fire`

---

## 🛠️ Technologies Used

- **Python**
- **Google Colab**
- **TensorFlow / Keras**
- **NumPy**
- **Matplotlib**
- **Kaggle API** for dataset download
- **GitHub** for version control and collaboration

---

## 📌 Project Structure

```plaintext
├── Forest_Fire_Detection_Using_DL.ipynb  # Main Jupyter Notebook
├── dataset/                              # Fire and No Fire images
├── model/                                # Saved model files (if any)
└── README.md                             # Project documentation

⚙️ How to Run
Clone this repository:

bash
Copy
Edit
git clone https://github.com/your-username/forest-fire-detection.git
cd forest-fire-detection
Open the notebook in Google Colab or Jupyter:

If using Colab, ensure you're connected to a GPU runtime.

Install dependencies (if running locally):

bash
Copy
Edit
pip install tensorflow numpy matplotlib
Use the Kaggle API to download the dataset:

python
Copy
Edit
from kagglehub import dataset_download
dataset_download("elmadafri/the-wildfire-dataset")
Run the entire notebook to train and evaluate the CNN model.

📈 Results
Achieved high accuracy in distinguishing between fire and non-fire images.

Evaluation metrics such as confusion matrix and accuracy plots are included.

Ready for integration into real-time monitoring systems.

🚀 Future Work
Real-time video or drone feed integration.

Use of transfer learning for improved performance.

Deployment via web or mobile interface.


