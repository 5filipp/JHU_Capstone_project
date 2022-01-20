# JHU_Capstone_project


[Project Link](https://rpubs.com/filipp55/Milestone_report_project)

title: "Milestone_Report"
author: "Filipp Trubin"
date: "1/20/2022"
output:
  html_document: default
  pdf_document: default
---

Intro
============
Over the past decade, there has been a dramatic increase in the usage of electronic devices for email, social networking and other activities. Errors typing on such devices are far from uncommon, and can have considerable implications concerning the efficient use of such devices for communication. 
Text prediction requires estimation of the next character or word given a string of the input history. This may represent a useful solution to the problem of mistyping words. 
In this project we aim to develop a text predictive algorithm derived from large data sets composed of different source material blogs, twitter etc. to develop an application. 


1. Data wrangling
======================================
Source: www.corpora.heliohost.org.   
Dataset contains txt files on four languages (english, german, finish, russian) of blogs, news and twitter.


**Goals:**

The main goal of this report is to do Exploratory Data Analysis of texts.


# 1. Data processing.
# 2. Creating Datasets (for this report all the .txt files where reduced on 70% in size to provide quicker loading). 
# 3. Visualizing.
# 4 Data cleaning:
The *stringi* and *tm* packages were used for the text transformation   into a compatible format for further tokenisation.

  Steps:
   - Apply lower case 
   - Replace i with I
   - Clear punctuation except for ".", and "'"
   - Remove white spaces, dot spaces, numbers 
   - Split lines by the postitioning of dots
   
*Profanity filter**
Was not applied by now to provide better prediction at eh end. Will be Applied at the end of the main project.
