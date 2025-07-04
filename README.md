# Fake-News-Detection-using-DistilBERT-
This project is a lightweight and fast Fake News Detection system built using DistilBERT, a distilled version of BERT, for binary text classification (Real vs Fake).
It focuses on classifying news headlines (short texts) as real or fake, based on a labeled dataset (Fake.csv and True.csv). The model is trained in Google Colab using Hugging Face Transformers and the Datasets library.
✅ Features:

1) Uses DistilBERT for fast and efficient fine-tuning
2) Headline-level prediction with softmax-based confidence
3) Input your own text and get real-time predictions
4) Runs entirely in Colab — no APIs, no external dependencies

📊 Dataset: Combined Fake.csv and True.csv news headlines .
🧠 Model: distilbert-base-uncased fine-tuned for 2 epochs .
🔍 Output: Binary label — "Real" or "Fake" with confidence score .
