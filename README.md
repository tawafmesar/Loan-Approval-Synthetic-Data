## **📁 Repository Description (Short Summary)**  
`Loan Approval Synthetic Dataset | 20k Records | CSV | Financial Analytics`

---

# **📊 Loan Approval Synthetic Dataset**  
**A synthetic dataset simulating loan application decisions with financial and demographic features.**

![image](https://github.com/user-attachments/assets/2a0f701a-2a62-4ce8-9119-350c759c3269)


---

## **🔍 Key Features**  
✅ **20,000 synthetic records**  
✅ **5 key financial/demographic columns**  
✅ **Realistic value ranges**  


---

## **📋 Column Descriptions**  

| Column          | Description                          | Range/Values              | Data Type |
|-----------------|--------------------------------------|---------------------------|-----------|
| `age`           | Applicant’s age                      | 21–69                     | Integer   |
| `income`        | Annual income (USD)                  | 20,000–99,999             | Integer   |
| `credit_score`  | Credit score                         | 300–849                   | Integer   |
| `loan_amount`   | Requested loan amount (USD)          | 1,000–49,999              | Integer   |
| `approved`      | Loan approval status                 | 0 = Denied, 1 = Approved  | Binary    |

---

## **🚀 Quick Start**  
### **1. Load the Data**  
```python
import pandas as pd

# Load the dataset
url = 'https://raw.githubusercontent.com/tawafmesar/Loan-Approval-Synthetic-Data/main/loan_credit_approval.csv'
df = pd.read_csv(url)

# Preview
print(df.head())


```

### **2. Basic Analysis Example**  
```python
# Approval rate calculation
approval_rate = df['approved'].mean() * 100
print(f"Global Approval Rate: {approval_rate:.1f}%")
```

---

## **📈 Suggested Use Cases**  
- 🏦 Loan approval prediction models  
- 📉 Exploratory data analysis (EDA)  
- 🎓 Machine learning education/tutorials  
- 🔍 Bias detection in synthetic systems  
