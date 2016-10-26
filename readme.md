# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 4: Web Scraping & Logistic Regression

### Description

This week, we learned about web scraping and logistic regression. Now, we're going to put both of these skills to the test!

You're working as a data scientist for a contracting firm that's rapidly expanding. To cement your position in the company and generally make a name for yourself, you have decided to present a ground-breaking new topic to the Board for Evaluation. This topic MUST be a categorical / classification problem, and aim to outline an untapped sector of an industry. For example, you might try correlating Oscar movie wins with genre and cast experience, or job salaries with the titles and contents of the job posting. Anything is fair game as long as it's well researched / documented and framed as a classification problem.

#### Project Summary

In this project, we will practice two major skills. Collecting data by scraping a website and building a binary predictor with Logistic Regression.

Your job is to:

1. Collect SCRAPED data from a website of your choice for your analysis.
  - Your dataset MUST contain at least 1000 entries / rows.
2. Find out what features most directly impact your target. If your target is continuous, convert it into a category (range of numbers).
  - Test, validate, and describe your models. What factors predict your target category? How do your models perform?
3. Author a report to your CEO detailing your analysis (non-technical).

**BONUS PROBLEMS:**
1. Text variables and regularization:
  - **Part 1**: Find more potentially useful information you could leverage from another source. Use this new information to find information you think would be important and add them as predictors to a model.
  - **Part 2**: Gridsearch parameters for Ridge and Lasso for this model and report the best model.


**Goal:** Scrape & clean data, run logistic regression, derive insights, present findings.

---

### Requirements

- Scrape and prepare your data using BeautifulSoup.
- A Jupyter Notebook with your regression analysis for a peer audience of data scientists.
- A written report directed to your (non-technical!) Principal

 **Pro Tip:** You can find a good example report [here](https://www.dlsweb.rmit.edu.au/lsu/content/2_assessmenttasks/assess_tuts/reports_ll/report.pdf).

---

### Necessary Deliverables / Submission

- Materials must be in a clearly labeled Jupyter notebook.
- Materials must be pushed to student's github master branch.
- Materials must be submitted by the end of Week 5.

---

### Dataset

1. We'll be utilizing a dataset derived from live web data

2. To get the data, we will use the requests library and BeautifulSoup to scrape the webpage.

---

### Suggested Ways to Get Started

- Read the docs for whatever technologies you use. Most of the time, there is a tutorial that you can follow, but not always, and learning to read documentation is crucial to your success!
- Document **everything**.
- Look up sample executive summaries online.

### Additional Resources
- [Advice on How to Write for a Non-Technical Audience](http://programmers.stackexchange.com/questions/11523/explaining-technical-things-to-non-technical-people)
- [Documentation for BeautifulSoup can be found here](http://www.crummy.com/software/BeautifulSoup/).

---

### Project Feedback + Evaluation

[Attached here is a complete rubric for this project.](./project-04-rubric.md)

Your instructors will score each of your technical requirements using the scale below:

    Score | Expectations
    ----- | ------------
    **0** | _Incomplete._
    **1** | _Does not meet expectations._
    **2** | _Meets expectations, good job!_
    **3** | _Exceeds expectations, you wonderful creature, you!_

 This will serve as a helpful overall gauge of whether you met the project goals, but __the more important scores are the individual ones__ above, which can help you identify where to focus your efforts for the next project!
