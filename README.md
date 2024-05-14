# Research-gaps-analysis
## Multilingual Hate Speech Detection

Further research is needed to evaluate the performance of deep learning models on multilingual hate speech detection. This could involve collecting and annotating datasets from different languages and evaluating the performance of deep learning models on these datasets.

## Hate Speech Detection in Different Domains and Contexts

Further research is needed to evaluate the performance of deep learning models on hate speech detection in different domains and contexts. This could involve collecting and annotating datasets from different domains and contexts and evaluating the performance of deep learning models on these datasets.

## Real-World Hate Speech Detection

Further research is needed to evaluate the performance of deep learning models on hate speech detection in real-world scenarios, such as online platforms and social media networks. This could involve deploying deep learning models on these platforms and evaluating their performance in detecting hate speech in real-time.


## Journal Paper Used: 
Headline: A systematic review of hate speech automatic detection using natural language processing
Abstract of Journal: 
With the multiplication of social media platforms, which offer anonymity, easy access and online community formation and online debate, the issue of hate speech detection and tracking becomes a growing challenge to society, individual, policy-makers and researchers. Despite efforts for leveraging automatic techniques for automatic detection and monitoring, their performances are still far from satisfactory, which constantly calls for future research on the issue. This paper provides a systematic review of literature in this field, with a focus on natural language processing and deep learning technologies, highlighting the terminology, processing pipeline, core methods employed, with a focal point on deep learning architecture. From a methodological perspective, we adopt PRISMA guideline of systematic review of the last 10 years literature from ACM Digital Library and Google Scholar. In the sequel, existing surveys, limitations, and future research directions are extensively discussed.
Link : https://www.sciencedirect.com/science/article/pii/S0925231223003557?ref=pdf_download&fr=RR-2&rr=88226281ce718a1e


## Dataset Used:
Headline: Hate Speech Detection curated Dataset🤬
About the Data: Social media platforms have become the most prominent medium for spreading hate speech, primarily through hateful textual content. An extensive dataset containing emoticons, emojis, hashtags, slang, and contractions is required to detect hate speech on social media based on current trends. This dataset contains hate speech sentences in English and is confined into two classes, one representing hateful content and the other representing non-hateful content.
	Specifications table
Subject	Natural Language Processing - NLP
Specific subject area	A curated dataset comprising emojis, emoticons, and contractions bundled into two classes, hateful and non-hateful, to detect hate speech in text.
Type of data	Text
Data format	Annotated, Analysed, Filtered Data
Data Article	A curated dataset for hate speech detection on social media text

Data source location	https://data.mendeley.com/datasets/9sxpkmm8xn/1

Value of this Data :
1.	This dataset is useful for training machine learning models to identify hate speech on social media in text. It reflects current social media trends and the modern ways of writing hateful text, using emojis, emoticons, or slang. It will help social media managers, administrators, or companies develop automatic systems to filter out hateful content on social media by identifying a text and categorizing it as hateful or non-hateful speech.
2.	Deep Learning (DL) and Natural Language Processing (NLP) practitioners can be the target beneficiaries as this dataset can be used for detecting hateful speech through DL and NLP techniques. Here the samples are composed of text sentences and labels belonging to two categories “0″ for non-hateful and “1″ for hateful.
3.	Additionally, this data set can be used as a benchmark data set to detect hate speech
4.	The data set is neutralized in such a way that it can be used by anyone as it doesn't include any entities or names which can have an impact or cyber harm on the user that generated the content. Researchers can take advantage of the pre-processed dataset for their projects as it maintains and follows the policy guidelines.
Link: 
https://www.kaggle.com/datasets/waalbannyantudre/hate-speech-detection-curated-dataset/data

 
## Research Gaps: 
1.	Multilingual Hate Speech Detection: 
Further research is needed to evaluate the performance of deep learning models on multilingual hate speech detection. This could involve collecting and annotating datasets from different languages and evaluating the performance of deep learning models on these datasets.
2.	Hate Speech Detection in Different Domains and Contexts:
Further research is needed to evaluate the performance of deep learning models on hate speech detection in different domains and contexts. This could involve collecting and annotating datasets from different domains and contexts and evaluating the performance of deep learning models on these datasets.
3.	Real-World Hate Speech Detection: 
Further research is needed to evaluate the performance of deep learning models on hate speech detection in real-world scenarios, such as online platforms and social media networks. This could involve deploying deep learning models on these platforms and evaluating their performance in detecting hate speech in real-time.


## Explanation and Way to fill the gaps:
•	For the given Research paper, the research gaps could be filled in several ways. One way is to address the need for more multilingual datasets, which are not widely available. These datasets can be collected and annotated by researchers and data enthusiasts.
•	Another approach could be to evaluate the performance of different deep learning models, such as BERT and RoBERTa, on multilingual hate speech detection datasets. This can be done by comparing their performance metrics, such as accuracy, precision, recall, and F1-score.
•	Additionally, further research could be conducted on evaluating the performance of these models in different domains and contexts, such as online platforms, social media networks, and news websites. This could involve evaluating their performance on hate speech detection in real-time scenarios and understanding the factors that contribute to their effectiveness.
•	Another research gap that could be addressed is the need for more diverse datasets. This can be achieved by collecting and annotating datasets from diverse linguistic and cultural backgrounds. These datasets can then be used to train deep learning models for hate speech detection, leading to more accurate and reliable models.
•	Furthermore, the effectiveness of pre-trained models and their ability to adapt to new languages could be investigated. This can be done by fine-tuning pre-trained models on new datasets and evaluating their performance.
•	Finally, the research gaps in the given paper could be addressed by investigating the limitations of current deep learning models in detecting hate speech. This can involve studying the types of hate speech that these models struggle to detect and understanding the reasons behind their inadequacy. This can lead to the development of more effective models and techniques for detecting hate speech.
•	These approaches can be complemented by exploring other aspects of hate speech detection, such as detecting the presence of toxicity and other harmful behaviors in online discussions. This can be done by training deep learning models on datasets containing examples of toxicity and other harmful behaviors. These models can then be used to detect hate speech, toxicity, and other harmful behaviors in online discussions.
•	This approach involves conducting further research in the area of hate speech detection, particularly in multilingual settings, and exploring other aspects of hate speech detection that have not been thoroughly investigated in the literature. It aims to address the research gaps identified in the given Research paper and contribute to the advancement of the field of hate speech detection.


## Code: 
In this notebook, I aim to explore various methods for detecting hateful speech within the dataset.
1.	TF-IDF with Linear Regression model
2.	Bert model with native Pytorch
3.	Fine-tuning a model with the Trainer API

