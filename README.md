# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Testing, Statistical Summaries and Inference

## Docker setup

**Docker students only** (disregard if you're using Anaconda): For instructions on how to run lectures and labs in Docker, click here: https://youtu.be/E54JvUKnF-4

### Overview

This week in class we went over some basic statistics, learned some Python programming concepts, and also learned how to navigate files, packages, and libraries using the command line. Great start! At this point you should be champing at the bit to _do some Data Science_. If so, good - because it's time for Project 1!

For our first project, we're going to take a look at SAT and ACT scores around the United States. Suppose that the College Board - the organization that administers the SAT - seeks to improve the participation rate of its exams. Your presentation should be geared toward **non-technical** executives with the College Board and you will use, at minimum, the provided data to make recommendations about how the College Board might work to increase the participation rates of these exams.

**Goal**: A Jupyter notebook that describes your data with visualizations & statistical analysis.

**Goal**: A 5-7 minute presentation targeted to your hypothetical client that highlights your findings.

**Goal**: Your Jupyter notebook hosted on your personal static site.

---

### Requirements

Your work must _at a minimum_:

- Describe the data
- Perform methods of exploratory data analysis, including:
  - Use Matplotlib to create visualizations
  - Use NumPy to explore distributions of individual variables and relationships among pairs of variables
- Display your cleaned Jupyter notebook on a personal static website.

#### ***Bonus:***
 - Recreate all of your MatPlotLib graphs in Seaborn!
 - Use Tableau Public to create visualizations!
 - Create a blog post of at least 500 words (and 1-2 graphics!) describing your data, analysis, and approach. Link to it in your Jupyter notebook.
 - Using existing features, engineer new features

While there are very specific requests in the starter code, these are only requirements, not restrictions. Feel free to do more EDA, feature engineering, visualization, etc. than what is requested.

---

### Necessary Deliverables / Submission

- Materials must be submitted in a clearly commented Jupyter notebook.
- Notebook must be submitted via pushing to your remote repo.
- Presentation must be submitted via Slack (for a PowerPoint file) or shared via a Google Form.
- Your notebook and presentation slides must be additionally hosted on your personal static site.
- **Materials must be submitted by 10:00 AM on Friday, May 4th.**

---

### Starter code

For this project we will be using a Jupyter notebook. This notebook will use matplotlib for plotting and visualizing our data. This type of visualization is handy for prototyping and quick data analysis. We will discuss more advanced data visualizations for communicating your work.

Open the [starter code instructions](./code/) in a Jupyter notebook.

### Dataset

For this project, you'll be using two datasets:

- [Dataset: SAT Scores](./data/sat.csv)
- [Dataset: ACT Scores](./data/act.csv)

You can see the source for the SAT data [here](https://blog.prepscholar.com/average-sat-scores-by-state-most-recent), and the source for the ACT data [here](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows).

These data give average SAT and ACT scores by state, as well as participation rates, for the graduating class of 2017.

---

### Presentation Structure

- 5-7 minutes long.
- Use PowerPoint or some other visual aid.
- Consider the audience. Assume you are presenting to non-technical executives with the College Board (the organization that administers the SATs).
- Start with the guiding question/big idea.
- Talk about your procedure/methodology (high level, no need to show code unless you found a useful method to share).
- Talk about your findings/answers to prompts (include visuals).
- Conclude - highlight any next steps, further questions, what you would do with more time, additional data that would be useful.

Be sure to rehearse and time your presentation before class.

---

### Suggested Ways to Get Started

- Read in your datasets.
- Try out a few NumPy commands to describe your data.
- Write pseudocode before you write actual code. Thinking through the logic of something helps.  
- Read the documentation for whatever technologies you use. Learning how to read documentation is crucial to your success - and oftentimes the documentation will include a tutorial you can follow!
- Document **everything**.

### Useful Resources

- [How to find the data you need](http://flowingdata.com/2009/10/01/30-resources-to-find-the-data-you-need/)
- [How to give a good lightning talk](https://www.semrush.com/blog/16-ways-to-prepare-for-a-lightning-talk/)

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

The four categories for this rubric are:

- [Organization](#organization)
- [Data Structures](#data-structures)
- [Python Syntax and Control Flow](#python-syntax-and-control-flow)
- [Probability and Statistics](#probability-and-statistics)


#### Organization

Clearly commented, annotated and sectioned Jupyter notebook or Python script.  Comments and annotations add clarity, explanation and intent to the work.  Notebook is well-structured with title, author and sections. Assumptions are stated and justified.


| Score | Status                     | Examples                                                                                                                                                                                                                                         |
|-------|----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 0     | Does not Meet Expectations | 1. Comments and annotations are **absent** <br> 2. There is no clear notebook structure <br> 3. Assumptions are not stated                                                                                                                                       |
| 1     | Approaching Expectations   | 1. Comments are present but generally unclear or uninformative (e.g., comments do not clarify, explain or interpret the code) <br> 2. There are some structural components like section/subsection headings <br> 3. Assumptions are stated but not justified |
| 2     | Meets Expectations         | 1. Comments and annotations are clear and informative <br> 2. There is a clear structure to the notebook with title and appropriate sectioning <br> 3. Assumptions are both stated and justified                                                             |
| 3     | Exceeds Expectations       | 1. Comments and annotations are clear, informative and insightful <br> 2. There is a helpful and cogent structure to the notebook that clarifies the analysis flow <br> 3. Assumptions are stated, justified and backed by evidence or insight               |


#### Data Structures

Python data structures including lists, dictionaries and imported structures (e.g. DataFrames), are created and used correctly.  The appropriate data structures are used in context.  Data structures are created and accessed using appropriate mechanisms such as comprehensions, slices, filters and copies.

| Score | Status | Examples |
|-------|----------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 0 | Does not Meet Expectations | 1. Appropriate data structures are not identified or implemented <br> 2. Data structures are not created appropriately <br> 3. Data structures are not accessed or used effectively |
| 1 | Approaching Expectations | 1. Contextually appropriate data structures are identified in some but not all instances <br> 2. Data structures are created successfully but lacked efficiency or generality (e.g., structures were hard-coded with values that limits generalization; brute-force vs automatic creation/population of data) <br> 3. Data structures are accessed or used but best practices are not adopted |
| 2 | Meets Expectations | 1. Contextually appropriate data structures are identified and implemented given the context of the problem <br> 2. Data structures are created in an effective manner <br> 3. Data structures are accessed and used following general programming and Pythonic best practices |
| 3 | Exceeds Expectations | 1. Use or creation of data structures is clever and insightful <br> 2. Data structures are created in a way that reveals significant Pythonic understanding <br> 3. Data structures are used or applied in clever or insightful ways |


#### Python Syntax and Control Flow

Python code is written correctly and follows standard style guidelines and best practices.  There are no runtime errors.  The code is expressive while being reasonably concise.

| Score | Status | Examples |
|-------|----------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 0 | Does not Meet Expectations | 1. Code has systemic syntactical issues <br> 2. Code generates incorrect results <br> 3. Code is disorganized and needlessly difficult |
| 1 | Approaching Expectations | 1. Code is generally correct with some runtime errors <br> 2. Code logic is generally correct but does not produce the desired outcome <br> 3. Code is somewhat organized and follows some stylistic conventions |
| 2 | Meets Expectations | 1. Code is syntactically correct (no runtime errors) <br> 2. Code generates desired results (logically correct) <br> 3. Code follows general best practices and style guidelines |
| 3 | Exceeds Expectations | 1. Code adopts clever or advanced syntax <br> 2. Code generates desired results in an easily consumable manner (e.g., results are written to screen, file, pipeline, etc, as appropriate within the flow of the analysis) <br> 3. Code is exceptionally expressive, well formed and organized |


#### Probability and Statistics

Descriptive and inferential statistics are calculated and applied where appropriate.  Probabilistic reasoning is demonstrated.  There is a clear understanding of how probability and statistics affects the analysis being performed.

| Score | Status | Examples |
|-------|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 0 | Does not Meet Expectations | 1. Descriptive statistical calculations are absent <br> 2. Inferential statistical calculations are absent <br> 3. Probabilities or statistics are not relevant given the context of the analysis |
| 1 | Approaching Expectations | 1. Descriptive statistics are present in some cases <br> 2. Inferential statistics are present in some cases <br> 3. Probabilities or statistics are somewhat relevant to the analysis context |
| 2 | Meets Expectations | 1. Descriptive statistics are calculated in all relevant situations <br> 2. Inferential statistics are calculated in all relevant situations <br> 3. Probabilities or statistics are relevant to the analysis |
| 3 | Exceeds Expectations | 1. Descriptive statistics are calculated, interpreted and visualized (where appropriate) <br> 2. Inferential statistics are calculated, interpreted and visualized (where appropriate) <br> 3. Probabilities or statistics are leveraged to draw meaningful or insightful conclusions |
