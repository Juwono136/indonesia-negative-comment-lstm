# Sentiment Analysis of Indonesian Negative Comments on Social Media Using LSTM
![negative-comment-banner](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/91923438-86c9-45fb-9f28-22eba392787c)

### Demo or Live Website
➡️ Project Demo: https://huggingface.co/spaces/juwono136/indonesia-negative-comment-classification <br>
➡️ Journal Publication: https://journal.formosapublisher.org/index.php/ijis/article/view/4990

## Introduction
Currently, in addition to discussing in the real world, most people also engage in discussions online, one of which is by commenting on a post on social media. Sometimes, the quality of the discussion deteriorates due to the emergence of various negative comments, especially among Indonesian people who frequently comment on social media. This sentiment analysis aims to classify and make predictions about a comment so that in the future, the discussion space on social media can be improved and unnecessary conflicts can be avoided.


The Long-Short Term Memory (LSTM) method has been widely used, especially in NLP technology, as it has the advantage of understanding context or words in long-term memory. This sentiment analysis is still in the development stage, with the continuous addition of diverse datasets containing a wider range of sentences.

### 📑 Dataset
➡️ The dataset originates from one of the GitHub users, namely [Ahmad Izzan and team](https://github.com/ahmadizzan/netifier), inspired by the [Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge). 
This dataset consists of approximately 7,773 example sentences (raw_data) categorized into positive and negative sentences in the Indonesian language. 
Negative sentences are divided into 4 types: Pornography, Hate Speech (SARA), Radicalism, and Defamation, whereas positive sentences are those that do not carry negative meanings.

### 🎯 Key Features:
- ➡️ Sentiment Analysis Using LSTM Method with TensorFlow Framework
- ➡️ Text classification to predict negative comments based on 4 categories: Pornography, Hate Speech (SARA), Radicalism, and Defamation

### 🧑‍💻 Technologies:
- ➡️ Python 3.x
- ➡️ TensorFlow Framework
- ➡️ Hugging Face for Deploy (https://huggingface.co/)
- ➡️ Numpy
- ➡️ Gradio Interface
- ➡️ Long-Short Term Memory (LSTM)
- ➡️ TensorFlow Embedding Projector

## Project Overview
- ➡️ Label Distribution Graph for Sentences in the Raw Data Dataset

  ![image](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/5b4467ac-451a-4bc4-bfcb-66d6ebc12a0b)

- ➡️ Correlation Matrix Between Labels

  ![image](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/f7d4e800-bf02-42d9-8abd-272565e1dcf1)

- ➡️ Word Cloud from SARA label

  ![image](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/cdaae054-6bba-4dfb-bf7f-25e318c8baef)

- ➡️ Workflow
  <br>The core steps of this workflow are data construction which includes the stages of data collection from social media, data analysis, preprocessing and create a model.

  ![image](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/548e9a2e-9fd4-4b3a-9868-8e0a96e9069f)

- ➡️ TensorFlow Data Pipelines

  ![image](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/49842a14-29e4-4c5e-af47-1228045710cf)

- ➡️ Network Architecture Models

  ![model_layers drawio](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/1ff7d83d-f9c9-44d3-abc5-2d77ac1a6c62)

- ➡️ Training and Validation Accuracy Values

  ![image](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/cdf01102-1274-4f22-b5fe-53aa77978693)

- ➡️ Training and Validation Loss Values

  ![image](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/9ee015fa-a7e7-4782-b2ce-a9cabec01633)

- ➡️ Embedding Projector in Positive Class

  ![image](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/c3a7f623-3f12-4fbb-a729-4286b39820b7)

- ➡️ Embedding Projector in Negative Class

  ![image](https://github.com/Juwono136/indonesia-negative-comment-lstm/assets/70443393/841c6cd5-d521-42d7-ada1-c6404b150530)


### 🤝 Project Members
- Juwono
