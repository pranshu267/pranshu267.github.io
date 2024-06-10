---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

NewsLens | [GitHub](https://github.com/pranshu267/NewsLens)
======
A comprehensive system for delivering concise, unbiased news insights by leveraging advanced retrieval and generation models. 

* **Retrieval-Augmented Generation (RAG) Model:**
  * Implemented a Retrieval-Augmented Generation (RAG) model to retrieve and fetch relevant articles based on user queries, ensuring the information provided is timely and relevant.

* **Multi-Document Summarization:**
  * Fine-tuned a BART transformer model to generate concise multi-document summaries. This model synthesizes complex information across different articles into a coherent narrative, providing users with comprehensive, precise, and unbiased news insights.

* **Contextual Image Generation:**
  * Integrated the Stable Diffusion model to generate contextual images corresponding to textual news summaries. Utilized a large language model (LLM) to generate prompts for the Stable Diffusion model, ensuring the images are contextually relevant and enhance the user’s understanding of the news content.

NYU Assistant | [GitHub](https://github.com/pranshu267/NYUAssistant/tree/main)
======
A sophisticated system designed to address the diverse inquiries of the NYU community by leveraging advanced data retrieval and natural language processing techniques. 

* **Data Extraction and Storage:**
  * Implemented advanced web scraping techniques to systematically extract a wide range of information from multiple NYU websites, ensuring comprehensive coverage of relevant data.
  * Utilized instructor embeddings to compute high-dimensional text embeddings for the extracted information, enhancing the system’s ability to understand and retrieve contextually relevant data.
  * Stored the computed embeddings in a FAISS (Facebook AI Similarity Search) vector database, optimizing the retrieval process for speed and accuracy in handling large volumes of data.

* **NLP Pipeline Development:**
  * Engineered a robust Natural Language Processing (NLP) pipeline leveraging LangChain, a framework that enables the seamless integration of various NLP models and tools.
  * Integrated Google Palm LLM, a state-of-the-art language model, to generate precise and contextually appropriate answers to user queries, enhancing the overall accuracy and reliability of the system.

* **Interactive Web Application:**
  * Developed an interactive web application using Streamlit, providing a user-friendly and visually appealing interface for users to interact with the RAG system.
  * Designed the application to significantly enhance user engagement by offering intuitive navigation, real-time query handling, and visually rich responses.

Real-Time Forex Arbitrage and Price Prediction System | [GitHub](https://github.com/pranshu267/Real-Time-Forex-Arbitrage-Detection-and-Price-Prediction-System)
======
A comprehensive system designed to optimize forex trading strategies by leveraging advanced data processing, predictive analytics, and real-time monitoring tools. 

* **Data Processing and Storage:**
  * Engineered a forex trading system utilizing Apache Spark for efficient data processing and arbitrage calculations, significantly enhancing the accuracy and speed of trading strategies.
  * Implemented Google BigQuery for optimized data storage, ensuring quick and reliable access to large datasets, thereby improving operational efficiency and decision-making.

* **Predictive Analytics:**
  * Designed, trained, and deployed a Bi-Directional Long Short-Term Memory (LSTM) model for precise forex price prediction. This model leverages historical data to predict future price movements with high accuracy.
  * Utilized Flask to serve the trained LSTM model in real-time, enabling responsive and informed trading decisions based on the latest predictive analytics.

* **Data Ingestion and Monitoring:**
  * Scheduled and managed data ingestion processes using Apache Airflow, ensuring timely availability of data for continuous analytics and reporting.
  * Developed a real-time dashboard using Looker Studio to monitor forex trends and arbitrage opportunities. This dashboard provides traders with instant insights and actionable information, enhancing their ability to capitalize on market movements.

Exploring the Role of Cultural Context in Cross-Lingual Transfer Capabilities | [GitHub](https://github.com/sharad5/Cross-Lingual-Transfer-mBERT)
======
A research project investigating the generalization ability of cross-lingual transfer for universal language tasks such as sentiment analysis and contextual language tasks like hate speech detection across high and low resource languages.

* **Experiment Development and Leadership:**
  * Developed and led experiments to test the generalization ability of cross-lingual transfer for universal language tasks like sentiment analysis and contextual language tasks like hate speech detection across high and low resource languages.
  
* **Multilingual Model Fine-Tuning:**
  * Fine-tuned mBERT, a multilingual language model, for sentiment analysis and hate speech detection tasks across English and Turkish languages. This comparative analysis validated the research hypothesis regarding cross-lingual transfer capabilities.
 
Advanced Paraphrase Detection | [GitHub](https://github.com/pranshu267/Paraphrase)
======
Developed an advanced paraphrase detection system using a fine-tuned transformer model, enhancing the accuracy and efficiency of detecting paraphrased content. 

* **Model Fine-Tuning:**
  * Fine-tuned a state-of-the-art transformer model specifically for paraphrase detection tasks, optimizing it for high accuracy and robust performance.

* **API Development and Deployment:**
  * Made the model servable using FastAPI, providing a scalable and efficient API for real-time paraphrase detection.
  * Implemented multi-threading to enable parallel processing of requests, significantly improving the system's throughput and responsiveness.

* **Containerization and Deployment:**
  * Dockerized the application to ensure consistent and reliable deployment across different environments.
  * Streamlined the deployment process, making the system easy to set up and maintain, and enhancing its scalability and portability.


Custom ResNet for CIFAR-10 Image Classification | [GitHub](https://github.com/vibhor18/Deep-Learning-CiFar10-ResNet-)
======
Designed and developed a Custom Residual Network (ResNet) architecture optimized for the CIFAR-10 image classification dataset, achieving high accuracy while maintaining a low parameter count. 

* **Model Design:**
  * Created a custom ResNet architecture with an emphasis on efficiency and performance, ensuring the total number of trainable parameters did not exceed 5 million.
  * Incorporated various architectural enhancements, including adjustments to layer depth and filter sizes, to balance model complexity and accuracy.

* **Training and Optimization:**
  * Employed advanced training techniques and hyperparameter tuning to enhance model performance, using optimizers such as AdamW and learning rate schedulers to stabilize and accelerate the training process.
  * Utilized extensive data augmentation strategies, including random cropping, horizontal flipping, and rotation, to improve model generalization and robustness against overfitting.
