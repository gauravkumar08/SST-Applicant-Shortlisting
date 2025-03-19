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

### ✅ Shortlisted Applicants  
- The number of students meeting the eligibility criteria.  
- List of top-performing students based on scores.  

### 📉 Performance Insights  
- The average X and XII scores of the applicants.  
- Percentage of students shortlisted vs. total applicants.  

### 📅 Interview Allocation  
- Candidates successfully assigned to interviewers.  
- Number of interview slots scheduled.  


## 📌 Installation & Usage  
### 🔧 Prerequisites  
Ensure you have **Python 3.x** installed along with the required libraries:  

```bash
pip install pandas matplotlib seaborn tabulate openpyxl
