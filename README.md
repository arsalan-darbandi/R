
![](https://github.com/asikhalaban/R/blob/master/img/blogs_kdnuggets.jpg)

# How to Become a Data Scientist?
In this page I want to explain basic but important materials for who wants to be a Data Scientist. All materials in this page is from experiences from several projects, I gained and from courses that I took. I hope that at least some codes and information give you some help. Most of explanation I bring them directly here without any paraphrasing because this place is kind of my note and I spend more time on codes and maths. 

## Table of Contents

#### 1. Introduction<br>
[a. A Road Map for Reader and Structures](#structures) 
#### 2. Data Mining<br>
[a. Introduction to Analytics](#Introduction)  
[b. Project Understanding](#Project)  
[c. Data Understanding](#Data)
[d. Data Preparation](#Preparation)  
[e. Principles of Modeling](#Principles) 
[f. Multiple Linear Regression](#Multiple)  
#### 3. Machine Learning<br>
#### 4. R<br>
[a. Introduction to R and R studio](#centos)
[b. Coding in R](#manager)
#### 5. Python
[a. Introduction to Python and libraries](#centos)
[b. Coding in Python](#manager)
#
<br><br><br><br><br><br>






## 1. Introduction
<a name="structures"/>
### a. A Road Map for Reader and Structures

First, Section 2 describes the most important part which is data mining. Lots of information about data and different purposes and types of data processing can be find in this section. Then, Section 3 is about Machine Learning which is mixed and related to data mining and some of the materials in this section are similar to previous section. Section 4 and 5 are about two important languages which are used for data processing and commands and helps are brought over these two sections. 

References: I will add this part later.

<br><br>

## 2. Data Mining
<a name="Introduction"/>
### a. Introduction to Analytics

What is Analytics?<br> 
[Analytics is an encompassing and multidimensional field that uses mathematics, statistics, predictive modeling and machine-learning techniques to find meaningful patterns and knowledge in recorded data.](http://www.sas.com/en_us/insights/analytics/what-is-analytics.html) <br>
There are four types of big data BI that really aid business:<br>
Prescriptive – This type of analysis reveals what actions should be taken. This is the most valuable kind of analysis and usually results in rules and recommendations for next steps.<br>
Predictive – An analysis of likely scenarios of what might happen. The deliverables are usually a predictive forecast.
Diagnostic – A look at past performance to determine what happened and why. The result of the analysis is often an analytic dashboard.<br>
Descriptive – What is happening now based on incoming data. To mine the analytics, you typically use a real-time dashboard and/or email reports. Descriptive analytics as the least complex while fundamentally important because this analytics can answer simple questions about the past.<br>

What is Data Analytics outline?<br>

Data Science and Analytics has an important duty in a company because it tries to solve the problems by given information. 
First of all a data science must understand the problem then by using data mining tools which are collecting, cleaning and understanding(Visualizing) Data. <br>
Next by using different machine learning algorithm develop and validate models.<br>
After that interpret the results and explain the problem and the results and implement them. 

What is Big Data? <br>

Each data has three properties Volume, Velocity and Variety. In my opinion it is not easy to say which data is considered as big data just we can compare data and see which data has large size of volume with high velocity and variety then it can be considered as big data. In general, Velocity of Big Data is real time, or near real time, Data Volume is more than GB and for Variety of Data, data from social network, videos, unstructured data, mobile data and etc.

What is CRISP-DM? <br>

Cross Industry Standard Process for Data Mining, commonly known by its acronym CRISP-DM, was a data mining process model that describes commonly used approaches that data mining experts use to tackle problems.

<img align="right" src="https://github.com/asikhalaban/R/blob/master/img/220px-CRISP-DM_Process_Diagram.png?raw=true"><br>
CRISP=DM is composed of six high-level phases:<br>
- Project Understanding,
- Data Understanding,
- Data Preparation, 
- Modeling,
- Evaluation,
- Deployment<br>

This reflects the basic ordering of tasks is necessary in most analytics projects, however the process is not entirely linear. There are several places where iteration is necessary. You can find them in the above figure. 

- Project Understanding:<br>
The first phase is up to the data scientist and project owner to determine what exactly is the problem. The problem, assumptions, expectations, and goals should be listed as clearly as possible. oftentimes the data scientists will not be an expert in the specific field and will be working with subject matter experts, also known as SME's. It is data scientists job to learn their problem and their language and to help them meet their goals. 

- Data Understanding: <br>
The goal is to explore the data and to determine what is available and what gaps exist. That is data scientists need to determine the data relevancy, validity and sufficiency. 

- Data Preparation: <br>
This part is where you spend 90% of the work in and the task will likely be preformed many times. These tasks include collection, assessment, consolidation, cleaning, selection, and transformation. The objective is to take the initial raw data and convert it into a data set that can be used with our modeling tools . 

- Modeling Phase: <br>
The data set which is came out from data preparation is implemented in several models. Various approaches may benefit from different types of data preparation, so this phase is highly linked to the data preparation phase and there is lots of iteration between the two.

- Evaluation: <br>
The last model is evaluated over this phase. The final result must be evaluated to ensure it achieves the original project objectives. If there is some important issue that has not been sufficiently considered, the whole process returns back to phase one to flesh out those details. 

- Deployment: <br>
Deployment is where that the model and all processes which are chosen, implement for data. 


<br><br>

<a name="Project"/>
### b. Project Understanding

Project and Data Understanding are critical steps. You have to spend 20% time of a project for these to steps till get success for other 80%. 
There are four tasks in data understanding: 
- Determine business objectives, in my opinion this part is one of the important parts because you have to understand what is the problem from a business perspective then identify critical factors which influence outcome of the project, competing objectives and constraints. Sometimes, you are looking for right answer for wrong question. So this part is very important to understand what is the problem. The goal for determine business objectives is a background description, you would want to understand and describe the organization situation, understand primary objectives, you need to be able to describe criteria to success the project. This part could be sound easy but it is not that much easy that you think. In some of my project I stop at the middle of my project or I saw that my solution is not useful because the problem not only wasn't that much clear for me but also the owner of business doesn't know about the problem. So it is very important to make it clear that "What exactly is the problem?". 
- Assess situation, Detained fact-finding, that is digging into the details from factors which are found from previous task. Outputs are inventory of resources, for business intelligent it is important to consider costs and benefits. 
- Determine data mining goals, You have to know what data mining tasks and outputs you are looking for. Problem is figured out but it needs to match with data analysis task otherwise you cannot find related solution. 
- produce a project plan, in this part plan must be described and documented. 

<a name="Data"/>
### c. Data Understanding

<a name="Preparation"/>
### d. Data Preparation

<a name="Principles"/>
### e. Principles of Modeling

<a name="Multiple"/>
### f. Multiple Linear Regression


