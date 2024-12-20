# My Portfolio
---
Hello! I'm Dhanvanth Voona, currently working as an AI Engineer Intern at Liminal XR Solution with expertise in Prompt Engineering, LLMs, RAG applications, Data Analysis, Business Intelligence, Computer Vision and pursuing Master of Data Science student at Illinois Institute of Technology, expected to graduate in May 2025.

---
## Experience Summary
- **1+ years** in Generative AI and Large Language Models (LLMs)
- **2+ years** in Business Intelligence tools, data visualization, and SQL
- **3+ years** in Deep Learning, NLP, and Computer Vision


## Education

**Master of Data Science**  
*Illinois Institute of Technology, Chicago, IL*  
- Concentration in Generative AI and Data Analytics.
- Graduate Pathway Scholarship Awardee **($ 10,000)** awarded for Academic Merit
  
**Bachelor’s Degree in Electronics and Communication Engineering**  
*Vellore Institute of Technology, Chennai, TN*  
- Research focus: Deep Learning, Computer Vision, and Natural Language Processing.

---

## Work Experience

### Artificial Intelligence Intern  
**Liminal XR Solutions**  
*Feb 2024 - Present*  
-	Developed and deployed a Python-based web application leveraging GPT-4o, LLaMA-3.3-70B, LangChain, Chroma-DB, and FastAPI framework to create a restaurant recommender system using client-sourced data. 
-	Implemented a secondary LLM as a validation checker, reducing hallucination rates from 9.6% to 3.2% and improving text relevancy in a Retrieval-Augmented Generation (RAG) application, decreasing irrelevant responses from 96 to 32 per 1,000 test samples.
-	Automated web scraping using the Google Maps API to extract images of restaurants present in database, achieving an 80% improvement in scraping speed with 94% accuracy and significantly reducing manual scraping costs
-	Designed a log-transformation-based relevancy score for attributes such as average cost and number of reviews, resulting in an unbiased ranking system for sorting the top-K results retrieved from vectordb. 
-	Enhanced content engagement by developing AI-driven personalized welcome messages for event delegates, utilizing web scraping, LLMs, and text-to-speech technology, increasing engagement and reducing manual effort by 80%.
-	Currently developing multimodal image generation models inspired by Indian art and heritage to create abstract art for enriching cultural VR experiences.


### Data Science Intern  
**National Institute of Education, Nanyang Technological University (NTU)**  
*Aug 2022 - Aug 2023*  
- Applied Excel's statistical functions to conduct in-depth analysis and identify trends in stock price movements, enhancing financial insights.  
- Developed an interactive dashboard in Microsoft Power BI, reducing report generation time by 25% and enabling more informed decision-making with real-time market insights.  
- Enhanced accuracy in detecting stationarity, trend, and seasonality components, leading to a 15% improvement in prediction performance and a reduction in forecasting errors.  

#### Key Achievements:
- Designed and developed a unique classroom emotion dataset by integrating landmark detection and Facial Action Unit (FAU) mapping with state-of-the-art datasets through web scraping, resulting in a final dataset comprising 18,000 images across 15 emotion classes.  
- Fine-tuned state-of-the-art models, including VGGNet, ResNet, and EfficientNet, by unfreezing 20% of the neural network layers for training on the constructed dataset, achieving a 15% improvement in test accuracy through optimized model weights.  
- Implemented a novel framework for academic emotion classification using VGG-19 as a feature extractor and Multi-Layer Perceptron (MLP) as a classifier, achieving 82.73% classification accuracy on the test set after performing 5-fold cross-validation for complex emotions such as boredom and frustration.  
- Developed a multimodal analysis pipeline for emotion recognition in memes, achieving 89% accuracy by integrating Optical Character Recognition (OCR) for text extraction and deep learning for image analysis in TensorFlow/Keras.  


### Data Analyst Intern  
**National University of Singapore, Changi, Singapore**  
*Jun 2022 – Jan 2023*  
- Developed a Healthcare Management System with Python and SQL, enhancing data processing efficiency by 25%.
- Created Power BI dashboards for patient scheduling, improving efficiency by 30%.
- Built an eye-movement detection system using transfer learning and neural networks, achieving 95% accuracy in identifying eye positions for communication aid in paralyzed patients.

### Computer Vision Intern  
**Samsung PRISM**  
*Jun 2021 – Feb 2022*  
- Researched and developed an AI-based reflection scene category classifier, achieving 93% accuracy.
- Generated weekly Power BI reports, reducing data analysis time by 35%.

---

## Projects 

### Analysis of Skip connections effect on Vanishing gradient
*Aug - Dec 2024*
- **Innovative Architecture:** Incorporated skip connections in ResNets to combat the vanishing gradient problem,
  resulting in a 10.2% improvement in accuracy compared to plain networks, with the 40-layer ResNet
  achieving 91.76% test accuracy.
- **Gradient Stability:** Implemented gradient clipping (maximum norm of 1) and reduced the learning rate from 0.001 to
  0.00008, which eliminated exploding gradient issues and improved training stability, leading to consistent validation accuracy across epochs.
- **Enhanced Model Generalization:** Applied data augmentation techniques like rotation and zooming, increasing training data
  diversity and contributing to a 15% improvement in F1-score for deeper ResNet architectures.
- **Optimized Performance Metrics:** Achieved a precision of 92.30% and an F1-score of 91.58% with ResNet models, significantly
  outperforming plain networks, which struggled to exceed 85.71% F1-score due to depth-related instability.
