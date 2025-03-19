# SST Admissions Data Processing & Shortlisting  

## 📌 Overview  
This project focuses on automating the **admissions shortlisting process** for SST. It involves **data cleaning, filtering applicants based on selection criteria, statistical analysis, visualization, and interview scheduling**.  

## 🔍 Features  
- **Data Cleaning & Processing:** Handles inconsistencies in the dataset.  
- **Applicant Shortlisting:** Filters students based on minimum X and XII scores.  
- **Statistical Analysis:** Computes key metrics like average scores and top performers.  
- **Data Visualization:** Generates histograms and bar charts for insights.  
- **Interview Scheduling:** Assigns interviewers and slots to shortlisted candidates.  
- **Excel Export:** Saves shortlisted candidates and interview schedules.  

## 📂 Dataset  
The dataset is an **Excel file** (`Assignment [SST Admissions Team].xlsx`) containing:  
- **Student details:** User ID, Name, Gender, Family Income, etc.  
- **Academic scores:** X Score, XII Overall Score, Math Score, JEE Mains Score.  

## 🎯 Shortlisting Criteria  
A student is shortlisted if:  
✅ **X Score ≥ 85**  
✅ **XII Overall Score ≥ 80**  

## 📊 Statistical Insights  
- **Total applicants**: Computed dynamically.  
- **Total shortlisted**: Number of candidates meeting criteria.  
- **Average scores**: Mean of X and XII scores.  
- **Top performers**: Identifies highest scorers.  

## 📅 Interview Scheduling  
- **Interviewers**: Assigned from a fixed list.  
- **Slots**: 30-minute sessions per candidate.  
- **Rounds**: Conducted in multiple phases.  
- **Output**: Interview schedule saved as an Excel file.

## 🏆 Results  

![image](https://github.com/user-attachments/assets/f30e96a7-6301-4ff6-8964-7b74936bff6c)
![image](https://github.com/user-attachments/assets/c334dfbf-6975-4615-ae83-69927bb1332f)

### ✅ Shortlisted Applicants  

![image](https://github.com/user-attachments/assets/066d31a8-5613-429d-904d-9cd59d2c1572) 

### 📉 Performance Insights  

![image](https://github.com/user-attachments/assets/2d19b1ad-4a67-4a26-a755-e5b0012b5466)
![image](https://github.com/user-attachments/assets/13de5c9d-c915-4be8-a34e-4002dc758070)


### 📅 Interview Allocation  

![image](https://github.com/user-attachments/assets/13e4b3f8-3fda-4b62-939d-4b8360d31e4b)

## 📌 Installation & Usage  

### 🔧 Prerequisites  
Ensure you have **Python 3.x** installed along with the required libraries.  

### 📦 Install Dependencies  
Run the following command to install the necessary packages:  

```bash
pip install pandas matplotlib seaborn tabulate openpyxl
```

### 🚀 Running the Script  
Execute the script using:  

```bash
python test.py
```

### 🛠 Technologies Used

- Python 🐍  
- Pandas 📊  
- Matplotlib & Seaborn 📈  
- Tabulate 📝  
- OpenPyXL (for Excel file handling)  


