# Suitable ML Model for Students – Code Review Edition

**Objective :**  
Find the **best LLM(s) for code reviewing** that are actually accessible and affordable for students (budget-friendly or free-tier).

**Approach :**  
Exploratory Data Analysis (EDA) following six key practices:  
- Discovering  
- Structuring  
- Cleaning  
- Joining  (not applied in this analysis) 
- Validating  
- Presenting  

**Dataset used:**  
[LLM Benchmark Wars 2025–2026 – 24 Models Compared] **kaggle dataset** <br>  
(24 rows + 31 columns, including SWE-Bench, HumanEval, price_tier, performance_per_dollar, etc.)

**Key Findings :**  
- **SWE-Bench** is the strongest real-world benchmark for code-review capability.  
- Filtered top models with **SWE-Bench > 60%**.  
- Focused on **Budget** price tier (free or very low-cost inference) for student accessibility.

**Top Recommendations for Students :**  
These models offer excellent code-review performance at **minimal or zero cost**:

1. **MiniMax-M2.5**  
   - Strong SWE-Bench, Chinese market leader  
   - Budget tier  

2. **Qwen 3.5 Plus**  
   - Coding & multilingual specialist  
   - Budget tier  

3. **DeepSeek V3.2**  
   - Outstanding value (very high performance per dollar)  
   - Budget tier  

**Tech Stack :**  
- Python, Pandas, Matplotlib, Seaborn  
- EDA best practices

⭐ If you found this useful, please star the repo!  
Feedback & suggestions welcome.
