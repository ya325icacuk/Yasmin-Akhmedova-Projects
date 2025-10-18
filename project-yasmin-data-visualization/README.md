# ST115 Managing and Visualising Data

## Project

### 2021/22 Lent term

---

The maximum mark for the project is 100.

* Due date: 28/4/2022 12noon
* Hard deadline: 5/5/2022 12noon

**It is a summative assessment and it accounts for 70% of your final grade.** Requests for extensions are only granted in exceptional circumstances. In particular, no extension will be granted for job-related applications, late course add drop, clash with other course work, etc. If you want to apply for an extension, please fill in the [extension request form](https://info.lse.ac.uk/current-students/services/assets/documents/Extension-Request-Form.pdf). Without an extension, 10 marks (out of 100 marks) will be deducted for late submission every 24 hours. **Any submission after the hard deadline will automatically receive 0 marks.**

**Your work will only be treated as submitted if you have done all of the following:**
1. Sign the plagiarism statement below with your _candidate number_
2. Submit your work (including this README.md file with the Plagiarism statement signed) via GitHub as usual
3. Submit the pdf version of the final report on Moodle

---

## Plagiarism statement

Plagiarism is an examination offence and carries heavy penalties.

I declare that, this submission is my own work and contains no plagiarism. I have read and understood the plagiarism policy for this project stated below and the Schoolʹs [policy on plagiarism](https://www.lse.ac.uk/social-policy/Current-Students/Plagiarism).

Your 5-digit candidate number: 31380

---

## Objectives

The project serves as the most important coursework for us to assess your progress in the course in terms of:
* Understanding of the course materials
* Ability to perform the data science project life cycle to answer real-life questions using data
* Other skills like self-learning skills

---

## Tasks

To allow us to assess the qualities listed in the objectives section, you are asked to perform data analysis to answer some questions related to LSE (London School of Economics). You are required to hand in all the code and show all the steps of your data analysis from collecting the data to reporting the result in a report (in the form of a Jupyter Notebook). Data needs to be submitted as well.

In your project submission, you need to demonstrate your knowledge of applying the methods learned in the course. It may not be possible for you to utilise all methods introduced in the course. For example, visualising high dimensional or graph data may not be applicable to your analysis. However, your work must utilise sufficient data collection, manipulation and visualisation (for both exploration and explanation purposes) methods and techniques we have introduced in the course.

#### Selecting a topic

You need to select a topic / main question related to LSE by yourself. Here are some considerations when selecting the questions / topic:
* The questions that you want to answer needs to be _non-trivial_ and _motivative_
    * Think about why you want to answer the question and the significance of answering the question
* You are advised to select a topic that allows you to demonstrate your capability in data collection, manipulation and visualisation  
* Analysis of different topics may require different amounts of effort, and this will be taken into account when grading the submissions
* You _may_ also select a topic that is not related to LSE, but the topic must be approved by the lecturer


#### Structure of the project

Your report is expected to tell a story with the analysis nicely presented, and it should have the following structure:

1. Short introduction
    * Motivation
    * Goal of the study, main question(s) to answer
2. Data acquisition
    * What datasets to use and how those datasets can be used to answer the questions
    * Description of the data you have collected, including when and where you collected them
    * Specify where you have stored the data
    * If API, web scraping, etc is used to collect the data, the code used to collect the data must be submitted
3. Prepare the data for analysis
    * Anything you need to do before performing EDA. For example, importing the data, quick data exploration, data cleaning, merging data, reshaping the data, etc.
4. EDA
    * Visualisation and other means
5. Conclusion
    * Summarise the main result
        * Answer to the question
        * Other findings
    * Discussion of the limitations
    * What else can be done?

As data science lifecycle is an iterative process, it is possible that you will have multiple sections for part 2-4.

#### Other requirements

* Make sure your work is reproducible. When marking your work, we will download your repository and rerun your notebook to verify your result. Make sure all the code and data are submitted, and use _relative paths_ when loading the data
* Your work needs to demonstrate your techniques AND provide a complete, sound analysis
  * _Appropriate_ use of the techniques is important. The data manipulation and visualisation tasks you perform should lead to answering the questions that you have
    * Try to find a balance between being exhaustive and efficient in using those that best serve your underlying goals
    * Avoid using some methods that are not appropriate or necessary
  * The analysis needs to be _complete_ - report with missing parts will be likely to score low marks
  * A good analysis does not necessarily earn you a good grade - this course is about "managing" and "visualising" data. For example, even if your analysis is good, if you start from a simple, clean, ready-to-download dataset, your work may not demonstrate enough data collection and manipulation skills for us to award you a high mark

---

## Plagiarism policy

* Misconduct can lead to a zero for the entire coursework element or more serious consequences
  * Sharing your work to others also counts as misconduct
* Your submission must be 100% your own work. It means that (_unless_ you are told otherwise / you have got the permission from the lecturer):
    * All analysis must be your own work
    * You _cannot_ **(unless it is stated otherwise in the question)**
      * Borrow other people's analysis
        * You can _reference_ other people's work, but you must clearly state your reference. Also, there must be enough originality in your work
      * Have any form of communication with your fellow classmates or any other people except the lecturer (e.g. fellow classmates, previous students, your parents, someone you pay to help you to do the coursework) about the summative work between the release date and the hard deadline. This includes (but does not restrict to):
        * Showing, discussing, viewing, copying the solution to/from other people
        * Having someone else to do your work
     * Submit different versions of the code to GitHub and Moodle with/without the intention to tamper with the plagiarism checker

* We take plagiarism seriously. Any suspicious plagiarism will be reported for further investigation

If in doubt, always ask the instructor for clarification.

---

## Marking criteria

You need to have the characteristics below to get the corresponding mark:

| Mark | Characteristics                                           |
|:-----|:----------------------------------------------------------|
|70-100| Non-trivial and well-motivated questions to ask           |
|      | Programming: Code is correct and has no bugs              |
|      | Data collection: _Appropriate_ use of API, web scraping or some other more "sophisticated" ways to collect the main data. Data collected can be used to answer the questions. Ideally, more than one data source is used |
|      | Effective data manipulation: _Effective_ use of some data manipulation tools like `pandas` for data exploration, data cleaning, formatting, data extraction (e.g. with the use of regular expression, query, etc), data merging, data reshaping, etc. |
|      | Effective visualisation: _Effective_ use of a _wide_ variety of plots including some more complex and possibly interactive plots for EDA and presenting of the results. Plots are carefully designed, follow the advice from the lecture. For example, avoid chartjunk, appropriate use of colour, labels, scale, annotations, etc. |
|      | Good analysis: Sensible, complete and in-depth analysis with evidence of critical thinking. Effective use of descriptive statistics and visualisation for EDA |
|      | Well written report: Self-contained report with good introduction and conclusion, including discussion about limitations and future work. Easy to follow and good storytelling. Good use of Jupyter Notebook|
|60-69 | Non-trivial and well-motivated questions to ask           |
|      | Programming: Code is mostly correct, but may have some minor mistakes         |
|      | Data collection: API, web scraping or some other more "sophisticated" ways are used appropriately as _part_ of the data collection process. Data collected can be used to answer the questions. Ideally, more than one data source is used |
|      | Effective data manipulation: _Effective_ use of some data manipulation tools like `pandas` for data exploration, data cleaning, formatting, data extraction (e.g. with the use of regular expression, query, etc), data merging, data reshaping, etc. |
|      | Effective visualisation: _Effective_ use of a _wide_ variety of plots for EDA and presenting of the results. Plots are carefully designed and follow the advice from the lecture. For example, avoid chartjunk, appropriate use of colour, labels, scale, annotations, etc. <br>   |
|      | Good analysis: Sensible and complete analysis with evidence of critical thinking. Effective use of descriptive statistics and visualisation for EDA |
|      | Well written report: Self-contained report with good introduction and conclusion, including discussion about limitations and future work. Easy to follow and good storytelling. Good use of Jupyter Notebook|
|50-59 | Non-trivial questions to ask                               |
|      | Programming: No serious mistakes in the code                  |
|      | Data collection: Data collected can be used to answer the questions. Ideally, more than one data source is used. |
|      | Appropriate data manipulation: _Appropriate_ use of some data manipulation tools like `pandas` for data exploration, data cleaning, formatting, data extraction (e.g. with the use of regular expression, query, etc), data merging, data reshaping, etc. |
|      | Appropriate visualisation: _Appropriate_ use of plots for EDA and presentation of the results <br> Follow the advice from the lecture. For example, avoid chartjunk, appropriate use of colour, labels, scale, annotations, etc.   |
|      | Sensible analysis with appropriate use of descriptive statistics and visualisation for EDA |
|      | Complete report: Self-contained report with introduction and conclusion, including discussion about limitations and future work. Easy to follow with good use of Jupyter Notebook|
|40-49 | Sensible questions to ask                                     |
|      | Programming: The code shows that the student has an acceptable level of programming skill for data analysis |
|      | Data collection: Data collected can be used to answer the questions. |
|      | Data manipulation: The code demonstrates that the student is capable of using some data manipulation tools like `pandas` for meaningful data manipulation |
|      | Appropriate visualisation: _Appropriate_ use of plots for EDA and presentation of the results  |
|      | Sensible analysis with appropriate use of descriptive statistics and visualisation for EDA |
|      | Report: report has all required parts|
|0-39  | Trivial and/or non-sensible questions to ask                                     |
|      | Poor programming: The code does not work, or demonstrates a lack of basic level of programming skill for data analysis |
|      | Poor data collection: Data collected may not answer the questions. |
|      | Poor data manipulation: Not able to use data manipulation tools like `pandas` for meaningful data manipulation |
|      | Poor visualisation. For example, inappropriate use of plots or plots cannot be read easily |
|      | Poor analysis, for example, insensible analysis with inappropriate descriptive statistics. |
|      | Poor report: poor structure and/or ineffective communication. Some parts like the introduction and conclusion are missing |
