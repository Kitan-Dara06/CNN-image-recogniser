# CNN-image-recogniser
🧠 Image Classification with Keras
This project demonstrates image classification using a Convolutional Neural Network (CNN) with TensorFlow/Keras. It leverages model training best practices such as ModelCheckpoint and EarlyStopping for efficient and optimal model performance.

🚀 Features
Data augmentation and generator-based training

Checkpointing the best model using val_accuracy

Early stopping to prevent overfitting

Progressive improvement in model performance across training runs

📁 Files

best_model.weights.h5: Saved best weights from training

🧪 Training Summary

Run	Best Val Accuracy	Epoch	Notes
Run 1	67.16%	8	Base model with x_train_generator2
Run 2	72.71%	10	Further training with x_train_generator
Run 3	63.86%	2	Fresh training cycle
📈 Sample Training Output (Truncated)
Epoch 8/10
accuracy: 0.5637 - loss: 1.2463 - val_accuracy: 0.6716 - val_loss: 0.9429
Epoch 10/10
accuracy: 0.6694 - loss: 0.9580 - val_accuracy: 0.7271 - val_loss: 0.7986
🛠 How to Run
Clone the repo

Install dependencies:

bash
Copy
Edit
pip install tensorflow
Run training:

python
Copy
Edit
python train.py
📚 Libraries Used
TensorFlow / Keras

NumPy

Python 3.x

