Paper:01

  

Title:Bangla hate speech detection on social media using attention-based recurrent neural network

Abstract

Hate speech has spread more rapidly through the daily use of technology and, most notably, by sharing your opinions or feelings on social media in a negative aspect. Although numerous works have been carried out in detecting hate speeches in English, German, and other languages, very few works have been carried out in the context of the Bengali language. In contrast, millions of people communicate on social media in Bengali. The few existing works that have been carried out need improvements in both accuracy and interpretability. This article proposed encoder–decoder-based machine learning model, a popular tool in NLP, to classify user’s Bengali comments from Facebook pages. A dataset of 7,425 Bengali comments, consisting of seven distinct categories of hate speeches, was used to train and evaluate our model. For extracting and encoding local features from the comments, 1D convolutional layers were used. Finally, the attention mechanism, LSTM, and GRU-based decoders have been used for predicting hate speech categories. Among the three encoder–decoder algorithms, attention-based decoder obtained the best accuracy (77%).

  
  

Paper 02:

Title: LLM-Based Multi-Task Bangla Hate Speech Detection: Type, Severity, and Target

  

Abstract

Online social media platforms have become central to communication and information exchange, however, they also serve as fertile ground for hate speech, offensive language, and bullying targeting individuals and communities. Such content undermines online safety and inclusion, underscoring the need for reliable detection systems—especially in low-resource languages with limited moderation tools. For Bangla, existing work provides valuable resources and models, however, they are mostly single-task (e.g., binary hate/offense) with narrow coverage of key dimensions such as type, severity, and target. We address these gaps by introducing *the first multi-task* Bangla hate-speech dataset, *BanglaMultiHate*, one of the largest manually annotated dataset to date. Using this resource, we performed a comparative study across different baselines, monolingual pretrained models, and LLMs under zero-shot, few-shot, and LoRA fine-tuning settings. Our findings show that while LoRA-tuned LLMs rival BanglaBERT, culturally grounded pretraining remains crucial for robust performance. Overall, *BanglaMultiHate* establishes a stronger benchmark for hate speech detection in low-resource contexts. All data and scripts are released for reproducibility.

  

Paper:03

  

Title: Reason Based Machine Learning Approach to Detect Bangla Abusive Social Media Comments

  

Abstract

For the study issue of abusive language detection, English is the most commonly employed language. There are just a few works accessible in low-resource languages such as Bangla. People use these sorts of statements on many social media sites. As a result, detection of this type of language is a demand of time. Our goal is to identify this abusive Bangla language in a novel approach. There are some works that use Bengali corpus and transliterated Bengali corpus to detect abusive language. However, in this research, we utilized annotated translated Bengali corpora, and we added a formal justification in each remark for being classified as abusive or non abusive language. For evaluations, we employed a variety of machine learning classifiers where logistic regression achieves 97% accuracy.

  

Paper 04:

  

Title: Multimodal Hate Speech Detection from Bengali Memes and Texts

  

Abstract

Numerous machine learning (ML) and deep learning (DL)-based approaches have been proposed to utilize textual data from social media for anti-social behavior analysis like cyberbullying, fake news detection, and identification of hate speech mainly for highly-resourced languages such as English. However, despite of having a lot of diversity and millions of native speakers, some languages like Bengali are under-resourced, which is due to lack of computational resources for natural language processing (NLP). Similar to other languages, Bengali social media contents also include images along with texts (e.g., multimodal memes are posted by embedding short texts into images on Facebook). Therefore, only the textual data is not enough to judge them since images might give extra context to make a proper judgement. This paper is about hate speech detection from multimodal Bengali memes and texts. We prepared the only multimodal hate speech dataset for-a-kind of problem for Bengali, which we use to train state-of-the-art neural architectures (e.g., Bi-LSTM/Conv-LSTM with word embeddings, ConvNets + pre-trained language models, e.g., monolingual Bangla BERT, multilingual BERT-cased/uncased, and XLM-RoBERTa) to jointly analyze textual and visual information for hate speech detection. Conv-LSTM and XLM-RoBERTa models performed best for texts, yielding F1 scores of 0.78 and 0.82, respectively. As of memes, ResNet-152 and DenseNet-161 models yield F1 scores of 0.78 and 0.79, respectively. As of multimodal fusion, XLM-RoBERTa + DenseNet-161 performed the best, yielding an F1 score of 0.83. Our study suggest that text modality is most useful for hate speech detection, while memes are moderately useful.

  
  

Paper 05:

  

Title:

Bengali Hate Speech Detection in Public Facebook Pages

  

Abstract:

Hate speech is a form of negative communication intended to harm people and communities. Hate speech is quite common in the real world, and it has reached alarming proportions on social media as well. These days our lives have become increasingly reliant on social media platforms, such as Facebook. This is due to the rapid advancement of technology and communication. In Bangladesh, the number of people using social media platforms is also rapidly increasing. In English, detecting hate speech on social media is a difficult task. Comparatively, Bengali is a complicated language with few datasets available. As a result, detection of Bengali hate speech becomes even more challenging. In this paper, we present a new dataset of 10,133 user comments. We have collected them from the comment section of various public Facebook pages. We explore the performance of various machine learning and deep learning models in detecting hate speech. Bengali pre-trained word embeddings from fastText are used to train the models. We are especially interested in Convolutional Neural Network (CNN). To our knowledge it was never used for hate speech detection in binary classification. Another goal of this research is to create a new and large dataset, which will facilitate further research of Bengali Hate Speech Detection. All machine learning and deep learning models performed very well from our experiments. But, Support Vector Machine (SVM) is the one that performed the best among them.

  
  

Paper 06:

  

Title: Toxicity Detection on Bengali Social Media Comments using Supervised Models

  

Abstract:

Social media playing an indispensable role in our daily life providing a public platform to share opinions including threats, spam and vulgar words often referred to as toxic comments. This type of expression depicts the anti-social behavior of the commentators which may hamper the online atmosphere. Filtering such toxic comments by handcrafting rules is cumbersome because they are unstructured and often include misspelled obscene words. Automated machine learning-based models to classify such toxic comments constitute a part of Sentiment Analysis and they are extensively used for the English language; showing promising results than statistical models. Though Bengali is a widely spoken language around the globe, little research works have been done to detect toxic comments in this language. Hence in this scholarly manuscript, we provide a comparative analysis of five supervised learning models (Naive Bayes, Support Vector Machines, Logistic Regression, Convolutional Neural Network, and Long Short Term Memory) to detect toxic Bengali comments from an annotated publicly available dataset. As our research finding, we demonstrate that both the deep learning-based models have outperformed other classifiers by 10% margin where Convolutional Neural Network achieved the highest accuracy of 95.30%.

  
  

Paper 07:

  

Title: BengaliHateCB: A Hybrid Deep Learning Model to Identify Bengali Hate Speech Detection from Online Platform

  

Abstract:

Online issues including hate speech, abusive communications, and harassment have been exacerbated by the rising number of Internet users. People in Bangladesh often face online harassment and threats expressed in Bengali on various social media platforms. Also, there has not been nearly enough investigation into the possibility of Offensive language in Bengali literature. Although finding realistic ways to reduce hate speech in Bengali texts is urgently needed, there is a notable lack of study in the area of Bengali abusive speech detection, despite the widespread detrimental impacts of abusive text on people's well-being. The results of this research provide a method for spotting bad hateful comments in Bengali online profiles. This research provides a methodology to identify potentially manipulative hate speech in Bengali social media postings. The BERT architecture is used to gather characteristics of Bengali texts. The next step in hate speech classification is to use a Convolutional Neural Network (CNN) model including a softMax activation function. We propose a new model, BERT-CNN, that combines both models. On the Bengali Hate Speech from Social Platforms (BD-SHS) dataset, the BERT-CNN model outperformed most baseline architectures, with accuracy, precision, recall, and F1-scores of 95.67%, 93.55%,92.67%, and 94.44%, respectively. According to our research, the method we suggested for spotting hate speech in Bengali writings posted on social networking sites works well, which can lessen online hate comments and foster a more civilized online community.

  

Paper 08:

  

Title : Mitigating Online Harassment: Machine Learning Approaches for Hate Speech Detection in Transliterated Bengali Comments

  

Abstract:

In the era of widespread online communication, the detection of hate speech has become increasingly critical for maintaining a healthy digital discourse. This significance is magnified when considering languages with unique characteristics, such as transliterated Bengali, where challenges in distinguishing hate speech abound. This work undertakes the task of exploring machine learning algorithms to tackle this challenge and contribute to the broader effort of fostering a respectful and inclusive online environment. The study introduces a novel dataset for hate speech detection in transliterated Bengali text, employing two distinct data preprocessing approaches—TF-IDF and Bag of Words. Eight diverse machine learning algorithms are then applied to evaluate their performance under each preprocessing technique. The results showcase the efficacy of specific algorithms, with Multinomial Naive Bayes excelling in the binary dataset and Logistic Regression emerging as a top performer in the multiclass dataset. Despite encountering challenges like imbalanced data and word length distribution, our models demonstrate enhanced precision and recall. This work not only contributes valuable insights to the field but also provides a new dataset, paving the way for future advancements in hate speech detection and model robustness.

  
  

Paper 09:

  

Title: Leveraging RF and BERT for Superior Hate Speech Detection in the Bengali Language

  

Abstract:

The present research utilises the BHSSP dataset, which has 50,000 labelled instances, to use machine learning and deep learning models to offer a hybrid architecture for Bengali hate speech identification. A robust preprocessing pipeline was implemented to address noise, including the removal of duplicates, punctuation, digits, stop words, and emojis. Bangla GloVe embeddings were used for enhanced feature extraction, while models such as Random Forest (RF), Decision Tree (DT), XGBoost (XGB), and Support Vector Machine (SVM) were compared with deep learning approaches like CNN, LSTM, GRU, and BERT. Additionally, hybrid models RF+BERT and GRU+BERT were introduced. Results demonstrate the superiority of BERT-based models, with GRU+BERT achieving an F1-Score of 0.99, effectively capturing the complexities of Bengali hate speech. This work highlights the efficacy of advanced embeddings and hybrid architectures in low-resource linguistic settings and provides a foundation for broader applications in hate speech detection for Bengali and similar languages.

  

Paper 10:

  

Title: Bengali Social Media Post Sentiment Analysis using Deep Learning and BERT Mode

  

Abstract:

Social media platforms such as Facebook, Twitter, and others are becoming incredibly popular for expressing sentiments and thoughts. People use these platforms to express not only their happy moments, but also their feelings when they are depressed. Using sentiment analysis in natural language processing to analyse these social media posts, one’s emotional state can be determined, such as happy, sad, or angry at a particular time. The majority of research in this topic is conducted in English, therefore sentiment analysis from Bengali is not very accurate. So, our goal is to work on this topic using Bengali datasets obtained from various social media posts to improve sentiment detection accuracy. This work can be used to help building a system in our country’s mental health sector. In this research, we first gathered social media data. Then we used a number of feature selection and extraction techniques like Word2Vec, GloVe etc. and applied a number of deep learning model, such as RNN, LSTM, GRU etc. We have also applied hybrid and transformer-based BERT models like CNN-BiLSTM Bangla-BERT, mBERT etc and finally got the highest accuracy of 88.59% for the CNN-BiLSTM hybrid model using the GloVe feature vector.

  
  

Paper: 11

  

Title: Explainable AI: Transformer-based Bangla Hate Speech Detection

  

Abstract:

People spend a tremendous amount of time on social media sites these days, including Instagram, Twitter, Facebook, and YouTube. Anyone may attack an individual or a community via social media, which reduces human respect. Consequently, we detect the Bangla hate speech in this investigation. A challenging endeavor while dealing with low-resource languages like Bangla is the dearth of publicly accessible datasets. We made use of a publicly accessible dataset [1] that has a problem with data imbalance. We processed the raw data using a variety of preprocessing techniques, then we utilized SMOTE to balance the dataset. To categorize the speech as hate speech or non-hate speech, we used machine learning, deep learning, and fine-tuned BanglaBERT. In the end, we used Explainable AI (XAI) to elucidate predictions from models. The results show that BanglaBERT is a transformer-based model beyond conventional methods of machine learning with a 90.89% accuracy rate. We compared our suggested strategy with existing work, and our suggested approach performs better in terms of accuracy.

  

Paper 12:

  

Title: G-BERT: An Efficient Method for Identifying Hate Speech in Bengali Texts on Social Media

  

Abstract:

The rapid increase in Internet users has increased online concerns such as hate speech, abusive texts, and harassment. In Bangladesh, hate text in Bengali is frequently used on various social media platforms to condemn and abuse individuals. However, Research on recognizing hate speech in Bengali texts is lacking. The pervasive negative impact of hate speech on individuals’ well-being and the urgent need for effective measures to address hate speech in Bengali texts have created a significant research gap in the Bengali hate speech detection field. This study suggests a technique for identifying hate speech in Bengali social media posts that may harm individuals’ sentiments. Our approach utilizes the Bidirectional Encoder Representations from Transformers (BERT) architecture to extract Bengali text properties, whereas hate speech is categorized using a Gated Recurrent Units (GRU) model with a Softmax activation function. We propose a new model, G-BERT, that combines both models. We compared our model’s performance with several other algorithms and achieved an accuracy, precision, recall, and F1-score of 95.56%, 95.07%, 93.63%, and 92.15%, respectively. Our proposed model outperformed all other classification algorithms tested. Our findings show that the strategy we have suggested is successful in locating hate speech in Bengali texts posted on social media platforms, which can aid in mitigating online hate speech and promoting a more respectful online environment.

  
  

Paper 13:

  

Title: Abusive Bangla comments detection on Facebook using transformer-based deep learning models

  

Abstract

In the era of social networking platforms, user-generated content is flooding every second on online social media platforms like Facebook. So observing and identifying many contents, including threats and sexual harassment, are more accessible than traditional media. Online content with extreme toxicity can lead to online harassment, profanity, personal attacks, and bullying acts. As Bangla is the seventh most spoken language worldwide, the utilization of Bangla language in Facebook has raised current times. The use of abusive comments on Facebook with Bangla also has increased alarmingly, but the research regarding this is very low. In this research work, we concentrate on identifying abusive comments of Bangla language in social media (Facebook) that can filter out at the primitive stage of social media’s affixing. To classify abusive comments swiftly and precisely, we apply transformer-based deep neural network models. We employ pre-training language architectures, BERT (Bidirectional Encoder Representations from Transformers) and ELECTRA (Efficiency Learning an Encoder that Classifies Token Replacements Accurately). We have conducted this work with a novel dataset comprises 44,001 comments from multitudinous Facebook posts. In this classification process, we have exhibited an average accuracy, precision, recall, and f1-score to evaluate our proposed models. The outcomes have brought a percipience of our applied BERT and ELECTRA architecture that performs notably with 85.00% and 84.92% test accuracy, respectively.

  

