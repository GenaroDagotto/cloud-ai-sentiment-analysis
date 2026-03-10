# Cloud AI Sentiment Analysis Workflow

This project performs AI sentiment analysis on YouTube comments using Microsoft Azure.

## Tools Used
- Azure Ubuntu Virtual Machine
- Azure AI Language
- Azure Blob Storage
- Python
- Power BI
- Nginx

## Project Overview
The workflow uses a CSV file of YouTube comments from a Roger Federer video about tennis and life.  
A Python script running on an Azure Ubuntu VM sends the comments to Azure AI Language for sentiment analysis.  
The output includes sentiment labels and confidence scores, which are saved in a CSV file and uploaded to Azure Blob Storage.  
A simple HTML summary page is also hosted live on the VM, and the results are visualized in Power BI.

## Files
- `youtube_comments.csv` → input dataset
- `sentiment_results.csv` → output results
- `sentiment_analysis.py` → Python workflow
- `summary.html` → HTML summary page

## Sample Visuals

### Live Web Page
![Live Web Page](images/foto%20100.png)

### Azure AI Language Resource
![Azure AI Language](images/foto%20103%20Language%20Service.png)

### Blob Storage Results
![Blob Storage](images/foto%20104%20results%20container.png)

### Power BI Dashboard
![Power BI](images/power%20bi%20charts.png)

## Workflow Steps
1. Collect YouTube comments in a CSV file
2. Upload the dataset to an Azure Ubuntu VM
3. Run Python sentiment analysis using Azure AI Language
4. Save results to a CSV file
5. Upload results to Azure Blob Storage
6. Host a summary page with Nginx
7. Visualize the results in Power BI

## Outcome
This project demonstrates a complete cloud workflow using Azure virtualization, AI services, storage, web hosting, and data visualization.