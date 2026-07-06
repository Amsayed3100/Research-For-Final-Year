## A.Writer verification/identification

  

### End-To-End Evaluation of Deep Learning Architectures for Off-Line Handwriting Writer Identification: A Comparative Study

#### Abstract

Identifying writers using their handwriting is particularly challenging for a machine, given that a personâ€™s writing can serve as their distinguishing characteristic. The process of identification using handcrafted features has shown promising results, but the intra-class variability between authors still needs further development. Almost all computer vision-related tasks use Deep learning (DL) nowadays, and as a result, researchers are developing many DL architectures with their respective methods. In addition, feature extraction, usually accomplished using handcrafted algorithms, can now be automatically conducted using convolutional neural networks. With the various developments of the DL method, it is necessary to evaluate the suitable DL for the problem we are aiming at, namely the classification of writer identification. This comparative study evaluated several DL architectures such as VGG16, ResNet50, MobileNet, Xception, and EfficientNet end-to-end to examine their advantages to offline handwriting for writer identification problems with IAM and CVL databases. Each architecture compared its respective process to the training and validation metrics accuracy, demonstrating that ResNet50 DL had the highest train accuracy of 98.86%. However, Xception DL performed slightly better due to the convergence gap for validation accuracy compared to all the other architectures, which were 21.79% and 15.12% for IAM and CVL. Also, the smallest gap of convergence between training and validation accuracy for the IAM and CVL datasets were 19.13% and 16.49%, respectively. The results of these findings serve as the basis for DL architecture selection and open up overfitting problems for future work.

# An effective DeepWINet CNN model for off-line text-independent writer identification

## Abstract

Writer identification based on handwriting recognition is considered one of the most common research areas in pattern recognition and biometrics. It has attracted much attention in recent decades due to the urgent need to develop biometric systems for many security applications. In this paper, Deep Writer Identification Network (DeepWINet), an effective deep Convolutional Neural Network (CNN) for writer identification, is proposed. The proposed model is evaluated in two different ways. In the first scenario, DeepWINet’s CNN activation features, computed from the connected components of the writing, are passed to a customized nearest neighbor classifier for writer identification. In the second scenario, DeepWINet is evaluated as an end-to-end CNN network where the predicted results are averaged using an efficient strategy, Score Averaging Component-Decision Combiner. The proposed approach achieves competitive or the highest State-Of-The-Art performance on eight challenging handwritten databases with different languages.

# WriterINet: a multi-path deep CNN for offline text-independent writer identification

## Abstract

andwriting-based identification is a fundamental pattern recognition problem that has attracted considerable interest in recent years. Writer identification is a major challenge, considering how diverse the written content is and how much handwriting differs between writers. This paper presents _WriterINet_, a CNN-based approach to learning and characterizing each writer’s writing style. The proposed _WriterINet_ approach takes handwritten documents as input, decomposing each of them into word images and connected component sub-images. Each segmented image is then fed into our feature learning step to generate discriminative and deep features. To this end, we developed a powerful deep CNN feature architecture consisting of two CNN streams derived from fine-tuning the ResNet-50 and DenseNet-201 models. Deep learned features are computed from all segmented images representing the writer’s document and classified using a proposed 1D artificial neural network for predicting writer identification by averaging the similarity scores. Experimental results on IAM, ICDAR2013, CVL, IFNENIT, ICDAR2011, Firemaker and CERUG show that our _WriterINet_ approach achieves the highest or competitive performance over the state-of-the-art.

# Forged document detection and writer identification through unsupervised deep learning approach

## Abstract

  

In recent years, there has been a significant increase in document forgery, which includes the fraudulent replication of currency, diplomas, and works of art. This has become a major issue due to the widespread usage of paper-based documentation. Handwriting is closely linked to document forgery and forensics as it possesses unique characteristics, including variations in text characters, pen pressure, writing angle, and stroke patterns, which makes it impossible to replicate accurately. As a result, handwriting serves as a personalized biometric that can be used to determine the authenticity of documents. However, traditional methods of writer identification are both time-consuming and destructive, requiring substantial expertise. To overcome these limitations, the study explores the potential of hyperspectral imaging (HSI) as a non-destructive and advanced approach for detecting and preventing document forgery. HSI provides detailed spectral information from a scene, making it possible to capture subtle spectral differences in handwriting samples. This imaging technique has diverse applications in various fields such as agriculture, environmental monitoring, remote sensing, forensics, document analysis, and medical imaging. Our study proposes a novel unsupervised approach, CAE-SVM that uses Convolutional Autoencoder (CAE) for feature extraction and Support Vector Machine (SVM) for writer identification. It was tested on the UWA writing ink hyperspectral images dataset for blue and black inks which is available publicly and compared with state-of-the-art methods and CNN. The proposed approach achieved the highest accuracy of 92.78% for blue ink, surpassing existing methods. The study’s results emphasize the efficacy of HSI as a potent forensic analysis tool for detecting and preventing document forgery.

# A survey on different feature extraction methods for writer identification and verification

## Abstract

  

Identifying and verifying a person based on scanned images of their handwriting is a needful biometric application in historical document analysis, behavioural biometrics study, forensic science, access control, graphology, and copyrights management. Writer identification and verification are still challenging in offline and online handwriting recognition. Since the performances of handwriting biometric identification and verification systems depend on both the quality and types of chosen features, this is one of the most critical phases. This article represents a literature survey on offline and online biometric features used in different scripts for writer verification and identification techniques. Several previous efficient works on online and offline writer authentication methods for biometrics using cutting-edge hand-craft features in different levels of handwriting analysis like documents, paragraphs, words, and characters are analysed systematically to date for the first time in detail.

# Deep neural networks-based offline writer identification using heterogeneous handwriting data: an evaluation via a novel standard dataset

## Abstract

  

In modern societies, handwritten identification is a great practical need and challenge for forensic sciences. Moreover, few research studies have focused on automatic offline handwritten document analysis. Also, there are very few standard datasets on handwritten document identification. In addition, handwritten documents lose their nature over time due to the spread and drying of ink. From this standpoint, the present study presents an offline writer identification system (in presence of the uncertainties such as different experimental conditions and environmental noises for more realistic assumptions) that is a critical need in forensic studies. For this purpose, a comprehensive right-to-left dataset is developed and devised by gathering data from 62 participants at different time intervals under different experimental conditions. This dataset is designed based on American Society for Testing and Materials (ASTM) standards. A Deep Convolutional Neural Network (DCNN) model based on modified pre-trained networks is designed and developed to extract features from raw data hierarchically. The proposed DCNN model is tested and investigated not only on the designed dataset but also on different datasets. One notable advantage of the present study is that it has made use of heterogeneous data. Another remarkable aspect of the proposed study is that the proposed DCNN model is independent of any specific languages which can be applied on various languages. The results of the study indicate that the proposed DCNN model can learn features hierarchically from the handwriting raw data and achieve higher accuracy than other comparative methods.

# Handwriting identification and verification using artificial intelligence-assisted textural features

## Abstract

  

Intelligent process control and automation systems require verification authentication through digital or handwritten signatures. Digital copies of handwritten signatures have different pixel intensities and spatial variations due to the factors of the surface, writing object, etc. On the verge of this fluctuating drawback for control systems, this manuscript introduces a Spatial Variation-dependent Verification (SVV) scheme using textural features (TF). The handwritten and digital signatures are first verified for their pixel intensities for identification point detection. This identification point varies with the signature’s pattern, region, and texture. The identified point is spatially mapped with the digital signature for verifying the textural feature matching. The textural features are extracted between two successive identification points to prevent cumulative false positives. A convolution neural network aids this process for layered analysis. The first layer is responsible for generating new identification points, and the second layer is responsible for selecting the maximum matching feature for varying intensity. This is non-recurrent for the different textures exhibited as the false factor cuts down the iterated verification. Therefore, the maximum matching features are used for verifying the signatures without high false positives. The proposed scheme’s performance is verified using accuracy, precision, texture detection, false positives, and verification time.

# A deep learning based system for writer identification in handwritten Arabic historical manuscripts

## Abstract

  

Determining the writer or transcriber of historical Arabic manuscripts has always been a major challenge for researchers in the field of humanities. With the development of advanced techniques in pattern recognition and machine learning, these technologies have been applied to automate the extraction of paleographical features in order to solve this issue. This paper presents a baseline system for writer identification, tested on a Historical Arabic dataset of 11610 single and double folio images. These texts were extracted from a unique collection of 567 Historical Arabic Manuscripts available at the Balamand Digital Humanities Center. A survey has been conducted on the available Arabic datasets and previously proposed techniques and algorithms. The Balamand dataset presents an important challenge due to the geo-historical identity of manuscripts and their physical conditions. An advanced Deep Learning system was developed and tested on three different Latin and Arabic datasets: ICDAR19, ICFHR20 and KHATT, before testing it on the Balamand dataset. The system was compared with many other systems and it has yielded a state-of-the-art performance on the new challenging images with 95.2% mean Average Precision (mAP) and 98.1% accuracy.

# A deep learning framework for historical manuscripts writer identification using data-driven features

## Abstract

  

Writer identification form historical manuscripts presents a challenging problem with significant implications for understanding the authorship of ancient texts. In this paper, we propose a novel deep learning framework tailored for the task of historical manuscripts writer identification. Our approach leverages data-driven features, harnessing the power of neural networks to extract and learn discriminative patterns from handwritten historical documents. The key innovation of our framework lies in its ability to automatically discover and utilize relevant features from data to profile the writer, eliminating the need for manual feature engineering. Our methodology encompasses three well-defined steps: initially, manuscript preprocessing involves image denoising using advanced techniques such as non-local means and total-variation, followed by binarization using a Canny-edge detector. In the subsequent phase, we employ Harris corner detector for automatic key-point detection and clustering, allowing us to identify the regions of interest within the documents. Lastly, the features extracted from these regions are subjected to classification through transfer learning, utilizing a deep learning-based model specifically trained on the extracted patches. To achieve the final document-level identification, we enhance the system accuracy by implementing a majority vote scheme, where the aggregated decisions from multiple patches contribute to the ultimate classification outcome. We validate our approach on “ICDAR 2017” dataset, spanning different periods and writing styles of historical manuscripts. Experimental results demonstrate the superior performance of our method in accurately identifying the authors of historical documents, surpassing existing techniques. Moreover, our framework exhibits robustness in scenarios where limited training data is available. This work not only contributes to the field of historical manuscripts analysis but also highlights the potential of deep learning in solving intricate problems in the realm of document analysis and authorship attribution. Our framework offers a promising avenue for scholars and historians to gain deeper insights into the authors of historical texts, opening new doors for historical research and preservation.