Paper 14:

  

Title: Investigating the Predominance of Large Language Models in Low-Resource Bangla Language over Transformer Models for Hate Speech Detection: A Comparative Analysis

  

Abstract

The rise in abusive language on social media is a significant threat to mental health and social cohesion. For Bengali speakers, the need for effective detection is critical. However, current methods fall short in addressing the massive volume of content. Improved techniques are urgently needed to combat online hate speech in Bengali. Traditional machine learning techniques, while useful, often require large, linguistically diverse datasets to train models effectively. This paper addresses the urgent need for improved hate speech detection methods in Bengali, aiming to fill the existing research gap. Contextual understanding is crucial in differentiating between harmful speech and benign expressions. Large language models (LLMs) have shown state-of-the-art performance in various natural language tasks due to their extensive training on vast amounts of data. We explore the application of LLMs, specifically GPT-3.5 Turbo and Gemini 1.5 Pro, for Bengali hate speech detection using Zero-Shot and Few-Shot Learning approaches. Unlike conventional methods, Zero-Shot Learning identifies hate speech without task-specific training data, making it highly adaptable to new datasets and languages. Few-Shot Learning, on the other hand, requires minimal labeled examples, allowing for efficient model training with limited resources. Our experimental results show that LLMs outperform traditional approaches. In this study, we evaluate GPT-3.5 Turbo and Gemini 1.5 Pro on multiple datasets. To further enhance our study, we consider the distribution of comments in different datasets and the challenge of class imbalance, which can affect model performance. The BD-SHS dataset consists of 35,197 comments in the training set, 7542 in the validation set, and 7542 in the test set. The Bengali Hate Speech Dataset v1.0 and v2.0 include comments distributed across various hate categories: personal hate (629), political hate (1771), religious hate (502), geopolitical hate (1179), and gender abusive hate (316). The Bengali Hate Dataset comprises 7500 non-hate and 7500 hate comments. GPT-3.5 Turbo achieved impressive results with 97.33%, 98.42%, and 98.53% accuracy. In contrast, Gemini 1.5 Pro showed lower performance across all datasets. Specifically, GPT-3.5 Turbo excelled with significantly higher accuracy compared to Gemini 1.5 Pro. These outcomes highlight a 6.28% increase in accuracy compared to traditional methods, which achieved 92.25%. Our research contributes to the growing body of literature on LLM applications in natural language processing, particularly in the context of low-resource languages.

  

Paper 15:

  

Title: Bangla Hate Speech Detection System Using Transformer-Based NLP and Deep Learning Techniques

  

Abstract:

Hate speech is a form of discriminatory communication disrupts community standards and breaches the line of self-limitation, causing harm to others and occasionally leading to cyberbullying. Hate speech spreads hatred toward a person or a particular group based on various characteristics, e.g., race, religion, gender, and so on is referred to as bias. The offensive speech detection system is the frontier where researchers are battling to provide secure internet using natural language processing and machine learning approaches. In this research, we strive to create an automatic Bangla hate speech detection system using natural language processing (NLP) and deep learning approaches. We utilized our custom dataset and some labeled data from an open-access repository in this work. 4,978 data from both sources were merged and implemented in our proposed model. Different data preprocessing techniques, tokenization, stemming, and removal of stopwords have been applied. Four deep learning and NLP-based classifiers have been applied to detect Bangla hate speech. Google API has been employed to convert text from Bangla to English. The emojis were removed from the datasets and the data were translated into Bangla. The GRU and Attention techniques performed best with 98.87% and 98% accuracies, respectively.

  
  

Paper 16:

  

Title: Bengali Cyberbullying Detection in Social Media Comments Using Machine Learning Algorithms

  

Abstract:

Facebook and Twitter are the most popular social media sites where cyberbullying is common. It is defined as the exploitation of digital communication to harass, intimidate, or degrade people, and this may cause serious psychological and social harm. Cyberbullying can occur at any time and is more difficult to avoid as opposed to traditional bullying. In this paper, we aim to identify cyberbullying in Bengali social media comments, a lowresource language, and to detect abusive content in depth. To address the problem, we trained and evaluated five models: Bangla-BERT, m-BERT, LSTM, Bi-LSTM, and SVM with a labelled dataset of Bengali social media comments. The models were trained to label the comments as abusive and non-abusive. The models were trained to classify comments as abusive or non-abusive. Experimental results show that Bangla-BERT achieved the highest accuracy (94 %), followed by m-BERT (91 %), Bi-LSTM (89 %), LSTM (87 %), and SVM (76 %). Although the Bangla-BERT is better than the other models, it can still be improved with bigger and more varied datasets. The study illustrates the usefulness of machine learning in cyberbullying detection in Bengali and also leads to safer online communication, although it also indicates future directions of low-resource language processing.

  

Paper 17:

  

Title: Threat and Abusive Language Detection on Social Media in Bengali Language

  

Abstract:

Threat and abusive languages spread quickly through social media which can be controlled if we can detect and remove them. Since there exist many social media like Facebook, Twitter, Instagram etc and a huge number of social media users, we need a robust and effective automatic system to identify threat and abusive languages. In our proposed system Machine Learning and Natural Language Processing techniques have been implemented to build an automatic system. Previous research on Bengali abusive language detection used Multinomial Näıve Bayes (MNB), Support Vector Machine(SVM) algorithms and considered Bengali Unicode characters to build their system. We considered both Unicode emoticons and Unicode Bengali characters as valid input in our proposed system. Besides MNB and SVM algorithm, we implemented Convolutional Neural Network (CNN) with Long Short Term Memory(LSTM). Among three algorithms, SVM with linear kernel performed best with 78% accuracy.

  

Paper 18:

Title: Comparative Analysis of Machine Learning and Deep Learning Models for Bangla Cyberbullying Detection Using LIME for Model Explainability

  

Abstract:

Cyberbullying is a growing concern in the digital age, particularly on social media platforms, with serious psychological impacts such as anxiety, depression, and suicidal thoughts. Although various machine learning and deep learning models have been applied to detect cyberbullying in high-resource languages like English, limited research exists for low-resource languages such as Bangla. This study addresses these gaps by developing a custom Bangla cyberbullying dataset comprising 3,178 manually labeled comments categorized as bullying or non-bullying. We comparative analysis of performance several traditional machine learning models including Logistic Regression, SVM, and Random Forest and deep learning models such as LSTM, BiLSTM, GRU, CNN, and their hybrid combinations. Among these, the LSTM model achieved the highest accuracy of 87%, outperforming both traditional and other deep learning models. To enhance transparency, we applied Explainable AI using LIME, allowing insight into the model’s decision-making process. This study contributes robust, interpretable framework for Bangla cyberbullying detection, and future research.

  
  

Paper 19:

  

Title: Bengali Cyberbullying Detection in Social Media Using Machine Learning Algorithms

  

Abstract:

Social media has become more prevalent and it is now fairly easy to communicate with people online. Social network users have many options to cooperate, interact positively, and exchange information. The same system might create a toxic environment that can create an unpleasant environment for online abuse and bullies. Young adults and celebrities are vulnerable to online abuse more often. That's why cyberbullying should be identified and eliminated from social media because it may significantly lead to psychological as well as emotional suffering. By utilizing Natural Language Processing (NLP), Machine Learning (ML), as well as Deep Learning Models based on Transformers like BERT, we can identify patterns in social media texts used by bullies and create an automated method that can detect abusive texts. In this study, we proposed a reliable machine-learning model for social media cyberbullying detection in the Bengali language. We applied text preprocessing, followed by feature extraction using the TF-IDF vectorizer. Then, we applied 4 ML algorithms and 1 transformer-based pretrained BERT model and evaluated their performances by different performance metrics. Our study found that BERT worked best compared to other algorithms and achieved an accuracy of 90% and an AUC (Area under the ROC Curve) of 0.96.

  

Paper 20:

  

Title: A robust hybrid machine learning model for Bengali cyber bullying detection in social media

  

Abstract

Social networking platforms give users countless opportunities to share information, collaborate, and communicate positively. The same platform can be extended to a fabricated and poisonous atmosphere that gives an impersonal, harmful platform for online misuse and assault. Cyberstalking is when someone uses an internet system to ridicule, torment, insult, criticize, slander, and discredit a victim while never seeing them. With the growth of social networks, Facebook has become the online arena for bullying. Since the effects could result in a widespread contagion, it is vital to have models and mechanisms in place for the automatic identification and removal of internet cyberbullying data. This paper presents a robust hybrid ML model for cyberbullying detection in the Bengali language on social media. The Bengalibullying proposal involves an effective text preprocessing to make the Bengali text data into a useful text format, feature extraction using the TfidfVectorizer (TFID) to get the beneficial information of text data and resampling by Instance Hardness Threshold (IHT) procedure to balance the dataset to avoid overfitting or underfitting problems. In our experiment, we used the publicly available Bangla text dataset (44,001 comments) and got the highest performance ever published works on it. The model achieved the most elevated accuracy rate of 98.57% and 98.82% in binary and multilabel classification to detect cyberbullying on social media in the Bengali language. Our best performance findings are more effective than any previous effort in identifying and categorizing bullying in the Bengali language. As a result, we might use our model to correctly classify Bengali bullying in online bullying detection systems, protecting people from being the targets of social bullying.


Paper 01:

  

Title: A multi-class cyberbullying classification on image and text in code-mixed Bangla-English social media content

  

Abstract

Social media platforms like Facebook, Instagram, and Twitter are widely used; users frequently share their daily lives by uploading pictures, posts, and videos, which gain significant popularity. However, social media posts often receive a mix of reactions, ranging from positive to negative, and in some instances, negative comments escalate into cyberbullying. Numerous studies have addressed this issue by focusing on cyberbullying classification, primarily through binary classification using multimodal data or targeting either text or image data. This study investigates the identification of multi-class images like No-bullying, Religious, Sexual, and Others using the deep learning pre-trained model MobileNetV2 to detect multiple image labels and achieved an F1-score of 0.86. For categorizing hate comments, we consider multiple classes, including Not Hate, Slang, Sexual, Racial, and Religious-related content. Extensive experiments were conducted on a novel Bengali-English code-mixed dataset, utilizing a combination of advanced transformer models, traditional machine learning techniques, and deep learning approaches to detect multiple hate comment labels. Bangla BERT achieved the highest F1-score of 0.79, followed closely by SVM at 0.78 and BiLSTM with attention at 0.73. These findings underscore the effectiveness of these models in capturing the complexities of code-mixed Bengali-English, offering valuable insights into cyberbullying detection in diverse linguistic contexts. This research contributes essential strategies for improving online safety and fostering respectful digital interactions.

  

Paper 02:

  

Title: BnSentMix: A Diverse Bengali-English Code-Mixed Dataset for Sentiment Analysis

  

Abstract

The widespread availability of code-mixed data in digital spaces can provide valuable insights into low-resource languages like Bengali, which have limited annotated corpora. Sentiment analysis, a pivotal text classification task, has been explored across multiple languages, yet code-mixed Bengali remains underrepresented with no large-scale, diverse benchmark. Code-mixed text is particularly challenging as it requires the understanding of multiple languages and their interaction in the same text. We address this limitation by introducing BnSentMix, a sentiment analysis dataset on code-mixed Bengali comprising 20,000 samples with 4 sentiment labels, sourced from Facebook, YouTube, and e-commerce sites. By aggregating multiple sources, we ensure linguistic diversity reflecting realistic code-mixed scenarios. We implement a novel automated text filtering pipeline using fine-tuned language models to detect code-mixed samples and expand code-mixed text corpora. We further propose baselines using machine learning, neural networks, and transformer-based language models. The availability of a diverse dataset is a critical step towards democratizing NLP and ultimately contributing to a better understanding of code-mixed languages.

  

Paper 03:

  

Title: MixSarc: A Bangla-English Code-Mixed Corpus for Implicit Meaning Identification

  

Abstract:

Bangla-English code-mixing is widespread across South Asian social media, yet resources for implicit meaning identification in this setting remain scarce. Existing sentiment and sarcasm models largely focus on monolingual English or high-resource languages and struggle with transliteration variation, cultural references, and intra-sentential language switching. To address this gap, we introduce MixSarc, the first publicly available Bangla-English code-mixed corpus for implicit meaning identification. The dataset contains 9,087 manually annotated sentences labeled for humor, sarcasm, offensiveness, and vulgarity. We construct the corpus through targeted social media collection, systematic filtering, and multi-annotator validation. We benchmark transformer-based models and evaluate zero-shot large language models under structured prompting. Results show strong performance on humor detection but substantial degradation on sarcasm, offense, and vulgarity due to class imbalance and pragmatic complexity. Zero-shot models achieve competitive micro-F1 scores but low exact match accuracy. Further analysis reveals that over 42\% of negative sentiment instances in an external dataset exhibit sarcastic characteristics. MixSarc provides a foundational resource for culturally aware NLP and supports more reliable multi-label modeling in code-mixed environments.

  

Paper 04:

  

Title: Mixed-Distil-BERT: Code-mixed Language Modeling for Bangla, English, and Hindi

  

Abstract:

One of the most popular downstream tasks in the field of Natural Language Processing is text classification. Text classification tasks have become more daunting when the texts are code-mixed. Though they are not exposed to such text during pre-training, different BERT models have demonstrated success in tackling Code-Mixed NLP challenges. Again, in order to enhance their performance, Code-Mixed NLP models have depended on combining synthetic data with real-world data. It is crucial to understand how the BERT models' performance is impacted when they are pretrained using corresponding code-mixed languages. In this paper, we introduce Tri-Distil-BERT, a multilingual model pre-trained on Bangla, English, and Hindi, and Mixed-Distil-BERT, a model fine-tuned on code-mixed data. Both models are evaluated across multiple NLP tasks and demonstrate competitive performance against larger models like mBERT and XLM-R. Our two-tiered pre-training approach offers efficient alternatives for multilingual and code-mixed language understanding, contributing to advancements in the field.

  

Paper 05:

  

Title: Banglalish on social media: A corpus-based study of Bangla–English code-mixing across four platforms in Bangladesh

  

Abstract

