# Consumers Energy Analyst Job Description Text Analysis

## Project Overview:

- Open the [Consumers Energy Careers Website](https://www.consumersenergy.com/company/careers)
- Use Selenium and BeautifulSoup to open each job listing page, open job listings and scrape the job description text from the page.
- Results pulled as of 10/18/2020.  However, each time you run the script, it will pull what job listings are currently available.
  
 
## Tools Used In This Project
- **Python Version:** 3.6
- **Python Packages:** selenium, pandas, lxml,bs4,os,time,re,nltk,gensim.models,numpy,matplotlib,wordcloud,string,pprint

 

## Data Cleaning [Link to the Python Jupyter Notebook](https://github.com/abrambeyer/consumers_energy_job_text_analysis/blob/main/CMS%20Energy%20Analyst%20Job%20Description%20Skills.ipynb)
- Filter down to only jobs I thought sounded like an "analyst."  Usually, job titles with the word "data" or "analyst" or "business consultant."  
- Only scrape job description text under the html div "jobs" to eliminate unwanted text. 
- Tokenize the job description text
- Remove stop words, punctuation, extra spacing and other commong job description words.  
- Convert to lowercase

## Exploratory Data Analysis



### Job Listings Scraped as of 10/18/2020
<img src="https://github.com/abrambeyer/consumers_energy_job_text_analysis/blob/main/job_description_job_title_counts_10.18.PNG" width="500">

### Word Counts and Dispersion Plot

*Most Common Words in the Vocabulatry*
 <img src="https://github.com/abrambeyer/consumers_energy_job_text_analysis/blob/main/top_50_analytics_job_words.png" width="500">  
 <img src="https://github.com/abrambeyer/consumers_energy_job_text_analysis/blob/main/top_50_analytics_job_verbs.png" width="500">  
 <img src="https://github.com/abrambeyer/consumers_energy_job_text_analysis/blob/main/top_50_analytics_job_adj.png" width="500">  
 
 *Word Cloud* 
 ##### Most common words appearing in Consumers Energy job listings for analytics-related jobs as of 10/18/2020.
 <img src="https://github.com/abrambeyer/consumers_energy_job_text_analysis/blob/main/cms_job_description_word_cloud.png" width="500">  
 
 *Lexical Dispersion Plot*
 ##### I was interested in which common data analytics technologies appear in the aggregate job listing text.  The technologies
 ##### in the below plot are simply the ones I thought of in the moment or was most interested in seeing.
 <img src="https://github.com/abrambeyer/consumers_energy_job_text_analysis/blob/main/cms_jobs_lexical_dispersion.png" width="500">  
 
 