- [Github Repository](https://github.com/dhanvanth342/How-Skip-Connections-working-to-reduce-impact-of-Vanishing-gradient-for-Brain-Tumor-Dataset).

### Predictive Analysis of Retail Sales Using Regression Modeling
*Nov - Dec 2024*
- **Enhanced Model Performance by 15%:** Improved adjusted R-squared from 62.5% to 71.9% and reduced residual standard error by 48% (from 1045 to 0.539) through systematic feature selection, backward elimination, and logarithmic transformations to address multicollinearity and heteroscedasticity.

- **Optimized Data Handling:** Preprocessed a dataset of 8,000+ observations by imputing missing values (mean for `Item_Weight`, mode for `Outlet_Size`), standardizing categories, and applying advanced encoding techniques (target, ordinal, and one-hot), reducing data inconsistencies by 100% and enabling seamless model integration.

- **Resolved Multicollinearity Issues:** Decreased Variance Inflation Factor (VIF) values of predictors by 98% (e.g., `Outlet_Type` from 305.42 to below 4.2) by removing redundant variables and retaining impactful ones like `Item_MRP`, leading to a stable, interpretable model.

- **Increased Predictor Significance:** Identified and retained impactful predictors such as `Item_MRP` and outlet-related features, resulting in 60% higher explanatory power for sales prediction while removing non-significant features to reduce model complexity by 30%.
- [Github Repository](https://github.com/dhanvanth342/Predictive-Analysis-of-Retail-Sales-Using-Regression-Modeling). 

### Cold Email Generator for Recruiters  
*Apr – Sep 2024*  
- Built an AI-driven email generator to personalize recruiter outreach, reducing manual effort by 90%.
- Utilized Llama 3.1 on Groq Cloud and Web Base Loader for data extraction, managed by ChromaDB within Langchain.
- [GitHub Repository](https://github.com/dhanvanth342/Email-generator-llama3.1-GenAi)

### Healthcare Management System  
*Jan - May 2024*  
- Enhanced patient data processing efficiency by 25% through Python and SQL.
- Developed automated Power BI reports for patient scheduling, reducing preparation time by 50%.
- [GitHub Repository](https://github.com/dhanvanth342/Healthcare-management-system-sql)

### Credit Card Approval Prediction Dashboard  
*May – Sep 2024*  
- Created a Power BI dashboard for credit card approval predictions, automating data processing and improving decision accuracy.
- Reduced data handling time by 30%, with advanced data modeling, DAX formulas, and SQL.
- [GitHub Repository](https://github.com/dhanvanth342/Credit-card-approval-ML)

### Over-volume vehicle classification using Deep CNN models 
*Jan - May 2022*
- Collected 3054 real-time image data across 3 classes to monitor and classify over-volume vehicles, providing an automated
  solution in rural and terrain areas where human surveillance is impractical, improving traffic management and safety.
- Developed and evaluated a transfer learning-based CNN model using ImageNet pre-trained weights and EfficientNet-B3
  architecture, fine-tuning dense layers to optimize performance on real-time vehicle data, achieving 95% accuracy.
- Performance was assessed using metrics such as confusion matrix, ROC curve, and AUC score to identify the most effective
  model for over-volume vehicle detection.
- [Publication](https://www.mdpi.com/2076-3417/13/4/2549)

---

## Skills

- **Data Visualization & Business Intelligence**: Tableau, Power BI, Google Charts, Excel, DAX, Power Query.
- **AI/ML Techniques**: Fine-tuning, vector embedding, NLP, neural network optimization, deep learning.
- **Modeling & Analytics**: Predictive Modeling, Data Mining, Data Modeling, Machine Learning, Deep Learning.
- **Data Engineering & ETL**: ETL Pipeline Development, SQL Querying, Apache Hadoop, Apache Spark.
- **Programming & Tools**: SQL (Advanced), Python (Pandas, NumPy), R, TensorFlow, PyTorch, LangChain, LlamaIndex, Streamlit, Groq Cloud, Flutter.
- **Cloud Platforms**: Microsoft Azure, AWS SageMaker.

---
## Research Publications

- **Performance Analysis of Deep Convolutional Network Architectures for Classification of Over-Volume Vehicles**  
  *Published in Applied Sciences* [Impact factor: 2.838]

- **Automated Classification of Student's Emotion Through Facial Expressions Using Transfer Learning**  
  *Published at The European Conference on Education 2023*

---
I know there are a zillion students and recent grads with Data Science projects portfolios and AI-generated summaries. Let me try something different.
A brief about my working style:

### Curiosity and Depth
- Consistently curious, especially in technology, machine learning, and data analysis.
- I approach complex topics methodically, asking detailed questions to fully grasp nuances.

### Analytical and Problem-Solving Mindset
- My analytical nature drives me to dig deeper into subjects, whether it's understanding LLMs, neural networks, applied mathematics, or building Flask applications.
- Strong inclination toward problem-solving and critical thinking.

### Adaptability Across Domains
- I transition smoothly across various technical domains, from exploring mathematical models of neuron activity in C. elegans to applying machine learning and data science techniques.
- This adaptability and cross-domain agility are strengths that stand out in tech-driven fields, where staying current with emerging models and methods is essential.

### Role-Specific Readiness
- As a Data Scientist or AI Engineer, I’m well-prepared to integrate my adaptability and curiosity into practical solutions.
- I stay agile and proactive, keeping pace with rapid developments in AI and data science.