This article reports a 12-month, 120,000-token corpus study of Bangla–English codemixing in Bangladesh’s social-media discourse across Facebook, Twitter, YouTube, and Instagram. Anchored in variational sociolinguistics and contact linguistics, we operationalise code-mixing using the Matrix Language Frame (MLF) model and related structural diagnostics (insertion vs. alternation; borrowing vs. switching), and we quantify platform effects on mixing frequency and structure. Findings indicate stable insertional patterns with Bangla as the matrix language; productive hybrid verb constructions (e.g., comment korchi, share korbo); strong preferences for Bangla determiners with English content nouns (e.g., ei app, amar phone); and domain-specific borrowing of digitalculture vocabulary. Platform affordances condition mixing: Facebook supports longer mixed turns, while Twitter compresses mixing and favours hashtag innovations; YouTube concentrates emphasis and evaluation in comment bursts; Instagram integrates visualtextual cues with searchable, multilingual tags. Demographic correlates (age, education, gender) are treated as tendencies rather than fixed categories. The article contributes (i) a transparent, replicable coding scheme for code-mixing in South Asia, (ii) cross-platform evidence of code-mixing as structured, not ad hoc, and (iii) research/pedagogical/policy implications of treating code-mixing as a regular, rule-bound resource in Bangladesh’s digital communication ecology.

  

Paper 06:

  

Ttile: Enhancing Bangla-English Code-Mixed Sentiment Analysis with Cross-Lingual Word Replacement and Data Augmentation

  

Abstract:

Sentiment analysis employs natural language processing, computational linguistics, and other textual analysis approaches to locate and extract subjective information to assess the text's conveyed attitude or emotional state. The prevalence of internet-based media and online businesses encourages extensive user engagement. Individuals frequently express their opinions, thoughts, ideas, attitudes, feelings, and more using familiar languages on various social media platforms. The majority of individuals tend to articulate their opinions using a combination of languages, often incorporating English with their native tongue. The lack of annotated code-mixed data poses a significant problem for automated sentiment analysis in languages with limited resources such as Bangla. To tackle this challenge, we aim to gather code-mixed content in Bangla and English. Subsequently, we plan to utilize data augmentation techniques to expand the dataset. Following this, we aim to conduct a comparative analysis by employing a variety of machine-learning techniques. This research delves into four common machine learning techniques—Support Vector Machine (SVM), Decision Tree (DT), Stochastic Gradient Descent (SGD), and Random Forest (RF)—employing feature extraction named TF-IDF methods. The experimental results indicate that Random Forest with TF-IDF gained the highest accuracy, reaching 83%, outperforming other techniques.

  
  

Paper 07:

  

Title: Preparing Bengali-English Code-Mixed Corpus for Sentiment Analysis of Indian Languages

  

Abstract:

Analysis of informative contents and sentiments of social users has been attempted quite intensively in the recent past. Most of the systems are usable only for monolingual data and fails or gives poor results when used on data with code-mixing property. To gather attention and encourage researchers to work on this crisis, we prepared gold standard Bengali-English code-mixed data with language and polarity tag for sentiment analysis purposes. In this paper, we discuss the systems we prepared to collect and filter raw Twitter data. In order to reduce manual work while annotation, hybrid systems combining rule based and supervised models were developed for both language and sentiment tagging. The final corpus was annotated by a group of annotators following a few guidelines. The gold standard corpus thus obtained has impressive inter-annotator agreement obtained in terms of Kappa values. Various metrics like Code-Mixed Index (CMI), Code-Mixed Factor (CF) along with various aspects (language and emotion) also qualitatively polled the code-mixed and sentiment properties of the corpus.

  
  

Paper 08:

  

Title: L-Boost: Identifying Offensive Texts From Social Media Post in Bengali

  

Abstract:

Due to the significant increase in Internet activity since the COVID-19 epidemic, many informal, unstructured, offensive, and even misspelled textual content has been used for online communication through various social media. The Bengali and Banglish(Bengali words written in English format) offensive texts have recently been widely used to harass and criticize people on various social media. Our deep excavation reveals that limited work has been done to identify offensive Bengali texts. In this study, we have engineered a detection mechanism using natural language processing to identify Bengali and Banglish offensive messages in social media that could abuse other people. First, different classifiers have been employed to classify the offensive text as baseline classifiers from real-life datasets. Then, we applied boosting algorithms based on baseline classifiers. AdaBoost is the most effective ensemble method called adaptive boosting, which enhances the outcomes of the classifiers. The long short-term memory (LSTM) model is used to eliminate long-term dependency problems when classifying text, but overfitting problems occur. AdaBoost has strong forecasting ability and overfitting problem does not occur easily. By considering these two powerful and diverse models, we propose L-Boost, the modified AdaBoost algorithm using bidirectional encoder representations from transformers (BERT) with LSTM models. We tested the L-Boost model on three separate datasets, including the BERT pre-trained word-embedding vector model. We find our proposed L-Boost’s efficacy better than all the baseline classification algorithms reaching an accuracy of 95.11%.

  
  

Paper 09:

  

Title:

Natural language processing and machine learning based cyberbullying detection for Bangla and Romanized Bangla texts

  

The popularity of social media has been increasing tremendously in recent times and thus cyberbullying towards people has also increased at an alarming rate. Many cyberbullying texts can be found in the comment sections of many well-known Bangladeshi social media personalities YouTube videos. It has the potential to cause severe emotional and psychological distress. Therefore, texts containing cyberbullying should be detected at the earliest stage and prevented from being displayed. In this study, we use natural language processing (NLP) techniques and various machine learning classifiers and presented model for cyberbullying detection in Bangla and Romanized Bangla texts obtained from YouTube video comments. We developed our own datasets using YouTube application programming interface (API) version 3.0. We collected 5000 Bangla comments, as well as 7000 Romanized Bangla comments from videos of different well-known social media personals. These two datasets, as well as a third dataset of 12000 texts which was the combination of the first two datasets were used to train the classifiers. These datasets were used to train machine learning classifiers after being preprocessed using NLP techniques. With an accuracy score of 76%, support vector machine (SVM) outperformed the other classifiers for the first dataset. The highest accuracy scores for the second and third datasets were 84% and 80%, respectively, which were both achieved by multinomial naive Bayes.

  
  

Paper 10:

  

Title: Unmasking Toxicity: A Comprehensive Analysis of Hate Speech Detection in Banglish

  

Abstract:

As the digital landscape expands, the rise of online hate speech presents a pressing challenge, necessitating sophis-ticated tools for effective detection and mitigation. This project focuses on the intricate linguistic landscape of Banglish a hybrid language amalgamating Bengali and English striving to develop robust models tailored to its unique characteristics. The dataset, comprising 5000 Banglish comments categorized into various hate speech types, serves as the foundation for model exploration. Our approach spans a wide variety of models, including traditional machine learning (SVM, Logistic Regression,random forest), advanced deep learning architectures and innovative hybrid models (CNN+BiLSTM). Approaches for feature extraction such word embedding, TF-IDF, and Bag-of-Words and sentiment analysis scores are adapted to the nuances of Banglish. Ethical considerations guide our development, addressing algorithmic bias and user rights. The experimental results provide a nuanced understanding of model performance, in- cluding accuracy (90%), precision, recall, and F1 score. Insights derived from these analyses contribute to the ongoing refinement of hate speech detection methodologies, advancing the field of computational linguistics and ethical artificial intelligence.


Paper 01:

  

Title: Offensive language and hate speech detection using deep learning in football news live streaming chat on YouTube in Thailand

  

Abstract

Today, hate speech is frequently seen on Thai social media platforms such as Facebook, Twitter, and even online video platforms such as YouTube. In live video broadcasts of football news, for example, some Thais expressed hate speech toward opposing football fans and players. This paper presented offensive language and hate speech detection for Thai in YouTube live streaming chat with transformer-based language models by using five BERT models, including BERT, XLM-RoBERTa, DistilBERT, WangchanBERTa, and TwHIN-BERT, which were trained with multilingual languages as well as Thai. In the data labeling process, a two-step data labeling procedure was developed. The first stage involved automated data labeling utilizing the WangchanBERTa model, and the second stage involved manual data labeling conducted by the researchers. We developed text classification models using 11 different positive and negative class ratio datasets to get the most efficient model. In terms of recall and F1 score, the results showed that XLM-RoBERTa performed the best. It yielded an average recall and F1 score of 0.9669 and 0.9530, respectively. However, neither of the five models has significantly different performance. When considering the purpose of the application, DistilBERT is most appropriate. Because of its similar performance to XLM-RoBERTa, it has smaller model sizes and works faster.

  

Paper 02:

Title: A Scoping Review of Research on Online Hate and Sport

  

Abstract

The rise of online hate speech in sports is a growing concern, with fans, players and officials subject to racist, sexist and homophobic abuse (in addition to many other prejudices) via social media platforms. While hate speech and discrimination have always been problems in sports, the growth of social media has seen them exacerbated exponentially. As a consequence, policy makers, sport governing bodies and grassroots anti-hate organisations are largely left playing catch-up with the rapidly shifting realm of online hate. Scholars have attempted to fill this vacuum with research into this topic, but such is the evolving nature of the issue that research has been diverse and fragmentary. We offer a scoping review into the scholarship of online hate in sport in order to encourage and facilitate further research into this urgent issue. Our review will achieve this through offering a comprehensive cataloguing of previously employed methodologies, case studies and conclusions. In doing so, it will not only equip future researchers with a concise overview of existing research in the field, but also illuminate areas and approaches in need of further examination.

  
  

Paper:03

  

Title: Transfer learning approach for identifying negative sentiment in tweets directed to football players

  

Abstract

In recent times, the rising cases of racial abuse toward football players are gravely concerning. This trend is becoming a recurrent decimal on social networks with little or no proactive measures to serve as a deterrent to others in most cases. There was a public outcry due to massive racial abuse remarks targeting some England footballers during the Euro2020 final between England and Italy on social media. This motivated us to investigate and recommend a better solution to the social pandemic through the application of transfer learning. This will go a long way to maintain unity in diversity in the game of football. Tweets with related hashtags to the football match were scraped. The researchers framed this problem as a multi-class classification task. The Valence Aware Dictionary and sEntiment Reasoner (VADER) compound score was employed to label the dataset as positive (POS), negative (NEG), and neutral (NEU). Seven pre-trained models were fine-tuned and corresponding models were built for identifying negative sentiments toward the football players. Three contributions were made – a review of literature on racial abuse targeting footballers, a new dataset to further research in this direction and a robust transformer-based model identified for policing Twitter during football games. Among the models built, the distilled version of Bidirectional Encoder Representations from Transformer (DistilBERT) proved superior with an F1-score of 0.99.

  
  

Paper 04:

Title: Hate speech on social media: behaviour of Portuguese football fans on Facebook

  

ABSTRACT

This article examines how Facebook is shaping the nature of hate speech. The observation field is the Facebook pages of the 18 Portuguese football clubs of the Portuguese League – the main professional competition in the country. Data extraction was performed automatically via Facebook Graph API in the first three months of the 2020/2021 season. The analysed dataset has 5,192 publications and 276,231 fan comments, which registered over 5 million reactions (like, haha, love, sad, wow, etc.). The findings reveal that the volume of hate speech material on Facebook pages has a low incidence. In any case, the most significant comments are racists, xenophobes, and regional antagonisms. These cases are also the ones that have attracted the most reactions from fans.

  
  

Paper 05:

  

Title: Kicking Prejudice: Large Language Models for Racism Classification in Soccer Discourse on Social Media

  

Abstract

In the dynamic space of Twitter, now called X, interpersonal racism surfaces when individuals from dominant racial groups engage in behaviours that diminish and harm individuals from other racial groups. It can be manifested in various forms, including pejorative name-calling, racial slurs, stereotyping, and microaggressions. The consequences of racist speech on social media are profound, perpetuating social division, reinforcing systemic inequalities, and undermining community cohesion. In the specific context of football discourse, instances of racism and hate crimes are well-documented. Regrettably, this issue has seamlessly migrated to the football discourse on social media platforms, especially Twitter. The debate on Internet freedom and social media moderation intensifies, balancing the right to freedom of expression against the imperative to protect individuals and groups from harm. In this paper, we address the challenge of detecting racism on Twitter in the context of football by using Large Language Models (LLMs). We fine-tuned different BERT-based model architectures to classify racist content in the Twitter discourse surrounding the UEFA European Football Championships. The study aims to contribute insights into the nuanced language of hate speech in soccer discussions on Twitter while underscoring the necessity for context-sensitive model training and evaluation. Additionally, Explainable Artificial Intelligence (XAI) techniques, specifically the Integrated Gradient method, are used to enhance transparency and interpretability in the decision-making processes of the LLMs, offering a comprehensive approach to mitigating racism and offensive language in online sports discourses.

  

Paper 06:

  

Title: Racial Biases in Social Media Discussions About Soccer Players

  

Abstract

Recent reports suggest that Black soccer players are often subjected to racial abuse from fans in social media commentary. This study develops a pipeline to collect data from Reddit and Twitter during a four-season period spanning three soccer tournaments, linking posts with mentioned soccer players to investigate the prevalence of racial bias in these posts. Our results highlight subtle forms of racial disparity in social media comments about soccer players. Specifically, we find that Black players tend to receive more toxic comments than White players and that Black players receive more comments related to their physical attributes, in line with previous findings in traditional media coverage. We hope that our research and multiplatform social media datasets help raise awareness of subtle forms of racial disparities in the discussion of athletes and motivate further research to characterize racial bias in soccer.

  
  

Paper 07:

  

Title: Anti-Racism Football Campaigns in Spain and England: Public Discourse and Polarization on X

  

Abstract

The efforts of institutions to eradicate hate both within and beyond the sporting domain have led professional football leagues such as the Premier League and La Liga to develop their own anti-racism campaigns. This study examines X users’ reactions to posts published by each competition under the slogans No Room for Racism and LaLiga VS Racismo. Through a longitudinal, mixed-method analysis, (

= 238) posts and (

= 20,329) responses were examined to assess the evolution of online discourse, the level of hostility, and the degree of polarization surrounding these campaigns. Our findings indicate that hostile discourse tends to emerge sporadically, particularly in response to visible social events rather than as a direct consequence of the campaigns themselves. Qualitative analysis further shows that a substantial proportion of toxic or negative responses does not stem from overtly racist discourse, but from users criticizing the perceived effectiveness or constituency of the campaigns. The results also reveal differences between the two leagues: while the Premier League exhibits a relatively balanced distribution of positive and negative responses, La Liga is characterized by a predominance of negative affect. These findings contribute to the literature on sport, racism and digital polarization by showing how institutional anti-racism campaigns become embedded in broader conflicts over their legitimacy and effectiveness.

Paper 08:

Title: Virtual football violence: exploring the resurgence of football’s deviant leisure cultures in England

