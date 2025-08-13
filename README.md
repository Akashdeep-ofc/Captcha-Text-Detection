🔍 Captcha Recognition with CRNN in PyTorch
This project implements an end-to-end deep learning model for automatic captcha text recognition using a Convolutional Recurrent Neural Network (CRNN).
The system can take an image of a captcha and output the predicted text without any manual segmentation.

📌 Highlights
CNN layers for robust visual feature extraction.

Bidirectional LSTM for sequence learning.

CTC loss for alignment-free training.

Works on generated captcha datasets and can be adapted to other image-based text tasks.

🛠 Tech Stack
Language: Python 3.x

Framework: PyTorch

Libraries: Torchvision, NumPy, Pillow, Matplotlib

📂 Files in this Repo
5-Captcha-Text-Recognition-With-CRNN.ipynb   # Main implementation
README.md                                    # Project documentation

🚀 How to Run
Clone the repository
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>

Install dependencies
pip install torch torchvision numpy pillow matplotlib

Run the notebook
jupyter notebook 5-Captcha-Text-Recognition-With-CRNN.ipynb

📊 Example Output
Captcha Image	Predicted Text
x7prq

📜 Notes
The model uses a CRNN architecture: CNN → BiLSTM → CTC Decoder.

Training data can be replaced with your own captcha images for customization.

Can be extended to recognize other forms of distorted or stylized text.


