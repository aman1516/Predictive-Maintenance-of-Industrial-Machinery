# Predictive-Maintenance-of-Industrial-MachineryIBM SkillsBuild 4-Week Internship on AI & Cloud Technologies
This repository documents the capstone project completed during the IBM SkillsBuild 4-Weeks Internship on AI & Cloud Technologies. This program is a collaborative initiative by the Edunet Foundation, AICTE, and IBM SkillsBuild.

The internship's primary goal is to provide hands-on experience in emerging technologies, enhancing employability and confidence by solving real-world challenges using the IBM SkillsBuild and IBM Cloud platforms.

📝 Table of Contents
Intern Details
About the Internship
Project: Predictive Maintenance of Industrial Machinery
Problem Statement
⚙️ Technology Stack
🚀 Project Workflow
📊 Results
📁 Repository Contents
👨‍💻 Intern Details
Name: AMAN JAMBHULKAR
Institute: WAINGANGA COLLEGE OF ENGINEERING, NAGPUR
Duration: 4 Weeks (15th July 2025 to 7th August 2025)
📖 About the Internship
This 4-week program focused on providing practical skills in AI and Cloud Computing. The internship was structured with weekly virtual sessions, mentor guidance, and hands-on labs. The curriculum included:

Week 1: Internship Orientation, IBM Cloud Registration, Artificial Intelligence.
Week 2: Data Analytics concepts, Hands-On Labs, and Cloud EDA.
Week 3 & 4: Building a Chat Bot, AI/ML experiments on the cloud, and a deep dive into AutoAI experiments on IBM Cloud.
Successful completion required active participation, completion of at least two courses on IBM SkillsBuild, and the submission of a final project presentation. This internship was offered with no stipend.

💡 Project: 
Problem Statement-Predictive Maintenance of Industrial Machinery
Develop a predictive maintenance model for a fleet of industrial machines to anticipate
failures before they occur. This project will involve analyzing sensor data from machinery
to identify patterns that precede a failure. The goal is to create a classification model that
can predict the type of failure (e.g., tool wear, heat dissipation, power failure) based on
real-time operational data. This will enable proactive maintenance, reducing downtime
and operational costs.


Solution Overview
An end-to-end machine learning solution was developed to Predictive Maintenance of Industrial Machinery projects. These trained model was deployed as a real-time web service on the IBM Cloud platform.

⚙️ Technology Stack
Cloud Platform: IBM Cloud
AI/ML Service: IBM watsonx.ai Studio
Automated ML Tool: IBM AutoAI
Core Language & Libraries:
Python
scikit-learn
pandas
XGBoost
ibm-watsonx-ai

🚀 Project Workflow
Data Ingestion: The Predictive Maintenance of Industrial Machinery dataset from the kaggle was uploaded to an IBM Cloud project.
Automated Model Building: An AutoAI experiment was configured in watsonx.ai. This powerful tool automated the entire machine learning pipeline, including data preprocessing, feature engineering, model selection, and hyperparameter optimization.
Model Selection: AutoAI trained and ranked multiple classification algorithms. The XGBoost Classifier was identified as the best-performing model based on accuracy.
Deployment: The top-performing pipeline was saved as a model asset and deployed as an Online Web Service within a Deployment Space on IBM Watsonx.ai, which provides a REST API for real-time predictions.
Testing: The deployed API endpoint was successfully tested with sample data to validate its real-time classification capabilities.

📊 Results
The deployed model demonstrated high accuracy in classifying infrastructure projects, proving the effectiveness of using automated AI tools for rapid development and deployment. The project successfully met all requirements for the final evaluation and submission.