ABSTRACT

This paper examines the resurgence of deviant leisure cultures in football, with a focus on virtual football violence. Despite advancements in curbing violence in UK football stadiums, new challenges emerge online. By analysing social media discourse from three English Premier League matches in 2022, the study reveals the prevalence of several forms of virtual violence, including threats of physical and sexual violence, emotional violence, and discriminatory violence. The research highlights the resurgence of ‘traditional’ norms of masculinity, aggression, and misogyny facilitated by anonymity in online spaces. Paradoxically, the results show that fans engage in derogatory language while simultaneously condemning similar actions by others. This phenomenon is particularly evident in the category of discriminatory violence, where comments are frequently challenged, indicating a ‘raising of consciousness’ and a growing intolerance to certain forms of discriminatory language. However, despite some evidence of social consciousness and pushback against discriminatory language, the prevalence of virtual violence remains concerning on multiple levels. This underscores the need for continued efforts to promote respectful discourse and foster inclusive environments online.

  
  

Paper 09:

  

Title: Catching Stray Balls: Football, fandom, and the impact on digital discourse

  

Abstract

This paper examines how emotional responses to football matches influence online discourse across digital spaces on Reddit. By analysing millions of posts from dozens of subreddits, it demonstrates that real-world events trigger sentiment shifts that move across communities. It shows that negative sentiment correlates with problematic language; match outcomes directly influence sentiment and posting habits; sentiment can transfer to unrelated communities; and offers insights into the content of this shifting discourse. These findings reveal how digital spaces function not as isolated environments, but as interconnected emotional ecosystems vulnerable to cross-domain contagion triggered by real-world events, contributing to our understanding of the propagation of online toxicity. While football is used as a case-study to computationally measure affective causes and movements, these patterns have implications for understanding online communities broadly.

  

Paper 10:

  

Title: Sentiment analysis of sports fans’ behaviour: A multimodal review of digital and in-venue fan affect

  

Abstract

Sports spectatorship is fundamentally affective, and the rise of fan-generated data has enabled large-scale computational analysis of fan sentiment and emotion. This paper synthesises 64 studies (2000–2025) that infer fan affect from (i) digital text and online discourse, (ii) broadcast-linked second-screen interaction, and (iii) in-venue or non-textual signals such as crowd audio, video, and wearable sensing. We organise the literature into three modality-based categories: text-centric discourse analytics, second-screen/social-TV behaviour, and in-venue or multimodal sensing. Across studies, a consistent empirical pattern is event-driven synchrony: aggregate affective signals shift rapidly around salient match events and controversy. However, three structural limitations constrain behavioural inference and generalisability: strong platform dependence (especially Twitter/X), overreliance on coarse polarity sentiment, and conceptual slippage between affective expression and behaviour. Research on harmful expressions (e.g., toxicity, hate speech) is expanding and behaviourally relevant, but introduces methodological and ethical challenges. Overall, the literature is effective at detecting affective expression but weaker in linking affect to explicit behavioural outcomes or integrating evidence across modalities. We highlight directions for behaviour-centred, multimodal fan analytics, including improved construct validity, clearer outcome definitions, cross-modality integration, and stronger cross-platform and ethical considerations.

  

Paper 11:

  

Title: An approach to automatic classification of hate speech in sports domain on social media

  

Abstract

Hate Speech encompasses different forms of trolling, bullying, harassment, and threats directed against specific individuals or groups. This phenomena is mainly expressed on Social Networks. For sports players, Social Media is a means of communication with the widest part of their fans and a way to face different cyber-aggression forms. These virtual attacks can harm players, distress them, cause them to feel bad for a long time, or even escalate into physical violence. To date, athletes were not observed as a vulnerable group, so they were not a subject of automatic Hate Speech detection and recognition from content published on Social Media. This paper explores whether a model trained on the dataset from one Social Media and not related to any specific domain can be efficient for the Hate Speech binary classification of test sets regarding the sports domain. The experiments deal with Hate Speech detection in Serbian. BiLSTM deep neural network was learned with different parameters, and the results showed high Precision of detecting Hate Speech in sports domain (96% and 97%) and pretty low Recall.

  
  

Paper 12:

  

Title: Racism, Football Fans, and Online Message Boards: How Social Media Has Added a New Dimension to Racist Discourse in English Football

  

Abstract

This article presents the findings of a discourse analysis carried out from November 2011 to February 2012 on two prominent association football (soccer) message boards that examined fans’ views toward racism in English football. After analyzing more than 500 posts, the article reveals the racist discourse used by some supporters in their online discussions and the extent to which the posts were either supported or contested by fellow posters. The overall findings are that social media sites such as fan message boards have allowed racist thoughts to flourish online, in particular by rejecting multiculturalism and Islam through the presentation of whiteness and national belonging and an outright hostility and resistance toward the Other. Despite this, the majority of posts that contained some form of racist discourse were openly challenged.

  

Paper 13:

Title: Social Media and Online Hate in Sport

A Case Study of Association Football

  

ABSTRACT

The aim of this chapter is to explore the relationship between sport and online hate, via a case study of the work of Tackling Online Hate in Football (TOHIF). In elucidating the challenge of online hate in sport, the chapter showcases how TOHIF is responding to online hate through a range of timely and innovative methodologies and interventions, including accessing large-scale longitudinal empirical datasets, developing tools and techniques to identify and classify online abuse, undertaking over 120 interviews and focus groups with professional male and female footballers from across the UK, a major survey of football fans, interviews with player care professionals, and interviews and educational workshops with sport journalists. The chapter advocates that scholarly research must play a leading role in combatting online hate; initially by deepening the understanding of it, and additionally through shaping the public discourse and education on how to respond to it. We finish this chapter by advocating for some blue sky thinking and identifying some core areas for future investment.

  

Paper 14:

  

Title: The ‘beautiful game’ in a world of hate

Sports journalism, football and social media abuse

  

ABSTRACT

Daniel Kilvington and John Price examine the problems of football-related hate speech and abuse on social media in the context of sports journalism. They endeavour to explain and understand this online hate through a discussion of a number of recent examples of online abuse of English Premier League footballers and an analysis of how the British sports media has reported them. The chapter then critically assesses the response of football authorities and clubs to the problem, arguing both that the collective response to date has failed to properly address the issue and that the sports media has a role in scrutinising and challenging authorities on this topic. Finally, the chapter examines how sports journalists themselves have become the regular subject of online abuse, hate and threats and offers advice for young and aspiring reporters on how best to survive in this online world.


Paper 01:

Title: A Multi-Task Learning Approach to Hate Speech Detection Leveraging Sentiment Analysis

  

Abstract:

The rise of social media platforms has significantly changed the way our world communicates, and part of those changes includes a rise in inappropriate behaviors, such as the use of aggressive and hateful language online. Detecting such content is crucial to filtering or blocking inappropriate content on the Web. However, due to the huge amount of data posted every day, automatic methods are essential for identifying this type of content. Seeking to address this issue, the Natural Language Processing community is increasingly involved in testing a wide range of techniques for hate speech detection. While achieving promising results, these techniques consider hate speech detection as the sole optimization objective, without involving other related tasks such as polarity and emotion classification that are strongly linked to offensive behavior. In this paper, we propose the first Multi-task approach that leverages the shared affective knowledge to detect hate speech in Spanish tweets, using a well-known Transformer-based model. Our results show that the combination of both polarity and emotional knowledge helps to detect hate speech more accurately across datasets.

  

Paper 02:

Title: A Rationale-Guided Multi-Task Learning Framework for Hate Speech Detection

  

Abstract:

Hate Speech Detection (HSD) plays a crucial role in ensuring respectful online communication and preventing the spread of harmful content. However, existing studies on HSD often focus on the overall intent of the target message while overlooking the fine-grained details in the message. We propose a RatIonale-guided multi-taSk lEarning framework (RISE), which frames HSD as the main task and Human Rationales Tagging (HRT) as the auxiliary task. This enables simultaneous message-level understanding and the identification of expressions that trigger human judgments of hate speech, mimicking human cognitive processing to capture fine-grained information and enhance HSD performance. Furthermore, we extend rationale annotations from binary labels to BIO tagging, capturing the positional roles of tokens within rationales. Additionally, we integrate an emoji semantics interpretation module that interprets emoji meanings, enriching contextual information. Extensive experiments demonstrate that RISE outperforms state-of-the-art models, with each component contributing significantly to improved performance.

  

Paper 03:

Title: TAMA: Target-Aware Multilingual Abuse Detection by Cascaded Conditional Multi-Task Learning

  

Abstract

Protecting public figures from online abuse requires models that go beyond post-level classification to determine whether abuse is directed at a designated target, characterize the abuse intent, and extract textual evidence. We introduce a Target-Aware Multilingual Abuse (TAMA), benchmark of 9,386 X (Twitter) posts aimed at public figures, with aligned supervision for (i) tri-class target detection, (ii) 12-way fine-grained abuse type classification, and (iii) phrase-level abusive spans localization. To exploit the hierarchical coupling of these tasks, we propose Cascaded-MTL, a dependency-aware multi-task framework that conditions downstream predictions on upstream beliefs via three lightweight modules: Cross-Task Feature Fusion (CTF), Task-Adaptive Gating (TAG), and Label-Guided Span Detection (LGSD). Experiments across three multilingual encoders show that Cascaded-MTL consistently yields higher average F1 than single-task and standard multi-task training and delivers robust gains on type classification and span localization. The code and the dataset are released here: https://github.com/zgjiangtoby/CASCADED-MTL

  

Paper 04:

Title: Fuzzy Multi-task Learning for Hate Speech Type Identification

  

Abstract

In traditional machine learning, classifiers training is typically undertaken in the setting of single-task learning, so the trained classifier can discriminate between different classes. However, this must be based on the assumption that different classes are mutually exclusive. In real applications, the above assumption does not always hold. For example, the same book may belong to multiple subjects. From this point of view, researchers were motivated to formulate multi-label learning problems. In this context, each instance can be assigned multiple labels but the classifiers training is still typically undertaken in the setting of single-task learning. When probabilistic approaches are adopted for classifiers training, multi-task learning can be enabled through transformation of a multi-labelled data set into several binary data sets. The above data transformation could usually result in the class imbalance issue. Without the above data transformation, multi-labelling of data results in an exponential increase of the number of classes, leading to fewer instances for each class and a higher difficulty for identifying each class. In addition, multi-labelling of data is very time consuming and expensive in some application areas, such as hate speech detection. In this paper, we introduce a novel formulation of the hate speech type identification problem in the setting of multi-task learning through our proposed fuzzy ensemble approach. In this setting, single-labelled data can be used for semi-supervised multi-label learning and two new metrics (detection rate and irrelevance rate) are thus proposed to measure more effectively the performance for this kind of learning tasks. We report an experimental study on identification of four types of hate speech, namely: religion, race, disability and sexual orientation. The experimental results show that our proposed fuzzy ensemble approach outperforms other popular probabilistic approaches, with an overall detection rate of 0.93.

  

Paper: 5

Title: Emotionally Informed Hate Speech Detection: A Multi-target Perspective

  

Abstract

Hate Speech and harassment are widespread in online communication, due to users' freedom and anonymity and the lack of regulation provided by social media platforms. Hate speech is topically focused (misogyny, sexism, racism, xenophobia, homophobia, etc.), and each specific manifestation of hate speech targets different vulnerable groups based on characteristics such as gender (misogyny, sexism), ethnicity, race, religion (xenophobia, racism, Islamophobia), sexual orientation (homophobia), and so on. Most automatic hate speech detection approaches cast the problem into a binary classification task without addressing either the topical focus or the target-oriented nature of hate speech. In this paper, we propose to tackle, for the first time, hate speech detection from a multi-target perspective. We leverage manually annotated datasets, to investigate the problem of transferring knowledge from different datasets with different topical focuses and targets. Our contribution is threefold: (1) we explore the ability of hate speech detection models to capture common properties from topic-generic datasets and transfer this knowledge to recognize specific manifestations of hate speech; (2) we experiment with the development of models to detect both topics (racism, xenophobia, sexism, misogyny) and hate speech targets, going beyond standard binary classification, to investigate how to detect hate speech at a finer level of granularity and how to transfer knowledge across different topics and targets; and (3) we study the impact of affective knowledge encoded in sentic computing resources (SenticNet, EmoSenticNet) and in semantically structured hate lexicons (HurtLex) in determining specific manifestations of hate speech. We experimented with different neural models including multitask approaches. Our study shows that: (1) training a model on a combination of several (training sets from several) topic-specific datasets is more effective than training a model on a topic-generic dataset; (2) the multi-task approach outperforms a single-task model when detecting both the hatefulness of a tweet and its topical focus in the context of a multi-label classification approach; and (3) the models incorporating EmoSenticNet emotions, the first level emotions of SenticNet, a blend of SenticNet and EmoSenticNet emotions or affective features based on Hurtlex, obtained the best results. Our results demonstrate that multi-target hate speech detection from existing datasets is feasible, which is a first step towards hate speech detection for a specific topic/target when dedicated annotated data are missing. Moreover, we prove that domain-independent affective knowledge, injected into our models, helps finer-grained hate speech detection.

  

Paper 06:

Title: Predicting the Type and Target of Offensive Posts in Social Media

  

Abstract

As offensive content has become pervasive in social media, there has been much research in identifying potentially offensive messages. However, previous work on this topic did not consider the problem as a whole, but rather focused on detecting very specific types of offensive content, e.g., hate speech, cyberbulling, or cyber-aggression. In contrast, here we target several different kinds of offensive content. In particular, we model the task hierarchically, identifying the type and the target of offensive messages in social media. For this purpose, we complied the Offensive Language Identification Dataset (OLID), a new dataset with tweets annotated for offensive content using a fine-grained three-layer annotation scheme, which we make publicly available. We discuss the main similarities and differences between OLID and pre-existing datasets for hate speech identification, aggression detection, and similar tasks. We further experiment with and we compare the performance of different machine learning models on OLID.

  

Paper 07:

Title: Vulnerable community identification using hate speech detection on social media

  

Abstract

