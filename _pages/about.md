---
permalink: /
title: "About"
layout: single
author_profile: true
---

**Hi, I'm Linan Wu.**  
**Beijing Normal – Hong Kong Baptist University (BNBU)**  
*Bachelor of Science (Honors) in Data Science (GPA 3.7/4.0)*  
*Minor in Economics (GPA 3.8/4.0)*  
*09/2022 – 06/2026*  

- Guangdong Provincial Third Prize in 2024 China Undergraduate Mathematical Contest in Modeling  
- BNBU Second-tier Scholarship (2022-23 & 2023-24)  

---



## INTERNSHIP
### **Guangzhou Yunke Information Technology Co., Ltd.**  
*Intern of Backend Development*  
*06-08/2025*  

1. Participated in the development and optimization of APIs for the logistics management module of the company’s SaaS ERP system  
   - Assisted in developing core APIs such as driver QR code check-in and vehicle transport statistics; conducted self-testing via Postman and collaborated with QA teams to carry out functional validation  
   - Learned and utilized the Spring Boot framework to implement API logic, and, according to the team coding standards, optimized data processing logic via Java Collections Utility Classes; assisted in developing fundamental APIs for logistics tracking by studying using thread pools to handle concurrent data writes, enabling scheduled reception and storage of vehicle GPS data  
   - Assisted in troubleshooting the problem of ‘slow generation of weighing data report' by identifying unindexed join queries through analysis of slow query logs; shortened the report generation time from 15 minutes to 3 minutes  

2. Participated in the development of the data interaction layer of the company’s LED vehicle queuing system  
   - Learned the use of Redis string and hash structures, and assisted in building a Redis cache basic model for storing temporary data of vehicle queuing status  
   - Wrote scheduled task scripts to realize the automatic synchronization of queuing information to the Redis cache every 5 minutes, reducing query pressure of database  
   - Studied the use of distributed locks to solve the problem of dirty data caused by multiple threads modifying queuing numbers at the same time, to deal with the high-concurrency scenario of real-time update of vehicle queuing information  

---

## PROJECTS
### **Construction of Large Language Model Inference System**  
*02-06/2025*  
- Built a multi-model architecture based on open-source models such as Mistral-7B, Yi-34B, and LLaMA 2, using Zero-shot, Few-shot, and SFT fine-tuning strategies, combined with H2O LLM Studio, to optimize the model, achieving an accuracy improvement of over 10% in specific fields such as physics/biology  
- Used LoRA fine-tuning and cached past_key_values, increasing inference speed by 60%  
- Dynamically enhanced context by integrating RAG and LangChain, building a corpus containing 60 million paragraphs based on multi-source Wikipedia data, developing a FAISS vector retrieval system, and entering pre-designed multi-round Prompt templates  
- Implemented confidence integration based on results of multiple models, combined with methods such as TF-IDF re-ranking and Embedding similarity, to increase the Top3 hit rate to 93%; and the integrated model was 15% more accurate than the single model  

### **Identification of Offensive Language in Chinese Social Media Environment**  
*10-12/2024*  
- Conducted the collection, cleaning, and annotation of Chinese social media data; built and optimized multiple dedicated datasets including COLD, ToxiCN, and ToxiCloakCN  
- Built and trained LSTM neural networks and pre-trained language models (BERT and RoBERTa) to achieve accurate identification and classification of aggressive language  
- Evaluated and optimized the model through performance evaluation indicators (Accuracy, ROC-AUC, F1-score); eventually decided on the RoBERTa model, which achieved an accuracy of 78.54% and performed outstandingly in complex language recognition  

### **Predictive Analysis of Diamond Prices**  
*05-06/2024*  
- Used Python and R languages to model and analyze 5000 pieces of diamond transaction data, attempting to build a high-precision price prediction model  
- Implemented data cleaning, feature engineering, and multivariate transformation (Box-Cox) to optimize model performance  
- Explored data features through data visualization tools, identified multicollinearity between variables, and improved model prediction accuracy  
- Adopted stepwise regression and cross-validation methods; the final model achieved an R² of 0.9853 and a cross-validation RMSE of 0.1308, showing superior and stable performance  
- The model successfully passed regression assumption tests such as residual independence, normal distribution, and homoscedasticity to ensure the robustness of predictions  

### **Processing and Analyzing of Earthquake Data from 1900 to 2023**  
*03-05/2023*  
- Utilized big data frameworks such as Hadoop and Spark for large-scale data storage and parallel computing, completing efficient processing and analysis of global long-time series earthquake data  
- Performed data cleaning and time format standardization, used reverse geocoding technology to obtain accurate geographical information, and conducted in-depth analysis of the spatiotemporal distribution characteristics of earthquakes  
- Adopted visualization tools such as Plotly and WordCloud to clearly display the spatial hotspots and key event characteristics of earthquake data, providing strong data support for subsequent risk prediction and disaster prevention and mitigation  

---

## TECHNIQUES SKILLS
- **Programming languages:** Python, R, C, Java  
- **Deep learning frameworks:** PyTorch, TensorFlow, Hugging Face Transformers, JAX  
- **Machine learning & NLP:** Transformer (GPT, BERT, RoBERTa, LLaMA), CNN, RNN, LSTM  
- **LLM applications and methods:** LangChain, Prompt Engineering  
- **Data processing & visualization:** Pandas, NumPy, SQL, Matplotlib, Seaborn, Plotly  
- **Big Data and Distributed Computing:** Hadoop, Spark, Docker, Kubernetes  

---


## ADDITIONAL
### **BNBU Dream Weavers Club**  
*10/2022 – Now*  
- Have served in the club, one of the most renowned student organizations at BNBU, from initially an ordinary member to currently a vice president who manages a team of 50+ members  
- Help plan, organize, and coordinate various student activities including fund-raising charity campaigns, guest speeches, volunteer programs, and so forth; independently led my team to launch a new activity of monthly guest speech from scratch  
- Contact and negotiate with external organizations to acquire sponsorship of more than RMB 10,000+  

