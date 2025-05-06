# Toxicity-Analysis-of-Social-Media-Texts-Using-Deep-Learning-Models
This project uses  LSTMs and Transformer-based models from Hugging Face to Detect and Analyze Offensive Speech in SOcial media texts. Fine-tuned pre-trained models on the Hate Speech Detection curated dataset from Kaggle.


Project Files
dlp_project LSTM.ipynb: Implements LSTM, Bidirectional LSTM, and LSTM with Dropout.

dlp_project_HF.ipynb: Implements fine-tuning of the DistilBERT model using Hugging Face Transformers.

Dataset:
https://www.kaggle.com/datasets/waalbannyantudre/hate-speech-detection-curated-dataset
The dataset contains labeled news articles:
1: Hate Content
0: Clean Content

Preprocessing includes cleaning text, removing nulls, and tokenization.

Models Used
LSTMs
Transformer | DistilBERT (pretrained model from Hugging Face)

Requirements
bash
Copy
Edit
pip install tensorflow pandas numpy scikit-learn transformers
How to Run
Open the desired notebook (.ipynb) in Jupyter or Colab.

Run all cells sequentially.

Ensure the dataset file is in the correct path if not embedded.

Evaluation Metrics
Accuracy
Precision
Recall
F1-score

# Summary
LSTM models perform well and are lightweight.
Transformer model (DistilBERT) achieves better accuracy but requires more computational resources.