With the rapid development in mobile computing and Web technologies, online hate speech has been increasingly spread in social network platforms since it's easy to post any opinions. Previous studies confirm that exposure to online hate speech has serious offline consequences to historically deprived communities. Thus, research on automated hate speech detection has attracted much attention. However, the role of social networks in identifying hate-related vulnerable community is not well investigated. Hate speech can affect all population groups, but some are more vulnerable to its impact than others. For example, for ethnic groups whose languages have few computational resources, it is a challenge to automatically collect and process online texts, not to mention automatic hate speech detection on social media. In this paper, we propose a hate speech detection approach to identify hatred against vulnerable minority groups on social media. Firstly, in Spark distributed processing framework, posts are automatically collected and pre-processed, and features are extracted using word n-grams and word embedding techniques such as Word2Vec. Secondly, deep learning algorithms for classification such as Gated Recurrent Unit (GRU), a variety of Recurrent Neural Networks (RNNs), are used for hate speech detection. Finally, hate words are clustered with methods such as Word2Vec to predict the potential target ethnic group for hatred. In our experiments, we use Amharic language in Ethiopia as an example. Since there was no publicly available dataset for Amharic texts, we crawled Facebook pages to prepare the corpus. Since data annotation could be biased by culture, we recruit annotators from different cultural backgrounds and achieved better inter-annotator agreement. In our experimental results, feature extraction using word embedding techniques such as Word2Vec performs better in both classical and deep learning-based classification algorithms for hate speech detection, among which GRU achieves the best result. Our proposed approach can successfully identify the Tigre ethnic group as the highly vulnerable community in terms of hatred compared with Amhara and Oromo. As a result, hatred vulnerable group identification is vital to protect them by applying automatic hate speech detection model to remove contents that aggravate psychological harm and physical conflicts. This can also encourage the way towards the development of policies, strategies, and tools to empower and protect vulnerable communities.

  

Paper 08:

  

Title: Targets and Aspects in Social Media Hate Speech

  

Abstract

Mainstream research on hate speech focused so far predominantly on the task of classifying mainly social media posts with respect to predefined typologies of rather coarse-grained hate speech categories. This may be sufficient if the goal is to detect and delete abusive language posts. However, removal is not always possible due to the legislation of a country. Also, there is evidence that hate speech cannot be successfully combated by merely removing hate speech posts; they should be countered by education and counter-narratives. For this purpose, we need to identify (i) who is the target in a given hate speech post, and (ii) what aspects (or characteristics) of the target are attributed to the target in the post. As the first approximation, we propose to adapt a generic state-of-the-art concept extraction model to the hate speech domain. The outcome of the experiments is promising and can serve as inspiration for further work on the task

  

Paper 09:

Title: Identifying and Categorizing Offensive Language in Social Media

  

Abstract:

Offensive language is pervasive in social media. Individuals frequently take advantage of the perceived anonymity of computer-mediated communication, using this to engage in behavior that many of them would not consider in real life. The automatic identification of offensive content online is an important task that has gained more attention in recent years. This task can be modeled as a supervised classification problem in which systems are trained using a dataset containing posts that are annotated with respect to the presence of some form(s) of abusive or offensive content. The objective of this study is to provide a description of a classification system built for SemEval-2019 Task 6: OffensEval. This system classifies a tweet as either offensive or not offensive (Sub-task A) and further classifies offensive tweets into categories (Sub-tasks B \& C). We trained machine learning and deep learning models along with data preprocessing and sampling techniques to come up with the best results. Models discussed include Naive Bayes, SVM, Logistic Regression, Random Forest and LSTM.

  
  

Paper 10:

Title: Multi-Task Learning with Sentiment, Emotion, and Target Detection to Recognize Hate Speech and Offensive Language

  

Abstract:

The recognition of hate speech and offensive language (HOF) is commonly formulated as a classification task to decide if a text contains HOF. We investigate whether HOF detection can profit by taking into account the relationships between HOF and similar concepts: (a) HOF is related to sentiment analysis because hate speech is typically a negative statement and expresses a negative opinion; (b) it is related to emotion analysis, as expressed hate points to the author experiencing (or pretending to experience) anger while the addressees experience (or are intended to experience) fear. (c) Finally, one constituting element of HOF is the mention of a targeted person or group. On this basis, we hypothesize that HOF detection shows improvements when being modeled jointly with these concepts, in a multi-task learning setup. We base our experiments on existing data sets for each of these concepts (sentiment, emotion, target of HOF) and evaluate our models as a participant (as team IMS-SINAI) in the HASOC FIRE 2021 English Subtask 1A. Based on model-selection experiments in which we consider multiple available resources and submissions to the shared task, we find that the combination of the CrowdFlower emotion corpus, the SemEval 2016 Sentiment Corpus, and the OffensEval 2019 target detection data leads to an F1 =.79 in a multi-head multi-task learning model based on BERT, in comparison to .7895 of plain BERT. On the HASOC 2019 test data, this result is more substantial with an increase by 2pp in F1 and a considerable increase in recall. Across both data sets (2019, 2021), the recall is particularly increased for the class of HOF (6pp for the 2019 data and 3pp for the 2021 data), showing that MTL with emotion, sentiment, and target identification is an appropriate approach for early warning systems that might be deployed in social media platforms.

  

Paper 11:

Title: Improving Hate Speech Type and Target Detection with Hateful Metaphor Features

  

Abstract

We study the usefulness of hateful metaphorsas features for the identification of the type and target of hate speech in Dutch Facebook comments. For this purpose, all hateful metaphors in the Dutch LiLaH corpus were annotated and interpreted in line with Conceptual Metaphor Theory and Critical Metaphor Analysis. We provide SVM and BERT/RoBERTa results, and investigate the effect of different metaphor information encoding methods on hate speech type and target detection accuracy. The results of the conducted experiments show that hateful metaphor features improve model performance for the both tasks. To our knowledge, it is the first time that the effectiveness of hateful metaphors as an information source for hatespeech classification is investigated.

  

Paper 12:

Title: Enhanced Hate Speech Detection through Mean-Pooling in Embedding Fusion

  

Abstract:

The rise of social media has transformed communication globally, but the anonymity it offers often leads to aggressive and offensive language, making it essential to address hate speech, cyberbullying, and harassment. While much research has focused on detecting hate speech, fewer studies have examined the intended audience and linguistic aggression. This paper investigates hate speech detection on Twitter, emphasizing the classification of both target individuals and aggressive behavior in hateful tweets. We propose a fusion-based deep learning model that combines Bidirectional Encoder Representations from Transformers (BERT) and fastText embeddings for enhanced hate speech classification. Our experiments utilize the benchmark dataset from SemEval 2019 Task 5, which is dedicated to the Shared Task for Multilingual Detection of Hate. Our model outperformed all methods proposed by participants in Subtask B–Aggressive Behavior and Target Classification –achieving a 67% F1-score. Additionally, it demonstrated competitive performance in Subtask A–Hate Speech Detection against immigrants and women –matching the top team’s 65% F1-score. Our approach contributes valuable insights into effective embedding fusion for improved hate speech detection on Twitter, along with advancements in classifying the intended audience and linguistic aggression


Paper 01:

Title: BanglaBERT: Language Model Pretraining and Benchmarks for Low-Resource Language Understanding Evaluation in Bangla

  

Abstract

In this work, we introduce BanglaBERT, a BERT-based Natural Language Understanding (NLU) model pretrained in Bangla, a widely spoken yet low-resource language in the NLP literature. To pretrain BanglaBERT, we collect 27.5 GB of Bangla pretraining data (dubbed ‘Bangla2B+’) by crawling 110 popular Bangla sites. We introduce two downstream task datasets on natural language inference and question answering and benchmark on four diverse NLU tasks covering text classification, sequence labeling, and span prediction. In the process, we bring them under the first-ever Bangla Language Understanding Benchmark (BLUB). BanglaBERT achieves state-of-the-art results outperforming multilingual and monolingual models. We are making the models, datasets, and a leaderboard publicly available at https://github.com/csebuetnlp/banglabert to advance Bangla NLP.

  

Paper 02:

  

Title: Bangla-BERT: Transformer-Based Efficient Model for Transfer Learning and Language Understanding

  

e advent of pre-trained language models has directed a new era of Natural Language Processing (NLP), enabling us to create powerful language models. Among these models, Transformer-based models like BERT have grown in popularity due to their cutting-edge effectiveness. However, these models heavily rely on resource-intensive languages, forcing other languages into multilingual models(mBERT). The two fundamental challenges with mBERT become significantly more challenging in a resource-constrained language like Bangla. It was trained on a limited and organized dataset and contained weights for all other languages. Besides, current research on other languages suggests that a language-specific BERT model will exceed multilingual ones. This paper introduces Bangla-BERT,a a monolingual BERT model for the Bangla language. Despite the limited data available for NLP tasks in Bangla, we perform pre-training on the largest Bangla language model dataset, BanglaLM, which we constructed using 40 GB of text data. Bangla-BERT achieves the highest results in all datasets and vastly improves the state-of-the-art performance in binary linguistic classification, multilabel extraction, and named entity recognition, outperforming multilingual BERT and other previous research. The pre-trained model is assessed against several non-contextual models such as Bangla fasttext and word2vec the downstream tasks. Finally, this model is evaluated by transfer learning based on hybrid deep learning models such as LSTM, CNN, and CRF in NER, and it is observed that Bangla-BERT outperforms state-of-the-art methods. The proposed Bangla-BERT model is assessed by using benchmark datasets, including Banfakenews, Sentiment Analysis on Bengali News Comments, and Cross-lingual Sentiment Analysis in Bengali. Finally, it is concluded that Bangla-BERT surpasses all prior state-of-the-art results by 3.52%, 2.2%, and 5.3%.

  

Paper 03:

  

Title: Analyzing Sentiments in eLearning: A Comparative Study of Bangla and Romanized Bangla Text Using Transformers

  

Abstract:

In the modern world, learning is becoming increasingly critical due to rapid technological breakthroughs, which highlight the need for continuous skill development in both the personal and professional spheres. As a result, eLearning is a cutting-edge approach to education that delivers lessons, courses, and instructional materials remotely via digital technology and the Internet. It makes learning more flexible and accessible by enabling users to interact with teachers online and access classes or other content. Sentiment analysis is an eLearning technique that evaluates user opinions, typically via written feedback, to improve the overall quality of instruction in a course. Sentiment analysis for e-learning feedback has been extensively studied in several languages, except Bangla and Romanized Bangla. The three datasets produced were one for Bangla, one for Romanized Bangla, and one for a combination of Bangla and Romanized. Three datasets contained 3178 Bangla, 3090 Romanized Bangla, and 6268 Bangla and Romanized Bangla texts. The feedback has been divided into three categories: positive, negative, and neutral. The validation of the datasets was conducted using Krippendorff’s alpha and Cohen’s kappa metrics, ensuring the reliability and consistency of the dataset annotations. Several techniques were used to train the preprocessed datasets, including transformers, deep learning, machine learning, ensemble learning, and hybrid approaches. Transformer-based algorithms, such as XLM-RoBERTa, outperformed the others in terms of accuracy, achieving the highest values of 89.46% and 85.81% for the Bangla and Combined datasets. At 89.59%, ANN demonstrated exceptional performance on the Romanized Bangla dataset.

  

Paper 04:

Title: Bangla Text Classification using Transformers

  

Abstract:

Text classification has been one of the earliest problems in NLP. Over time the scope of application areas has broadened and the difficulty of dealing with new areas (e.g., noisy social media content) has increased. The problem-solving strategy switched from classical machine learning to deep learning algorithms. One of the recent deep neural network architecture is the Transformer. Models designed with this type of network and its variants recently showed their success in many downstream natural language processing tasks, especially for resource-rich languages, e.g., English. However, these models have not been explored fully for Bangla text classification tasks. In this work, we fine-tune multilingual transformer models for Bangla text classification tasks in different domains, including sentiment analysis, emotion detection, news categorization, and authorship attribution. We obtain the state of the art results on six benchmark datasets, improving upon the previous results by 5-29% accuracy across different tasks.

  

Paper 05:

Title: Dual-Task Learning with XLM-RoBERTa: A Unified Model for Bangla Emotion and Hate Speech Classification

  

Abstract:

Emotion recognition and hate speech detection are crucial NLP tasks for ensuring safe and inclusive digital communication. Although typically addressed separately, these tasks share linguistic and semantic cues, making them suitable for a unified learning approach. We propose a dualtask learning framework based on XLM-RoBERTa that follows a backbone-neck-head design for Bangla text classification. The Backbone uses the XLM-RoBERTa encoder to generate contextual representations, the Neck employs a shared adapter and task-specific adapters to separate task-agnostic and taskspecific features, and the Heads include private MLP branches and linear classifiers for each task. To stabilize joint optimization, we incorporate an uncertainty-based dynamic loss weighting mechanism that automatically balances the contribution of each task during training. The model simultaneously predicts three emotion classes and binary hate speech labels. Experimentally, the model achieves state-of-the-art performance and the model achieves up to 84.54% accuracy, 85.0% F1-score, macro average precision 85.0%, and macro average recall 85.0% for hate speech classification (HSC) and up to 70.2% accuracy, 70.9% F1-score, macro average precision 72.0%, and macro average recall 71.0% for emotion classification (EC) across two repeated runs.

  

Paper 06:

Title: Leveraging Transformer Models in the Cyberbullying Text Classification System for the Low-resource Bengali Language

  

Abstract:

Cyberbullying is when a perpetrator attacks a person or a group of people using insulting or dehumanizing messages sent over digital networks. The availability of the internet and unrestricted usage of social networking sites are the reasons for the sharp rise in cyberbullying occurrences every day. It degrades the victim mentally and socially. Therefore, classifying cyberbullying text is currently an important research topic for scholars. A limited number of articles are recognized for identifying cyberbullying material for the low-resource Bengali language, in contrast to English and other high-resource languages, due to resource limitations. In our research, we have attempted to develop an effective Bengali cyberbullying text classification system. At first, we investigate a benchmark dataset of 44001 entries for five cyberbullying classes: Not Bully, Troll, Sexual, Religious, and Threat. After that, we exploit five cutting-edge transformer models, including multilingual Bidirectional Encoder Representations from Transformers (mBERT), Bangla-BERT-Base, BanglaBERT, DistilmBERT, and XLM-RoBERTa. Finally, we have proposed a new combined-transformer model, Transformer-ensemble, obtaining outstanding results with 87.54% accuracy and 87.52% F1-score. This method outperforms the state-of-the-art approaches for identifying five Bengali cyberbullying classes. Thus, our proposed system can play a vital role in reducing cyberbullying occurrences on digital platforms.

  
  

Paper 07:

  

Title: A Review of Bangla Natural Language Processing Tasks and the Utility of Transformer Models

  

Abstract:

Bangla -- ranked as the 6th most widely spoken language across the world (this https URL), with 230 million native speakers -- is still considered as a low-resource language in the natural language processing (NLP) community. With three decades of research, Bangla NLP (BNLP) is still lagging behind mainly due to the scarcity of resources and the challenges that come with it. There is sparse work in different areas of BNLP; however, a thorough survey reporting previous work and recent advances is yet to be done. In this study, we first provide a review of Bangla NLP tasks, resources, and tools available to the research community; we benchmark datasets collected from various platforms for nine NLP tasks using current state-of-the-art algorithms (i.e., transformer-based models). We provide comparative results for the studied NLP tasks by comparing monolingual vs. multilingual models of varying sizes. We report our results using both individual and consolidated datasets and provide data splits for future research. We reviewed a total of 108 papers and conducted 175 sets of experiments. Our results show promising performance using transformer-based models while highlighting the trade-off with computational costs. We hope that such a comprehensive survey will motivate the community to build on and further advance the research on Bangla NLP.

  
  

Paper 08:

  

Title: Bangla Book Genre Classification: An Advanced Multi-Class Approach Using Transformer-Based Models

  

Abstract:

This paper explores a diverse range of multiclass classification methods for Bangla books, particularly those accessible on digital platforms. Despite being one of the most widely spoken languages with a rich literary heritage, Bangla remains underexplored in content classification due to the lack of a comprehensive dataset. We introduce an expanded dataset of 46,429 books classified into 14 distinct categories. The categories are Education, Fiction, Non-Fiction, Poetry, Children’s Book, History, Biography, Literature, Adventure, Crime, Sci-Fi, Programming, Others. In order to achieve this, we used advanced machine learning models like BanglaBERT, XLM-RoBERTa and a CNN-LSTM attention-based deep learning approach. Our models demonstrate substantial improvements in classification accuracy, attributed to the increased dataset size and the adoption of refined model architectures. Both attention base and transformer based have outperformed previous benchmarks, with accuracy leaping from approximately around 16% to around 75% a direct result of the novel dataset we developed.Among the models that we have tested, BanglaBERT stands out in terms of stability, showcasing exceptional performance due to its advanced transformer-based architecture. This positions BanglaBERT as the most effective model for Bangla content classification in our study, highlighting its superiority in handling the linguistic complexities of Bangla text.

  
  

Paper 09:

  

Title: From Trees to Transformers: Advancement in Bengali Sentiment Classification on BANEMO with mBERT and Deep Learning

  

Abstract:

In this study, we present BANEmo, a novel Bangla language dataset designed specifically for sentiment analysis tasks which is derived from a diverse range of Bangla text/comments, harvested from both social media and newspapers, encompassing a total of 15,000 individual comments. Each comment in the data set is meticulously labeled for various sentiments, such as happiness, sadness, disgust, anger, and more. In our investigation, we initially focus on a binary classification of sentiments, specifically happiness and sadness, where two classical machine learning algorithms, called Support Vector Machine (SVM) and Decision Tree (DT), were employed to establish a baseline performance on the Banemo dataset. In particular, these conventional models achieved state-of-the-art accuracy levels for binary Bangla sentiment analysis. To further push the boundaries, we employed mBERT, a transformer-based pre-training method, for sentiment analysis which exceeded the benchmarks set by the traditional models, underlining the potential of transformer-based models in Bangla sentiment analysis. Finally, this study aims to stimulate further advancements in the field of Bangla natural language processing and sentiment analysis.

  

Paper 10:

Title: Assessing the Trade-Off Between Hybrid BERT-CNN and Transformer Models for Low-Resource Language: Javanese

  

Abstract:

Sentiment analysis for low-resource languages is still becoming a challenge due to limited datasets and the absence of large native pre-training corpora. This study investigates whether hybridizing BERT with Convolutional Neural Networks can improve the accuracy of Javanese sentiment classification. Using the Javanese IMDb dataset, we evaluate Hybrid BERT and CNN architecture against monolingual Transformer baselines. Results show that the hybrid model achieves 72.08 percent accuracy, falling short of the Javanese BERT baseline 76.37 percent. The additional convolutional layer introduces unnecessary complexity, increasing the risk of overfitting rather than providing complementary local features. This study indicates that, in low-resource scenarios, maximizing the utility of pretrained Transformer representations is more effective than architectural hybridization. This highlights the importance of data-centric strategies such as curated Javanese pre-training corpora, improved data filtering, and data-efficient learning methods for advancing NLP in underrepresented languages.

  

Paper 11:

  

Title: Which Matters More: Model or Language? An Empirical Study in English-Bangla Mental Health Classification

  

Abstract:

We present an empirical comparison of classical baselines and pretrained transformer encoders for mental health status classification across English and Bangla social media text. Using two public datasets-an English multi-class corpus and a Bangla binary corpus-we evaluate TF-IDF with Logistic Regression and Random Forest against BERT, RoBERTa, DeBERTa, and BanglaBERT under a matched setup with a stratified eighty twenty split and macro F1 for model selection. In English, RoBERTa achieves 81.6% accuracy with a macro F1 of 78.8, while TF-IDF with Logistic Regression reaches 77.3% accuracy. In Bangla, BanglaBERT attains 88.3% accuracy with a macro F 1 of 88.3, and classical baselines surpass several non-Bangla encoders. Findings highlight the value of language models and the importance of classical machine learning models in classifying mental status across different languages.

  

paper 12:

  

Title: “Low-Resource” Text Classification: A Parameter-Free Classification Method with Compressors

  

Abstract

Deep neural networks (DNNs) are often used for text classification due to their high accuracy. However, DNNs can be computationally intensive, requiring millions of parameters and large amounts of labeled data, which can make them expensive to use, to optimize, and to transfer to out-of-distribution (OOD) cases in practice. In this paper, we propose a non-parametric alternative to DNNs that’s easy, lightweight, and universal in text classification: a combination of a simple compressor like gzip with a k-nearest-neighbor classifier. Without any training parameters, our method achieves results that are competitive with non-pretrained deep learning methods on six in-distribution datasets.It even outperforms BERT on all five OOD datasets, including four low-resource languages. Our method also excels in the few-shot setting, where labeled data are too scarce to train DNNs effectively.

  

Paper 13:

  

Title: Comparative Analysis of Transformer Models for Sentiment Analysis in Low-Resource Languages.

  

Abstract

The analysis of sentiments expressed on social media platforms is a crucial tool for understanding user opinions and preferences. The large amount of the texts found on social media are mostly in different languages. However, the accuracy of sentiment analysis in these systems faces different challenges in multilingual low-resource settings. Recent advancements in deep learning transformer models have demonstrated superior performance compared to traditional machine learning techniques. The majority of preceding works are predominantly constructed on the foundation of monolingual languages. This study presents a comparative analysis that assesses the effectiveness of transformer models, for multilingual lowresource languages sentiment analysis. The study aims to improve the accuracy of the existing baseline performance in analyzing tweets written in 12 low-resource African languages. Four widely used start-of-the-art transformer models were employed. The experiment was carried out using standard datasets of tweets. The study showcases AfriBERTa as a robust performer, exhibiting superior sentiment analysis capabilities across diverse linguistic contexts. It outperformed the established benchmarks in both SemEval-2023 Task 12 and AfriSenti baseline. Our framework achieves remarkable results with an F1-score of 81% and an accuracy rate of 80.9%. This study provides validation of the framework's robustness in the domain of sentiment analysis across a low-resource linguistics context. our research not only contributes a comprehensive sentiment analysis framework for low-resource African languages but also charts a roadmap for future enhancements. Emphasize the ongoing pursuit of adaptability and robustness in sentiment analysis models for diverse linguistic landscapes.

  

Paper 14:

  

Title: Pre-Trained Transformer-Based Models for Text Classification Using Low-Resourced Ewe Language

  

Abstract

Despite a few attempts to automatically crawl Ewe text from online news portals and magazines, the African Ewe language remains underdeveloped despite its rich morphology and complex "unique" structure. This is due to the poor quality, unbalanced, and religious-based nature of the crawled Ewe texts, thus making it challenging to preprocess and perform any NLP task with current transformer-based language models. In this study, we present a well-preprocessed Ewe dataset for low-resource text classification to the research community. Additionally, we have developed an Ewe-based word embedding to leverage the low-resource semantic representation. Finally, we have fine-tuned seven transformer-based models, namely BERT-based (cased and uncased), DistilBERT-based (cased and uncased), RoBERTa, DistilRoBERTa, and DeBERTa, using the preprocessed Ewe dataset that we have proposed. Extensive experiments indicate that the fine-tuned BERT-base-cased model outperforms all baseline models with an accuracy of 0.972, precision of 0.969, recall of 0.970, loss score of 0.021, and an F1-score of 0.970. This performance demonstrates the model’s ability to comprehend the low-resourced Ewe semantic representation compared to all other models, thus setting the fine-tuned BERT-based model as the benchmark for the proposed Ewe dataset.

  

Paper 15:

  

Title: Natural language processing applications for low-resource languages

  

Abstract

Natural language processing (NLP) has significantly advanced our ability to model and interact with human language through technology. However, these advancements have disproportionately benefited high-resource languages with abundant data for training complex models. Low-resource languages, often spoken by smaller or marginalized communities, need help realizing the full potential of NLP applications. The primary challenges in developing NLP applications for low-resource languages stem from the need for large, well-annotated datasets, standardized tools, and linguistic resources. This scarcity of resources hinders the performance of data-driven approaches that have excelled in high-resource settings. Further, low-resource languages frequently exhibit complex grammatical structures, diverse vocabularies, and unique social contexts, which pose additional challenges for standard NLP techniques. Innovative strategies are emerging to address these challenges. Researchers are actively collecting and curating datasets, even utilizing community engagement platforms to expand data resources. Transfer learning, where models pre-trained on high-resource languages are adapted to low-resource settings, has shown significant promise. Multilingual models like Multilingual Bidirectional Encoder Representations from Transformers (mBERT) and Cross Lingual Models (XLM-R), trained on vast quantities of multilingual data, offer a powerful avenue for cross-lingual knowledge transfer. Additionally, researchers are exploring integrating multimodal approaches, combining textual data with images, audio, or video, to enhance NLP performance in low-resource language scenarios. This survey covers applications like part-of-speech tagging, morphological analysis, sentiment analysis, hate speech detection, dependency parsing, language identification, discourse annotation guidelines, question answering, machine translation, information retrieval, and predictive authoring for augmentative and alternative communication systems. The review also highlights machine learning approaches, deep learning approaches, Transformers, and cross-lingual transfer learning as practical techniques. Developing practical NLP applications for low-resource languages is crucial for preserving linguistic diversity, fostering inclusion within the digital world, and expanding our understanding of human language. While challenges remain, the strategies outlined in this survey demonstrate the ongoing progress and highlight the potential for NLP to empower communities that speak low-resource languages and contribute to a more equitable landscape within language technology.


Paper 01:

  

Title: Enhancing social media hate speech detection in low-resource languages using transformers and explainable AI

  

Abstract

Hate speech (HS) on social media exposes public discourse and community well-being. Despite its prevalence, majority of the research and technological advances have focused on rich-resourced languages. In contrast, Albanian, a language marked by dialects, limited NLP tools, and scarcity of annotated data, remains underexplored. To address this gap, this paper explores the enhancement of automatic hate speech detection in Albanian social media using advanced deep neural techniques. We collected a real-life dataset comprising 20,860 Facebook comments manually annotated using a rigorous multi-annotator process. Various techniques, including machine learning, deep neural networks, and transformers, are tested on the collected dataset. Our findings show that character-level 4-gram TF-IDF consistently reinforces ML classifiers effective with informal spelling and slang. However, the fine-tuned transformer XLM-RoBERTa achieves the highest performance with an F1-score up to 86%. These results mark a new benchmark for Albanian HS detection and highlight the impact of thorough feature engineering and robust representation techniques in a low-resource context. We also carried out an error analysis using both manual inspection and explainable AI approaches such as SHAP and LIME. Key language challenges include dialectal writing, short sentences, and implicit insults. These insights highlight the importance of domain-aligned embedding resources, more extensive annotation, and fine-grained context handling for improved detection. This study establishes a new state-of-the-art result for Albanian hate speech detection, provides a valuable comparison of models and feature engineering, and underscores the potential of multilingual transformers in low-resource scenarios.

  

Paper 02:

  

Title: Improving Hate Speech Classification Through Ensemble Learning and Explainable AI Techniques

  

Abstract

Identifying offensive and discriminatory content, commonly referred to as hate speech, within textual data is a critical task. This study addresses the task of identifying hate speech in textual data, focusing on the challenge of selecting optimal word embedding methods and classifiers. Leveraging the Google Jigsaw dataset, the research employs explainable artificial intelligence (XAI) for hate speech detection. Following preprocessing, which includes converting text to lowercase, removing punctuation, extra whitespace, numbers, and non-ASCII characters, a thorough analysis reveals high-frequency words. The research extensively compares three-word embedding techniques—CountVectorizer, GloVe, and bidirectional encoder representations from transformers (BERT)—in combination with two machine learning models (support vector classifier and logistic regression) and four deep learning models [artificial neural network (ANN), recurrent neural network (RNN), bidirectional gated recurrent unit (Bi-GRU), bidirectional long-short term memory (Bi-LSTM)] for hate speech detection. The fusion of BERT with a bidirectional gated recurrent unit (Bi-GRU) achieved an impressive accuracy of 92%, and an ensemble of the top-performing models further improves accuracy by nearly 2%. To enhance result interpretability, the study employs XAI techniques such as local interpretable model agnostic explanations (LIME) and Shapley additive explanations (SHAP) on the top-performing ensembled model to provide insights into its predictions. The paper concludes by suggesting potential future research directions, including exploring additional embedding techniques and models, addressing dataset generalizability, improving interpretability methods, and considering computational resource constraints.

  

Paper 03:

  

Title: Explainable hate speech detection using LIME

  

Abstract

Free speech is essential, but it can conflict with protecting marginalized groups from harm caused by hate speech. Social media platforms have become breeding grounds for this harmful content. While studies exist to detect hate speech, there are significant research gaps. First, most studies used text data instead of other modalities such as videos or audio. Second, most studies explored traditional machine learning algorithms. However, due to the increase in complexities of computational tasks, there is need to employ complex techniques and methodologies. Third, majority of the research studies have either been evaluated using very few evaluation metrics or not statistically evaluated at all. Lastly, due to the opaque, black-box nature of the complex classifiers, there is need to use explainability techniques. This research aims to address these gaps by detecting hate speech in English and Kiswahili languages using videos manually collected from YouTube. The videos were converted to text and used to train various classifiers. The performance of these classifiers was evaluated using various evaluation and statistical measurements. The experimental results suggest that the random forest classifier achieved the highest results for both languages across all evaluation measurements compared to all classifiers used. The results for English language were: accuracy 98%, AUC 96%, precision 99%, recall 97%, F1 98%, specificity 98% and MCC 96% while the results for Kiswahili language were: accuracy 90%, AUC 94%, precision 93%, recall 92%, F1 94%, specificity 87% and MCC 75%. These results suggest that the random forest classifier is robust, effective and efficient in detecting hate speech in any language. This also implies that the classifier is reliable in detecting hate speech and other related problems in social media. However, to understand the classifiers’ decision-making process, we used the Local Interpretable Model-agnostic Explanations (LIME) technique to explain the predictions achieved by the random forest classifier.

  