# Dynamics of Digital Pen-Tablet: Handwriting Analysis for Person Identification Using Machine and Deep Learning Techniques

## Abstract:

  

Handwriting is controlled by neurons in the brain’s nervous system, reflecting an individual’s personality and psychology. This unique characteristic can be used for various applications, including user authentication, assessment of neurodegenerative disorders, and classification of handedness, gender, and age groups. Traditional authentication systems require memorization, information leakage, and fingerprints, making them vulnerable to security breaches. The majority of researchers have studied the limitations of image quality, camera frames, and light effects on text and image-dependent performance. Therefore, this paper mainly focused on real-time, text-independent handwriting fine-motor data and proposed an efficient authentication system with low cost using efficient feature extraction and optimal feature selection approaches. This research utilizes two benchmark databases, including the handwriting data of 48 (24+24) participants collected via a sensor-based pen tablet. Each participant wrote the 10 words five times repeatedly, making it a total of 2400 samples. The handwriting classification of the different individuals is in 3 phases: feature extraction, feature selection, and classification. A total of 91 features (statistical, kinematic, spatial, and composite) were extracted from more accurate, real-time numerical handwriting data. The efficient and optimal features have been selected using four feature selection approaches, namely, Pearson’s r correlation, ANOVA-F, Mutual Information Gain, and PCA, among which the ANOVA-F test and PCA perform well for handwriting-extracted data. Then, 14 machine learning (ML) models and 7 deep learning (DL) models were applied to handle the problem of individual classification, with both no- and full-feature-selection scenarios considered. The experimental analysis has been conducted with different angles and perspectives, such as K-Fold cross-validation, testing system efficiency considering 5/10/15/24/48 individuals, and in the case of individual tasks. It shows that ML-based algorithms, namely, CATBOOST (99.07%) with ANOVA-F and DL-based models, namely, BiLSTM (98.31%) with PCA-selected features, provide the highest accuracy with dataset 2, among others that advocate the practicality and reliability of choosing this system for user identification.



## ***B. Signature verification/forgery detection***

  

# Enhancing Signature Verification Using Triplet Siamese Similarity Networks in Digital Documents

## Abstract

  

In contexts requiring user authentication, such as financial, legal, and administrative systems, signature verification emerges as a pivotal biometric method. Specifically, handwritten signature verification stands out prominently for document authentication. Despite the effectiveness of triplet loss similarity networks in extracting and comparing signatures with forged samples, conventional deep learning models often inadequately capture individual writing styles, resulting in suboptimal performance. Addressing this limitation, our study employs a triplet loss Siamese similarity network for offline signature verification, irrespective of the author. Through experimentation on five publicly available signature datasets—4NSigComp2012, SigComp2011, 4NSigComp2010, and BHsig260—various distance measure techniques alongside the triplet Siamese Similarity Network (tSSN) were evaluated. Our findings underscore the superiority of the tSSN approach, particularly when coupled with the Manhattan distance measure, in achieving enhanced verification accuracy, thereby demonstrating its efficacy in scenarios characterized by close signature similarity.

# Signature Forgery Detection and Verification using Deep Learning Techniques

## Abstract:

  

Signature Verification plays a vital role in this current digital era. This work is aimed at studying how signatures can be verified using image processing and Deep Learning methods for forgery detection. We implement Sobel edge detection techniques to allocate the features coming from original signature images and then fake ones, followed by the statistical analysis that inquires the color channels, shape and the average pixel values. Besides that, we do the LSTM and CNN models, which are used to recognize if the given signature is real or forged. LSTM model bases on the finding of flattened images, instead the convolutional layers are being applied for the feature extraction in CNN model. In this process, we plan to create a way to examine images and signatures in order to ensure the safety and higher level of security. We have attained a good accuracy by using the Convolution Neural Network.

# Siamese Convolutional Neural Network-Based Twin Structure Model for Independent Offline Signature Verification

## Abstract

  

One of the toughest biometrics and document forensics problems is confirming a signature’s authenticity and legal identity. A forgery may vary from a genuine signature by specific distortions. Therefore, it is necessary to continuously monitor crucial distinctions between real and forged signatures for secure work and economic growth, but this is particularly difficult in writer-independent tasks. We thus propose an innovative and sustainable writer-independent approach based on a Siamese neural network for offline signature verification. The Siamese network is a twin-like structure with shared weights and parameters. Similar and dissimilar images are exposed to this network, and the Euclidean distances between them are calculated. The distance is reduced for identical signatures, and the distance is increased for different signatures. Three datasets, namely GPDS, BHsig260 Hindi, and BHsig260 Bengali datasets, were tested in this work. The proposed model was analyzed by comparing the results of different parameters such as optimizers, batch size, and the number of epochs on all three datasets. The proposed Siamese neural network outperforms the GPDS synthetic dataset in the English language, with an accuracy of 92%. It also performs well for the Hindi and Bengali datasets while considering skilled forgeries.

# A Hybrid Method of Feature Extraction for Signatures Verification Using CNN and HOG a Multi-Classification Approach

## Abstract:

  

The offline signature verification system’s feature extraction stage is regarded as crucial and has a significant impact on how well these systems perform because the quantity and calibration of the features that are extracted determine how well these systems can distinguish between authentic and fake signatures. In this study, we introduced a hybrid method for extracting features from signature images, wherein a Convolutional Neural Network (CNN) and Histogram of Oriented Gradients (HOG) were used, followed by the feature selection algorithm (Decision Trees) to identify the key features. Finally, the CNN and HOG methods were combined. Three classifiers were employed to evaluate the efficacy of the hybrid method (long short-term memory, support vector machine, and K-nearest Neighbor). The experimental findings indicated that our suggested model executed satisfactorily in terms of efficiency and predictive ability, with accuracies of (95.4%, 95.2%, and 92.7%) the UTSig dataset, and (93.7%, 94.1%, and 91.3%, respectively) with the CEDAR dataset. This accuracy is deemed to be of high significance, particularly given that we checked skilled forged signatures that are more difficult to recognize than other forms of forged signatures like (simple or opposite).

## Offline signature verification using deep neural network with application to computer vision

## Abstract

  

Biometric technologies, such as handwritten signature verification, are extremely useful for identifying individuals inside an organization or finance department. The improvement of picture categorization using deep learning (DL) neural networks has offered an opportunity to exhibit computer vision in contemporary research applications by applying image processing approaches. Manual signature verification is inefficient, error-prone, time-consuming, and inconvenient; therefore, it is critical to create an automatic signature verification recognition system. This research offers an automatic recognition method based on DL that makes use of the Grupo de Procesado Digital de Seales. The biggest publicly accessible handwritten signature dataset, the synthetic signature dataset, was used to classify the signatures of 100 people, each of whom possessed 24 genuine signatures and 30 forged signatures. An inception V3 transfer learning (TL) model is proposed by hyper-tuning different layers from the middle of its architecture and this model is fine-tuned by adding layers, such as flatten, dense (1024), dropout (0.5), and dense (1). The suggested model was tested against six well-known pre-trained TL convolutional neural network models: VGG 16, VGG 19, ResNet 50, ResNet 101, MobileNet, and EfficientNet. The suggested model surpasses the pre-trained models. Precision, sensitivity, and F1-score are likewise outperformed by the model, with the values of 88%, 88%, and 87%, respectively. The accuracy of the pre-trained models was evaluated as 80%, 81%, 77%, 73%, 71%, and 74%, respectively. The suggested fine-tuned inception V3 gives the highest accurate classifications, distinguishing between genuine and forged signatures with an accuracy of 88%. This study will aid researchers in developing more effective CNN-based models for offline signature verification with application to computer vision.

# SigScatNet: A Siamese + Scattering based Deep Learning Approach for Signature Forgery Detection and Similarity Assessment

## Abstract:

  

The surge in counterfeit signatures has inflicted widespread inconveniences and formidable challenges for both individuals and organizations. This groundbreaking research paper introduces SigScatNet, an innovative solution to combat this issue by harnessing the potential of a Siamese deep learning network, bolstered by Scattering wavelets, to detect signature forgery and assess signature similarity. The Siamese Network empowers us to ascertain the authenticity of signatures through a comprehensive similarity index, enabling precise validation and comparison. Remarkably, the integration of Scattering wavelets endows our model with exceptional efficiency, rendering it light enough to operate seamlessly on cost-effective hardware systems. To validate the efficacy of our approach, extensive experimentation was conducted on two open-sourced datasets: the ICDAR SigComp Dutch dataset and the CEDAR dataset. The experimental results demonstrate the practicality and resounding success of our proposed SigScatNet, yielding an unparalleled Equal Error Rate of 3.689% with the ICDAR SigComp Dutch dataset and an astonishing 0.0578% with the CEDAR dataset. Through the implementation of SigScatNet, our research spearheads a new state-of-the-art in signature analysis in terms of EER scores and computational efficiency, offering an advanced and accessible solution for detecting forgery and quantifying signature similarities. By employing cutting-edge Siamese deep learning and Scattering wavelets, we provide a robust framework that paves the way for secure and efficient signature verification systems.

# Handwritten Signature Verification System using Deep Learning

## Abstract:

  

Every person has a unique signature, which is primarily used for identity documents and the authentication of significant documents or legal documentation. Static and dynamic signature verification are the two types of signature verification. The basic parameters that must be addressed when creating a signature verification system are user acceptance, the level of security necessary, accuracy, cost, and implementation. The objective of Signature verification used to determine whether a signature is real or a fake. This has proven to be a difficult endeavor, particularly in the offline scenario, which employs images of scanned signatures and does not have access to dynamic information about the signing process. The offline handwritten signature is one of the most essential biometrics used in banking systems, administrative, and financial applications. The study is to evaluate the performance of a few well-known deep convolutional neural networks as feature extractors in Handwritten Signature Verification (HSV) using transfer learning with activation function, as well as to review the available convolutional neural network signature verification methods. This is achieved by three pretrained models, VGG16, VGG19, and ResNet50, which are most often used generic models in computer vision tasks. Obtained experimental results, by comparing three models with SigComp2009 datasets and adding different parameters to each model. And conclude that VGG19 is best suitable for dataset, which has 97.83 percent accuracy than another model. These findings will help academics construct more effective Deep Learning-based signature verification methods.

# Deep Learning Approach to Offline Signature Forgery Prevention

## Abstract:

  

