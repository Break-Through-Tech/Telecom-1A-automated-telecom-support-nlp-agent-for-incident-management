
# TelcoTriage: Automated Support NLP Agent

**Company / Org:** Verizon  
**Challenge Advisor:** Toby Sheung, tobsheung@gmail.com    
**AI Coach:** Srihari Kamath, srihari.kamath@breakthroughtech.org   
**Program:** Break Through Tech AI Studio - Fall 2026

---

## 🏢 About Verizon

Verizon is a leading telecommunications company that provides wireless and wireline services to consumers, businesses, and government entities. With a commitment to innovation and customer service, Verizon is focused on enhancing user experiences in a rapidly evolving digital world.

---

## 🎯 The Challenge

### Project Summary
In this project, you will use customer tweets and Classification + Natural Language Processing (NLP) to build an AI agent to resolve or to escalate customer issues. This will help out company address customer satisfaction and provide quick turn around times for customer service problems.

### Success Criteria
The model accuracy of classification of customer tweets and whether or not the agent  is outputting useful insights on customer problems. 

- Model Accuracy <= 70%
- Nice looking agent AI outputs

### Stretch Goal
Adding more functionality to agent AI and creating different dashboards to the agent output.

### Project Milestones

Use these milestones to guide your work. Your team will create a **GitHub Projects board** to track tasks within each milestone.

| Month | Milestone | Key Activities |
|---|---|---|
| September | Data Cleaning & Labeling | EDA + cleaning dataset to isolate just telecom messages and important phrases <br>- Drop General/Other label from data due to noise <br>- Address class imbalanced labels (ex.use weights)<br>-Remove @mentions <br>-Remove URLs https://t.co/... links <br>-Decode HTML entities like &amp;amp; to & and &lt;lt to < using html.unescape() <br>-Normalize text with lowercase, remove punctuation, special characters |
| October | Vectorization & Baseline Modeling | Vectorize words to matrix + Baseline model training + Experimentation + Evaluation <br> - F1 score, Accuracy, Precision, Confusion Matrix |
| November | AI Agent Development | Creation of AI Agent of using model to output a action (creating issue ticket) |

---

## 📊 Dataset

**Name and Source:** Customer support on Twitter (Kaggle)  
**Format:** CSV/TSV  
**Size:** under 1gb  
**Location:** https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter

### Key Details
- Description of Original data: https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter
- I filtered to have only telecom companies: Verizon, Spectrum, AT&T, Sprint and T-Mobile 
- Add a label column for classification (dataset currently has 6 labels)
- We are focusing on 5 class labels: Billing/Payment, Network Connectivity, Device + Technical Support, Account/Plan Management and Cancellation

### Datasets
- Preprocess + Train + Validation: filitered_label
- Testing: labeled 3000 

---

## 🛠️ Suggested Approach

**ML Problem Type:** Classification, Natural Language Processing (NLP)

**Recommended Libraries:**
- pandas, scikit-learn, TensorFlow, Hugging Face

**Evaluation Metrics:**
- F1 score, Accuracy, Precision, Confusion Matrix

---

## 📚 Resources to Get Started

The following resources will help your team understand the problem space and potential technical approaches for this project:

**Background Reading:**
- https://www.verizon.com/business/resources/articles/s/how-ai-customer-service-can-help-enable-better-interactions/

**Technical Tutorials:**
- Preprocessing: https://www.geeksforgeeks.org/nlp/text-preprocessing-for-nlp-tasks/
- Preprocessing: https://medium.com/@devangchavan0204/complete-guide-to-text-preprocessing-in-nlp-b4092c104d3e
- Text classification: https://www.datacamp.com/tutorial/text-classification-python

**Code Examples:**
- [e.g., Link to a relevant GitHub repo]
- [e.g., Link to a sample implementation or starter code]

**Other:**
- NLTK: https://www.nltk.org/
- F1: https://towardsdatascience.com/micro-macro-weighted-averages-of-f1-score-clearly-explained-b603420b292f/
- Confusion matrix: https://www.geeksforgeeks.org/machine-learning/confusion-matrix-machine-learning/

*Feel free to explore beyond these, and share anything interesting you find with me!*

---

## 🤝 How We'll Work Together

**Official check-ins:** During our biweekly 45-minute AI Studio Lab Section meeting block (2nd and 4th week of every month)

 **Other ways to reach out to me with questions:** 
* Team's Discord
* Email
* Request Meeting by Email
* [Note: I will aim to respond within 48 hours. Please reach out to your AI Studio Coach with urgent questions.]

> 💡 **Challenge Advisor: Please update the above based on your availability and preference. If you are not able to answer questions or meet with fellows outside of the biweekly Lab Section check-ins, simply write in "N/A (only available during the official check-in times)"**

**Recommended free coding / collaboration tools**
* […]
* […]

---

## 🚀 Getting Started

1. **Review this overview document** and note any questions for our first meeting
2. **Begin reviewing the dataset** using the link above
3. **Read the GitHub Projects documentation** [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)

I’m excited to work with you!

---

## ❓ Questions?

Please bring any questions to our first meeting during the week of August 24th (Break Through Tech’s Bridge to Studio - Session C). 