Paper 04:

  

Title: Explainable Bangla Linguistic Style Classification into Saint and Common Forms: A Deep Neural Network and Transformer-Based Approach with LIME-Based Interpretability

  

Abstract

This study explores a deep neural network and transformer-based framework for classifying Bengali texts into saint (Sadhu) and common (Cholito) forms. We evaluated six architectures: BiLSTM with attention, GRU-CNN, BanglaBERT, BanglaBERT-Enhanced CNN, XLM-RoBERTa Large, and SahajBERT, all implemented using the dataset BanglaBlend. Among these, transformer-based models, particularly SahajBERT and XLM-RoBERTa Large, consistently achieved high performance across the evaluation metrics. SahajBERT achieved the best overall results, with performance metrics of 0.95 ± 0.01, outperforming BiLSTM, GRU-CNN, and BanglaBERT by a significant margin in predictive accuracy and robustness. To enhance interpretability, we incorporated LIME, a widely used explainable AI (XAI) technique that provides token-level attribution for individual predictions. We further examined the robustness of these explanations across random seeds, assessed lexical overlap between splits to ensure fair evaluation, and benchmarked inference efficiency for the transformer models. This enables transparent validation of stylistic cues aligned with linguistic expectations. Our findings demonstrate the strength of transformer-based models in capturing stylistic and lexical distinctions in Bangla, setting a benchmark for future research in literary style detection, text normalization, and digital language preservation.

  

Paper 05:

  

Title: Interpretable Multi Labeled Bengali Toxic Comments Classification using Deep Learning

  

Abstract:

This paper presents a deep learning-based pipeline for categorizing Bengali toxic comments, in which at first a binary classification model is used to determine whether a comment is toxic or not, and then a multi-label classifier is employed to determine which toxicity type the comment belongs to. For this purpose, we have prepared a manually labeled dataset consisting of 16,073 instances among which 8,488 are Toxic and any toxic comment may correspond to one or more of the six toxic categories - vulgar, hate, religious, threat, troll, and insult simulta-neously. Long Short Term Memory (LSTM) with BERT Embedding achieved 89.42% accuracy for the binary classification task while as a multi-label classifier, a combination of Convolutional Neural Network and Bi-directional Long Short Term Memory (CNN-BiLSTM) with attention mechanism achieved 78.92% accuracy and 0.86 as weighted F1-score. To explain the predictions and interpret the word feature importance during classification by the proposed models, we utilized Local Interpretable Model-Agnostic Explanations (LIME) framework. We have made our dataset public and can be accessed at - https://github.com/deepu099cse/Multi-Labeled-Bengali-Toxic-Comments-Classification

  

Paper 06:

  

Title: Classifying Offensive Speech of Bangla Text and Analysis Using Explainable AI

  

Abstract

The rapid rise of social networking websites and blogging sites not only provides freedom of expression or speech, but also allows people to express society-prohibited behaviors such as online harassment and cyberbullying, which are known as offensive speech or hate speech. Despite the fact that various research work has been done on detecting hate or abusive speech on social networking websites in the English language, the opportunities for research for detecting offensive or abusive speech in the Bengali language remain open due to the computational resource constraints or the lack of standard-labeled datasets for accurate or effective Natural Language Processing (NLP) of Bangla language. In this paper, an Explainable AI approach is used for analysis as well as for detecting offensive comments or speech in the Bengali language is proposed. Moreover, Convolutional Neural Network (CNN) model is used to extract and classify features. Since the Neural Network is time-consuming for extracting features from the dataset, our proposed approach allows people to save time and effort. In the dataset, we classified all user’s comments from social media comment sections into four categories: religious, personal, geopolitical, and political. Our proposed model successfully detects Bangla offensive speeches from the dataset (Bengali Hate Speech Dataset) by evaluating Machine Learning algorithms like linear and tree-based models and Neural Networks like CNN, Bi-LSTM, Conv-LSTM, and SVM models. Moreover, we calculate scores for completeness and sufficiency to assess the quality of explanations in terms of fidelity, achieving the results with the accuracy of 78% score, significantly outperforming ML and DNN baselines.

  

Paper 07:

  

Title: DeepHateExplainer: Explainable Hate Speech Detection in Under-resourced Bengali Language

  

Abstract:

In this paper, we propose an explainable approach for hate speech detection from the under-resourced Bengali language, which we called DeepHateExplainer. In our approach, Bengali texts are first comprehensively preprocessed, before classifying them into political, personal, geopolitical, and religious hates using a neural ensemble method of transformer-based neural architectures (i.e., monolingual Bangla BERT-base, multilingual BERT-cased/uncased, and XLM-RoBERTa). Subsequently, important (most and least) terms are identified using sensitivity analysis and layer-wise relevance propagation (LRP), before providing human-interpretable explanations11To foster reproducible research, we make available the data, source codes, models, and notebooks: https://github.com/rezacsedu/DeepHateExplainer. Finally, we compute comprehensiveness and sufficiency scores to measure the quality of explanations w.r.t faithfulness. Evaluations against machine learning (linear and tree-based models) and neural networks (i.e., CNN, Bi-LSTM, and Conv-LSTM with word embeddings) baselines yield F1-scores of 78%, 91%, 89%, and 84%, for political, personal, geopolitical, and religious hates, respectively, outperforming both ML and DNN baselines22Read an extended version of this paper: https://arxiv.org/abs/2012.14353.

  

Paper 08:

  

Title: Analyzing Abusive Bangla Comments on Social Media: NLP & Explainable AI

  

Abstract:

Popularity of Social media sites has been on the rise ever since its invention. Due to the anonymity the social media sites provide to the users, an influx of divergent behavior has also been increasing. Abusive language and offensive content are posted on these sites to ridicule others which creates a harmful environment for the people affected. Detecting these misconducts, especially for Bengali Language is still vague. Our paper tries to bridge the gap between the abusive content detection using Natural Language Processing with five different machine learning classifiers such as Decision Tree, Random Forest, Multinomial Naïve Bayes, Support Vector Classifier and Logistic Regression and give clarity on the factors that contribute to the prediction using Explainable AI. The dataset was preprocessed in multiple steps including stop words and punctuation removal, null and duplication value check and tokenization. The dataset was then processed to created TF-IDF representations with n-grams. Grid Search Cross Validation technique was used to find out optimal combination of hyperparameters for our machine learning models. Among all the models Logistic Regression performed the best with an accuracy of 85.57%. For transparency and clarification of the model's detection methodologies Lime model was used.

  

Paper 09:

  

Title: An Interpretable Machine Learning Approach for Bengali Toxic Comments Detection

  

Abstract:

Toxic comment detection is critical for providing a positive online environment and to detect this type of comment is very important for people’s mental health. In this research, a machine learning based pipeline was created to detect if a comment is toxic or not. For prediction purposes, two datasets were utilized.The first dataset, which is publicly available, contains a total of 16,073 comments. Out of 16,073, 8,488 comments are classified as toxic, and 7,585 comments are classified as not toxic.The second dataset, also publicly available and collected from Mendeley Data, contains 44,001 comments. Among these, 28,661 comments are classified as toxic or bully, while 15,340 comments are classified as not toxic or not bully. Preprocessing was completed, and features were extracted using TF-IDF, before training the models on the datasets. Then we evaluated the results using a confusion matrix and performance metrics like precision, f1 score, recall, accuracy. For Dataset-1, the Stochastic Gradient Descent (SGD) classifier achieved the best performance among the implemented models, with a weighted F1 score of 0.91 and an accuracy of 91.44%.For Dataset-2, the Stochastic Gradient Descent (SGD) classifier demonstrated the highest performance among the implemented models, achieving a weighted F1 score of 0.88 and an accuracy of 88.42%..To explain the model’s prediction, LIME framework was implemented. With the use of explainable artificial intelligence, the decision-making process of our models becomes more transparent. Source Code: https://github.com/ZobayerAkib/An-Interpretable-Machine-Learning-Approach-for-Bengali-Toxic-Comments-Detection-IEEE2025

  
  

Paper 10:

  

Title:

DeepHateDetect: A Comparative Study of Traditional, Sequential, Transformer, and Large Language Models for Hate Speech Detection in Bengali using Explainable AI

  

Abstract:

The spread of hate speech on the internet has been associated with an increase in violent acts committed against minority groups all across the world. Nowadays, usage of social media is at its peak, and so is hate speech on online social media. Almost every continent has reported incidents. Most of the world’s population uses Facebook alone, and many people increasingly converse on social media. This study used a private dataset collected from different social media platforms. This study aims to discover an efficient and optimal method by using various models that can detect Bengali hate speech on a different text corpus. The overall procedure includes analyzing the collected data. Labeling, cleaning, vectorization, and further data set processing. Several traditional machine learning (ML) models implemented with advanced grid search. In addition, several sequential and transformer-based models were used. Also, a large language model was applied using quantization. Among these different types of models, LLaMA 3-8B gained the highest accuracy of 0.99. Furthermore, the predictability of LLaMA 3-8B has been demonstrated using explainable AI with the LIME framework.

  
  

Paper 11:

Title: Interpretable Fine-Grained Hate Speech Detection in Bangla: CNN with LIME and Comparative Evaluation

  

Abstract:

Detecting hate content in Bangla is notably difficult because of primarily stemming from a scarcity of labeled datasets and the nuanced complexity of fine-grained hate categories. Existing approaches have largely relied on traditional ML models trained on imbalanced datasets, limiting their effectiveness and generalization capabilities. To bridge these gaps, this paper presents a novel, manually annotated Bangla hate speech dataset with three fine-grained categories : Personal Attack, Misogyny/Sexist Abuse, and Ideological Hate. To mitigate the inherent class imbalance, synonym-based data augmentation was employed to create a balanced corpus for robust model training. A comprehensive comparative study was conducted between classical ML models LR and SVM and DL models based on LSTM, BiLSTM, and CNN based deep learning model. Experimental results demonstrate that the CNN model , trained on the augmented and balanced dataset, significantly outperforms the classical models, achieving an accuracy of 94%. In comparison, SVM and LR achieved accuracies of 83% and 69%, respectively. Furthermore, LSTM and BiLSTM models achieved accuracies of 92.47% and 92.36%, respectively.To enhance interpretability and trust in model decisions, this study also applies Explainable AI (XAI) techniques using the LIME framework, providing insights into how the models make predictions and highlighting the most influential features for each hate category. Ultimately, this paper’s findings confirm the fundamental need for data augmentation and highlights the superior capability of DL models in discerning the underlying context for effective fine-grained hate speech classification in languages with limited available resources, such as Bangla.

  

Paper 12:

Title: Analyzing Arrogant Comments in the Bengali Language Through Explainable AI and NLP

  

Abstract:

Detecting arrogance in language is challenging, especially in low-resource languages such as Bangla, where it is often expressed subtly and without overt toxicity. This paper introduce the first large-scale Bangla arrogance detection framework by combining weak supervision with deep learning and explainable AI. The weak supervision framework automatically annotates 46,000 Bangla comments, reducing the need for costly manual annotation. We compare a BiLSTM baseline and the transformer-based BanglaBERT model. BanglaBERT achieved 96% accuracy and a 95% F1-score, outperforming BiLSTM (89.78% accuracy, 87% F1-score). LIME-based explainability revealed that self-referential pronouns and possessive words strongly influenced the arrogance classification. The results demonstrate that our approach effectively detects arrogance in Bangla text and can be adapted for use in other low-resource languages.


Paper 01:

Title: Exploring Cross-Cultural Differences in English Hate Speech Annotations: From Dataset Construction to Analysis

  

Abstract

Most hate speech datasets neglect the cultural diversity within a single language, resulting in a critical shortcoming in hate speech detection. To address this, we introduce CREHate, a CRoss-cultural English Hate speech dataset. To construct CREHate, we follow a two-step procedure: 1) cultural post collection and 2) cross-cultural annotation. We sample posts from the SBIC dataset, which predominantly represents North America, and collect posts from four geographically diverse English-speaking countries (Australia, United Kingdom, Singapore, and South Africa) using culturally hateful keywords we retrieve from our survey. Annotations are collected from the four countries plus the United States to establish representative labels for each country. Our analysis highlights statistically significant disparities across countries in hate speech annotations. Only 56.2% of the posts in CREHate achieve consensus among all countries, with the highest pairwise label difference rate of 26%. Qualitative analysis shows that label disagreement occurs mostly due to different interpretations of sarcasm and the personal bias of annotators on divisive topics. Lastly, we evaluate large language models (LLMs) under a zero-shot setting and show that current LLMs tend to show higher accuracies on Anglosphere country labels in CREHate.Our dataset and codes are available at: https://github.com/nlee0212/CREHate

  

Paper 02:

Title:

Dataset for Identification of Homophobia and Transophobia in Multilingual YouTube Comments

  

Abstract:

The increased proliferation of abusive content on social media platforms has a negative impact on online users. The dread, dislike, discomfort, or mistrust of lesbian, gay, transgender or bisexual persons is defined as homophobia/transphobia. Homophobic/transphobic speech is a type of offensive language that may be summarized as hate speech directed toward LGBT+ people, and it has been a growing concern in recent years. Online homophobia/transphobia is a severe societal problem that can make online platforms poisonous and unwelcome to LGBT+ people while also attempting to eliminate equality, diversity, and inclusion. We provide a new hierarchical taxonomy for online homophobia and transphobia, as well as an expert-labelled dataset that will allow homophobic/transphobic content to be automatically identified. We educated annotators and supplied them with comprehensive annotation rules because this is a sensitive issue, and we previously discovered that untrained crowdsourcing annotators struggle with diagnosing homophobia due to cultural and other prejudices. The dataset comprises 15,141 annotated multilingual comments. This paper describes the process of building the dataset, qualitative analysis of data, and inter-annotator agreement. In addition, we create baseline models for the dataset. To the best of our knowledge, our dataset is the first such dataset created. Warning: This paper contains explicit statements of homophobia, transphobia, stereotypes which may be distressing to some readers.

  

Paper 03:

  

