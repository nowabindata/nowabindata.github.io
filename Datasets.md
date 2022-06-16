---
layout : default
title: Datasets
permalink: /Datasets/
---

# Datasets
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

### Download 

| Name | Datasets | Document | Last update| 
|-------|--------|---------|--------|
| Questions | [.Zip]() | [.Zip](www.) | 16/06/2022 |


## Transcript :


| Code | Date | Transcript | Document|
|-------|--------|---------|--------|
| 44 | 06/06/2022 | [.Zip](www.) | [.pdf](www.)|
| 43 | 30/05/2022 | [.Zip](www.) | [.pdf](www.)|
