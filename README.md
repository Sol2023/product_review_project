# Product_review_project

## Project Purpose
The primary objective of this project is to enhance customer satisfaction by identifying key customer concerns and implementing internal measures for improvement. Throughout this project, tasks such as web data scraping, sentiment analysis, text labeling, and data visualization will be undertaken to gain valuable insights.

## Main Steps

![image](https://github.com/Sol2023/product_review_project/assets/92194263/021806f4-9847-41a9-ae6d-b457b856bcc4)


### **1. Web scraping**

1.1 *Data Source*: 

[1] Company Website

- Fetch all the product name using python with selenium library, [check company product here](https://npicpet.com/collections/all)

[2] Amaozon

- First use instant data scraper to fetch existing data;

- After the pipeline built, use python to fetch the incoming new comments. 

*note: Since Amazon Anti-scraping technology keeps improving, the current code might not fit for future situation

1.2 **Tools**:

[1] Python (with Selenium)

[2] Instant Data Scraper


### **2. Data Cleaning in Python**

- Fetch the comment datetime
- Transfer rate stars from text to float
- Select only product_id, username, rate_date, title, comment_body

### **3. OPENAI Labeling**

Appling OPENAI API to conduct labeling in three dimensions: 

1) Sentiment analysis: [Positive, Netural, Negative]
2) Complaint Category:
3) Quality Issues:

OPENAI API Fees for 3000 reviews labeling:

<img width="1279" alt="image" src="https://github.com/Sol2023/product_review_project/assets/92194263/72f656a6-11ad-4122-84ed-c285f159270f">


### **4. Database Build**

MySQL

### **5. Data Visualization**

Power BI

<img width="863" alt="image" src="https://github.com/Sol2023/product_review_project/assets/92194263/e3c89275-9589-4720-812a-1a0521cdd4f2">


## **To do**

- Keep fetching latest comment
- Modify the dashboard, make the trend of positive rate for each product when mouse float on it
- Mapping all the product_id to company product name
- Fetch client prodcut name and product id, after that fetch the related comment information
- Keep accumulating the data
- Add more marketing brand, and get insight with the market bench mark
