DIVA-Digital-Intelligence-Virtual-Agent-
I'm trying to learn to build AI from 0 with the help of other AI's to fully understand.

DIVA Project (Digital Intelligence Virtual Agent) 🤖
Welcome to the DIVA project repository! This project is a learning journey to build an intelligent virtual assistant from scratch. The goal is to understand the fundamental concepts behind Artificial Intelligence (AI), Machine Learning (ML), and Natural Language Processing (NLP) through practical implementation.

Project Status
In Development & Experimentation Phase.

Currently, DIVA is in the active development phase where various models and techniques are being explored to find the best architecture for intent classification.

✨ Main Features (Currently)
Intent Classification: Able to understand and predict user intent from input sentences using Machine Learning models.

Semantic Understanding: Using Word Embedding models (FastText) to understand the meaning of words, not just matching spelling. This allows DIVA to understand synonyms and paraphrasing.

Model Evaluation: Implementation of standard evaluation procedures using Train-Test Split and Accuracy metrics to objectively measure model performance.

Modular & Expandable: The code has been restructured using functions and command mappings to facilitate the addition of new features in the future.

🛠️ Technologies Used
Programming Language: Python 3.x

Environment: Google Colaboratory (Colab)

Machine Learning: Scikit-learn

KNeighborsClassifier (Classification Model)

TfidfVectorizer (Vectorization)

train_test_split, accuracy_score (Model Evaluation)

NLP / Word Embeddings:

fasttext (Pre-trained Model for Indonesian Language)

Others:

numpy

🚀 How to Run
Environment: It is highly recommended to run this notebook in Google Colab to avoid dependency issues and take advantage of free RAM.

Library Installation: Run the first cell in the notebook that contains the following command to install the required libraries:

bash
Copy
Edit
!pip install fasttext scikit-learn
Download Model: Run the cell that is responsible for downloading the FastText model (cc.id.300.bin). This process only needs to be done once per Colab session and may take a few minutes.

Run All: Run all cells sequentially (Runtime > Run all) to load the dataset, train the model, and view the evaluation and testing results.

🗺️ Roadmap & Future Plans
This project will continue to evolve. Some next steps include:

 More Advanced Classification Models: Experimenting with SVM (Support Vector Machines) and simple Neural Networks.

 Advanced Evaluation Metrics: Implementing Precision, Recall, F1-Score, and Confusion Matrix for deeper error analysis.

 Hybrid Architecture: Combining NLP models with Fuzzy Matching as a fallback to handle typos and severe abbreviations.

 Entity Recognition: Teaching DIVA to recognize and extract important information from sentences (e.g., names, locations, dates).

 State Management: Building a more advanced conversational memory system.

👤 Author
Created and developed by: Diva Juan Nur Taqarrub Aka EnVyxS

This project is guided and directed by an "AI Lecturer" from Google.
