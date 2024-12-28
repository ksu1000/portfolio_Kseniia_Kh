# Portfolio

## 1. Introduction
This repository showcases a collection of my projects focused on **Machine Learning** and **Deep Learning**, leveraging Python and TensorFlow. The work is categorized into three main areas according to the input data type: image, tabular data, and text. Below, you will find a description of these categories and completed projects. 

One of my latest work is a **Question-Answering** System built using Retrieval Augmented Generation (RAG) with the Llama **LLM**. This system takes user queries, retrieves relevant context from a set of documents, and generates coherent answers in multiple languages, adapting to the language of the input. The project highlights my ability to work with large language models, retrieval systems, and text-based data, providing a real-world example of how machine learning can be applied to natural language processing tasks.

But first, let me introduce myself a little.

## 2. About Me: A Picture is Worth a Thousand Words

| **In My Mind** | **My Life Balance** |
|:--:|:--:|
| ![My Activities (Pie Chart)](https://raw.githubusercontent.com/ksu1000/portfolio_Kseniia_Kh/c9e47a0568c9d120d358b113e281b151f6c33520/assets/silueta_word_cloud.png) | ![Word Cloud](https://github.com/ksu1000/portfolio_Kseniia_Kh/blob/d1b5f18c8e4c88e838e403472cb6f0b17d2e731a/assets/activities.png) |

<br><br>
<p align="center"><strong>My Data Science Master's Performance</strong></p>
<div align="center">
  <img src="https://github.com/ksu1000/portfolio_Kseniia_Kh/blob/e76ddc7dd4126e205b408a1bb13c105eb77399ca/assets/grades.png" width="80%"/>
</div>

<br><br>

<p align="center"><strong>Courses Dedication (My Passion in Hours)</strong></p>
<div align="center">
  <img src="https://github.com/ksu1000/portfolio_Kseniia_Kh/blob/942a82abbbfc10e482baa39a79a236b473ee86c9/assets/courses.png" width="80%"/>
</div>

## 3. Repository Structure

- **images/**: Projects related to image processing, computer vision models, and other works involving images as input.
- **tabular_data/**: Projects focused on analyzing tabular data, such as classification, regression, and exploratory data analysis (EDA).
- **text/**: Projects that focus on natural language processing (NLP), such as text analysis, text classification models, question-answering, and generative models.

## 4. Tools
- **Language**: Python
- **Main Libraries**: 
  - Pandas, NumPy (for data handling)
  - Matplotlib, Seaborn (for visualization)
  - TensorFlow (for deep learning)
  - Scikit-learn (for ML models)
  - Transformers (Hugging Face, for state-of-the-art NLP models)
  - Optuna (for hyperparameter optimization)
  - LangChain (for building and managing NLP pipelines, especially for RAG tasks)
 
## 5. Completed Works
### Image Projects
| Project               | Description                                               | Approach & Techniques Applied                                                                  |
|-----------------------|-----------------------------------------------------------|------------------------------------------------------------------------------------|
| pneumonia_segmentation | Multitask learning for segmenting and classifying pneumonia from chest X-ray images | Deep Learning, **U-Net**, Residual Blocks, Multi-input Multi-output, Late Fusion (multimodal data), Personalized Loss Function, `tf.data.Dataset` |
| vegetables_classification | Classification of vegetables using images                | Deep Learning, Data Augmentation, Transfer Learning, Fine Tuning, MobileNet, `ImageDataGenerator` |

### Tabular Data Projects

| Project                     | Description                                               | Approach & Techniques Applied                                                                 |
|-----------------------------|-----------------------------------------------------------|------------------------------------------------------------------------------------|
| insurance_premium_prediction | Regression for insurance premiums based on customer attributes | Machine Learning, EDA, Feature Engineering, Log Transformations, Imputation of Missing Data, Encoding Categorical Features, Standardization, Pipeline, LGBMRegressor, **Optuna** |

### Text Projects

| Project               | Description                                               | Approach & Techniques Applied                                                                 |
|-----------------------|-----------------------------------------------------------|------------------------------------------------------------------------------------|
| tweets_classification | Binary classification of tweets into two categories: disaster and normal | Deep Learning, Data Cleaning, Tokenizer, Hidden States & Logistic Regression, Fine-tuning, **DistilBERT**, Class Weights, Learning Curves, Confusion Matrix, Classification Report |
| about_me_questions_answering_llama_rag | A question-answering system about Kseniia, using **Retrieval-Augmented Generation (RAG)** with **Llama LLM** | **LangChain**, Retrieval-Augmented Generation (RAG), Question Answering Pipeline, Llama LLM, FAISS, Semantic Search, Prompt Engineering |






