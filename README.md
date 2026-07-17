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

<img width="1903" height="882" alt="image" src="https://github.com/user-attachments/assets/e7f0a762-3f28-4853-871a-7b6a8f2ac422" />    


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


---

---

# Documentation: Using the Application

This documentation provides insights about the application. It highlights valuable information about the application, purpose and audience, user manual, modules, libraries, and technology used, limitations of the app, and future improvements. It also details where to find codes for debugging and improvement. 

# Content 
## About the Application: Purpose 

The application is designed to provide analysis of the sentiments, demographics and cross-demographic analysis of pilgrims visiting the Umrah and Hajj. The models work by classifying comments either positive or negative in their respective key service areas. In reality, Hajj and Umrah experience more than 30 million visitors who leave comments and feedback in their native languages; more than 27 languages across the globe. Analyzing the comments and feedback is a real challenge considering the characteristics of the big data: volume, Velocity, Variety, Veracity, and Value.  Accordingly, this AI-driven application remains valuable to authorities helping them to leverage on the comments towards addressing and sorting recurring concerns systematically. The application is significant in understanding the demographic nature of visitors significantly important for preparation, planning, management, and effecting hosting of Umrah and Hajj pilgrims. 

## User Manuals 

The user of the application being administrators and authorities in Hajj and Umrah, can use the application to either analyze sentiments, demographics, or cross-demographic characteristics of visitors. The following sections highlights how to use the features for analysis and text classification. 

## A. Demographics and Cross-demographics Analysis 

This feature can be accessed from the homepage (https://sentimentalanalysispilgrim-mwaaysgfzdssubzst7dba2.streamlit.app/). Once on the home page, a user should scroll down to the Cross-Demographic and Demographic Analysis and Sentimental and Text Classification analysis (See the figure below) section on the bottom left of the home page.

<img width="494" height="154" alt="backhome" src="https://github.com/user-attachments/assets/28306de5-3e02-4374-b1c0-dc3ac930e95e" />


Double click on the Cross-Demographic and Demographic Analysis button to navigate to demographic and cross demographic analysis section.      
In this section, the user can get comprehensive and interactive insights into the demographics of Hajj and Umrah pilgrims. The key characteristics analyzed here in include: 

        •	Age Distribution: Interactive visualizations illustrating the range and concentration of pilgrims’ ages.    
        •	Statistical Overview: Key metrics including minimum, maximum, mean, quartiles, and mode of pilgrim ages.    
        •	Nationality & Gender Breakdown: Detailed analysis of visitor nationalities segmented by gender.    
        •	Cross-Demographic Insights: Integrated visualizations combining age, gender, and nationality to highlight deeper demographic trends.  
        
To leverage on this feature, scroll down on the page to a section where can input data either as a file, url, API, or textual data. The section can be found on the middle left part of the page. A user should come across the following section:       

Load Data Appropriately by Select the right Data Source     
 
Upload File
 
Enter API URL
 
Paste Raw Text

<img width="334" height="99" alt="load" src="https://github.com/user-attachments/assets/4ed69594-8195-4cde-acca-58f23c837962" />


Select your appropriate source and load data. A user should ensure that the data loaded has the following at least the following columns:      

a.	'الجنسية Nationality',     
b.	'الجنس Gender',     
c.	 'العمر Age'      

Note: Without these columns, the analysis will throw an error.      
 Once data is loaded, the system analyzes the data and displays the visuals of the analysis.     
Once data is loaded, a user has the ability to filter data accordingly.     

<img width="1504" height="335" alt="filterpic" src="https://github.com/user-attachments/assets/92eeee5d-1e95-4edc-bee4-5087a36de981" />


Users should expect to see:  

a.	A line graphs showing descriptive and dispersion statistical distribution of age characteristics      
b.	An interactive plotly linear age distribution      
c.	An interactive Comparative bar graph of nationality by gender      
d.	An interactive bubble plot of mean ages of nationality and gender     
e.	An interactive histogram visualizing demographics by nationality, gender, and age     

There are no limits to the data a user can input since the system is designed to work with Big data     
Once done and need to access the sentimental and text classification feature, double click on the tab Back Home found at the left bottom of the dashboard board.     

<img width="494" height="154" alt="backhome" src="https://github.com/user-attachments/assets/9fca9364-3147-482b-bda9-33a60c3675ff" />



## A. Sentimental and Text Classification Analysis    

Once on the main page, https://sentimentalanalysispilgrim-mwaaysgfzdssubzst7dba2.streamlit.app/, scroll down to the bottom left of the page. Click on the button sentimental and text classification.    
  




<img width="653" height="145" alt="sentpic" src="https://github.com/user-attachments/assets/b426ca94-6685-4c8b-b98e-d113c9698408" />


  
This feature accepts data inputs as files or text comments. Future improvements will include url and API to allow for real-time sentimental and text classification analysis. For sentiment and text classification analysis, a user can upload a file, type, or copy and paste comments appropriately. Once loaded the data is analyzed and output displayed as dataframe which can be downloaded for further analysis or documentation.  

The expected output is:     

<img width="1735" height="669" alt="outputpic" src="https://github.com/user-attachments/assets/dde66590-2318-437c-8fdf-7431ba684b43" />


Once done, a user can input more data or navigate to the main page using the Back Home tab at the left top of the page.     


# Tech Stack

PilgrimageAI is built using a modern and modular tech stack, enabling real-time data visualization, multilingual NLP processing, and a rich interactive user experience. Here's a breakdown of the technologies used:     
Backend & App Framework     
•	Python: Core programming language for logic, data processing, and NLP.     
•	Streamlit: Rapid web app framework used to build interactive dashboards and forms.      
•	Streamlit Autorefresh: Enables real-time dashboard updates by auto-refreshing at set intervals.     

# Data Processing & Visualization    
•	Pandas: Efficient data handling and analysis of tabular feedback data.    
•	Plotly Express: Used for building interactive visualizations (e.g., line charts, histograms, scatter plots).    
•	Seaborn & Matplotlib: Statistical plotting libraries used for advanced visual analytics like age distribution with statistical markers.   

#### Natural Language Processing (NLP)
•	Transformers (Hugging Face): For sentiment analysis using pretrained models like distilbert-base-uncased-finetuned-sst-2-english.      
•	GoogleTranslator (Deep Translator): Translates multilingual user feedback into English before processing.     
•	Custom Text Classification Pipeline: Uses keyword token matching to categorize feedback into themes (e.g., transport, accommodation, staff behavior).  

#### File & API Handling    
•	pdfplumber: Extracts text from PDF feedback files.    
•	Requests: Fetches data from external APIs.    
•	StringIO: Converts text and raw CSV input into readable data frames.    

#### UI/UX Enhancements    
•	Custom HTML & CSS: Embedded styles add rich visual design (e.g., background images, overlays, styled buttons).    
•	Responsive Layouts: Uses st.columns, container sizing, and adaptive rendering to ensure the app works well across devices.     

### Runtime Environment
•	Streamlit Watchdog Disabled: To avoid inotify limit errors on Linux systems, file system watchers are turned off with:      
         os.environ["STREAMLIT_DISABLE_WATCHDOG_WARNINGS"] = "true"
         os.environ["STREAMLIT_WATCHDOG_MODE"] = "none"
OpenAI and Chatgpt:  to improve generated codes and debugging the app end-to-end      

#### Code Structure 

For Full code structure and debugging visit the notebook and app.py on github public repo     
 

