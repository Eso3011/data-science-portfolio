# WHO Antibiotic Resistance Web Scraping Project

This project collects and analyzes World Health Organization (WHO) news articles related to antimicrobial (antibiotic) resistance using Python.

## Live Notebook
You can view and run the full Python notebook here:
https://colab.research.google.com/drive/1iOljMOV9PEYPTtTqQzpEfNDUovK4iyOi?usp=sharing

## Project Summary
The goal of this project was to automatically collect WHO health news and identify articles related to antibiotic resistance.

Because the WHO website uses dynamic content, direct scraping was not reliable. To solve this, I used the official WHO RSS feed, which provides structured and up-to-date article data.

The script:
- Fetches WHO RSS feed data  
- Parses article titles, links, and publication dates  
- Filters articles using antibiotic resistance keywords  
- Stores results in structured formats (Excel and CSV)

## Tools Used
- Python  
- Requests  
- BeautifulSoup  
- Pandas  
- WHO RSS Feed  

## Why This Matters
Antibiotic resistance is a major global health challenge. This project demonstrates how data automation and analysis can support public health monitoring and decision-making.