# University Student

## Skills & Technologies 🛠️

### Programming Skills

* **Python:** Intermediate knowledge, mainly for data analytics (data cleaning and manipulation). 
    * **Libraries:** NumPy, Pandas (Sufficient Knowledge); Matplotlib (Basic Knowledge)
    * *Currently practicing to enhance skills in machine learning (Scikit-learn) and data visualization (Seaborn).* 
* **SQL:** Basic knowledge, mainly for data analytics purposes.
    * *Currently still practicing to enhance data manipulation skills using SQL.* 

### Non-Programming Skills

* **Video Editing:** Basic editing skills (manual subtitling, custom transitioning) using Adobe Premiere Pro.
* **Stock Fundamental Analysis:** Basic skills in analyzing a stock’s fundamental performance.
* **Microsoft Office 365:** Basic knowledge in Word, Excel, and PowerPoint. 

## Education 🎓

* **Sampoerna University (Jakarta)** 
    * Undergraduate Student majoring in Information Systems
    * Expected Graduation: 2027
    * Current GPA: 3.84
* **University of Arizona (Joint Campus with Sampoerna University)** 
    * Undergraduate Student majoring in Applied Computing
    * Expected Graduation: 2027
    * Current GPA: 3.84
* **SMA IPEKA PLUIT (Jakarta)**
    * Science Major
    * Graduated: 2023

## Organizational Experience 💼

* **Sampoerna Youth Investment Club** as Member of Publications and Documentations Division (_August 2024 - May 2025_)
    * Responsible for documentation throughout club events. 
    * Conduct video editing for marketing videos and event recordings (Instagram, TikTok). 
* **TEDxSampoernaUniversity** as Member of Publications and Documentations Division (_2024_)
    * Responsible for documenting the event’s press conference and video-recording the main event. 
    * Worked with cross-functional teams (e.g., marketing) to align documentation with organizational goals. 
    * Conducted video editing for marketing videos and main event recordings for YouTube. 
* **Career Month** as Member of Content Planning Division (_October 2024_) 
    * Responsible for brainstorming content ideas for social media marketing. 
* **FETO Volunteer Organizer** (_March 2023_) 
    * Mainly worked on logistical backstage. 
    * Responsible for setting up stage and backstage logistics (chair setup, lunch management). 

## Projects 🚀

1.  **TECH STOCK PRICES ANALYSIS**
    * **Description:** This project involved data cleaning and analysis of daily prices and volumes for ten major technology stocks (AAPL, AMZN, BABA, CRM, FB, GOOG, INTC, MSFT, NVDA, TSLA) sourced from Yahoo Finance. 
    * **Key Findings:**
        * Identified Amazon (AMZN) as having the highest closing price ($3731.41 on July 8th, 2021) based on the most recent data. 
        * Visualized the closing price at the end of each month for the 10 tech stocks. 
        * Determined NVIDIA (NVDA) experienced the greatest percent increase in closing price (29.81% on November 11th, 2016). 
    * **Technologies Used:** Python, Pandas (CSV I/O, `to_datetime` conversions, `groupby` aggregations, percentage-change calculations), Matplotlib (Time-series plotting with customized ticks, legends, and annotations). 
    * **🔗 Link:** [View Project on DataCamp](https://www.datacamp.com/datalab/w/ff573cec-0ba1-423e-93b2-c0bf98e3ce3c/edit)

2.  **INTERNATIONAL DEBT ANALYSIS**
    * **Description:** This project focused on using PostgreSQL for data extraction and analysis of a dataset containing 2,300 rows of debt indicators for various countries. 
    * **Key Queries & Findings:**
        * Determined the number of distinct countries present (124). 
        * Identified the country with the highest amount of debt (China). 
        * Found the country with the smallest debt repayment entry (Timor Leste, though the resume lists "highest" twice, context suggests "smallest" for the `MIN(debt)` aggregation).
    * **Technologies Used:** PostgreSQL (SQL).
    * **SQL Aggregations Used:** `COUNT(DISTINCT country_name)`, `SUM(debt) ... GROUP BY country_name ORDER BY SUM(debt) DESC LIMIT 1`, filtering by `indicator_code` and using `MIN(debt)`. 
    * **🔗 Link:** [View Project on DataCamp](https://www.datacamp.com/datalab/w/c7099794-242b-457b-868e-32402b95e894/edit) 

3.  **SIGN LANGUAGE INTERPRETER**
    * **Description:** A group project for the Object-Oriented Programming course, creating a sign language interpreter.
    * **My Role:** Handled the back-end development, specifically how the program reads and trains the dataset to predict sign language from a camera feed. 
    * **Architecture:** Used Java for the GUI interface and Python for the back-end (sign language reader and model training). 
    * **Technologies Used (Back-end):** Python, NumPy (array modifications), TensorFlow (deep-learning frameworks, training, inference, tensor math), Scikit-learn (split and train dataset), Mediapipe (real-time hand landmark detection), OpenCV (camera frame grabbing, image manipulation, displaying live footage and predictions). 
    * **🔗 Link:** [View Project Files on Google Drive](https://drive.google.com/drive/folders/1EgQaPcSx_NtoFmGpBwcFHAexBaZ-gXDq) 


