---

> ## Challenge Advisor: Update & Finalize Your Project Overview
>
> > 💡 **These grey text instructions are just for you, the team's Challenge Advisor; please delete them once you have completed the steps below.**
>
> We've pre-populated this Challenge Project Overview page — which is what will be shared with your Break Through Tech student team in August — using the details from your submission form. You should have received an email inviting you to join this repo as a Collaborator, enabling you to add files and make edits.
> 
> In order for your project to be finalized and assigned to a team, please:
> 1. **Review all sections below** and update or expand any content as needed, making sure to address the SME Feedback in the section immediately below. Look for square brackets to find the places below that require additional inputs from you (e.g., "About [Company / Org Name]").
> 2. **Add your dataset** to the [data folder](data) in this repo.
> 3. **Close the Issue assigned to you in this repo** to let us know that you have made your edits and the overview page is ready for final review. You can do this by going to the _Issues_ tab in the top left section of the menu above, add a comment that says "CA review complete", and click the button to Close the Issue. 
>
> If you're unfamiliar with how to edit a page like this in GitHub, check out [this tutorial](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/handson/edit-readme.html) for a quick overview (start with step 2 and only edit this page), and [this guide](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/markdown.html) on how to use Markdown to compose text.
>
>
> ❌ Remember that this is a public repo. Do NOT include: Proprietary data, PII, API keys, credentials, or anything confidential.

---

## 📋 BTT Internal Evaluation Notes
*(This section is for BTT staff only — remove before sharing with students)*

| Check | Status | Notes |
|-------|--------|-------|
| Python Compatibility | 🟢 | The tech stack is primarily Python-based, using libraries such as pandas and scikit-learn, making it highly compatible with students' skill sets. |
| Data Readiness | 🟢 | The data is stored in CSV format, is under 1GB, and appears to be structured and ready for use, minimizing the need for extensive cleaning. |
| Resource Check | 🟢 | The project uses free-tier tools such as Google Colab, making resources accessible to students without requiring specialized hardware. |

**Student Fit Score:** 7/10  
**Technical Depth Score:** 8/10  
**Overall Recommendation:** REVISE

**Advisor Feedback Draft:**
The project offers a strong real-world application in the insurance domain that could be highly engaging for students. However, the project scope may benefit from clearer definitions around feature selection and model interpretability. Additionally, consider emphasizing the process of setting baseline models before moving to more complex algorithms. A call to action is to refine the learning outcomes for better clarity.
---

# Predicting Auto Claims Severity

**Company / Org:** Allstate  
**Challenge Advisor:** Krystal Smuda, krystal.smuda@allstate.com  
**Program:** Break Through Tech AI Studio - Fall 2026

---

## 🏢 About Allstate

Allstate is a leading provider of insurance and financial services in the United States. We specialize in auto insurance, providing coverage and support to help our customers during times of need.

---

## 🎯 The Challenge

### Project Summary
It can take months to know the final cost to Allstate from a claim due to repair times and legal determinations. If the cost can be estimated up front when the claim is first filed, it can be used to help set reserves and gain a better understanding of what contributes to higher claims. The main goal is to predict the claim’s final cost using insurance claim data.

### Success Criteria
Mean Absolute Error (MAE), students getting hands-on experience setting up and running models, and students understanding how the model works including its input parameters and output.

### Project Milestones

Use these milestones to guide your work. Your team will create a **GitHub Projects board** to track tasks within each milestone.

| Month      | Milestone                | Key Activities                                         |
|------------|--------------------------|-------------------------------------------------------|
| **September** | Data Understanding      | Explore dataset, handle missing values, document findings |
| **October**  | Model Development       | Train baseline model, experiment with approaches, iterate |
| **November** | Evaluation & Presentation| Finalize model, prepare presentation, document results |

> **Note for the team:** Please create a GitHub Projects board in this repository to break these milestones into weekly tasks. Go to the **Projects** tab → **New project** → Choose **Board** → Add columns for each month.

---

## 📊 Dataset

**Name and Source:** [Auto Insurance Claims Dataset]  
**Format:** CSV  
**Size:** under 1gb  
**Location:** [Link to dataset or instructions for accessing it]

### Key Details
- Numerical and categorical data stored in CSV format. Each record represents one auto insurance claim, its total paid amount ('loss' field), and different anonymized claim and vehicle characteristic fields (cat#, cont# fields).
- [Any known limitations or preprocessing needed]
- [Link to data dictionary or documentation, if available]

---

## 🛠️ Suggested Approach

**ML Problem Type:** Regression

**Recommended Libraries:**
- linear regression
- decision trees
- random forest
- boosting
- pandas
- Sci-kit Learn
- xgboost
- Tensorflow
- Keras
- Pytorch
- matplotlib
- seaborn
- folium

**Evaluation Metrics:**
- Mean Absolute Error (MAE)

---

## 📚 Resources to Get Started

The following resources will help your team understand the problem space and potential technical approaches for this project:

**Background Reading:**
- [Link to an article or blog post about the problem domain]
- [Link to an industry report or case study]

**Technical Tutorials:**
- [Link to a free tutorial on the ML technique(s) involved]
- [Link to documentation for a key library or tool]

**Code Examples:**
- [Link to a relevant GitHub repo]
- [Link to a sample implementation or starter code]

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
- **Virtual Meetings:** Zoom

---

## 🚀 Getting Started

1. **Review this overview document** and note any questions for our first meeting
2. **Begin reviewing the dataset** using the link above
3. **Read the GitHub Projects documentation** [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)

I'm excited to work with you!

---

## ❓ Questions?

Please bring any questions to our first meeting during the week of August 24th (Break Through Tech's Bridge to Studio - Session B).
