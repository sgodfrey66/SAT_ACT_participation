# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Testing, Statistical Summaries and Inference

### Overview

Our first module in DSI covers:
- basic statistics (distributions, confidence intervals, hypothesis testing)
- many Python programming concepts
- programmatically interacting with files and directories
- visualizations
- EDA

You might wonder if you're ready to start doing data science. While you still have **tons** to learn, there are many aspects of the data science process that you're ready to tackle. Project 1 aims to allow you to practice and demonstrate these skills.

For our first project, we're going to take a look at aggregate SAT and ACT scores and participation rates from each state in the United States. We'll seek to identify trends in the data and combine our data analysis with outside research to identify likely factors influencing participation rates and scores in various states.

Generally speaking, you will be asked to come up with a data science problem. Here's a specific prompt that should help you craft this statement:
> The new format for the SAT was released in March 2016. As an employee of the College Board - the organization that administers the SAT - you are a part of a team that tracks statewide participation and recommends where money is best spent to improve SAT participation rates. Your presentation and report should be geared toward **non-technical** executives with the College Board and you will use the provided data and outside research to make recommendations about how the College Board might work to increase the participation rate in a **state of your choice**.

---

### Datasets

#### Provided Data

For this project, you'll have two provided datasets:

- [2017 SAT Scores](./data/sat_2017.csv)
- [2017 ACT Scores](./data/act_2017.csv)

These data give average SAT and ACT scores by state, as well as participation rates, for the graduating class of 2017.

You can see the source for the SAT data [here](https://blog.prepscholar.com/average-sat-scores-by-state-most-recent), and the source for the ACT data [here](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows). **Make sure you cross-reference your data with your data sources to eliminate any data collection or data entry issues.**

#### Additional Data

2018 state-by-state average results and participation for the SAT are available in PDF reports [here](https://reports.collegeboard.org/sat-suite-program-results/state-results). 2018 ACT state-by-state mean composite scores and participation rates are [here](http://www.act.org/content/dam/act/unsecured/documents/cccr2018/Average-Scores-by-State.pdf) .

**You will be manually collecting this data.**

---

### Deliverables

All of your projects will comprise of a written technical report and a presentation. As we continue in the course, your technical report will grow in complexity, but for this initial project it will comprise:
- A Jupyter notebook that describes your data with visualizations & statistical analysis.
- A README markdown file the provides an introduction to and overview of your project.
- Your presentation slideshow rendered as a .pdf file.
**NOTE**: Your entire Github repository will be evaluated as your technical report. Make sure that your files and directories are named appropriately, that all necessary files are included, and that no unnecessary or incomplete files are included.

For your first presentation, you'll be presenting to a **non-technical** audience. You should prepare a slideshow with appropriately scaled visuals to complement a compelling narrative. **Presentation duration will differ by market, so check with your local instructor.**

---

### Submission

**Materials must be submitted by the beginning of class on November 20.**

Your technical report will be hosted on Github Enterprise. Make sure it includes:

- A README.md (that isn't this file)
- Jupyter notebook(s) with your analysis
- Data files
- Presentation slides
- Any other necessary files (images, etc.)

**Check with your local instructor for how they would like you to submit your repo for review.**

---

### Presentation Structure

- **Must be within time limit established by local instructor.**
- Use Google Slides or some other visual aid.
- Consider the audience. Assume you are presenting to non-technical executives with the College Board (the organization that administers the SATs).
- Start with the **data science problem**.
- Use visuals that are appropriately scaled and interprettable.
- Talk about your procedure/methodology (high level, **CODE IS ALWAYS INAPPROPRIATE FOR A NON-TECHNICAL AUDIENCE**).
- Talk about your primary findings.
- Make sure you provide **clear recommendations** that follow clearly from your analyses and narrative and answer your data science problem.

Be sure to rehearse and time your presentation before class.

---

### Technical Report Requirements

Future projects will require you to decide on the entire structure of your technical report. Here, we provide you with [starter code](./code/starter-code.ipynb) in a Jupyter notebook that will help to guide your data exploration and analysis.

Skills you will demonstrate:

- Module imports (using appropriate aliases)
- Data import (using relative paths)
- Data munging
- Exploratory data analysis (EDA), including:
    - Summary statistics
    - Visualizations
- Data cleaning
    - Are there data entry issues?
    - Are data appropriately labeled?

#### ***Bonus:***
 - Recreate all of your MatPlotLib graphs in Seaborn!
 - Use Tableau Public to create visualizations!
 - Create a blog post of at least 500 words (and 1-2 graphics!) describing your data, analysis, and approach. Link to it in your Jupyter notebook.
 - Using existing features, engineer new features

While there are very specific requests in the starter code, these are only requirements, not restrictions. Feel free to do more EDA, feature engineering, visualization, etc. than what is requested.

---

### Starter code



---

---

### Project Feedback + Evaluation

Data science is a field in which we apply data to solve real-world problems. Therefore, projects and presentations are means by which we can assess your ability to solve real-world problems in a data-driven manner.

As a best practice, consider the following points when preparing your project.
1. **Project Requirements: Did you meet all project requirements?** In answering this question, your instructors want to assess how well you met the project requirements as established. These will generally be laid out in the project readme.

2. **Audience: Is your presentation appropriate for the stakeholder?** In answering this question, your instructors want to assess how well you present your results to stakeholders. For example:
  - Did you frame the problem appropriately for the audience?
  - Did you use the appropriate level of technical language for your audience?
  - Did you effectively use your time, or did you encounter an issue such as going significantly beyond or under the allotted time or rushing to conclude the presentation in the allotted time?
  - Did you present effectively, or were there things that detract from the overall presentation such as not speaking loudly enough for the audience or repeating oneself?

3. **Methods: Are your methods appropriate for solving the problem?** In answering this question, your instructors want to assess how well you have applied data science methodology to the problem at hand. For example:
  - Did you make well-reasoned modeling choices, or is there clear evidence that the model is inadequate or improper?
  - Are you able to clearly defend your methodological decisions and results?
  - Did you generalize your results properly, or were your conclusions/inferences improper or fallacious?

4. **Value: Have you provided value to the stakeholder through clear, data-driven recommendations?** In answering this question, your instructors want to assess the value you provide to the stakeholder as a data scientist. For example:
  - Did you answer the problem posed to you?
  - Did you make your recommendations clear, or were the recommendations unclear?
  - Were your recommendations data-driven and based on the results of your work?

---

### Rubric

Your final assessment ("grade" if you will) will be calculated based on a topical rubric (see below).  For each category, you will receive a score of 0-3.  From the rubric you can see descriptions of each score and what is needed to attain those scores.


