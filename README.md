This project aims to classify BBC news articles data into five distinct categories: Business, Entertainment, Politics, Sport, and Tech. We will leverage three different approaches: DistilBERT-based classification, ALBERT-based classification, and an RNN-based classifier with a Feed-Forward Neural Network (FFN) classification head. The goal is to compare the performance of these models in terms of precision, recall, and F1 score for each of the five classes or categories.

Dataset link:https://www.kaggle.com/datasets/jacopoferretti/bbc-articles-dataset

Steps
1. DistilBERT-Based Classification: Utilizing the DistilBERT model to perform text classification of BBC news articles into five categories. 2. ALBERT-Based Classification: Leveraging the ALBERT model to classify news articles into the same categories. 3. RNN-Based Classification with FFN: Developing and training a custom RNN-based classifier with a Feed-Forward Neural classification head to classify news articles and compare performance metrics.

Workflow
1. User Input and Preprocessing: → Text of BBC news articles is provided, and preprocessing steps are applied to clean and prepare the input for classification models.
2. DistilBERT Model Classification: → The preprocessed text is classified using a fine-tuned DistilBERT model to assign it to one of the five categories.
3. ALBERT Model Classification: → The same preprocessed text is classified using a fine-tuned ALBERT model for further comparison.
4. RNN-FFN Model Classification: → The preprocessed text is processed through an RNN with an FFN classification head to capture sequential dependencies and assign the text to a category.
5. Performance Reporting: → Performance metrics, including precision, recall, and F1 scores for each category, are calculated and compared for all three models.

Technologies Used
- Models: DistilBERT, ALBERT, RNN-FFN - Development Frameworks: PyTorch or TensorFlow - Programming Language: Python
