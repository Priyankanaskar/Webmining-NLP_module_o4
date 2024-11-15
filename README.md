## P4: Employ Requests, JSON, NLP & Engage 
### Requests, JSON, and basic NLP with spaCy

Complete the tasks in the Python Notebook in this repository.
To be submitted for credit, all changes must be committed and pushed to this repository (do not create your own repository unless instructed to on the course website).
## Objectives
This exercise illustrates how to access web-hosted APIs, get back a response in JSONLinks to an external site. format, and extract the information we need from the JSON. Accessing APIs is a key skill for data analysts. We can use web APIs to get stock data, weather data, and much more. We'll use an API to access song lyrics or poems in this exercise. We don't care which API - there are many and they change. The skill skills are being able to (a) make an API request and (b) find the information we need in the returned response. 
## Rubric

* (Question 1) Lyrics printed: 1 pt
* (Question 1) File created and submitted with notebook: 1 pt
* (Question 2) Correct polarity reported: 1 pt
* (Question 2) Question answered thoughtfully: 1 pt
* (Question 3) Function defined as specified: 1 pt
* (Question 3) Song lyrics retrieved and stored in separate files (0.5 pts/song): 2 pts
* (Question 4) Polarity scores printed (with appropriate label containing song title, .25 pts/song): 1 pt
* (Question 4) Questions answered thoughtfully: 2 pts

## Before Starting: Install SpaCy (Multi-Step Process) 
***First - Read***
Read about spaCy and spaCy NLP pipelines - the installation process is not easy. Read first. 

### spaCy is a library for natural language processing.
See: https://spacy.io/Links to an external site.
spaCy 101: https://spacy.io/usage/spacy-101Links to an external site.
installation: https://spacy.io/usageLinks to an external site.
spaCy provides pre-trained pipelines to process text. For example, the "en_core_web_sm" package is a small English pipeline that supports all core capabilities and is trained on web text.
spacytextblob is a pipeline component that enables sentiment analysis using the TextBlobLinks to an external site. library.  See https://spacy.io/universe/project/spacy-textblobLinks to an external site.
### Second - Install
Install  spaCy and its pipeline.  You must select your options first and it will provide the necessary commands for your type of system.

***Verify: Select your options - then take a screenshot and post it along with the commands provided.*** 

### Install spaCyTextBlob

### Third - Document Results of each Command
You will need to open a terminal and run each command.

***Verify: Run each command one at a time and verify each step completes successfully before continuing. Use screenshots and post any error messages as you proceed.***

### Fourth - Get Help as Needed
We need the above information to help solve any Why doesn't my spaCy work?" issues.  You can post your screenshots by themselves if you like - before your submission.

Save time by verifying these common issues:  Use the correct kernel (with all your installed dependencies) and in the pyvenv.cfg file change 'include-system-site-packages' to 'true' .

## Task 1. Get Started
### Copy the base repository into your GitHub account by selecting the "Use this Template" button on GitHub and specifying yourself as the owner.  The base repository is available at: https://github.com/wmnlp-materials/json-sentimentLinks 
to an external site.
Clone YOUR new repo down to your machine.

## Task 2. Open Notebook and Complete Tasks 
* 1.On your machine, open the Jupyter Notebook for editing. 
* 2.Required: In your Markdown introduction, add a viewable, clickable link to  your GitHub repo after your name. Build your brand and make your Markdown introduction clear and professional. 
* 3.Required: Use Markdown headings  (e.g. Question 1) to clearly show your content by each question number. 
* 4.Complete the first task.
* 5.Execute the notebook. Commit and push to GitHub. Verify your notebook appears correctly.
* 6.Complete the second task.
* 7.Execute the notebook. Commit and push to GitHub. Verify your notebook appears correctly.
* 8.Work this way until all tasks have been completed. 

### Task 3. Export to HTML and Finalize Repo
* 1.Execute each notebook.
* 2.After executing, export each notebook to HTML.
* 3.Commit and push your HTML files to your GitHub repo along with the executed notebooks. 
* 4.Verify you have a professional README.md that introduces your GitHub repository and provides helpful information about your project.

# Refrence : https://github.com/wmnlp-materials/json-sentiment
### A special thanks to Prof. Denise Case for instruction and guidence 