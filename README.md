# -FUTURE_DS_03-.
# 📊 Campus Feedback Analysis  

**Use Data Science & NLP to turn student feedback into actionable insights!**  

This project analyzes structured and text-based feedback collected from students after campus events and courses. Using pandas, matplotlib, seaborn, and TextBlob, we explore ratings, apply sentiment analysis, and generate insights to improve the student experience.  


## 🚀 Project Overview  
Campus activities like workshops, tech fests, and classes often gather student feedback — but is it used effectively?  

In this project, we:  
- Perform **EDA (Exploratory Data Analysis)** on feedback ratings.  
- Apply **NLP sentiment analysis** on student comments.  
- Visualize patterns using charts.  
- Provide **recommendations** to improve future events.  


## 📂 Repository Structure  
📦 campus-feedback-analysis
┣ 📂 data/ # sample or anonymized dataset (CSV)
┣ 📂 notebooks/ # Jupyter/Colab notebooks
┣ 📂 mini-report/ # PDF mini-report 
┣ 📄 requirements.txt # dependencies
┣ 📄 README.md # project overview (this file)
┣ 📄 LICENSE # open-source license (MIT/Apache)
┗ 📄 .gitignore # ignored files (checkpoints, temp data)

## 🛠️ Tools & Libraries  
- [Google Colab](https://colab.research.google.com/)  
- **Python**: pandas, numpy, matplotlib, seaborn  
- **NLP**: TextBlob  

## 📊 Example Workflow  

1. **Data Preparation**  
   - Load Google Form CSV / sample dataset.  
   - Clean column names and handle missing values.  

2. **EDA**  
   - Distribution of ratings per question.  
   - Average ratings per course/event.  
   - Identify top strengths and weaknesses.  

3. **Sentiment Analysis (NLP)**  
   - Analyze comments using TextBlob.  
   - Classify feedback into Positive / Neutral / Negative.  
   - Compare sentiment trends with rating scores.  

4. **Insights & Recommendations**  
   - Highlight lowest-rated aspects (e.g., fairness of evaluation, session length).  
   - Suggest actionable improvements.  
## ▶️ How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/Maryem1206/-FUTURE_DS_03-..git
   cd -FUTURE_DS_03-.
  2. Install dependencies
    pip install -r requirements.txt
3. Open The notebook

## 📌 Results Summary  
- Students rated *teacher preparation* highly ✅.  
- *Fairness of evaluation* and *teaching methods* need improvement ⚠️.  
- Sentiment analysis shows **80% positive**, **10% neutral** feedback.

## 🔮 Future Work  
- Use advanced NLP (VADER, BERT) for better sentiment analysis.  
- Build a dashboard (Streamlit/Plotly Dash) for real-time feedback monitoring.  
- Automate keyword extraction to spot recurring issues.  

## 📜 License  
This project is licensed under the [MIT License](LICENSE).  

