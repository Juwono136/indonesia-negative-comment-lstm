# Sentiment Analysis of Negative Comments on Social Media Using Long Short-Term Memory (LSTM)

Testing Model
------------------
Click this link for testing the model: [Testing Model](https://huggingface.co/spaces/juwono136/indonesia-negative-comment-classification)

Introduction
------------------
Currently, social media has become a space for many people to discuss and share information. On social media, all users can provide responses or comments on a piece of informational content. 
Sometimes, within the comments on social media content, there are negative comments that make the discussion atmosphere uncomfortable for some users.
Hence, there is a need for sentiment analysis and classification of negative comments that can arise from it, such as defamation, ethnicity, race, religion, and intergroup issues (SARA), 
pornography, cyberbullying, or radicalism.

Dataset
------------------
The dataset originates from one of the GitHub users, namely [Ahmad Izzan and team](https://github.com/ahmadizzan/netifier), inspired by the [Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge). 
This dataset consists of approximately 7,773 example sentences (raw_data) categorized into positive and negative sentences in the Indonesian language. 
Negative sentences are divided into four types: pornography, Ethnicity, Race, Religion, and Intergroup (SARA) issues, radicalism, and defamation, whereas positive sentences are those that do not carry negative meanings.

#### Label Distribution Graph for Sentences in the Raw Data Dataset
![image](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/5b4467ac-451a-4bc4-bfcb-66d6ebc12a0b)

#### Correlation Matrix Between Labels
![image](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/f7d4e800-bf02-42d9-8abd-272565e1dcf1)

#### Word Cloud from SARA label
![image](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/cdaae054-6bba-4dfb-bf7f-25e318c8baef)

Workflow
------------------
The core steps of this workflow are data construction which includes the stages of data collection from social media, data analysis, preprocessing and create a model.

![image](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/548e9a2e-9fd4-4b3a-9868-8e0a96e9069f)

TensorFlow Data Pipelines
------------------
![image](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/49842a14-29e4-4c5e-af47-1228045710cf)

Network Architecture Models
------------------
![model_layers drawio](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/1ff7d83d-f9c9-44d3-abc5-2d77ac1a6c62)

Training and Validation Accuracy Values
------------------
![image](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/cdf01102-1274-4f22-b5fe-53aa77978693)

Training and Validation Loss Values
------------------
![image](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/9ee015fa-a7e7-4782-b2ce-a9cabec01633)

Embedding Projector in Positive Class
------------------
![image](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/c3a7f623-3f12-4fbb-a729-4286b39820b7)

Embedding Projector in Negative Class
------------------
![image](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/841c6cd5-d521-42d7-ada1-c6404b150530)


### Project Members
- Juwono
