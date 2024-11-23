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
# For example:
Entailment: "He looked disappointed" → "He was let down."
Neutral: "He tried not to feel guilty" → "He had caused trouble."
Contradiction: "He was excited" → "He was disappointed."
# Languages
The dataset includes 15 languages, such as English, Arabic, Spanish, French, Russian, and others.

# 🛠️ Technologies Used
Programming Languages: Python
Libraries: Hugging Face Transformers, scikit-learn, pandas, NumPy
Models: DeBERTa, MiniLM

# 📊 Results
Model	    Accuracy	Precision	Recall	F1 Score
mDeBERTa	90%	      91%	      90%	    90%
MiniLM	  61%	      61%	      61%	    61%

# 📝 Future Improvements
Developing a web interface for real-time inference.
Improving multilingual preprocessing technique.
