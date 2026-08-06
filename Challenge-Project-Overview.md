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
**Program:** Break Through Tech AI Studio - Fall 2026

---

## 🏢 About Verizon

Verizon is a leading telecommunications company that provides wireless and wireline services to consumers, businesses, and government entities. With a commitment to innovation and customer service, Verizon is focused on enhancing user experiences in a rapidly evolving digital world.

---

## 🎯 The Challenge

### Project Summary
In this project, you will use customer tweets and Classification + Natural Language Processing (NLP) to build an AI agent to resolve or to escalate customer issues. This will help our company address customer satisfaction and provide quick turnaround times for customer service problems.

### Success Criteria
Model accuracy of classification of customer tweets (target <= 70%), whether the agent is outputting useful insights on customer problems, and high-quality agent AI outputs.

### Project Milestones

Use these milestones to guide your work. Your team will create a **GitHub Projects board** to track tasks within each milestone.

| Month | Milestone | Key Activities |
| :--- | :--- | :--- |
| September | Foundations & Data Setup | • Set up environment in Colab using geospatial Python libraries (`rasterio`, `leafmap`).<br>• Stream and window-read cloud-optimized GeoTIFFs (COGs) from the Maxar Open Data catalog.<br>• Assemble a working dataset of VHR scenes filtered for higher cloud cover.<br>• Characterize visual features of clouds, smoke, and cloud-like surfaces (snow, bright rooftops, sand). |
| October | Classical Baseline Development | • Implement signal-processing baselines in the RGB/visible domain (brightness/saturation thresholding, dark-channel prior, HOT-style index).<br>• Construct a hand-labeled/visually-assessed evaluation set for quantitative comparison.<br>• Build a working classical cloud-mask pipeline and evaluate qualitative/quantitative performance. |
| November | Pretrained Models & Benchmark Comparison | • Apply pretrained segmentation models (e.g., zero-shot Segment Anything Model / SAM, RGB cloud-segmentation checkpoints).<br>• Conduct head-to-head benchmarking against classical baselines using standard segmentation metrics (IoU, Precision, Recall, F1-score).<br>• Perform qualitative error analysis on failure modes (smoke vs. cloud, bright non-cloud surfaces).<br>• Finalize benchmark notebook, results writeup, and final presentation deck. |

---

## 📊 Dataset

**Name and Source:** Customer support on Twitter (Kaggle)  
**Format:** CSV/TSV  
**Size:** under 1gb  
**Location:** [Link to dataset or instructions for accessing it]

### Key Details
- Publicly available text data (customer-support-on-twitter) from Kaggle in CSV/TSV format. The dataset requires significant cleaning and preprocessing.
- It is essential to ensure the dataset is cleaned to focus on relevant telecom messages for effective model training.
- [Link to data dictionary or documentation, if available]

---

## 🛠️ Suggested Approach

**ML Problem Type:** Classification, Natural Language Processing (NLP)

**Recommended Libraries:**
- Classification
- Natural Language Processing (NLP)
- AI Agent
- Prompting
- Google Colab

**Evaluation Metrics:**
- Accuracy, Precision/Recall, and useful insights from the agent outputs.

---

## 📚 Resources to Get Started

The following resources will help your team understand the problem space and potential technical approaches for this project:

**Background Reading:**
- [Introduction to Customer Service in the Digital Age](#)
- [Case Studies on AI in Customer Support](#)

**Technical Tutorials:**
- [Natural Language Processing with Python](#)
- [Kaggle's Guide to Data Cleaning](#)

**Code Examples:**
- [Example GitHub Repository on NLP](#)
- [Starter Code for Text Classification](#)

**Other:**
- [Links to any additional resources — e.g., papers, videos, podcasts, etc.]

*Feel free to explore beyond these, and share anything interesting you find with me!*

---

## 🤝 How We'll Work Together

**Check-ins:** During our biweekly 60-min AI Studio Lab Section meeting block (2nd and 4th week of every month)  
**Communication:** Slack (Break Through Tech workspace)  
**Response time:** Within 48 hours on weekdays  

**Recommended Tools:**
- **Coding:** Google Colab
- **Collaboration:** GitHub, Notion
- **Virtual Meetings:** Zoom, Google Meet

---

## 🚀 Getting Started

1. **Review this overview document** and note any questions for our first meeting
2. **Begin reviewing the dataset** using the link above
3. **Read the GitHub Projects documentation** [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)

I'm excited to work with you!

---

## ❓ Questions?

Please bring any questions to our first meeting during the week of August 24th (Break Through Tech's Bridge to Studio - Session B).

