# SMS Spam Detection

This project aims to classify SMS messages as either **spam** or **ham (non-spam)** using various machine learning techniques. The dataset consists of SMS messages that have been labeled as "spam" or "ham", and the goal is to develop a model that can predict whether a message is spam or not based on its content.

## Dataset

The dataset used in this project is the **SMS Spam Collection Dataset**. It contains SMS messages labeled as **spam** or **ham**, collected for the purpose of studying spam detection techniques. The dataset is available for public use and consists of over 5,000 messages.

### Dataset Overview:
- **Columns**:
  - `label`: The label for the message, either **"ham"** (non-spam) or **"spam"**.
  - `message`: The content of the SMS message.

## Installation

To run this project, you'll need Python and several libraries. You can install the required dependencies using `pip`:

```bash
pip install -r requirements.txt

---
```
## Required Libraries:
- pandas

- numpy

- scikit-learn

- seaborn

- matplotlib

## Results
The model's performance is evaluated on a test set. The accuracy of the model on the test set is reported as part of the evaluation process. You can compare different models to see which one performs better.

## Conclusion
This project demonstrates the process of building a spam detection system for SMS messages using machine learning techniques. By applying natural language processing (NLP) methods such as text cleaning, tokenization, and vectorization, the model can classify messages as spam or ham with high accuracy.

## Future Work
Experiment with more advanced models like Random Forests, SVMs, or Neural Networks for better performance.

Implement deep learning models such as LSTM or BERT for improved results.

Extend the project to detect other types of spam messages (e.g., email, social media).

## License
This project is licensed under the MIT License - see the LICENSE file for details.
