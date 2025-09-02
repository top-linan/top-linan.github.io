---
permalink: /internship/
title: "Intership"
layout: single
author_profile: true
---
### **SFMAP Technology (Shenzhen) Co., Ltd. (subsidiary to Shunfeng Holding Co., Ltd)**                 
*Algorithm Engineer Intern*                                                   
 *07-08/2025*
Participated in the development of a Flask-based platform for driver safety analytics, mainly modules such as automated anomaly detection, AI-driven insight generation, and Text-to-SQL, to achieve end-to-end intelligence in data analytics 
-Designed and implemented five APIs (overview, analysis list, operational analysis, AI-driven insights, and automatic insights), achieved the interfacing of the data service layer and the unifying of JSON serialization, to support frontend consumption
-Develop an automated insight engine: fulfilled the AnomalyInsight data structure, integrating Z-Score (threshold 3.0/2.5) + IQR detection methods and 4 business rules (safety score decreased by 10, accident rate month-over-month increased by 50%+, regional disparity decreased by 30%, and proportion of high-risk driver decreased by 20%); output the top 30 abnormal insights sorted by confidence level and deviation, achieving a coverage rate of 90%+, and identify high-risk drivers 1–2 weeks in advance
-Built a Text-to-SQL Self-Service Query Function: combined SentenceTransformer + Chroma Vector Retrieval with Qwen2.5-72B LLM to implement the conversion of natural language to SQL (limited to SELECT, first 20 rows), ensuring data security, and covering 95%+ common query scenarios
-Introduced accessing LLMs via a Bastion Host: integrated LLM services in an offline environment to automatically generate Chinese security reports and management summaries, supporting insight archiving and cross-month queries through a Flask interface to enhance managerial decision-making efficiency
-Optimized database performance: configured SQLAlchemy connection pool parameters (pool_pre_ping, pool_recycle=3600, pool_size=10), and, via combination with the logging module, monitored SQL execution and automated insight processes, significantly improving system stability and concurrency capability 


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


  





