# studious-fishstick
### AI-900 Exam Preparation 

Register for AI-900 
https://learn.microsoft.com/en-us/credentials/certifications/exams/ai-900/
https://learn.microsoft.com/en-us/credentials/certifications/register-schedule-exam

### AI-900 Exam Topics: 
1. Describe Ai Workloads & Considerations 
2. Fundamental Principles of ML on Azure 
3. Computer Vision on Azure 
4. NLP on Azure 
5. Generative AI Workloads on Azure

# Artificial Intelligence

### Areas of AI 
1. Machine Learning 
2. Natural Language Processing 
3. Perception

### 6 Principles of AI
1. **Fairness
2. **Reliability and safety 
3. **Privacy and security 
4. **Inclusiveness 
5. **Accountability/Responsibility
7. **Transparency
### AI Workloads 
- Prediction & Demand Forecasting 
- Anomaly detection 
- Computer Vision 
- NLP
- Knowledge Mining - Cognitive Search 
- Content Moderation
- Generative AI 
# Machine Learning 
- Recognize 
- Predict 
- Categorize 
- Understand 
### Supervised Learning: Humans label the data to give general guidance
- Regression 
- Classification 
### Unsupervised learning: The ability to find patterns in data 
- Clustering 
- _Anomaly detection_ 
- _Association_

### Supervised Learning
In supervised learning, humans provide labeled training data and give the algorithm a clear guidance of what our predictions should look like. The goal is to learn a general rule that maps inputs to outputs. There are two main types of tasks in supervised learning:
- **Regression**: This is a type of problem where we predict a continuous outcome variable (Y) based on the value of one or multiple predictor variables (X). For example, predicting house prices based on features like number of rooms, location, size etc.
- **Classification**: In classification, the goal is to predict the categorical class labels of new instances, based on past observations. Those classes are often called as targets, labels or categories. For example, predicting if an email is spam or not spam.
### Unsupervised Learning
Unsupervised learning is a type of machine learning that looks for previously undetected patterns in a data set with no pre-existing labels and with a minimum of human supervision. Key methods in unsupervised learning include:
- **Clustering**: This is a technique used to group data points or items into several groups based on the similarity of features. The goal is to partition the data into clusters such that the data points in the same cluster are more similar to each other than to those in other clusters. For example, customer segmentation in marketing.
- **Anomaly detection**: This is the identification of rare items, events or observations which raise suspicions by differing significantly from the majority of the data. For example, detecting fraudulent transactions in banking.
- **Association**: Association rules allow you to establish associations amongst data objects inside large databases. This unsupervised technique is about discovering interesting relationships hidden in large data sets. For example, people that buy a new home most likely buy new furniture as well.

Computer Vision is an AI field that helps computers understand and interpret the visual world, while Custom Vision is a Microsoft Azure service that allows developers to create their own image classifiers. Both contribute to the development of computer vision models.

Natural Language Processing (NLP) is an AI branch that focuses on computer-human interaction through natural language. NLP involves speech recognition, natural language understanding, and natural language generation. It is used in applications like translation, sentiment analysis, chatbots, and voice assistants, enabling more natural interactions between humans and technology.

![[Pasted image 20240305160341.png]]

![[Pasted image 20240306162812.png]]


NoCode ML: AutoML 
**Azure ML Designer:** More control than AutoML and allow examining data. (Also No code approach) (low code approach)
- Drag dataset onto the designer canvas 
- examine and visualize 
- Exclude columns 
- clean rows with missing data 
- Normalization - make the columns more standardized through transformations
### Computer Vision: 
Object Detection -
Semantic Segmentation - 
Optical Character Recognition -
Facial Detection and Recognition - 

**Computer Vision vs. Custom Vision:**
**Computer Vision** is a field of artificial intelligence that trains computers to interpret and understand the visual world. It involves methods for acquiring, processing, analyzing, and understanding digital images, and extraction of high-dimensional data from the real world in order to produce numerical or symbolic information. This can be used in controlling events, understanding context, recognizing patterns, navigation for robots, organizing information, modeling objects or environments, and more. On the other hand, **Custom Vision** is a specific service provided by Microsoft Azure. It's a part of Azure's Cognitive Services, and it allows developers to build, deploy and improve their own image classifiers. It's a tool that makes it easier to develop your own computer vision model, even if you don't have extensive machine learning expertise. You can train your model with your own images, tag them, and then use the trained model to identify the content of images. In summary, while Computer Vision is a broad field, Custom Vision is a specific tool that helps you create your own computer vision models.

Computer Vision Tools:

_Azure Cognitive Services - Umbrella for what follows_
Computer Vision Service - 
- Pretrained ML Model
- Can recognize over 10,000 objects 
- Can generate automatic caption for images and tags 
- Content moderation for adult, racy or gory content
- Detect faces 
- Text recognition 

Custom Vision Service - (separates out training and prediction into two resources)
- A model you can build and train 
- Classification or object detection 
- Upload an existing dataset of images and classes 
- Publish them for public use 

Face Service - (Similar Faces/ Face Grouping/ Identify API
- Can recognize a human face in an image 
- Returns the rectangle coordinates of those 1 or more faces 
- Can recognize celebrities 
- Needs to be trained with your own data 

Form Recognizer Service - 
- Ideal for invoices and receipts 
- Pre-built model or custom model 
- Pre-built model recognizes common receipt formats

### Natural Language Workloads: 
 ### **Natural Language Processing (NLP)**:
A branch of artificial intelligence that deals with the interaction between computers and humans through the natural language. The ultimate objective of NLP is to read, decipher, understand, and make sense of the human language in a valuable way.
NLP involves several challenges and complexities, including:
1. **Speech Recognition**: This involves identifying and processing human speech into a written format. Popular applications of this are voice-enabled assistants like Siri, Google Assistant, and Alexa.
2. **Natural Language Understanding**: This involves understanding the actual meaning, sentiment, and intent behind the phrases or sentences. It's not just about understanding individual words, but also how those words are connected to each other and in what context they are used.
3. **Natural Language Generation**: This involves generating natural language from a data set. A common application of this is in customer service bots, which can generate responses to customer queries.
NLP is used in many applications today, including translation, sentiment analysis, chatbots, voice assistants, and more. It's a rapidly evolving field and is a key part of how we're developing more sophisticated and natural interactions between humans and technology.

- Key Phrase Extraction 
- Entity Recognition 
- Sentiment Analysis 
- Language Modeling 
- Speech Recognition and Synthesis
- Translation

NLP Workload Tools - 
Text Analytics Service
- Key phrase extraction, entity detection, and sentiment analysis 
- Can detect the language of text 
- can detect multiple languages and identify the prominent language
- Return NaN when it cant determine

Language Understanding Service (LUIS) - 
Core Concepts: 
1. Utterance - something a user would say (eg. a customer)
2. Entities - Item the utterance refers to - (eg. DateTime, or Subject)
3. Intents - The purpose or goal expressed by the user (eg. TodayHoursOpen )

### Conversational Ai Workloads: 

### Features of Generative AI: 
