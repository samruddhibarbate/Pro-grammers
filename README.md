# Pro-grammers: Sentiment Analysis of Reviews

## Team Members
- **Samruddhi Barbate**  
- **Pritish Manwatkar**  

---

## Problem Statement
**Sentiment Analysis of Reviews**  
This project focuses on the collection and analysis of user reviews from three major e-commerce platforms—Yelp, Etsy, and AliExpress—to build a machine learning model for sentiment analysis.

---

## Introduction
The project involves collecting user reviews from Yelp, Etsy, and AliExpress to create a dataset for sentiment analysis. It details the methodologies used for data collection, the Python scripts for web scraping, and the challenges faced during the process. The README also includes an overview of the platforms, explanations of the implementation, and recommendations for future improvements.

---

## Platforms Overview

### 1. Yelp
- **Website**: [https://www.yelp.com](https://www.yelp.com)  
- **Description**: Yelp is an online business directory where users review and rate restaurants, retail stores, and service providers. Businesses use Yelp to connect with potential customers by showcasing user-generated content like ratings, photos, and reviews.

### 2. Etsy
- **Website**: [https://www.etsy.com](https://www.etsy.com)  
- **Description**: Etsy focuses on handmade, vintage, and unique products. Small business owners and independent creators use Etsy to sell their products directly to consumers. Customers leave reviews and ratings for their purchased items.

### 3. AliExpress
- **Website**: [https://www.aliexpress.com](https://www.aliexpress.com)  
- **Description**: AliExpress is a global online retail marketplace operated by Alibaba Group. It enables small businesses in China to sell their products worldwide. The platform includes reviews, ratings, and feedback from buyers.

---

## Data Collection Methodology

### Tools & Technologies Used
- **Programming Language**: Python  
- **Libraries**: 
  - `requests`
  - `BeautifulSoup`
  - `csv`
  - `random`
  - `time`  
- **Techniques**:
  - User-Agent Rotation to avoid detection and bypass restrictions.
  - Parsing HTML elements using BeautifulSoup.

### Scraping Process
1. **Identify Target Data**: Extracted user reviews, ratings, and timestamps.  
2. **Send HTTP Requests**: Utilized the `requests` library with randomized User-Agent headers.  
3. **Parse HTML Content**: Located and extracted data with BeautifulSoup.  
4. **Save Data**: Exported extracted information to CSV files for analysis.

---

## Results & Observations
- Successfully extracted data from Yelp, Etsy, and AliExpress.  
- Implemented User-Agent rotation to prevent blocks during scraping.  
- Faced anti-scraping measures on some platforms that required additional handling.  

---

## Conclusion
The project demonstrates the successful collection of user reviews from Yelp, Etsy, and AliExpress using Python for sentiment analysis. The data can provide insights into customer sentiment, business performance, and consumer behavior.  

### Future Improvements
- Implementing proxy usage for enhanced anonymity.  
- Incorporating captcha-solving techniques for more efficient data collection.  

---

## Acknowledgments
Thank you for exploring our project! Feel free to reach out for further collaboration or inquiries.
