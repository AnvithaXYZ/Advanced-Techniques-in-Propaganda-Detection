# Advanced Techniques in Propaganda Detection

## Project Overview

This project focuses on detecting propaganda in social media content using advanced Natural Language Processing (NLP) techniques. The study particularly emphasizes the challenges of code-switched text, where multiple languages or dialects are used within the same sentence or conversation. By leveraging models like RoBERTa and GPT-4, this project aims to improve the accuracy and effectiveness of propaganda detection in multilingual and cross-lingual contexts.

## Objective

The main objective of this project is to compare various NLP algorithms, ranging from traditional machine learning methods to advanced deep learning techniques, to identify propaganda in digital media. The project seeks to determine the most effective model for handling the complexities of multilingual and code-switched text in propaganda detection.

## Datasets

- **Data Sources:** The data was collected from various platforms, including Twitter and news articles.
- **Data Annotation:** The data was manually annotated for propaganda detection, and cross-validation was performed to ensure accuracy.

## Methodology

1. **Data Collection:** Gathered text data from social media and news sources.
2. **Data Annotation:** Manually annotated the data for propaganda and non-propaganda content.
3. **Data Preprocessing:** Cleaned and prepared the data using Python libraries.
4. **Data Exploration:** Visualized the data to gain insights and understand distributions.
5. **Data Splitting:** Split the dataset into training and testing sets.
6. **Model Selection and Building:**
   - Compared different models including Logistic Regression, BERT, GPT-4, and RoBERTa.
   - Selected RoBERTa as the primary model due to its superior performance in handling multilingual texts.
7. **Model Evaluation:**
   - Evaluated models based on accuracy, precision, and F1-score.
   - RoBERTa outperformed other models, achieving the highest accuracy in detecting propaganda.

## Results

- **Model Comparison:** RoBERTa demonstrated the best performance, particularly in detecting propaganda in code-switched texts.
- **Accuracy Analysis:** RoBERTa achieved a 100% accuracy rate in detecting propaganda, outperforming other models like Logistic Regression and BERT.
- **Propaganda Detection:** The project successfully identified patterns in propaganda dissemination, with the RoBERTa-BiLSTM-CRF model showing significant promise.

## Limitations

- **Scarcity of Annotations:** Limited high-quality annotations for multilingual propaganda detection.
- **Computational Constraints:** Challenges related to computational resources for larger-scale tasks.
- **Imbalanced Datasets:** Addressed using oversampling techniques, but still a limitation.

## Future Scope

- **Expand Annotated Data:** Focus on increasing annotated data, especially in low-resource languages.
- **Improve Models:** Further fine-tuning of models and exploration of more subtle forms of propaganda, including image-based content.
- **Wider Language Scope:** Extend the applicability of the model to languages beyond English.

## Tools and Libraries

- **Python**
- **Pandas** - Data manipulation and analysis.
- **Matplotlib/Seaborn** - Data visualization.
- **Scikit-learn** - Machine learning models.
- **Transformers (Hugging Face)** - Implementation of RoBERTa and other deep learning models.

## Conclusion

This project highlights the potential of advanced NLP techniques, particularly RoBERTa, in effectively detecting propaganda in digital media. The findings contribute to the ongoing development of unbiased and accurate information processing technologies, which are crucial in the fight against misinformation in the digital age.





