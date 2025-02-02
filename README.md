# NHS Scotland Operation Cancellations Analysis  

## 📊 Overview  
This project analyzes operation cancellations in NHS Scotland between **June 2015 - Jan 2024** to understand trends, reasons for cancellations, and their regional distribution. Using **data visualization, statistical analysis (OLS regression, hypothesis testing), and comparison by NHS board**, we derive insights into healthcare efficiency and disruptions.  

## 🔍 Key Findings  
- **Main reasons for cancellations:**  
  - **Patient-initiated (36.1%)** and **clinical reasons (35.2%)** account for over **70%** of all cancellations.  
  - **Nonclinical capacity issues (24.0%)** (e.g., lack of beds) are another significant factor.  
- **Regional disparities:**  
  - **NHS Borders** has the highest **nonclinical capacity cancellations**, potentially linked to **bed-blocking** issues.  
  - **NHS Orkney** has higher cancellation rates due to travel-related issues.  
- **Impact of COVID-19:**  
  - Sharp drop in planned operations at pandemic onset, followed by gradual recovery.  
  - **No significant long-term effect** on cancellation rates (based on t-test).  
- **Trend analysis:**  
  - A slight **downward trend** in cancellation rates over time.  
  - High variance suggests other **external factors** influencing trends.  

## 📂 Data  
- **Source:** Public Health Scotland (PHS) OpenData.scot  
- **Datasets:**  
  - **Overall cancellations** dataset (monthly data for Scotland)  
  - **NHS board-specific cancellations** dataset  
  - **Health board metadata**  

## 📈 Methods Used  
- **Data Cleaning & Processing**: Merging, filtering, and handling missing values  
- **Exploratory Data Analysis**: Visualization of trends and cancellation distributions  
- **Statistical Analysis**:  
  - **OLS Linear Regression** (identifying trends)  
  - **Two-sample t-test** (pre/post COVID-19 analysis)  