Image analytics solutions are very crucial for not only security, but also for authentication purposes. One such intriguing new Deep Learning application is automatic signature verification. Signed papers are the foundation of all transactions and governance in banks and government agencies, to mention a few examples. Verifying signatures on these documents is an important aspect of the back-office operations. Manual signature verification is not only time intensive, but also prone to mistakes and possible fraud. These flaws may be removed using AI-based automated signature analysis, resulting in considerable efficiency benefits. Based on the Siamese Neural Network, this research proposes an offline solution for signature identification and verification. To construct a feature vector, a collection of global features is utilised.

# DeepSignature: fine-tuned transfer learning based signature verification system

## Abstract

  

With the rapid advancement in computer science and information technology, the demand for authentication of a person in different organizations, institutions, banks or online trading, etc. is increasing day by day. Similarly, signature verification and recognition systems are frequently used for forgery and fraud detection. Signature authentication and verification have been important bio-metric traits for many decades. In this article, Convolutional Neural Network (CNN) architectures namely AlexNet, GoogleNet, ResNet, MobileNet, and DenseNet are examined and compared. Further, a fine-tuned transfer learning-based approach is also investigated to verify and identify the offline images of signatures. The evaluation has been done using Persian signatures of different persons using the UTSig dataset as a benchmark. The experimental analyses demonstrate that DenseNet architecture outperformed the other architectures of CNN.

# Real Time Signature Forgery Detection Using Machine Learning

## Abstract:

  

Every individual has their own signature, which is primarily used for personal identification and verification of vital papers or legal transactions. Even today, in many commercial instances, such as check payment, register office the signature verification process is still relied on a single known sample being reviewed by a human. The probability of two signatures made by the same person is very less. So, forgery detection becomes a huge task. The signatures that undergoing verification is not only difficult but also time consuming, especially when they are signed offline and no information about the procedure is available. To prevent the possibility of theft or fraud, a system that can distinguish between real and faked signatures is required. Before recognizing the signature is forged or not certain stages of pre-processing must be done for the images (signature) are acquired from the dataset since it is in raw form. The proposed work is based on off-line signature verification using deep learning model incorporating Convolution Neural Network (CNN) and novel method for extracting local features. This method can be used in various organizations where the number of individuals are confined so the model can train those before detecting any forged signatures in the future.

# Computer Vision-Based Signature Forgery Detection System Using Deep Learning: A Supervised Learning Approach

## Abstract:

  

Authentication is a crucial aspect of data security. It is one of the most important issues of our time. As technology advances, our interactions with machines are becoming increasingly automated. As a result, for a variety of security concerns, the demand for authentication is rapidly expanding. As a result, biometric-based authentication has become extremely popular. It has a significant edge over other approach. However, because different ways are utilized to verify people, this incidence is not a substitute for a problem. Signatures were one of the first commonly utilized biometric traits for identifying people. This paper describes a method for simplifying signature verification by preprocessing signatures. It also included a novel deep learning-based method for detecting faked signatures. With an accuracy of 85-95 %, the proposed method detects forgeries.

# Exploring offline signature verification techniques: a survey based on methods and future directions

## Abstract

  

One of the frequently used techniques of verifying a user as a legitimate or validated user is through signatures verification. Signature Verification could be achieved either through offline mode or by online mode. Due to limited resources required and widespread acceptance across the globe, offline signature verification is the most widely used signature verification technique. It has been carried out in several sectors including banking, finance, marketing and many other official institutes/organizations. Major challenge in the field of Offline Signature Verification (OSV) is the presence as well as the verification of forgeries in signatures. Various studies were proposed for signature verification purpose and they focused mainly on the usage of Machine Learning (ML) / Deep Learning (DL) based technologies in order to detect such forgeries in signatures, however barely few studies have described the survey that comprises of use of such recent technologies that has been used in signature verification task. Proposed work provides the categorical perspective of all the studies that were conducted in the field of OSV in recent times. Proposed study comprises of around 11 pre-existing as well as most prominent survey papers analysis summarization followed by providing novel categorical view of recent work being carried out in the field of OSV. Proposed study, along with providing most commonly used benchmark signature datasets description, primarily focuses on providing recent trends/ work (novel techniques/ ML/DL based work) that has been carried out in the field of OSV by considering 51 most prominent and relevant research papers, consolidating them in order to enlighten the work done in the field of OSV. Proposed study also provides various possible future trends/ researches that might be possible in the field of OSV.


  

## C. Exam/academic integrity fraud detection

  

# Cheating Detection in Online Exams Using Deep Learning and Machine Learning

## Abstract

  

This study aims to identify the best deep learning and machine learning models to identify the unethical behavior patterns of learners using distance education exam data of an educational institution. One hundred twenty-nine online exam data were analyzed by the researcher with three different scenarios to reveal the best model performance in regression and classification. For regression and classification, deep neural network (DNN) from deep learning algorithms and support vector machine (SVM), decision trees (DTs), k-nearest neighbor (KNN), random forest (RF), logistic regression (LR), and extreme gradient boosting (XGBoost) algorithms from machine learning algorithms were used. In the regression analysis conducted within the scope of Scenario-1, the model we proposed to detect “cheating” behavior, which is one of the unethical learner behaviors, was found to be a 5-layer DNN model with a test performance success of 80.9%. In the binary classification analysis for Scenario-2, students who “copied” from unethical behaviors were obtained with an accuracy rate of 96.9% by the model established by the 10-layer DNN algorithm we proposed. In the triple classification analysis for Scenario-3 defined in the study, the XGBoost model was found to have the highest accuracy rate of 97.7% for students who “cheated” due to unethical behaviors and the highest performance in all other metric values. In addition, SHAP and LIME methods, which are explanatory methods for the XGBoost model, which is one of the best-performing models, were applied, and the attributes and percentages affecting the model were shared. As a result of this study, it has been shown that the application of the most appropriate layer functions and parameter selection that will increase performance can be effective in estimating complex problems and target values that cannot be solved using classical mathematical models. The proposed models can provide educational institutions with a roadmap and insight in evaluating online examination practices and ensuring academic integrity. Future researchers may need more data sets and different analyses for better performance of the established models.

# Enhancing Academic Integrity in E-Exams Through AI-Driven Proctoring Technologies

## Abstract:

  

The rapid adoption of e-exams in education has revolutionized the assessment landscape, offering flexibility and accessibility to learners worldwide. However, this shift has also raised significant concerns about academic integrity. This study explores the role of artificial intelligence (AI)-driven proctoring technologies in mitigating cheating and fostering fairness in online examinations. Key features of AI-driven proctoring, including facial recognition, gaze tracking, keystroke analysis, and behavioral pattern detection, are analyzed for their effectiveness in ensuring a secure testing environment. The research highlights the challenges associated with these technologies, such as privacy concerns, potential biases, and technical limitations, while proposing solutions to address them. Through a mixed-methods approach combining case studies and surveys, the study evaluates the impact of AI-driven proctoring on student performance, engagement, and trust in e-exam systems. The findings suggest that integrating ethical AI practices and transparent communication can enhance academic integrity while maintaining learner confidence. This research contributes to the ongoing discourse on leveraging technology to uphold educational standards in an increasingly digital world.

# Reassessing academic integrity in the age of AI: A systematic literature review on AI and academic integrity

## Abstract

  

