---
permalink: /projects/
title: "Projects"
layout: single
author_profile: true
---
### **Image Matching Challenge 2025 (Kaggle)**                                     
*04-06/2025*
Aimed to construct a complete system of image matching and 3D reconstruction inference that can predict camera’s extrinsic parameters and scene affiliation in different scenarios
- Utilized FAISS cosine similarity retrieval, based on DINOv2 and CLIP global features, to generate candidate image pairs, ensuring coverage of matched pairs under cross-view and cross-illumination conditions
- Employed ALIKED to extract local key points and descriptors, combined with LightGlue for efficient matching; implemented a fallback to LoFTR when matched points are insufficient, boosting recall by over 15% in scenes with weak textures or repetitive structures
-Adopted PyCOLMAP for incremental mapping to estimate camera rotation matrices and translation vectors, while automatically performing scene clustering to ensure mapping purity and robustness
- Designed a mechanism for parameter tuning and caching (including SIM threshold, number of feature points, and fallback strategy) to significantly reduce inference time while maintaining accuracy; persist intermediate results in HDF5 supported resumable execution
- Implemented an automated submission module that writes the cluster, R, and t into a submission.csv file compliant with competition specifications; the coverage and localization accuracy on the local validation set remained stable and met the requirements for submission

### **BYU - Locating Bacterial Flagellar Motors 2025 (Kaggle)**                          
*04-06/2025*
Aimed to precisely localize bacterial flagellar motors in three-dimensional electron tomographic images reconstructed from a series of two-dimensional projection images, which are characterized by significant noise and substantial variations
- Constructed a two-stage inference pipeline: the first stage utilizes YOLOv8/YOLO11 combined with SAHI sliced inference and multi-resolution TTA to generate candidate points; the second stage employs rotation + zoomed cropping, Midpoint Reasoning (merging closely located detection points), and Bypass Logic (skipping the second stage for high-confidence detections) for refined screening and acceleration
- Trained YOLOv8l/YOLO11l by integrating official and externally corrected datasets; additionally trained a localized model utilizing random cropping to enhance robustness in detecting small-scale regions
- Performed model ensemble learning and constructed multiple submission configurations to explore various combinations of SAHI activation, different scaling factors (z1.5/z2/z3), and parallel pipelines, ensuring the model's generalization capability

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





