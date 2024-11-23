# ContradictoryMyDearWatson
# Detecting Contradiction, Entailment and Neutrality using mDeberta and miniLM Models in Multilingual text 

# 📖 Overview
ContradictoryMyDearWatson is a natural language inference (NLI) project that classifies text pairs into three categories: Contradiction, Entailment, and Neutrality. 
The project leverages transformer-based models like DeBERTa and MiniLM for high accuracy and supports multilingual text analysis.

# ✨ Features
Multilingual support for inference tasks.
Transformer models (DeBERTa and MiniLM) for efficient text classification.
Pre-trained and fine-tuned on the Contradictory, My Dear Watson dataset.

# Dataset Description
This project classifies pairs of sentences (premise and hypothesis) into Entailment, Contradiction, or Neutral.
For example:
Entailment: "He looked disappointed" → "He was let down."
Neutral: "He tried not to feel guilty" → "He had caused trouble."
Contradiction: "He was excited" → "He was disappointed."
# Languages
The dataset includes 15 languages, such as English, Arabic, Spanish, French, Russian, and others.

# 🛠️ Technologies Used
Programming Languages: Python
Libraries: Hugging Face Transformers, scikit-learn, pandas, NumPy
Models: DeBERTa, MiniLM

# Requirements
To run this project efficiently, it is recommended to use a GPU or TPU for training the models, especially for larger datasets or deeper models like mDeBERTa and MiniLM.

# 📊 Results
Model: mDeBERTa
Metric	  Score
Accuracy	90%
Precision	91%
Recall	  90%
F1 Score	90%

Model: MiniLM
Metric	  Score
Accuracy	61%
Precision	61%
Recall	  61%
F1 Score	61%

# 📝 Future Improvements
Developing a web interface for real-time inference.
Improving multilingual preprocessing technique.
