# Implicit_Hate_Classification
Implemented by ChihYing Huang and Ramón Villar Carreño for an NLP application class, this project focuses on identifying implicit hate comments using machine learning techniques. Leveraging the Latent Hatred dataset by ElSherief et al., we trained a DistilBERT model and enhanced its performance by incorporating the Irony RoBERTa model proposed by Liu et al. Our analysis revealed that the model exhibits better accuracy in detecting irony in affirmative sentences compared to questions. Through manual dataset modifications, we improved irony detection accuracy from 45% to 49%.

Abstract

The increase of hate speech in social media platforms has motivated NLP practitioners, institutions and companies to develop systems aimed at detecting and classifying such content. However, much of this work tends to focus on hate speech that immediately stands out given its level of explicitness, overlooking what lies beneath the surface but still can inflict damage. The latter is what we refer to as implicit hate speech: content that conveys hateful messages in subtler ways - mostly devoid of explicit derogatory language. In this report we will describe in detail the nature of this implicit hate speech, how we trained models to identify and classify it in a more fine grained taxonomy, and analyze some of the challenges arising from this task.
<img width="690" alt="截圖 2024-05-07 晚上10 59 11" src="https://github.com/elsa0713/Implicit_Hate_Classification/assets/73061577/9487e135-182b-4d83-aab4-44c90954a37e">
<img width="690" alt="截圖 2024-05-07 晚上11 00 50" src="https://github.com/elsa0713/Implicit_Hate_Classification/assets/73061577/dbab3280-ce4f-40fe-b1ee-9177e4d5cc6b">
<img width="690" alt="截圖 2024-05-07 晚上11 04 14" src="https://github.com/elsa0713/Implicit_Hate_Classification/assets/73061577/57b71543-2449-4e28-bd72-d98a8648ed7b">

