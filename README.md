# Next-word-prediction-using-RNN

## Objective
####### The objective of this project is to develop a high-accuracy LSTM-based RNN model for next word prediction, aiming to understand and predict word sequences effectively. The model is designed to enhance applications requiring context-aware text prediction, such as autocompletion tools, by providing accurate and contextually relevant word suggestions.


## Code Summary:
1. **Data Preprocessing**: The text data is loaded, tokenized, and transformed into sequences where each sequence consists of a series of words, ending with the target word to be predicted. Categorical encoding is applied to convert words into numerical values that the model can process.
  
2. **Model Architecture**: A sequential neural network model is created using LSTM layers to capture sequential dependencies in text. Dense layers follow to output probabilities for each word in the vocabulary, representing the predicted next word.

3. **Training**: The model is trained on the prepared sequences for a specified number of epochs, optimizing to minimize prediction error and improve accuracy.

4. **Evaluation**: After training, the model's accuracy and perplexity (a measure of prediction confidence) are calculated, indicating its effectiveness in predicting words based on prior context.

In short, this code prepares text data, trains an LSTM model for next word prediction, and evaluates its accuracy and reliability, demonstrating the model's ability to understand and generate contextually appropriate text.


## Key Insights
1. **Model Accuracy** : The high accuracy achieved indicates the model’s suitability for applications requiring context-aware word prediction, such as text autocompletion.
2. **Future Enhancements**: Potential improvements could include using pre-trained embeddings like GloVe or Word2Vec, or switching to Transformer-based models (e.g., GPT) for even better context handling.
3. **Applications**: This model could be integrated into typing assistants, chatbots, or other applications where predictive text helps improve user experience.


## Results
The LSTM-based Recurrent Neural Network (RNN) model demonstrated strong performance in the next word prediction task. The results are summarized as follows:
**Model Accuracy**: The model achieved a high accuracy of 99.57% on the test set after training for 100 epochs. This high accuracy indicates the model’s effectiveness in predicting the next word with minimal errors.
**Perplexity**: The model’s perplexity score on the test set was 1.12, indicating a close alignment between the predicted probabilities and the actual data distribution. This low perplexity value suggests the model has a strong grasp of contextual dependencies within the text data.
