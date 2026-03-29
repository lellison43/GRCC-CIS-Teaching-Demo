# CIS Teaching Demo – Predictive Maintenance with Machine Learning

This repository supports a 30-minute teaching demonstration focused on introducing **machine learning through predictive maintenance in manufacturing**.

The session is designed for early learners in AI/ML and emphasizes:
- Real-world application  
- Conceptual clarity over technical depth  
- Hands-on, project-based learning  

---

## Opening: Theme Song

To set the tone for the session, we begin with a song. Lyrics were created with [ChatGPT](https://chatgpt.com/), music created with [Suno](http://suno.com/), and video created by [OpenArt](https://openart.ai/home).

[Watch the intro song](https://youtu.be/7_oRyGmsioc?si=k_XP31jtIix8-99-)

---

## Presentation Slides

Click the link below to follow along with the presentation (created with [Gamma](https://gamma.app/))

[View presentation slides](https://docs.google.com/presentation/d/1C0SvIFoML8mqn_vWM7uPKV0aN33XJOJ9/edit?usp=sharing&ouid=116979576458868389132&rtpof=true&sd=true)

### Topics Covered
- What is predictive maintenance?
- Why it matters in manufacturing
- How machine learning supports decision-making
- Real-world impact (cost, downtime, efficiency)

---

## Sources

The following sources were used to support claims made throughout the presentation:

### [1] Cost of Downtime
[Forbes Tech Council](https://www.forbes.com/councils/forbestechcouncil/2021/02/26/manufacturing-without-unplanned-downtime-could-become-a-reality-sooner-than-you-think/?streamIndex=0) article discussing the impact of unplanned downtime in manufacturing.


### [2] Causes of Downtime
[iFactory blog](https://ifactoryapp.com/blog/hidden-cost-unplanned-downtime-manufacturing) outlining common causes of unplanned downtime, including equipment failure estimates.


### [3] Predictive Maintenance Benefits
[Olix365 article](https://olix365.com/blog/predictive-maintenance-benefits/) summarizing typical improvements from predictive maintenance (e.g., reduced breakdowns and cost savings).


### [4] Case Study: Predictive Maintenance in Practice
[ThinkAI](https://thinkaicorp.com/case-study-cutting-machine-downtime-with-predictive-maintenance-and-ai/) case study describing implementation of predictive maintenance in a manufacturing environment.

---

## Notes on Sources

- These sources are primarily industry and vendor articles intended for general understanding.
- Reported statistics (e.g., downtime costs, % causes) should be interpreted as **estimates rather than precise universal values**.

---

## Hands-On Activity: Orange Data Mining

We will use **Orange Data Mining** as a no-code tool to introduce the ML workflow.

[Download Orange Data Mining](https://orangedatamining.com/)

### What learners will do:
- Load the dataset: `[Dataset] predictive_maintenance.csv` provided above
- Build a simple workflow (visual pipeline)
- Observe:
  - How data flows through the system  
  - How models are applied  
  - What predictions/output mean  

### Learning Goal:
Understand **how machine learning works in practice**, not the underlying math.

---

## Jupyter Notebook: Extend Your Learning

The notebook (`CIS_Teaching_Demo_GRCC_2026.ipynb`) found above allows learners to go beyond the visual tool and explore the same ideas programmatically.

### How to Use

1. Open the notebook using Google Colab (link provided in notebook).

2. Load the dataset:
   - Ensure the CSV file is in the same directory  
   - Or update the file path in the notebook  

3. Run cells step-by-step:
   - Data loading  
   - Basic exploration  
   - Simple modeling  

---

## Suggested Next Steps for Learners

After the session, learners are encouraged to:

- Modify the dataset (try filtering or selecting features)
- Experiment with different models in Orange
- Add additional machine learning models to the Jupyter Notebook
- Ask:
  - What features best predict failure?
  - How accurate are the predictions?
  - What would this look like in a real factory?

