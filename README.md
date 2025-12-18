NLP Workbench (All-in-One)

NLP Workbench is a desktop-based Python application that integrates core Natural Language Processing techniques into a single, interactive GUI. It supports text ingestion from multiple file formats and enables preprocessing, sentiment analysis, named entity recognition, topic modeling, and supervised text classification with evaluation and visualization tools.

The project emphasizes data science rigor, robust evaluation, and user-friendly design, making it suitable for both academic analysis and practical NLP experimentation.

Features

Multi-format input: .txt, .pdf, .docx, .xlsx, .xls

Text preprocessing: tokenization, stopword removal, lemmatization

Sentiment analysis (TextBlob)

Named Entity Recognition (NER) with custom TECH entities (spaCy + EntityRuler)

Topic Modeling using LDA (with perplexity reporting)

Text Classification (TF-IDF + Linear SVM)

Stratified 5-fold cross-validation

Hold-out test evaluation

Confusion matrix & per-class F1

Explainable AI: top contributing tokens per prediction

Visualizations: metrics plots & topic word bars

Batch classification & CSV export

Automatic report generation (PDF or DOCX)

Asynchronous model training with progress bar

Tech Stack

Python, Tkinter

NLTK, spaCy, TextBlob

scikit-learn

matplotlib

pandas

Hugging Face Datasets

How to Run
pip install -r requirements.txt
python main.py


(Make sure required NLTK and spaCy models are downloaded.)

License & Visibility

Repository: Public (read-only for viewers)

Only authors can push changes

Report shared as PDF (read-only)

