---
layout : default
title: Datasets
permalink: /Datasets/
---

# Datasets


## Table of contents


## Deputy 

### Download
| Nome | Description | Link | Last update|
|-------|--------|---------|---------|
| Deputies | Data of deputies | [.Zip](www.) |16/09/2022|


## Parliament settings
### Questions
Each Monday, and in accordance with the Constitution, the House of Representatives convene in a plenary sitting devoted to oral questions. Before the sitting, the House of Representatives publishes the schedul of the sitting (pdf file in arabic). This document provide data about: 
  
  + Ministries present in a parliament setting.
  + The Number of questions and time allocated to each Ministry.
  + Questions asked by deputies during the sitting and  who asked these questions.

We store this data in JSON file with the following organization :
```markdown
Ministery: {
            + timeQuest: Time allocated for each question
            + parlGroup: Parliamentary group
            + txtQuest: The question
            + typeQuest: Question type (عادى,انى)
            + codeQuest”: Question code
            + indexQuest”: Question order
            + subjIden”:questions with the same subjIden means the the questions have the same subject (identical subject)(e.g. وحدة الموضوع)
}
```
***Exemple***
```markdown
{
  'ﺍﻟﻌﺪﻝ': {'timeQuest': ['00:02:00', '00:02:00', '00:01:40', '00:01:35'],
  'parlGroup': ['ﻓﺮﻳﻖ الأﺼﺎﻟﺔ ﻭ ﺍﻟﻤﻌﺎﺻﺮﺓ',
   'ﻓﺮﻳﻖ الأﺼﺎﻟﺔ ﻭ ﺍﻟﻤﻌﺎﺻﺮﺓ',
   'ﺍﻟﻔﺮﻳﻖ الاﺸﺘﺮﺍﻛﻲ',
   'ﺍﻟﻔﺮﻳﻖ الاﺴﺘﻘﺎﻟﻠﻲ ﻟﻠﻮﺣﺪﺓ ﻭ ﺍﻟﺘﻌﺎﺩﻟﻴﺔ'],
  'txtQuest': ['ﺗﻮﻓﻴﺮ ﺍﻟﺘﺠﻬﻴﺰﺍﺕ ﺍﻟﻀﺮﻭﺭﻳﺔ ﺇﻟﻨﺠﺎﺡ ﻋﻤﻠﻴﺔ ﺍﻟﻤﺤﺎﻛﻤﺔ ﻋﻦ ﺑﻌﺪ',
   'ﺗﻨﻔﻴﺬ الأﺤﻜﺎﻡ ﺍﻟﻘﻀﺎﺋﻴﺔ ﺿﺪ ﺷﺮﻛﺎﺕ ﺍﻟﺘﺄﻣﻴﻦ',
   'ﺧﻄﻮﺭﺓ ﻧﺸﺮ ﻭﺗﻮﺯﻳﻊ ﺻﻮﺭ الأﻄﻔﺎﻝ ﺃﻭ ﺍﻟﻘﺎﺻﺮﻳﻦ',
   'ﺇﺷﻜﺎﻟﻴﺔ ﺍﻟﺒﻂﺀ ﻓﻲ ﺇﺻﺪﺍﺭ الأﺤﻜﺎﻡ ﺍﻟﻘﻀﺎﺋﻴﺔ'],
  'typeQuest': ['ﻋﺎﺩﻱ', 'ﻋﺎﺩﻱ', 'ﻋﺎﺩﻱ', 'ﻋﺎﺩﻱ'],
  'codeQuest': ['1505 ', '2386 ', '2413 ', '2829 '],
  'indexQuest': ['22', '23', '24', '25'],
  'subjIden': [' ', ' ', ' ', ' ']}
}
``` 

| Name | Datasets | Document | Last update| 
|-------|--------|---------|--------|
| Questions | [.Zip](https://www.dropbox.com/sh/l12c9n81hsdo5jz/AAAsUukswbiuiXkPjenZ5Wx0a?dl=1) | [.Zip](www.) | 16/06/2022 |

## Transcript :
After a setting, the Parliament published a pdf file of the setting transcript in arabic containing all debates that took place during the setting. 
Unfortunatily we can’t use the transcript document as it is provided by the parliament website because the document is written with a special font. In fact, if we try to scrape the original document we get a text full of mistakes (characters not in the right order).So we must change document’s font before using it (For details go to [Scraper](https://nowabindata.github.io/Scraper/))


### Download
Here you can find transcripts in json and txt format with the correct font.

| Code | Date | Transcript |
|-------|--------|---------|
| 43 | 30/05/2022 | [.Zip](https://www.dropbox.com/s/3gopt580qbyrabt/43-cdr30052022WF.rar?dl=1) | 
| 42 | 23/05/2022 | [.Zip](https://www.dropbox.com/s/krk3js5cpr111j5/42-cdr23052022WF.rar?dl=1) | 
| 41 | 23/05/2022 | [.Zip](https://www.dropbox.com/s/9goc2noz4beejz6/41-cdr23052022WF.rar?dl=1) | 
| 40 | 16/05/2022 | [.Zip](https://www.dropbox.com/s/43mo9pwmwu39en5/40-cdr16052022WF.rar?dl=1) | 
| 38 | 09/05/2022 | [.Zip](https://www.dropbox.com/s/g7x4bve8p90r3uz/38-cdr09052022WF.rar?dl=1) | 
| 36 | 25/04/2022 | [.Zip](https://www.dropbox.com/s/xmu7kqlcx6woqra/36-cdr25042022WF.rar?dl=1) | 
| 33 | 11/04/2022 | [.Zip](https://www.dropbox.com/s/242kyrvy323f84a/33-cdr11042022WF.rar?dl=1) | 

Download pdf [Document](https://www.dropbox.com/s/3w2f43r040aszwr/PV.rar?dl=1)
