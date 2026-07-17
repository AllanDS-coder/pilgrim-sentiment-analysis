# Multilingual AI Platform for Pilgrim Sentiment Analysis   

### AI-powered multilingual sentiment analysis and demographic analytics for Hajj & Umrah service improvement   

<img width="1911" height="860" alt="image" src="https://github.com/user-attachments/assets/18e7b69c-885c-41c4-9117-ba280503c4aa" />        

---
## Business Problem   

Every year, more than 30 million pilgrims participate in Hajj and Umrah, generating millions of feedback comments in over 27 languages.   

Traditional manual analysis of this feedback is:   

- slow   
- expensive  
- inconsistent   
- impossible at scale   

Without automated analysis, authorities struggle to identify recurring service issues, understand demographic trends, and prioritize improvements.    

This project demonstrates how Artificial Intelligence and Natural Language Processing (NLP) can transform multilingual feedback into actionable insights for evidence-based decision-making.   

---

## Project Overview    

This project is an end-to-end AI application that combines multilingual text processing, sentiment analysis, and interactive analytics into a single Streamlit platform.   

The system enables decision-makers to:   

- Analyze multilingual pilgrim feedback    
- Automatically translate comments into English   
- Classify sentiment using transformer-based NLP models   
- Explore demographic and cross-demographic trends   
- Export processed results for further reporting   

The application demonstrates how modern AI techniques can support public-sector decision making at scale.
         This application leverages AI to analyze and interpret sentiments (comments) from pilgrims participating in Hajj and Umrah. It provides valuable demographic and cross-demographic insights—focusing on age, gender, and nationality—to help stakeholders better understand the experiences and backgrounds of pilgrims.    
         The Sentiment Analysis module classifies comments from pilgrims as either positive or negative, enabling service providers to assess satisfaction levels and identify recurring issues. This insight is crucial for enhancing service delivery and addressing pilgrims’ concerns.    
         Given the volume and linguistic diversity of over 30 million comments across 27+ languages, this tool offers a scalable, potential use case, and systematic approach for Saudi authorities and Hajj/Umrah service providers to make data-driven decisions.  

---

## Business Value   

The platform helps organizations:   

- Monitor service quality using real-time feedback   
- Identify recurring complaints across languages   
- Understand demographic differences in satisfaction   
- Improve operational planning    
- Support data-driven policy decisions    

--- 

## AI|NLP Pipeline   
Raw Comments|Multilingual Feedback     
         ↓       
Language Detection    
         ↓     
Translation to English       
         ↓     
Text Cleaning    
         ↓     
Transformer-based Sentiment Classification      
         ↓    
Interactive Analytics Dashboard    
         ↓     
Exportable Results    


## Features|Functionalities    
### 1. Dashboard Module    
•	Provides interactive visualizations of pilgrim demographics (age, gender, nationality).   
•	Filters available for gender, nationality, and age groups.    
•	Enables cross-demographic analysis.    

### 2. Sentiment & Text Classification Module    
•	Analyzes textual comments and classifies them as positive or negative.   
•	Outputs include:    
o	Original comment   
o	Translated comment (in English)    
o	Sentiment label    
o	Confidence score   
•	Output is exportable/downloadable. 

### 3. AI Sentiment Analysis   

•       The platform automatically:    

o       detects multilingual comments    
o       translates text into English    
o       predicts sentiment   
o       calculates confidence scores   
o       allows exportation of results     

### 4. Documentation Module   
•	Contains detailed guidance on system requirements, usage, inputs, and architecture.  

---

## Tech Stack & Major Tools   

•	Programming Language: Python 3.10   
•	Libraries/Frameworks:   
o	pandas, numpy, matplotlib, seaborn, plotly (for data processing & visualization)    
o	nltk, gensim, huggingface transformers, deep-translator (for NLP and translation)    
o	torch (for model inference)     
o	streamlit (for interactive UI)     
•	Others: Git, Bash    

---

## Input Requirements

### A. Demographics & Cross-Demographic Analysis    
•	Supported Data Sources:    
        o	Raw data
        o	File upload (CSV, Excel, others)
        o	API or URL
        
### •	Required Variables:    
o	Nationality, Gender, Age, Comments   

### •	Sample Format:
Nationality	Gender	Age	Comments
Egypt	Male	45	The experience was wonderful!


### B. Sentiment Analysis Module    
### •	Supported Input:    
     o	Raw text   
     o	File upload   
    o	API or URL input   
    
---

## Repository Structure     

pilgrim-sentiment-analysis/    

data/    
docs/    
images/    
notebooks/    

app.py    
requirements.txt    
README.md    

---

## Output    
### A. Demographic & Cross-Demographic Insights   
•	Interactive charts and tables showing pilgrim distribution across age, gender, and nationality   
•	Cross-tab analysis to explore patterns (e.g., satisfaction by gender & nationality)    

<img width="1639" height="369" alt="30" src="https://github.com/user-attachments/assets/251b33ff-42eb-4db5-9366-125024e2fab1" />    
<img width="1460" height="618" alt="31" src="https://github.com/user-attachments/assets/605ca15c-0c2d-4618-bd41-adaf1ba90e6a" />     
<img width="1792" height="642" alt="33" src="https://github.com/user-attachments/assets/fea40d3a-4549-4d67-9b4a-783850e04269" />     
<img width="1737" height="612" alt="34" src="https://github.com/user-attachments/assets/9581b52c-e2c6-4f8b-963b-7f97e3ff86b4" />     
<img width="1759" height="715" alt="35" src="https://github.com/user-attachments/assets/cb237c95-00cb-4e7a-8e92-cbe313c5ee16" />    
<img width="1629" height="750" alt="36" src="https://github.com/user-attachments/assets/58cf3aa8-8de3-4e4f-a656-39b2e650bb0f" />    


### B. Sentiment & Text Classification    
•	Table containing:   
     o	Original comment    
     o	English translation   
     o	Sentiment label (Positive/Negative)    
     o	Confidence score   

<img width="1903" height="882" alt="37" src="https://github.com/user-attachments/assets/815a85c4-6e35-43ca-b7f0-89a531962add" />

---
## Data Privacy   

- data shown is anonymized   
- project intended for demonstration   
- no confidential pilgrim information included   

---

## Future Improvements   
     •	Implement real-time data ingestion to replace the current manual data upload mechanism.   
     •	Expand sentiment classification to include neutral or mixed categories.   
     •	Integrate language-specific models to improve accuracy for underrepresented languages.  

### Other Improvements    

- Real-time streaming sentiment analysis    
- Multi-class sentiment prediction   
- Arabic-specific transformer models   
- Topic modelling for issue discovery   
- Interactive executive reporting   
- Docker deployment   
- REST API

---

## Skills Demonstrated   

- Python    
- Natural Language Processing   
- Transformer Models   
- Deep Learning   
- Machine Learning   
- Data Visualization   
- Streamlit   
- Plotly  
- Translation APIs   
- Interactive Dashboards   
- Business Intelligence   
- AI Application Development

---

## Lessons Learned    

This project strengthened my skills in developing end-to-end AI applications by integrating multilingual natural language processing (NLP), machine translation, transformer-based sentiment analysis, and interactive dashboard development. It enhanced my ability to build scalable data pipelines, process multilingual text, visualize demographic insights, and translate complex analytical outputs into actionable information for decision-makers. Through this project, I also gained valuable experience in deploying AI-powered applications with Streamlit and applying data science to solve real-world challenges in large-scale public service environments.     