Title: Misogynistic attitude detection in YouTube comments and replies: A high-quality dataset and algorithmic models

  

Abstract

Social media platforms are now not only a medium for expressing users views, feelings, emotions and sentiments but are also being abused by people to propagate unpleasant and hateful content. Consequently, research efforts have been made to develop techniques and models for automatically detecting and identifying hateful, abusive, vulgar, and offensive content on different platforms. Although significant progress has been made on the task, the research on design of methods to detect misogynistic attitude of people in non-English and code-mixed languages is not very well-developed. Non-availability of suitable datasets and resources is one main reason for this. Therefore, this paper attempts to bridge this research gap by presenting a high-quality curated dataset in the Hindi-English code-mixed language. The dataset includes 12,698 YouTube comments and replies, with each comment annotated under two-level categories, first as optimistic and pessimistic, and then into different types at second level based on the content. The inter-annotator agreement in the dataset is found to be 0.84 for the first subtask, and 0.79 for the second subtask, indicating the reasonably high quality of annotations. Different algorithmic models are explored for the task of automatic detection of the misogynistic attitude expressed in the comments, with the mBERT model giving best performance on both subtasks (reported macro average F1 scores of 0.59 and 0.52, and weighted average F1 scores of 0.66 and 0.65, respectively). The analysis and results suggest that the dataset can be used for further research on the topic and that the developed algorithmic models can be applied for automatic detection of misogynistic attitude in social media conversations and posts.

  

Paper 03:

  

Title: Handling Disagreement in Hate Speech Modelling

  

Abstract

Hate speech annotation for training machine learning models is an inherently ambiguous and subjective task. In this paper, we adopt a perspectivist approach to data annotation, model training and evaluation for hate speech classification. We first focus on the annotation process and argue that it drastically influences the final data quality. We then present three large hate speech datasets that incorporate annotator disagreement and use them to train and evaluate machine learning models. As the main point, we propose to evaluate machine learning models through the lens of disagreement by applying proper performance measures to evaluate both annotators’ agreement and models’ quality. We further argue that annotator agreement poses intrinsic limits to the performance achievable by models. When comparing models and annotators, we observed that they achieve consistent levels of agreement across datasets. We reflect upon our results and propose some methodological and ethical considerations that can stimulate the ongoing discussion on hate speech modelling and classification with disagreement.

  
  

Paper 04:

  

Title: The problem of varying annotations to identify abusive language in social media content

  

Abstract

With the increase of user-generated content on social media, the detection of abusive language has become crucial and is therefore reflected in several shared tasks that have been performed in recent years. The development of automatic detection systems is desirable, and the classification of abusive social media content can be solved with the help of machine learning. The basis for successful development of machine learning models is the availability of consistently labeled training data. But a diversity of terms and definitions of abusive language is a crucial barrier. In this work, we analyze a total of nine datasets—five English and four German datasets—designed for detecting abusive online content. We provide a detailed description of the datasets, that is, for which tasks the dataset was created, how the data were collected, and its annotation guidelines. Our analysis shows that there is no standard definition of abusive language, which often leads to inconsistent annotations. As a consequence, it is difficult to draw cross-domain conclusions, share datasets, or use models for other abusive social media language tasks. Furthermore, our manual inspection of a random sample of each dataset revealed controversial examples. We highlight challenges in data annotation by discussing those examples, and present common problems in the annotation process, such as contradictory annotations and missing context information. Finally, to complement our theoretical work, we conduct generalization experiments on three German datasets.

  

Paper 05:

  

Title: Sexism in Focus: An Annotated Dataset of YouTube Comments for Gender Bias Research

  

Abstract:

This paper presents a novel dataset of 200k YouTube comments from 468 videos across 109 channels in four content categories: Entertainment, Gaming, People & Blogs, and Science & Technology. We applied state-of-the-art NLP methods to augment the dataset with sexism-related features such as sentiment, toxicity, offensiveness, and hate speech. These features can assist manual content analyses and enable automated analysis of sexism in online platforms. Furthermore, we develop an annotation framework inspired by the Ambivalent Sexism Theory to promote a nuanced understanding of how comments relate to the gender of content creators. We release a small sample of comments annotated using this framework. Our dataset analysis confirms that female content creators receive more sexist and hateful comments than their male counterparts, underscoring the need for further research and intervention in addressing online sexism.

  
  

Paper 06:

  

Title: Quantifying the impact of context on the quality of manual hate speech annotation

  

Abstract

The quality of annotations in manually annotated hate speech datasets is crucial for automatic hate speech detection. This contribution focuses on the positive effects of manually annotating online comments for hate speech within the context in which the comments occur. We quantify the impact of context availability by meticulously designing an experiment: Two annotation rounds are performed, one in-context and one out-of-context, on the same English YouTube data (more than 10,000 comments), by using the same annotation schema and platform, the same highly trained annotators, and quantifying annotation quality through inter-annotator agreement. Our results show that the presence of context has a significant positive impact on the quality of the manual annotations. This positive impact is more noticeable among replies than among comments, although the former is harder to consistently annotate overall. Previous research reporting that out-of-context annotations favour assigning non-hate-speech labels is also corroborated, showing further that this tendency is especially present among comments inciting violence, a highly relevant category for hate speech research and society overall. We believe that this work will improve future annotation campaigns even beyond hate speech and motivate further research on the highly relevant questions of data annotation methodology in natural language processing, especially in the light of the current expansion of its scope of application.

  

Paper 07:

  

Title: When comments aren’t what they seem: The social media comment toxicity detector for understanding contextual comments

  

Abstract

Social media comments often contain toxic, sarcastic, or ambiguous language, challenging traditional toxicity detection models. However, most existing methods treat comments as isolated units and rely solely on surface-level textual cues, making them ineffective in identifying implicit toxicity such as sarcasm or context-dependent insults. These limitations hinder their performance in real-world scenarios, where toxicity often emerges across multi-turn interactions. This paper proposes a context-aware interactive framework using GPT models to simulate human-like interactions, transforming single comments into multi-level threads. This approach improves toxicity detection by leveraging contextual dialogue. We evaluate our method on 5018 comments from platforms such as Zhihu, Bilibili, Weibo, YouTube, and RedNote. Our experiments show that our method outperforms traditional models, especially on YouTube, where sensitive word frequency is high. Additionally, our approach demonstrates strong multilingual support, successfully detecting toxicity in six languages. This paper also compares the performance of GPT-4O, GPT-4, GPT-3.5 and DeepSeek-V3, highlighting the advantage of multimodal processing in the former for more robust detection. The dataset we have collected is publicly available at https://github.com/kanglzu/When-Comments-Aren-t-What-They-Seem.

  
  

Paper 08:

  

Title: A Multi-Task Benchmark for Abusive Language Detection in Low-Resource Settings

  

Abstract

Content moderation research has recently made significant advances, but remains limited in serving the majority of the world's languages due to the lack of resources, leaving millions of vulnerable users to online hostility. This work presents a large-scale human-annotated multi-task benchmark dataset for abusive language detection in Tigrinya social media with joint annotations for three tasks: abusiveness, sentiment, and topic classification. The dataset comprises 13,717 YouTube comments annotated by nine native speakers, collected from 7,373 videos with a total of over 1.2 billion views across 51 channels. We developed an iterative term clustering approach for effective data selection. Recognizing that around 64% of Tigrinya social media content uses Romanized transliterations rather than native Ge'ez script, our dataset accommodates both writing systems to reflect actual language use. We establish strong baselines across the tasks in the benchmark, while leaving significant challenges for future contributions. Our experiments demonstrate that small fine-tuned models outperform prompted frontier large language models (LLMs) in the low-resource setting, achieving 86.67% F1 in abusiveness detection (7+ points over best LLM), and maintain stronger performance in all other tasks. The benchmark is made public to promote research on online safety.

  

Paper 09:

Title: Detection of Offensive Language and ITS Severity for Low Resource Language

  

Abstract

Continuous proliferation of hate speech in different languages on social media has drawn significant attention from researchers in the past decade. Detecting hate speech is indispensable irrespective of the scale of use of language, as it inflicts huge harm on society. This work presents a first resource for classifying the severity of hate speech in addition to classifying offensive and hate speech content. Current research mostly limits hate speech classification to its primary categories, such as racism, sexism, and hatred of religions. However, hate speech targeted at different protected characteristics also manifests in different forms and intensities. It is important to understand varying severity levels of hate speech so that the most harmful cases of hate speech may be identified and dealt with earlier than the less harmful ones. In this work, we focus on detecting offensive speech, hate speech, and multiple levels of hate speech in the Urdu language. We investigate three primary target categories of hate speech: religion, racism, and national origin. We further divide these categories into levels based on the severity of hate conveyed. The severity levels are referred to as symbolization, insult, and attribution. A corpus comprising more than 20,000 tweets against the corresponding hate speech categories and severity levels is collected and annotated. A comprehensive experimentation scheme is applied using traditional as well as deep learning–based models to examine their impact on hate speech detection. The highest macro-averaged F-score yielded for detecting offensive speech is 86% while the highest F-scores for detecting hate speech with respect to ethnicity, national origin, and religious affiliation are 80%, 81%, and 72%, respectively. This shows that results are very encouraging and would provide a lead towards further investigation in this domain.

  

Paper 10:

  

Title: Tackling Sexist Hate Speech: Cross-Lingual Detection and Multilingual Insights from Social Media

  

Abstract

With the widespread use of social media, the proliferation of online communication presents both opportunities and challenges for fostering a respectful and inclusive digital environment. Due to the anonymity and weak regulations of social media platforms, the rise of hate speech has become a significant concern, particularly against specific individuals or groups based on race, religion, ethnicity, or gender, posing a severe threat to human rights. Sexist hate speech is a prevalent form of online hate that often manifests itself through gender-based violence and discrimination, challenging societal norms and legal systems. Despite the advances in natural language processing techniques for detecting offensive and sexist content, most research still focuses on monolingual (primarily English) contexts, neglecting the multilingual nature of online platforms. This gap highlights the need for effective and scalable strategies to address the linguistic diversity and cultural variations in hate speech. Cross-language transfer learning and state-of-the-art multilingual pre-trained language models provide potential solutions to improve the detection efficiency of low-resource languages by leveraging data from high-resource languages. Additional knowledge is crucial to facilitate the models’ performance in detecting culturally varying expressions of sexist hate speech in different languages. In this thesis, we delve into the complex area of identifying sexist hate speech in social media across diverse languages pertaining to different language families, with a focus on sexism and a broad exploration of datasets, methodologies, and barriers inherent in mitigating online hate speech in cross-lingual and multilingual scenarios. We primarily apply cross-lingual transfer learning techniques to detect sexist hate speech, aiming to leverage knowledge acquired from related linguistic data in order to improve performance in a target language. We also investigate the integration of external knowledge to deepen the understanding of sexism in multilingual social media contexts, addressing both the challenges of linguistic diversity and the need for comprehensive, culturally sensitive hate speech detection models. Specifically, it embarks on a comprehensive survey of tackling cross-lingual hate speech online, summarising existing datasets and cross-lingual approaches, as well as highlighting challenges and frontiers in this field. It then presents a first contribution to the field, the creation of the Sina Weibo Sexism Review (Swsr) dataset in Chinese —a pioneering resource that not only fills a crucial gap in limited resources but also lays the foundation for relevant cross-lingual investigations. Additionally, it examines how cross-lingual techniques can be utilised to generate domain-aware word embeddings, and explores the application of these embeddings in a cross-lingual hate speech framework, thereby enhancing the capacity to capture the subtleties of sexist hate speech across diverse languages. Recognising the significance of linguistic nuances in multilingual and cross-lingual settings, another innovation consists in proposing and evaluating a series of multilingual and cross-lingual models tailored for detecting sexist hate speech. By leveraging the capacity of shared knowledge and features across languages, these models significantly advance the state-of-the-art in identifying online sexist hate speech. As societies continue to deal with the complexities of social media, the findings and methodologies presented in this thesis could effectively help foster more inclusive and respectful online content across languages.

title
BanFootyHate-26: A Multi-Task Code-Mixed Bengali Dataset and Explainable Benchmark for Hate Speech, Toxicity, and Target Identification in Football Rivalry Conversations

4. BanFootyHate-26 (Mahdi)
A. Bangla hate speech/toxicity detection
•	(Bangla OR Bengali) AND ("hate speech" OR toxicity OR "offensive language") AND detection
•	(Bangla OR Bengali) AND "hate speech" AND ("deep learning" OR transformer OR BERT)
•	(Bangla OR Bengali) AND ("abusive language" OR cyberbullying) AND ("social media" OR detection)
B. Code-mixed/Banglish text classification
•	("code-mixed" OR "code-switched") AND (Bangla OR Bengali OR Hindi OR "South Asian") AND classification
•	("Banglish" OR "Romanized Bangla" OR "transliterated Bangla") AND ("text classification" OR NLP)
•	("code-mixing" OR "code-switching") AND ("hate speech" OR "sentiment analysis") AND "low-resource"
C. Sports/football fan discourse analysis
•	(football OR soccer) AND (fan OR rivalry OR comment) AND ("sentiment analysis" OR "hate speech" OR toxicity)
•	(sports OR football) AND ("social media") AND ("hate speech" OR "toxic comment")
D. Multi-task learning: toxicity + target identification — ✅ Type 1 (anchor: hate speech/toxicity present)
•	("multi-task learning" OR multitask) AND ("hate speech" OR toxicity) AND target
•	("target identification" OR "target classification") AND ("hate speech" OR "offensive language")
E. Transformer-based Bangla NLP methods
•	(BanglaBERT OR "XLM-RoBERTa" OR mBERT) AND (Bangla OR Bengali) AND classification
•	("low-resource language" OR "low-resource NLP") AND (transformer OR BERT) AND classification
F. Explainability in hate-speech classification — ✅ Type 1 (anchor present)
•	(LIME OR SHAP OR "explainable AI") AND ("hate speech" OR toxicity) AND (Bangla OR Bengali OR "low-resource")
G. Data collection/annotation methodology — ✅ Type 1 (anchor present)
•	("YouTube comments" OR "social media") AND dataset AND ("inter-annotator agreement" OR annotation) AND ("hate speech" OR toxicity)
•	("annotation guideline" OR "labeling scheme") AND ("hate speech" OR "offensive language") AND "low-resource"


---
Here are the abstracts of all the literature I've collected on this topic,
organized by sub-section. Please look at all of them carefully and help me
refine my research goals and title.

Tell me:
- what type of data I should collect, gather, or modify
- how I should conduct the research
- a final research title, clear goals, and a dataset description
- the baseline(s) I should aim to match or beat

