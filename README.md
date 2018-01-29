# AI-LawMiniCourse-HW
AI Homework Repository
AI Class Homework
Karin Hjorth

•	Review the Applied Example covered in class - Supreme Court Topic Modeling
o	For each step in this directory, write a paragraph or two of your interpretation of the code - in your own words describing what the code is doing
o	Include a description of the workflow being applied, what format the data is in during each step, what each function is doing, etc

Step 1: Data Collection & Preparation

Using “Beautiful Soup” to pull data out of HTML and XML files, this step prepares the date by creating a list of Supreme Court Documents and assigning a variable to house an array of documents.

Step 2:  Data Collection & Preparation
This step seems to be importing all the SCOTUS documents.  It reads in the case URL, collects case details, the scrapes for case details and adds them to the table.  See table is example with columns (variables?) of caseurl, casetitle, years, and case.

Step 3:  Data Processing
This step seems to be further preparing the data for processing by removing the state names, case names, stopwords, people’s names, days of week, non-words, and then finally lemmatizing.  There’s a note about keeping a robust stopword list, and it appears the stopword list will need to be curated as learnings come.  The text cleaner is the last part of Step 3 and it looks like the code is teaching how to set up and lemmatize the natural language in the date (case) we’ve imported.

Step 4:  Topic Modeling Method and Testing
This step seems to be the topic modeling testing step.  It tests models, and looks at frequency filters.

Step 5:  Topic Model Application to Data
This is the last step in the series and seems to pull everything together for visualization.  It covers creating a dictionary input for each, and arranges the topics for visualization.

-------

For the remaining parts of the exercise, I was able to:
•	Create a repository in GitHub
•	Command line “clone” the repository [git clone]
•	CD into my homework repository
•	Launch Jupyter Notebook
•	Launch an empty kernel
•	Go through the Tensorflow tutorial (starting with “highlights” section, etc.)
•	Pasted the minimalist implementation into an empty kernel (copying “from_future…”)

After these steps I got lost.  

What did I do to triage?
•	Reached out my homework partner but he was out of town and unable to connect with me
•	Reached out over Slack; I had one respondent but it was the blind leading the blind
•	Reached out to a random classmate who had posted notes about the homework; Grant Thomas was kind enough to get on the phone with me and help me through a few steps (turned out he recommended I remove Python 2 and install Python 3)
•	Then I continued to get stuck.
•	I turned to the other class readings for Monday, 01/28/18, to ensure I wasn’t missing something and to prepare for class.
