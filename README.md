## 📊 Research on ChatGPT's Impact on Student Learning
This repository contains materials related to our research project on the impact of ChatGPT on student learning and various machine learning tasks. The project includes survey data analysis, supervised learning models, and unsupervised learning techniques applied to educational datasets.

## 🗂 Contents
list cau hoi.docx - A document containing the questionnaire used in the survey, with questions covering personal information, usage of ChatGPT, opinions on its effectiveness, and personal reflections on its impact on learning.
NCKH_cleaned.xlsx - The cleaned dataset obtained from the survey responses. This dataset is used in both supervised and unsupervised learning tasks.
Supervised Learningg.ipynb - A Jupyter Notebook detailing the supervised learning tasks, such as regression and classification models, applied to predict student performance based on their ChatGPT usage.
Unsupervised Learning.ipynb - A Jupyter Notebook covering the clustering techniques, such as K-Means and DBSCAN, applied to segment students based on their interaction patterns with ChatGPT.
## 🔍 Project Overview
The goal of this project is to investigate how students in Ho Chi Minh City are using ChatGPT in their studies and how it impacts their learning outcomes. We aim to answer questions such as:
- How does the use of ChatGPT correlate with student performance?
- What are the key patterns in ChatGPT usage among students?
- Does ChatGPT influence students' motivation, creativity, and self-study skills?
The research consists of the following steps:
- Data Collection: Survey responses were collected from students using the questionnaire found in list cau hoi.docx.
- Data Cleaning: The raw data was cleaned and processed, resulting in the file NCKH_cleaned.xlsx.
- Supervised Learning: In the notebook Supervised Learningg.ipynb, we apply models like Logistic Regression and Random Forest to predict student performance based on their ChatGPT usage.
- Unsupervised Learning: The Unsupervised Learning.ipynb notebook explores clustering techniques like K-Means and DBSCAN to segment students based on their interaction patterns.
## 📊 Dataset
The cleaned dataset (NCKH_cleaned.xlsx) includes the following columns:
- Demographic Information: Gender, Year of Birth, Year in School, University, etc.
- ChatGPT Usage: Frequency, purpose of use (study, personal, etc.), time spent per day, preferred times for use, and more.
- Personal Opinions: Satisfaction, trust in ChatGPT, its perceived impact on motivation and creativity, etc.
- Additional Information: Other websites students use for study, perceived effects of ChatGPT on performance, and future intentions to use ChatGPT.
## 📈 Analysis and Results
We used both supervised and unsupervised learning methods to uncover insights from the data. Here are some of the key findings:
- Supervised Learning: Regression models showed a positive correlation between the amount of time students spend using ChatGPT and their academic performance.
- Unsupervised Learning: Clustering revealed distinct groups of students, with some using ChatGPT primarily for study purposes, while others use it more for personal or entertainment-related tasks.
## 📑 How to Use
Clone the repository:
```bash
git clone https://github.com/yourusername/research-chatgpt-impact.git
```
Navigate to the project directory:
```bash
cd research-chatgpt-impact
```
Install required dependencies:
```bash
pip install -r requirements.txt
```
Run the Jupyter notebooks:
```bash
jupyter notebook
```
