# Task C — Research Reflection

> **BAFAD Accelerated Research Track · Fall 2026**
> Complete **after** finishing Tasks A and B.

---

## Instructions

Write your responses directly in this file (replace the placeholder text).
Aim for **150–200 words total** across both questions.
Be specific — reference your actual experience with the data and code.

---

## Question 1 — Connecting the Work to Research

*After completing Tasks A and B, how does hands-on data exploration relate to the research problem described in **Anomaly Detection in Tactical Sensor Streams** (the document you read before the Canvas quiz)?*

Consider: What patterns did you observe in the SMAP data? How might those patterns complicate or inform the design of an autoencoder-based anomaly detector?

**Your response (75–100 words):**

Hands-on data exploration helped me understand how important it is to examine data before building a model. In Task A, I explored 500 SMAP observations with 27 variables. I found 24 anomalies (4.8% of the observations) and no missing values. This showed me that unusual patterns can exist even in a dataset without missing data. For an autoencoder-based anomaly detector, understanding normal patterns and unusual observations is important. Exploring the data first could help identify meaningful anomalies and reduce the chance of treating normal variation as an anomaly.

---

## Question 2 — Self-Assessment of Readiness

*What specific gaps in your current knowledge — Python skills, statistics concepts, or ML background — do you expect to encounter if you join the research group? What is your plan for addressing them?*

Be honest. There are no wrong answers — this helps us plan the onboarding schedule.

**Your response (75–100 words):**

I feel more comfortable using Python and pandas to inspect datasets, group values, and create visualizations after completing these tasks. However, I still need more practice with statistics, especially interpreting distributions, variability, and anomaly detection results. My machine learning background is also limited, and I want to better understand how autoencoders learn patterns and identify unusual data. If I join the research group, I plan to review Python and statistics, practice with small datasets, and study the basics of neural networks and autoencoders. I would also ask questions and use feedback from the research team to strengthen my understanding.

---

*Submission: commit this file to your fork and include it in the GitHub repo URL you submit on Canvas.*
