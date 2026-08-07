---

> ## Challenge Advisor: Update & Finalize Your Project Overview
>
> > 💡 **These grey text instructions are just for you, the team's Challenge Advisor; please delete them once you have completed the steps below.**
>
> We've pre-populated this Challenge Project Overview page — which is what will be shared with your Break Through Tech student team in August — using the details from your submission form. You should have received an email inviting you to join this repo as a Collaborator, which will allow you to add files and make edits.
> 
> In order for your project to be finalized and assigned to a team, please:
> 1. **Review all sections below** and update or expand any content as needed, making sure to address the SME Feedback in the section immediately below. Look for square brackets to find the places below that require additional inputs from you (e.g., "About [Company / Org Name]").
> 2. **Add your dataset** to the [data folder](data) in this repo.
> 3. **Close the Issue assigned to you in this repo** to let us know that you have made your edits and the overview page is ready for final review. You can do this by going to the _Issues_ tab in the top-left section of the menu above, adding a comment that says "CA review complete", and clicking the button to Close the Issue. 
>
> If you're unfamiliar with how to edit a page like this in GitHub, check out [this tutorial](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/handson/edit-readme.html) for a quick overview (start with step 2 and only edit this page), and [this guide](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/markdown.html) on how to use Markdown to compose text.
>
>
> ❌ Remember that this is a public repo. Do NOT include: Proprietary data, PII, API keys, credentials, or anything confidential.

---
## 📋 BTT Internal Evaluation Notes

| Check | Status | Notes |
|-------|--------|-------|
| Python Compatibility | 🟢 | The tech stack is centered on Python, particularly utilizing Google Colab, which supports Python-based libraries for NLP and classification. |
| Data Readiness | 🟡 | The dataset is publicly available but requires significant cleaning and preprocessing, which might take substantial time during the semester. |
| Resource Check | 🟢 | Only requires free-tier tools available on Google Colab, no specialized hardware needed. |

**Student Fit Score:** 8/10  
**Technical Depth Score:** 7/10  
**Overall Recommendation:** REVISE

**Advisor Feedback Draft:**
The project presents a strong industry application in NLP for customer service, aligning well with current trends in AI. However, it is essential to ensure students are well-equipped for the data preparation phase. Consider defining clearer success metrics to avoid ambiguity in performance criteria. Moving forward, I recommend refining the dataset-cleaning strategy to ensure students can proceed with model development within the allocated time frame. A more structured plan with milestones would enhance clarity and feasibility.

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
| September | Data Cleaning & Labeling | EDA + cleaning dataset to isolate just telecom messages and important phrases + labeling of tweets (issues or general/billing) |
| October | Vectorization & Baseline Modeling | Vectorize words to matrix + Baseline model training + Experimentation + Evaluation |
| November | AI Agent Development | Creation of AI Agent of using model to output a action (creating issue ticket) |

---

## 📊 Dataset

**Name and Source:** Customer support on Twitter (Kaggle)  
**Format:** CSV/TSV  
**Size:** under 1gb  
**Location:** https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter

### Key Details
- [Brief description of what's in the data]
- [Any known limitations or preprocessing needed]
- [Link to data dictionary or documentation, if available]

---

## 🛠️ Suggested Approach

**ML Problem Type:** Classification, Natural Language Processing (NLP)

**Recommended Libraries:**
- [e.g., pandas, scikit-learn, TensorFlow, Hugging Face]

**Evaluation Metrics:**
- [e.g., Accuracy, Precision/Recall, RMSE, BLEU score]

---

## 📚 Resources to Get Started

The following resources will help your team understand the problem space and potential technical approaches for this project:

**Background Reading:**
- [e.g., Link to an article or blog post about the problem domain]
- [e.g., Link to an industry report or case study]

**Technical Tutorials:**
- [e.g., Link to a free tutorial on the ML technique(s) involved]
- [e.g., Link to documentation for a key library or tool]

**Code Examples:**
- [e.g., Link to a relevant GitHub repo]
- [e.g., Link to a sample implementation or starter code]

**Other:**
- [Links to any additional resources — e.g., papers, videos, podcasts, etc.]

*Feel free to explore beyond these, and share anything interesting you find with me!*

---

## 🤝 How We'll Work Together

**Official check-ins:** During our biweekly 45-minute AI Studio Lab Section meeting block (2nd and 4th week of every month)

 **Other ways to reach out to me with questions:** 
* [e.g., Your team's channel within Break Through Tech’s Discord space]
* [e.g., Email; please copy your teammates and AI Studio Coach]
* [e.g., Request a team check-in on Zoom]
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