Academic integrity is a key factor in the quality of education that represents honesty, trust, and ethical conduct. In today's rapidly changing educational landscape, artificial intelligence (AI) poses significant challenges to the educational ecosystem's ability to maintain academic integrity. It also affects the qualifications offered by institutes. Although AI supports students in completing academic tasks, it usually risks violating the basic rules of academic integrity. In addition, AI can be used to detect academic misconduct. This study aims to critically examine the impact of AI on academic integrity through a [systematic literature review](https://www.sciencedirect.com/topics/social-sciences/systematic-review). The research question was developed using the PICO framework, and the articles considered in this study were collected from Scopus, PubMed, DOAJ, and [Base](https://www.sciencedirect.com/topics/pharmacology-toxicology-and-pharmaceutical-science/base). Of 1443 articles, 25 were selected based on the PRISMA framework. We used the Cochrane risk of bias tool (ROBINS-1) to analyse the risk of bias in the selected studies. The discussion section was developed based on PICO frameworks – population of the study, intervention with AI tools, comparison of modern and traditional methods, and outcome of AI use for academic activities – to answer the research question. This research contributes to the ongoing dialogue about AI and academic integrity by emphasising the importance of a balanced approach to using the benefits of AI in education while upholding ethical standards. This study concludes by emphasising the importance of creating a culture of academic integrity to ensure the ethical use of AI for educational purposes.

# A Delphi Study on Ethical Challenges and Ensuring Academic Integrity Regarding AI Research in Higher Education

### ABSTRACT

  

The rapid integration of artificial intelligence (AI) into higher education has revolutionised academic research and teaching, offered transformative opportunities while raising significant ethical challenges. This Delphi study investigates the ethical dilemmas and institutional requirements for maintaining academic integrity in AI-driven research. Through a structured, iterative process involving 12 international experts from academia, AI regulatory bodies, and research ethics committees, the study identifies key concerns such as data privacy, algorithmic bias, transparency, and authorship in AI-assisted research. The findings reveal a pressing need for clear ethical guidelines, robust institutional oversight, and enhanced collaboration between academia and industry to ensure responsible AI use. Experts emphasise the importance of developing enforceable policies, integrating AI ethics into academic curricula, and fostering transparency in AI decision-making processes. The study concludes that while AI offers immense potential for innovation, its ethical implications demand proactive governance and continuous policy refinement. By addressing these challenges, higher education institutions can uphold academic integrity, mitigate risks of misconduct, and promote the responsible development and application of AI technologies. This research provides actionable recommendations for policymakers, educators, and researchers, contributing to the creation of a sustainable and ethically sound AI ecosystem in academia.

  

# AI on Academic Integrity and Plagiarism Detection

## Abstract

  

Artificial Intelligence (AI) has introduced transformative advancements in academic integrity and plagiarism detection within educational institutions. This study explores how AI-driven tools are reshaping the landscape of academic honesty by enabling efficient and precise detection of plagiarised content, particularly in the face of sophisticated paraphrasing and AI-generated text. We analyse the effectiveness of traditional and AI-powered plagiarism detection tools, comparing their capabilities in recognising rephrased, translated, and synthetically generated content. Through a mixed-method approach, including quantitative tool performance analysis and qualitative insights from educators and students, the study assesses both the benefits and ethical challenges posed by AI in academic settings. Findings reveal that while AI significantly enhances detection accuracy, it raises concerns regarding dependency on automated assessments and ethical considerations in student evaluation. This research underscores the need for complementary human oversight and advocates for policy frameworks that guide the responsible integration of AI in academia.

  

# AI and Academic Integrity: Exploring Student Perceptions and Implications for Higher Education

## Abstract

  

The emergence of generative artificial intelligence tools, such as ChatGPT, presents new challenges impacting student perceptions of academic integrity. While extensive research exists on academic misconduct and student perceptions of various infractions, there is limited understanding of how AI tools impact these views and whether their use constitutes a violation of academic integrity policies. This study explores university students’ awareness and perceptions of academic misconduct, particularly concerning AI tool usage. A survey of domestic and international students enrolled at major universities in the United States received 277 valid responses. The results reveal high awareness of university integrity policies and significant concern about the use of AI for writing papers, with substantial variance in perceptions of misconduct severity. Notably, using AI to write entire papers is seen as major misconduct by a majority, while smaller AI-assisted tasks are viewed as less severe. Regression analysis highlights the importance of ethical education, revealing that students who view AI writing as cheating and those who believe cheating is unethical perceive academic misconduct more seriously. Conversely, student demographics (major, educational level, gender, international status), awareness of AI detection tools, and perceived ethics of AI use show complex, often non-significant relationships with perceptions of misconduct severity. These findings provide indication that education and clear policy about AI usage and academic misconduct could be useful in addressing a growing number of infractions in the face of emerging AI trends.

  

# Ensuring academic integrity in the age of ChatGPT: Rethinking exam design, assessment strategies, and ethical AI policies in higher education

# Abstract

  

The rapid advancement of artificial intelligence (AI) technologies, particularly OpenAI’s ChatGPT, has significantly impacted higher education institutions (HEIs), offering opportunities and challenges. While these tools enhance personalized learning and content generation, they threaten academic integrity, especially in assessment environments. This study systematically examines the impact of ChatGPT on academic integrity in HEIs, focusing on exam design, assessment strategies, AI detection tools, and policy frameworks. This research draws from current literature and expert recommendations to identify practical approaches for developing assessments that foster critical thinking and deep cognitive engagement, making them less susceptible to AI-generated content. Key areas explored include the creation of complex, analytical exam formats, deploying advanced AI detection software to counter AI-assisted cheating, and formulating institutional policies that promote the ethical use of AI. This comprehensive framework aims to equip educators and administrators with practical strategies to preserve academic standards while harnessing the potential benefits of AI, ensuring the continued validity of assessments in the AI-driven educational landscape.

# Striking Ethical Balance in AI-TAI: Promoting Academic Integrity through AI-Powered Tools

## Abstract:

  

Artificial intelligence (AI) is rapidly changing the landscape of academic integrity. AI-powered tools can be used to detect plagiarism, prevent cheating, and promote responsible research practices. However, there are also concerns about the ethical implications of using AI for academic integrity. This paper reviews the research on AI-powered academic integrity tools. It discusses the advantages and disadvantages of these tools, as well as the concerns that have been raised about their use. The paper also provides recommendations for how AI can be used to promote academic integrity in a responsible and ethical way. The conclusion of the paper states that AI-powered tools can be a valuable tool for promoting academic integrity. However, it is important to use these tools in a responsible and ethical way. This means being aware of the limitations of these tools, and using them in conjunction with other measures to promote academic integrity.The paper also calls for further research on the use of AI for academic integrity. This research should focus on the ethical implications of using these tools, as well as their effectiveness in detecting plagiarism and preventing cheating.


  

## D. Siamese networks/metric learning

# SigNet: Convolutional Siamese Network for Writer Independent Offline Signature Verification

Offline signature verification is one of the most challenging tasks in biometrics and document forensics. Unlike other verification problems, it needs to model minute but critical details between genuine and forged signatures, because a skilled falsification might often resembles the real signature with small deformation. This verification task is even harder in writer independent scenarios which is undeniably fiscal for realistic cases. In this paper, we model an offline writer independent signature verification task with a convolutional Siamese network. Siamese networks are twin networks with shared weights, which can be trained to learn a feature space where similar observations are placed in proximity. This is achieved by exposing the network to a pair of similar and dissimilar observations and minimizing the Euclidean distance between similar pairs while simultaneously maximizing it between dissimilar pairs. Experiments conducted on cross-domain datasets emphasize the capability of our network to model forgery in different languages (scripts) and handwriting styles. Moreover, our designed Siamese network, named SigNet, exceeds the state-of-the-art results on most of the benchmark signature datasets, which paves the way for further research in this direction.

# Multi-scale residual based siamese neural network for writer-independent online signature verification

## Abstract

  

How to extract effective features from a small number of signature samples provided by new registered users and achieve high accuracy authentication is a challenge for researchers in the field of online signature verification. In response to this challenge, we propose a novel writer-independent online signature verification method using the combin ation of one dimensional multi-scale residual based Siamese neural network (1D-MRSNet) and adaptive boosting softmax (ABSoftmax) classification. First of all, we propose a channel attention mechanism based Siamese neural network (CASNet) framework. The proposed CASNet framework can adaptively learn the weights of different signature feature sequences, which makes the network pay more attention to the information of important feature sequences. Since the proposed CASNet framework does not need to train the signature samples registered by new users, it effectively alleviated the problem of insufficient signature samples in practical applications. Next, a multi-scale residual attention mechanism (MSRA) block is proposed to automatically extract the multi-scale features of the signature, so as to improve the representation learning ability of the network. Then, the adaptive boosting (AdaBoost) algorithm is used to construct ABSoftmax classifier to achieve the integrated decision of online signature verification, thereby improving the accuracy of online signature verification. Finally, when using a reference sample, the proposed method has achieved 6.57% equal error rate (EER) and 11.74% EER in MCYT-100 database and SVC 2004-task2 database, respectively. When using five reference samples, the proposed has method achieved 1.38% EER and 2.33% EER in two databases respectively. The results illustrate the proposed method reached a state-of-the art level.

# Learning discriminative representations by a Canonical Correlation Analysis-based Siamese Network for offline signature verification

## Abstract

  

In offline signature verification tasks, capturing different writing behaviors between genuine and forged signatures is a crucial and challenging step. In this paper, a novel writer independent Canonical Correlation Analysis-based [Siamese Network](https://www.sciencedirect.com/topics/computer-science/siamese-neural-network) (CCASigNet) is proposed to learn discriminative representations between different signature pairs. Specifically, we first construct signature pairs with three types: genuine-genuine, genuine-forged, and forged-forged. Then, different signature pairs are fed into CCASigNet for training with the Canonical Correlation Analysis (CCA) and classification-based losses. After network training, we extract the feature of signatures by CCASigNet and use writer-dependent classifiers to construct a comprehensive [verification system](https://www.sciencedirect.com/topics/computer-science/verification-system). Extensive experiments on four benchmark signature datasets demonstrate that the proposed CCASigNet learns discriminative representations between different signature pairs and achieves state-of-the-art or competitive performance compared with advanced verification systems. In addition, the proposed CCASigNet has good [generalization ability](https://www.sciencedirect.com/topics/computer-science/generalization-ability) and is easy to transfer to different datasets with different language scripts within the realm of offline signature verification tasks.

# A novel fingerprint recognition method based on a Siamese neural network

## Abstract

  

Fingerprint recognition is the most widely used identification method at present. However, it still falls short in terms of cross-platform and algorithmic complexity, which exerts a certain effect on the migration of fingerprint data and the development of the system. The conventional image recognition methods require offline standard databases constructed in advance for image access efficiency. The database can provide a pre-processed image via a specific method that probably is compatible merely with the specific recognition algorithm. Then, the specific recognition algorithm starts the process of retrieving these specific pre-proessing images for recognition and inevitably will be blocked from other datasets. The proposed method in this research designed an embedded image processing algorithm based on a Siamese neural network in the recognition method that allows the proposed method to recognize images from any source without constructing a database for image storage in advance. In this research, the proposed method was applied to fingerprint recognition and evaluation of the proposed method was evaluated. The results showed that the accuracy of the proposed algorithm was up to 92%, and its _F_1 score was up to 0.87. Compared with the conventional fingerprint matching methods, its significant advantage in the FRR, FAR, and CR jointly indicated the remarkable correct recognition rate of the proposed method.

# Handwritten Signature Forgery Identification and Prediction using Harris Corner Detection and Siamese Network

## Abstract:

  

Signature is a powerful identity of a person for various legal acts, to authorize a transactions to avoid financial crimes. Now-a-days, we are using touch-sensitive pad for the verification of the signatures. Thus there is high risk of forgery to happen due to replicate the signature patterns. So it is essential to detection and verify the signatures while using public platforms to avoid crime of accessing the personal data. The advancements in image processing and artificial neural network helps in identifying and validating the real signature with the fack ones. This paper proposed a signature validation process using harris corner detection and Siamese neural network. Harris corner detector helps to extract the corners and infer the features of an signature image, whereas Siamese network identifies the pattern of signature by learning with the help of similarity function by taking the probability of the signature images. The proposed model achieves better accuracy of 98% for the new signature identification to the original signatures.

# Photoplethysmogram Biometric Authentication Using a 1D Siamese Network

## Abstract

  

In the head-mounted display environment for experiencing metaverse or virtual reality, conventional input devices cannot be used, so a new type of nonintrusive and continuous biometric authentication technology is required. Since the wrist wearable device is equipped with a photoplethysmogram sensor, it is very suitable for use for nonintrusive and continuous biometric authentication purposes. In this study, we propose a one-dimensional Siamese network biometric identification model using a photoplethysmogram. To maintain the unique characteristics of each person and reduce noise in preprocessing, we adopted a multicycle averaging method without using a bandpass or low-pass filter. In addition, to verify the effectiveness of the multicycle averaging method, the number of cycles was changed and the results were compared. Genuine and impostor data were used to verify the biometric identification. We used the one-dimensional Siamese network to verify the similarity between the classes and found that the method with five overlapping cycles was the most effective. Tests were conducted on the overlapping data of five single-cycle signals and excellent identification results were observed, with an AUC score of 0.988 and an accuracy of 0.9723. Thus, the proposed biometric identification model is time-efficient and shows excellent security performance, even in devices with limited computational capabilities, such as wearable devices. Consequently, our proposed method has the following advantages compared with previous works. First, the effect of noise reduction and information preservation through multicycle averaging was experimentally verified by varying the number of photoplethysmogram cycles. Second, by analyzing authentication performance through genuine and impostor matching analysis based on a one-dimensional Siamese network, the accuracy that is not affected by the number of enrolled subjects was derived.

# Siamese-Transformer Network for Offline Handwritten Signature Verification using Few-shot

## Abstract:

  

Handwritten signature verification is a crucial task with applications spanning authentication, financial transactions, and legal documents. In scenarios where only a single reference signature is available, the challenge of accurate verification becomes pronounced due to variations in writing styles, distortions, and limited labeled data. In this paper, we propose a novel Siamese-Transformer network tailored for handwritten signature verification using few-shot learning. By synergizing Siamese neural networks and Transformer architectures, our model excels in capturing contextual relationships and discerning genuine from forged signatures. A triplet loss function facilitates discriminative feature learning. Convolution layers extract local features from an image, while the transformer component utilizes these local features to capture global dependencies within signatures. Experimental results on benchmark datasets showcase the model’s superior performance in few-shot verification scenarios, marking it as a promising advancement in signature verification and few-shot learning techniques.

# Behavioral Biometrics Authentication in Critical Infrastructure Using Siamese Neural Networks

## Abstract

  

Cybersecurity is a crucial issue in today’s critical infrastructure to ensure a secure connection between the administrator and the session. Detecting insiders is a difficult task for cybersecurity professionals, as insiders are hard to detect and identify and thus require advanced techniques to prevent their activities. These users may be current or former employees with access to the organization’s data. A methodology for authenticating users of critical infrastructure systems using deep learning networks is proposed in this paper. Behavioral biometric data or user behavioral characteristics are converted into an image and used in the proposed methodology for authentication. The keystroke data obtained from the login password is transformed into a more acceptable format for deep neural networks. Siamese neural networks can be used for image similarity detection to distinguish a real user from an insider. In the current investigation, numerical keystroke data has been transformed into graphical representations. The transformed data are then subjected to comparative analysis, leading to the determination of similarities between the biometric keystroke profiles. The experiments have shown there is a tendency for the accuracy of a Siamese neural network with a triplet loss function to decrease with increasing margin size. The results obtained are promising, showing that using a deep learning-based approach to analyze images derived from user keystroke data can improve intrusion detection accuracy and perform user authentication more efficiently.

# FootprintNet: a Siamese network method for biometric identification using footprints

## Abstract

  

Biometric technologies are fast becoming a requirement in security systems today, providing solutions where traditional means alone would not be adequate. This paper proposes FootprintNet, a Siamese network that utilizes pre-trained convolutional neural networks, specifically EfficientNet, MobileNet, and ShuffleNet, to improve the robustness and accuracy of footprint recognition. By learning the ability to identify fine distinctions between images of footprints, FootprintNet offers great biometric identification potential. Detailed analysis of the Biometric 220 × 6 Human Footprint dataset shows a true positive rate over 99% under various thresholds and a precision rate of 100% during training. Most importantly, this system is also applicable to newborn and infant identification, making it especially significant in medical settings, including hospitals and birthing clinics. Furthermore, the model sizes range from 7.8 MB (ShuffleNet) to 24.5 MB (EfficientNet), which makes FootprintNet deployable on low-computational-power devices—a highly desirable trait for mobile or high-security applications.

# Siamese Neural Network for Keystroke Dynamics-Based Authentication on Partial Passwords

## Abstract

  

The paper addresses issues concerning secure authentication in computer systems. We focus on multi-factor authentication methods using two or more independent mechanisms to identify a user. User-specific behavioral biometrics is widely used to increase login security. The usage of behavioral biometrics can support verification without bothering the user with a requirement of an additional interaction. Our research aimed to check whether using information about how partial passwords are typed is possible to strengthen user authentication security. The partial password is a query of a subset of characters from a full password. The use of partial passwords makes it difficult for attackers who can observe password entry to acquire sensitive information. In this paper, we use a Siamese neural network and n-shot classification using past recent logins to verify user identity based on keystroke dynamics obtained from the static text. The experimental results on real data demonstrate that keystroke dynamics authentication can be successfully used for partial password typing patterns. Our method can support the basic authentication process and increase users’ confidence.

# Contactless Hand Knuckle Modality for Identity Verification Using Siamese Network

## Abstract:

  

People can be recognized by a lot of unique biometric features either physiological or behavioral. Therefore, a biometric security method for a smartphone is proposed in this paper for easier use and to improve recognition results by using a new knuckle modality: the major knuckle of the thumb finger modality instead of the major knuckle of the middle finger modality which is the most used in related works. In finger knuckle recognition domains, different CNN (Convolutional Neural Network) architectures have been applied, requiring a huge database. To deal with this problem, this paper presents a Siamese network for identity verification using contactless major knuckle of thumb finger modality. Actually, the Siamese network has been well used for one-shot learning that aims at learning and recognizing from little data. The FMK (Finger Major Knuckle) dataset was proposed and constructed for testing and evaluation. In fact, this study achieved good results with accuracy of 82% for the major knuckle of the left thumb finger and 79.63% for the major knuckle of the left middle finger.


  

## E. Explainability in forensic/biometric verification

  
  

# Explainable AI for Forensic Analysis: A Comparative Study of SHAP and LIME in Intrusion Detection Models

## Abstract

  

The lack of interpretability in AI-based intrusion detection systems poses a critical barrier to their adoption in forensic cybersecurity, which demands high levels of reliability and verifiable evidence. To address this challenge, the integration of explainable artificial intelligence (XAI) into forensic cybersecurity offers a powerful approach to enhancing transparency, trust, and legal defensibility in network intrusion detection. This study presents a comparative analysis of SHapley Additive exPlanations (SHAP) and Local Interpretable Model-Agnostic Explanations (LIME) applied to Extreme Gradient Boosting (XGBoost) and Attentive Interpretable Tabular Learning (TabNet), using the UNSW-NB15 dataset. XGBoost achieved 97.8% validation accuracy and outperformed TabNet in explanation stability and global coherence. In addition to classification performance, we evaluate the fidelity, consistency, and forensic relevance of the explanations. The results confirm the complementary strengths of SHAP and LIME, supporting their combined use in building transparent, auditable, and trustworthy AI systems in digital forensic applications.

# Explainable AI in Handwriting Detection for Dyslexia Using Transfer Learning

## Abstract:

  

This study introduces an explainable AI (XAI) framework for the detection of dyslexia through handwriting analysis, achieving an impressive test precision of 99.65%. The framework integrates transfer learning and transformer-based models, identifying handwriting features associated with dyslexia while ensuring transparency in decision-making via Grad-CAM visualizations. Its adaptability to different languages and writing systems underscores its potential for global applicability. By surpassing the classification accuracy of state-of-the-art methods, this approach demonstrates the reliability of handwriting analysis as a diagnostic tool. The findings emphasize the framework’s ability to support early detection, build stakeholder trust, and enable personalized educational strategies.

# Advanced Techniques for Biometric Authentication: Leveraging Deep Learning and Explainable AI

## Abstract:

  

Liveness face detection is essential for modern biometric systems, ensuring that input data is genuine and not derived from a false image or video. Liveness face detection in today’s biometric systems will ensure that input comes from a real, live person rather than a manipulated image or video. The novelty of this study lies in combining deep learning models with local interpretable model-agnostic interpretation (LIME) to enhance the interpretability and transparency of facial liveness detection systems. This technology is necessary for preventing spoofing attacks and attempts by hackers to break the security feature via pictures, videos, masks, etc. Spoofing refers to the compromise of a biometric system by providing it with untruthful material, photographs, videos, or masks to gain access. However, if not dealt with, such forms of fraud could affect the security of the biometrics. Liveness detection relies on several strategies, from basic facial actions like blinking and head twists to even more advanced algorithms that can identify natural skin texture and warmth or detect differences at the pixel level between live and static images. Robust liveness detection in biometric authentication significantly enhances security and reliability. The objective of this research is to test the different pre-trained models to detect spoofing attacks and to use LIME to explain the model’s predictions. This paper focuses on a dataset of Spoof in Wild with Multiple Attacks Version 2 (SiWMv2), comprising 14 different spoofing techniques, ranging from replay attacks and makeup disguises with paper glasses to more complex ones. Seven pre-trained architectures, VGG16, DenseNet201, InceptionV3, VGG19, ResNet50, MobileNetV2, and Xception, are fine-tuned with the potential for actual automatic liveness identification in facial images. Deep learning approaches achieve superior detection performance against contemporary spoofing techniques. These techniques aim to enhance the interpretability of their predictions. Building on deep learning approaches, LIME is incorporated to improve transparency further. LIME provides visual explanations of the prediction to represent what features support the.

# Explainable biometrics: a systematic literature review

## Abstract

  

Biometric systems are largely based on Machine Learning (ML) algorithms which are often considered as a black-box. There is a need to provide them with explanations to make their decision understandable. In this paper, we conduct a Systematic Literature Review aiming at investigating the present adoption of explainable Artificial Intelligence (XAI) techniques in biometric systems. By examining the biometric tasks performed by the selected papers (e.g., face detection or face spoofing), the datasets adopted by the different approaches, the considered ML models, the XAI techniques, and their evaluation methods. We started from 496 papers and, after an accurate analysis, selected 47 papers. Results revealed that XAI is mainly adopted in biometric systems related to the face biometric cues. The explanations provided were all based on model-centric metrics and did not consider how the end-users perceived the explanations, leaving wide space for the biometric researchers to apply the XAI models and enhance the explanation evaluation into an HCI perspective.

# SIFT: Sifting file types—application of explainable artificial intelligence in cyber forensics

## Abstract

  

Artificial Intelligence (AI) is being applied to improve the efficiency of software systems used in various domains, especially in the health and forensic sciences. Explainable AI (XAI) is one of the fields of AI that interprets and explains the methods used in AI. One of the techniques used in XAI to provide such interpretations is by computing the relevance of the input features to the output of an AI model. File fragment classification is one of the vital issues of file carving in Cyber Forensics (CF) and becomes challenging when the filesystem _metadata is missing_. Other major challenges it faces are: _proliferation of file formats_, _file embeddings_, _automation_, We leverage and utilize interpretations provided by XAI to optimize the classification of file fragments and propose a novel sifting approach, named SIFT (Sifting File Types). SIFT employs TF-IDF to assign weight to a byte (feature), which is used to select features from a file fragment. Threshold-based LIME and SHAP (the two XAI techniques) feature relevance values are computed for the selected features to optimize file fragment classification. To improve multinomial classification, a Multilayer Perceptron model is developed and optimized with five hidden layers, each layer with neurons, where _i_ = the layer number and _n_ = the total number of classes in the dataset. When tested with 47,482 samples of 20 file types (classes), SIFT achieves a detection rate of 82.1% and outperforms the other state-of-the-art techniques by at least 10%. To the best of our knowledge, this is the first effort of applying XAI in CF for optimizing file fragment classification.

# Explainable offline automatic signature verifier to support forensic handwriting examiners

## Abstract

  

Signature verification is a critical task in many applications, including forensic science, legal judgments, and financial markets. However, current signature verification systems are often difficult to explain, which can limit their acceptance in these applications. In this paper, we propose a novel explainable offline automatic signature verifier (ASV) to support forensic handwriting examiners. Our ASV is based on a universal background model (UBM) constructed from offline signature images. It allows us to assign a questioned signature to the UBM and to a reference set of known signatures using simple distance measures. This makes it possible to explain the verifier’s decision in a way that is understandable to non-experts. We evaluated our ASV on publicly available databases and found that it achieves competitive performance with state-of-the-art ASVs, even when challenging 1 versus 1 comparisons are considered. Our results demonstrate that it is possible to develop an explainable ASV that is also competitive in terms of performance. We believe that our ASV has the potential to improve the acceptance of signature verification in critical applications such as forensic science and legal judgments.

# Explainable Vision Transformers for Vein Biometric Recognition

## Abstract:

  

In the field of deep learning, understanding the rationale behind an automatic system’s decisions is essential for building users’ trust and ensuring accountability. In this regard, explainable artificial intelligence (XAI) recently emerged as a valuable tool to offer insights into a model behavior. The present study focuses on vein-based biometric recognition, investigating techniques allowing to identify which regions of a wrist-vein image are mostly exploited to carry out a verification process. Toward this aim, our research exploits vision transformers (ViTs), which rely on self-attention mechanisms to automatically detect and exploit the input parts with the content deemed most relevant for its further processing. Two distinct wrist-vein pattern datasets, namely PUT-wrist and FYO-wrist, are employed to fine-tune the considered models. Their behavior is interpreted by analyzing the attention maps generated when applying the trained networks to vein-pattern images, investigating which regions are exploited to decide a user’s identity. The proposed approach testifies that the performed recognition process can improve when a ViT focuses on areas with significant vein pattern content, achieving verification performance surpassing state-of-the-art methods in open-set scenarios, while promoting transparency through explainability.

# Revolutionizing User Authentication Exploiting Explainable AI and CTGAN-Based Keystroke Dynamics

## Abstract:

  

Due to the reliability and efficiency of keystroke dynamics, enterprises have adopted it widely in multi-factor authentication systems, effectively strengthening user authentication and thereby boosting the security of online and offline services. The existing works that detect imposter users suffer from performance and robustness degradation. Therefore, this article introduces a novel methodology to enhance user authentication and identify imposter users who attempt to have unauthorized access. We first use quantile transformation (QT) to mitigate outliers in the user's typing behavior that affects the authentication process and then employ conditional tabular generative adversarial networks (CTGAN) for data augmentation to learn the users' typing patterns better. Next, five accurate transfer learning models (VGG19, EfficientNetB0, Resnet50, MobileNetV2, and DenseNet121) are utilized for extracting effective features within the typing patterns, so our methodology can detect imposter users accurately and hence make precise decisions to enhance the user authentication process. Finally, we ensure transparency and trust in our user authentication methodology by incorporating explainable artificial intelligence (XAI), utilizing local interpretable model-agnostic explanations (LIME). Extensive experiments using a publicly available keystroke dynamics benchmark dataset from Carnegie Mellon University (CMU) showcase superior security performance and robustness using the proposed methodology compared to the state-of-the-art approaches.

# An Attention-Guided Framework for Explainable Biometric Presentation Attack Detection

## Abstract

  

Despite the high performances achieved using deep learning techniques in biometric systems, the inability to rationalise the decisions reached by such approaches is a significant drawback for the usability and security requirements of many applications. For Facial Biometric Presentation Attack Detection (PAD), deep learning approaches can provide good classification results but cannot answer the questions such as “Why did the system make this decision”? To overcome this limitation, an explainable deep neural architecture for Facial Biometric Presentation Attack Detection is introduced in this paper. Both visual and verbal explanations are produced using the saliency maps from a Grad-CAM approach and the gradient from a Long-Short-Term-Memory (LSTM) network with a modified gate function. These explanations have also been used in the proposed framework as additional information to further improve the classification performance. The proposed framework utilises both spatial and temporal information to help the model focus on anomalous visual characteristics that indicate spoofing attacks. The performance of the proposed approach is evaluated using the CASIA-FA, Replay Attack, MSU-MFSD, and HKBU MARs datasets and indicates the effectiveness of the proposed method for improving performance and producing usable explanations.


  

## F. Bangla writer/signature dataset gap-check

  

# BanglaWriting: A multi-purpose offline Bangla handwriting dataset

## Abstract

  

This article presents a Bangla handwriting dataset named BanglaWriting that contains single-page handwritings of 260 individuals of different personalities and ages. Each page includes bounding-boxes that bounds each word, along with the unicode representation of the writing. This dataset contains 21,234 words and 32,787 characters in total. Moreover, this dataset includes 5,470 unique words of Bangla vocabulary. Apart from the usual words, the dataset comprises 261 comprehensible overwriting and 450 handwritten strikes and mistakes. All of the bounding-boxes and word labels are manually-generated. The dataset can be used for complex optical character/word recognition, writer identification, handwritten word segmentation, and word generation. Furthermore, this dataset is suitable for extracting age-based and gender-based variation of handwriting.

  

## Development of a Lightweight Model for Handwritten Dataset Recognition: Bangladeshi City Names in Bangla Script

  

## ABSTRACT

  

The context of recognizing handwritten city names, this research addresses the challenges posed by the manual inscription of Bangladeshi city names in the Bangla script. In today’s technology-driven era, where precise tools for reading handwritten text are essential, this study focuses on leveraging deep learning to understand the intricacies of Bangla handwriting. The existing dearth of dedicated datasets has impeded the progress of Bangla handwritten city name recognition systems, particularly in critical areas such as postal automation and document processing. Notably, no prior research has specifically targeted the unique needs of Bangla handwritten city name recognition. To bridge this gap, the study collects real-world images from diverse sources to construct a comprehensive dataset for Bangla Hand Written City name recognition. The emphasis on practical data for system training enhances accuracy. The research further conducts a comparative analysis, pitting state-of-the-art (SOTA) deep learning models, including EfficientNetB0, VGG16, ResNet50, DenseNet201, InceptionV3, and Xception, against a custom Convolutional Neural Networks (CNN) model named “Our CNN.” The results showcase the superior performance of “Our CNN,” with a test accuracy of 99.97% and an outstanding F1 score of 99.95%. These metrics underscore its potential for automating city name recognition, particularly in postal services. The study concludes by highlighting the significance of meticulous dataset curation and the promising outlook for custom CNN architectures. It encourages future research avenues, including dataset expansion, algorithm refinement, exploration of recurrent neural networks and attention mechanisms, real-world deployment of models, and extension to other regional languages and scripts. These recommendations offer exciting possibilities for advancing the field of handwritten recognition technology and hold practical implications for enhancing global postal services.

# Performance Analysis of Few-Shot Learning Approaches for Bangla Handwritten Character and Digit Recognition

## Abstract:

  

Few-shot learning (FSL) offers a promising solution for classification tasks with limited labeled examples, offering a valuable solution for languages with limited annotated samples. Traditional deep learning research has largely centered on optimizing performance using large-scale datasets, yet constructing extensive datasets for all languages is both labor-intensive and impractical. FSL offers a compelling alternative, achieving effective results with minimal data. In this connection, this study investigates the performance of FSL approaches in Bangla characters and numerals recognition with limited labeled data, demonstrating their applicability to scripts with intricate and complex structures where dataset scarcity is prevalent. Given the complexity of Bangla scripts, we posit that models capable of performing well on these characters will generalize effectively to languages of similar or lower structural complexity. We introduce SynergiProtoNet, a hybrid network designed to enhance the recognition accuracy of handwritten characters and digits. Our model combines advanced clustering methods with a robust embedding framework to capture fine-grained details and contextual subtleties, leveraging multi-level (high- and low-level) feature extraction within a prototypical learning framework. We rigorously benchmark SynergiProtoNet against several state-of-the-art fewshot learning models, including BD-CSPN, Prototypical Network, Relation Network, Matching Network, and SimpleShot, across diverse evaluation settings. Our experiments-Monolingual Intra-Dataset Evaluation, Monolingual Inter-Dataset Evaluation, Cross-Lingual Transfer, and Split Digit Testing demonstrate that SynergiProtoNet consistently achieves superior performance, establishing a new benchmark in few-shot learning for handwritten character and digit recognition. The code is available on GitHub: https://github.com/MehediAhamed/SynergiProtoNet.

# Evaluating the Performance of Machine Learning Models in Handwritten Signature Verification

## Abstract:

  

Handwritten signatures remain a widely used method for personal authentication in various official documents, including bank checks and legal papers. The verification process is often labor-intensive and time-consuming, necessitating the development of efficient methods. This study evaluates the performance of machine learning models in handwritten signature verification using the ICDAR 2011 Signature and CEDAR datasets. The investigation involves preprocessing, feature extraction using CNN architectures, and optimization techniques. The most effective models undergo a rigorous evaluation process, followed by classification using supervised ML algorithms, such as linear SVM, random forest, logistic regression, and polynomial SVM. The results indicate that the VGG16 architecture, optimized with the Adam optimizer, achieves the satisfactory performance metrics. This study demonstrates the potential of ML methodologies to enhance the efficiency and accuracy of signature verification, offering a robust solution for document authentication.

# Evaluating the Tri-Script Writer Verification System Using a Handcrafted Features and Vision Transformer Learning Approach

## Abstract

  

A multi-script writer verification system poses a captivating research challenge in the fields of pattern recognition and computer vision. It entails the intricate task of authenticating the identities of writers who produce handwriting samples in various scripts. This scenario introduces complexities demanding robust techniques for accurate recognition across diverse scripts. In West Bengal, the native language is Bangla, with Hindi serving as the second language, while English finds use in official contexts. This study tackles the issue of block-level tri-script (Bangla, Hindi, and English) writer verification systems and presents promising results. The research demonstrates that a combination of handcrafted features outperforms automatically derived features, owing to limitations in the writers within the JUDVLP-TLWVdb dataset. Experimental results indicate that the SMO classifier outperforms other classifiers such as simple logistics and KNN. A novel dataset for writer verification systems using the tri-script approach is introduced, achieving a peak verification accuracy of 91.50% through a combination of Radon Transform, HOG, LBP, and LPQ features. The overall performance of the tri-script approach reaches 91.80%. Furthermore, this study employs the Vision Transformer (ViT) model for writer recognition, showcasing superior performance in comparison to ViT using tri-level block images of the page.

# SEN: Stack Ensemble Shallow Convolution Neural Network for Signature-based Writer Identification

## Abstract:

  

Signature-based writer identification (SWI) is an automated segmentation-free holistic approach where a person is identified based on their handwritten signature. Earlier research attempts mainly featured learning-based approaches where writing patterns were detected and fed to machine learning models for determining the writer. Nowadays, a deep learning-based approach is becoming very popular and several works are reported in the literature using such models. In this paper, we propose a two-stage convolution neural network (CNN) architecture that has two properties: (i) at first, two state-of-the-art CNN models namely VGG-19 and EfficientNet-B0 were truncated making them lightweight; (ii) Secondly, a stack ensemble network (SEN) was proposed where the truncated architectures were stacked along with a shallow base CNN model. The proposed system experimented on a newly built multi-script offline signature dataset where three popular Indic scripts namely: Bangla, Roman and Devanagari were considered. The proposed SEN outperforms individual CNN architectures in terms of recognition rate. In addition, the system converges considerably fast as the SEN architecture is shallower compared to heavier traditional networks. Overall, we obtained the highest writer identification accuracy of 99.44%, 99.04%, and 98.61% for Bangla, Roman, and Devanagari, respectively, by the proposed SEN architecture. Furthermore, the dataset used in this paper will be available freely for research purposes from the link mentioned in Section III.

# SWIS: Self-Supervised Representation Learning for Writer Independent Offline Signature Verification

## Abstract:

  

Writer independent offline signature verification is one of the most challenging tasks in pattern recognition as there is often a scarcity of training data. To handle such data scarcity problem, in this paper, we propose a novel self-supervised learning (SSL) framework for writer independent offline signature verification. To our knowledge, this is the first attempt to utilize self-supervised setting for the signature verification task. The objective of self-supervised representation learning from the signature images is achieved by minimizing the cross-covariance between two random variables belonging to different feature directions and ensuring a positive cross-covariance between the random variables denoting the same feature direction. This ensures that the features are decorrelated linearly and the redundant information is discarded. Through experimental results on different data sets, we obtained encouraging results.

# Multi-scale CNN-CrossViT network for offline handwritten signature recognition and verification

## Abstract

  

Developing technologies that can accurately identify and highlight subtle differences in signatures is crucial for improving the performance of signature recognition and verification. Especially for writer independent offline handwritten signature verification technology that can directly verify the authenticity of the signature without the need for additional training on unknown new writers. However, with the continuous advancement of forgery technology, the differences in features between forgery signatures and genuine signatures have become increasingly subtle, which undoubtedly increases the difficulty of signature verification. To address this challenge, we introduced the cross-attention vision transformer (CrossViT) and constructed a hybrid architecture that combines convolutional neural networks (CNN) to extract stronger multi-scale features from signature images. In the CrossViT branch, depth features of different sizes image blocks are extracted, and information exchange with another branch is achieved through a token based cross-attention mechanism. This hybrid architecture fully utilizes the local feature extraction capability of CNN and the global feature capture capability of CrossViT, improving the accuracy and robustness of feature extraction. In addition, in order to make distance metric methods more applicable for writer independent signature verification in real-world scenarios, we propose an adaptive threshold method that can automatically obtain the optimal threshold from the training set and apply it to writer independent signature verification tasks. To verify the effectiveness of the proposed method, we conducted experiments on publicly available Latin, Bengali and Hindi signature datasets, including recognition, verification and cross dataset validation. The experimental results show that the proposed method achieved recognition accuracy of 98.85% and 97.40% on CEDAR and MCYT datasets using only 25% of the training data, and achieved the highest validation accuracy of 95.12% and 92.33% on Bengali and Hindi datasets, which is a significant advantage compared to other advanced methods.

  

## Recognition of handwritten characters from Devanagari, Bangla, and Odia languages using transfer-learning-based VGG-16 networks

## ABSTRACT

  

Despite promising results in character recognition techniques, research on handwritten characters from Indian regional scripts is still limited. In fact, most character recognizers in Indian languages are far less accurate than those built for English alphanumeric characters. Traditional techniques rely on extracted characteristics that require extensive knowledge of the chosen script, which is never practical. In such a circumstance, automatically extracting features may create interest. This study demonstrates how deep CNN VGG-16 networks can be used to increase character recognition accuracy. We have used nine different datasets from three separate Indian regional languages, Devanagari, Bangla, and Odia, to validate the model's efficacy further. When the samples were very noisy, it was revealed that the VGG model performed exceptionally well. The model recognized up to 3% better accuracy when the input samples were noisy and without applying any preprocessing. Furthermore, the model was implemented via transfer learning rather than being trained from scratch. This accomplishment could pave the way for constructing an automatic character recognition system for Indian regional scripts. The model outperforms recognition accuracy by around 1% for two datasets, cMATERdb 3.1.2 Bangla Basic and NITROHCS_V1.0 Odia Basic, compared to the existing approaches in the literature.

  

## Handwritten Bengali Alphabets, Compound Characters and Numerals Recognition Using CNN-based Approach

  

## Abstract:

  

Accurately classifying user-independent handwritten Bengali characters and numerals presents a formidable challenge in their recognition. This task becomes more complicated due to the inclusion of numerous complex-shaped compound characters and the fact that different authors employ diverse writing styles. Researchers have recently conducted significant researches using individual approaches to recognize handwritten Bangla digits, alphabets, and slightly compound characters. To address this, we propose a straightforward and lightweight convolutional neural network (CNN) framework to accurately categorize handwritten Bangla simple characters, compound characters, and numerals. The suggested approach exhibits outperformance in terms of performance when compared too many previously developed procedures, with faster execution times and requiring fewer epochs. Furthermore, this model applies to more than three datasets. Our proposed CNN-based model has achieved impressive validation accuracies on three datasets. Specifically, for the BanglaLekha isolated dataset, which includes 84-character classes, the validation accuracy was 92.48%. On the Ekush dataset, which includes 60-character classes, the model achieved a validation accuracy of 97.24%, while on the customized dataset, which includes 50- character classes, the validation accuracy was 97.03%. Our model has demonstrated high accuracy and outperformed several prominent existing frameworks.


  

## G. Evaluation methodology

# t-EER: Parameter-Free Tandem Evaluation of Countermeasures and Biometric Comparators

## Abstract:

  

Presentation attack (spoofing) detection (PAD) typically operates alongside biometric verification to improve reliablity in the face of spoofing attacks. Even though the two sub-systems operate in tandem to solve the single task of reliable biometric verification, they address different detection tasks and are hence typically evaluated separately. Evidence shows that this approach is suboptimal. We introduce a new metric for the joint evaluation of PAD solutions operating in situ with biometric verification. In contrast to the tandem detection cost function proposed recently, the new tandem equal error rate (t-EER) is parameter free. The combination of two classifiers nonetheless leads to a set of operating points at which false alarm and miss rates are equal and also dependent upon the prevalence of attacks. We therefore introduce the concurrent t-EER, a unique operating point which is invariable to the prevalence of attacks. Using both modality (and even application) agnostic simulated scores, as well as real scores for a voice biometrics application, we demonstrate application of the t-EER to a wide range of biometric system evaluations under attack. The proposed approach is a strong candidate metric for the tandem evaluation of PAD systems and biometric comparators.

# A multi-dimensional review on handwritten signature verification: strengths and gaps

## Abstract

  

A handwritten signature is the most widely accepted method to authenticate an individual in banking, financial, business transactions, cheque processing, access control, and e-business due to its simplicity and distinctiveness. Many automated systems have been created to predict the authenticity of a signature. However, barely a few review papers provide a summary of the existing research on deep learning-based signature verification systems. An attempt is made to bring out the strengths and find gaps in handwritten signature verification in various dimensions considering both online and offline signatures. The primary objective of this comprehensive study is to present the most recent deep learning-based models for signature verification systems by putting emphasis on five different aspects: datasets, preprocessing techniques, feature extraction methods, machine learning-based verification models, and performance evaluation metrics. This review includes publications on both offline and online signature verification systems published between 2017 and 2022. This systematic review has discovered that recently, the deep learning-based neural network accomplished the most encouraging results for signature verification systems on public datasets. This comprehensive review revealed that recently, the deep learning-based neural network attained the most promising results for signature verification systems on public datasets. This article distinguishes itself from other reviews by revealing the twelve most significant research areas for researchers. (1) Intra-personal and inter-personal variability. (2) Few-shot Learning. (3) Offline signature recovery from online signature and vice versa. (4) Device Interoperability issues in the multi-device scenario. (5) Extracting signatures from Real World Document images. (6) Signature segmentation using Hyper Spectral Imaging. (7) Signatures as a means of retrieval of documents. (8) Multiscript Signature Verification Systems. (9) Automatic health state assessment. (10) Ensemble of Classifiers. (11) Synthetic Signature Generation. (12) Transfer Learning.

# A novel biometric system for signature verification based on score level fusion approach

## Abstract

  

The active modality of handwriting is broadly related to signature verification in the context of biometric user authentication systems. Signature verification aims to verify a questioned signature as being genuine or forged compared to some previously provided signatures from the claimed person. By doing so, we may be able to verify a person’s identity at accuracy and speed even better than human performance. Application areas of signature verification include different purposes and principally in access controls and forensic document examination. This work presents a novel biometric system for signature verification. We propose a new model that we called the Extended Beta-elliptic model and we integrate the fuzzy elementary perceptual codes (FEPC) to extract static and dynamic features. To discriminate the genuine and forgery signatures of a user, we explore a fusion using the sum rule combiner of three scores which are deep bidirectional long short-term memory (deep BiLSTM), support vector machine (SVM) with Dynamic Time Warping (DTW), and SVM with a new proposed parameter comparator. Our system has been evaluated on two publicly available online signature databases namely SVC2004 Task 2 and MCYT-100, and it shows promising performance gains.

# Offline Signature Verification with Auto Encoder CNN Hybrid Feature Extraction for Improved Fake Signature Detection

## Abstract:

  

Signature verification is also one of the most popular forms of biometric authentication, particularly when there is offline authentication, e.g. cheques, forms, letters and official documents. Accurate verification is essential since the signature of each person is unique, and this can help stop fraud. Nonetheless, the loss of human verification is usually susceptible to mistakes and irregularity. A hybrid solution to the offline signature verification through Convolutional Neural Networks (CNN) that integrates with Autoencoder-based data augmentation to enhance the detection of fake signatures is presented in this paper. A Writer-Dependent model is applied in which random distortions are produced on authentic signatures with the help of an autoencoder to produce counterfeit signatures. The CNN classifier is then trained using them. The paper describes the pre-processing procedures applied to the signature images, and gives experimental results under different conditions of varying the number of training samples. In the Persian signature dataset, the model was trained on 22 genuine images per user and its average test accuracy was 83%. At the lower reduction in the number of real training samples (9), accuracy was decreased by 9.4 percent, which indicates that the amount of training data does affect verification performance.

# Framework for Biometric User Authentication Based on a Dynamic Handwritten Signature

## Abstract

  

We developed the framework for biometric user authentication based on dynamic handwritten signature recognition using a graphics tablet. The framework was developed in the Scilab mathematical package with integration with C++ development environment. We considered the definition of the dynamic handwritten signature by the set of discrete functions (values of signals) received through different channels. We developed the mathematical models and algorithms for signature receiving, training, and recognition modules, taking into account the fuzzy nature of signatures and the presence of possible fakes. We presented the results of experimental studies of suggested models and algorithms. We determined the best parameters to get the minimum error rate. FAR and EER error rate values were considered. It was found that the recognition accuracy of the developed framework exceeds the accuracy of other well-known methods. The proposed framework can be used as a component of public service delivery, as well as in automated document flow systems.

# Biometric systems for identification and verification scenarios using spatial footsteps components

## Abstract

  

Humans are distinguished by their walking patterns; many approaches, including using various types of sensors, have been used to establish walking patterns as biometrics. By studying the distinguishing features of a person's footsteps, footstep recognition may be utilized in numerous security applications, such as managing access in protected locations or giving an additional layer of biometric verification for secure admittance into restricted regions. We proposed biometric systems for verifying and identifying a person by acquiring spatial foot pressure images from the values obtained from the piezoelectric sensors using the Swansea Foot Biometric Database, which contains 19,980 footstep signals from 127 users and is the most prominent open-source gait database available for footstep recognition. The images acquired are fed into the ConvNeXt model, which was trained using the transfer learning technique, using 16 stride footstep signals in each batch with an Adam optimizer and a learning rate of 0.0001, and using sparse categorical cross-entropy as the loss function. The proposed ConvNeXt model has been adjusted to acquire 512 feature vectors per image, and these feature vectors are used to train the logistic regression models. We propose two biometric systems. The first biometric system is based on training one logistic regression model as a classifier to identify 40 different users using 1600 signals for training, 6697 signals for validation, and 200 signals for evaluation. The second biometric system is based on training 40 logistic regression models, one for each user, to validate the user's authenticity, with a total number of 2363 training signals, 7077 validation signals, and 500 evaluation signals. Each of the 40 models has a 40-training signal per client and a different number of signals per imposter, a different number of signals for the validation that ranges between 8 and 650 signals, a 5-signal for an authenticated client, and a different number of signals per imposter for evaluation. Independent validation and evaluation sets are used to evaluate our systems. In the biometric identification system, we obtained an equal error rate of 15.30% and 21.72% for the validation and evaluation sets, while in the biometric verification system, we obtained an equal error rate of 6.97% and 10.25% for the validation and evaluation sets.

# Sensing In-Air Signature Motions Using Smartwatch: A High-Precision Approach of Behavioral Authentication

## Abstract:

  

By virtue of the stability of signatures and the high difficulty of imitation, handwriting signatures, as an important behavioral biometric trait, have been broadly adopted for authorization and identity verification. The emergence of consumer-level wrist-worn devices incorporating rich sensors has profoundly changed human-machine interactions, enabling new signature observation method. In this study, we investigate the feasibility of authenticating users by sensing hand motions of signing in air using fingers. Each signature is represented by the readings of the gyroscope and accelerometer which are compensated by the device attitude readings. A recurrent neural network-based algorithm is proposed to characterize signatures and accurately determine whether a signature is from the claimed genuine user or an imposter. We empirically investigate 22 participants by recording their in-air signing gestures using smartwatch motion sensors. The verification shows that despite the inevitable variability of repeating genuine signature drawing, forged signatures tend to show more dissimilarity than variability. The high-precision experimental result (i.e., equal error rate of 0.83%) against insider adversaries not only demonstrates the effectiveness of our proposed approach but also indicates the feasibility of a more user-friendly signature authentication method by signing their names in the air. Moreover, we investigate the impact of the properties of motion sensory data on signature authentication. In addition, we include more details of the experiments, validation of the proposed pre-processing method, and analysis of the circumvention as one of the desirable properties of biometrics of signing motions by measuring the skill of forgery.

# BrainNet: Improving Brainwave-based Biometric Recognition with Siamese Networks

## Abstract:

  

With the advent of consumer wearables that capture brain activity, the use of brainwaves to verify a user's identity has been proposed as a convenient alternative to passwords. While recent work on brain biometrics shows feasible performance, it falls short in considering practical applicability. We propose a new solution, BrainNet, which trains a Siamese Network to measure the similarity of two electroencephalogram (EEG) inputs, and uses time-locked brain reactions instead of continuous mental activity to improve accuracy. This approach removes the need for retraining the brainwave recognition system, a common pitfall in current solutions, facilitating practical deployment. Furthermore, BrainNet achieves Equal Error Rates (EERs) of 0.14% in verification mode and 0.34% in identification mode, outperforming the state of the art even when evaluated under unseen attacker scenarios.

# On error reduction by the symmetric rejection method in multi-stage biometric verification systems

## Abstract

  

A multi-stage biometric verification system serially activates its verifiers and improves performance-cost trade-off by allowing users to submit a subset of the available biometrics. In the heart of a verifier in multi-stage systems lies the concept of ‘reject option’ where a reject region is used to identify a bad quality test sample. If the match-score falls inside the reject region, no binary (genuine/impostor) decision is made in the current stage and the verifier in the next stage is activated. Recent studies have demonstrated a significant promise of the ‘symmetric rejection method’ in choosing a suitable reject region for multi-stage verification systems. In this paper, we delve into the symmetric rejection method to gain more insights into its error reduction capabilities. Specifically, we develop a theory which mathematically proves that the symmetric rejection method reduces the false accept rate and false reject rate. Then, we empirically validate our theory. Results show that the symmetric rejection method significantly reduces the error rates, both the false accept rate and false reject rate.

# Keystroke Verification Challenge (KVC): Biometric and Fairness Benchmark Evaluation

## Abstract:

  

Analyzing keystroke dynamics (KD) for biometric verification has several advantages: it is among the most discriminative behavioral traits; keyboards are among the most common human-computer interfaces, being the primary means for users to enter textual data; its acquisition does not require additional hardware, and its processing is relatively lightweight; and it allows for transparently recognizing subjects. However, the heterogeneity of experimental protocols and metrics, and the limited size of the databases adopted in the literature impede direct comparisons between different systems, thus representing an obstacle in the advancement of keystroke biometrics. To alleviate this aspect, we present a new experimental framework to benchmark KD-based biometric verification performance and fairness based on tweet -long sequences of variable transcript text from over 185,000 subjects, acquired through desktop and mobile keyboards, extracted from the Aalto Keystroke Databases. The framework runs on CodaLab in the form of the Keystroke Verification Challenge (KVC). Moreover, we also introduce a novel fairness metric, the Skewed Impostor Ratio (SIR), to capture inter - and intra -demographic group bias patterns in the verification scores. We demonstrate the usefulness of the proposed framework by employing two state-of-the-art keystroke verification systems, TypeNet and TypeFormer, to compare different sets of input features, achieving a less privacy-invasive system, by discarding the analysis of text content (ASCII codes of the keys pressed) in favor of extended features in the time domain. Our experiments show that this approach allows to maintain satisfactory performance.


title

Explainable Exam Impersonation Detection Using Handwriting and Signature Biometrics

2. Exam Impersonation Detection (Sayed)
A. Writer verification/identification
•	("writer verification" OR "writer identification") AND (handwriting OR "handwritten text") AND ("deep learning" OR CNN)
•	("offline handwriting" OR "online handwriting") AND verification AND biometric
B. Signature verification/forgery detection
•	("signature verification" OR "signature forgery") AND detection AND ("deep learning" OR CNN OR siamese)
•	("offline signature" OR "online signature") AND verification AND ("skilled forgery" OR "random forgery")
C. Exam/academic integrity fraud detection
•	("exam fraud" OR "academic integrity") AND (detection OR AI OR "machine learning")
•	("impersonation detection" OR "identity fraud") AND (exam OR assessment OR test-taking)
•	("proxy" OR "ghost writer" OR "answer script") AND (fraud OR impersonation OR detection) AND education
D. Siamese networks/metric learning — ✅ Type 1 (anchor: handwriting/signature/biometric present)
•	("siamese network" OR "siamese neural network") AND (verification OR matching) AND (handwriting OR signature OR biometric)
•	("metric learning" OR "triplet loss" OR "contrastive learning") AND (writer OR signature OR handwriting)
E. Explainability in forensic/biometric verification — ✅ Type 1 (anchor present)
•	("explainable AI" OR XAI OR "Grad-CAM" OR LIME) AND (forensic OR signature OR handwriting OR biometric)
•	("forensic document examination" OR "questioned document examination") AND ("machine learning" OR AI OR "deep learning")
F. Bangla writer/signature dataset gap-check
•	(Bangla OR Bengali) AND ("writer verification" OR "signature verification" OR "handwriting biometrics") AND dataset
G. Evaluation methodology — ✅ Type 1 (anchor present)
•	(EER OR "equal error rate") AND (signature OR handwriting OR biometric) AND verification
•	(FAR OR FRR OR "false acceptance rate") AND biometric AND verification


---
Here are the abstracts of all the literature I've collected on this topic,
organized by sub-section. Please look at all of them carefully and help me
refine my research goals and title.

Tell me:
- what type of data I should collect, gather, or modify
- how I should conduct the research
- a final research title, clear goals, and a dataset description
- the baseline(s) I should aim to match or beat


