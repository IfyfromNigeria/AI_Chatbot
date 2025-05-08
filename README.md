# Smart Reply: AI-Powered Chatbot for Context-Aware Customer Review Responses
**Smart Reply** is an AI-powered chatbot designed to generate context-aware responses for customer reviews. It utilizes state-of-the-art transformer models, including T5 and DialoGPT, for sentiment analysis, emotion detection, and text generation.
1. Mount Google Drive & Install Dependencies
To begin, mount your Google Drive and install the necessary Python packages.
2. Datasets: The project uses the following datasets:
Sentiment Analysis: Amazon Reviews 2023 dataset, categorized into six categories.
Emotion Detection: GoEmotions dataset by Google Research and DailyDialog dataset
Customer Chat Interaction: Customer Support on Twitter dataset.
These datasets are loaded and preprocessed to extract relevant columns, clean the text, and save them as CSV files.
3. Data Preprocessing: Data preprocessing involves cleaning the text, normalizing spaces, and removing special characters. After that, the datasets are split into train, validation, and test sets.
4. Model Training:The models for sentiment analysis, emotion detection, and text generation are trained using the T5 and DialoGPT models. The training loop saves the best model based on validation loss.
5. Model Prediction & Evaluation: Once the models are trained, they are used for sentiment classification, emotion detection, and generating context-aware responses to customer reviews.
   The evaluation of the models includes calculating accuracy, F1 score, precision, and recall.
6. Full Automation Process: The pipeline combines sentiment analysis, emotion detection, and text generation to provide dynamic responses based on user input.
   The chatbot is capable of generating responses considering the sentiment and emotion of the input text.
