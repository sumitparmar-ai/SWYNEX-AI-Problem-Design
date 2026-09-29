# SWYNEX-AI-Problem-Design
A narrow AI project for classifying emails into predefined categories.

# AI Email Category Classifier

## Task 1 — AI Problem Design

### 1. Problem Statement

People receive emails from different areas such as education, work, internships, finance, shopping, and promotional services. Manually sorting these emails can be time-consuming.

This project proposes an AI-based system that analyzes the subject and content of an email and automatically classifies it into a predefined category.

### 2. AI Use Case

This project focuses on **text classification**.

The AI will classify emails into the following categories:

* Education
* Work/Internship
* Finance
* Shopping
* Spam/Promotional

### 3. Target Users

The target users are students and general users who receive multiple emails and want to organize them efficiently.

### 4. Input

The system will take:

* Email subject
* Email body/content

### 5. Output

The system will provide:

* Predicted email category
* Confidence score

### 6. Example

**Input:**

> Your application for the Software Developer Internship has been shortlisted. Your interview is scheduled for Monday.

**Expected Output:**

> Category: Work/Internship

### 7. Data Source

A small labeled dataset of sample emails will be created or collected from publicly available datasets. Each email will be assigned to one of the predefined categories.

No private or personally identifiable email data will be used.

### 8. Constraints

* The initial system will use a limited number of predefined categories.
* The prototype will focus on text-based emails.
* Ambiguous emails may result in lower prediction confidence.
* The dataset will be limited in size for the initial prototype.
* The system will not automatically send or delete emails.

### 9. Success Criteria

The classifier will be evaluated using:

* Accuracy
* Precision
* Recall
* F1-score

The initial target is to achieve at least **85% accuracy** on an unseen test dataset.

### 10. Evaluation Approach

The dataset will be divided into training and testing data.

The AI model will learn from the training data and then classify emails from the unseen test dataset.

The predicted categories will be compared with the actual labels to calculate the evaluation metrics.

### 11. Future Scope

In later stages, the project could be extended with features such as AI-generated reply suggestions and email summarization.

However, the current Task 1 scope is limited to **email classification**.

---

**Project Status:** Task 1 — Problem Design
