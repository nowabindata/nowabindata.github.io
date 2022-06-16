---
layout : default
title : Nowab In Data   نواب فى بيانات
---


##   Welcome to Nowab In Data
## نواب فى بيانات

Parliament records, reports, written questions, and transcription of debates are rich sources of data for research in various disciplines. Not only do they enable new lines of research in fields such as political science, sociology, gender studies, and information retrieval, but they can also be an important source of data for natural language processing. For example, this data can be used to gain insight into what topics members of parliament and parties discuss and vote on.

In this context, the Moroccan house of representatives website can be very useful, especially since it provides data in Arabic (mainly classic, debate transcript may contain text in Dareja). For this, we created a website where we share parliament datasets the following datasets :


  - Datasets of deputies: for each deputy, we provide general info about the deputy(Name, Party, Group, District..), deputy's activities (parliamentary tasks, deputy's Agenda), and in particular, details if deputy written questions: number of questions and their content, question status (answered or not)...
  - Datasets of parliament sessions: what questions were asked during a session and which Ministery was concerned ...
  - Transcripts: after a session, the Parliament published a pdf file of the setting transcript in Arabic containing all debates that took place during the setting. Those transcripts are available in JSON and txt format
 


In order to (re-)produce these datasets, we created a Python library called "barlaman". barlaman is a collection of Python scripts to retrieve data from the Parliament website (web-scraping) and documents (pdf scraping)

### Support or Contact

Having trouble with something? [Contact me](https://nowabindata.github.io/Contact/) and we’ll help you sort it out.
