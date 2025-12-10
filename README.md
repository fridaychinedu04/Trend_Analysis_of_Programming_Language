# **Trend Analysis of Programming Language**

---
## **TABLE OF CONTENTS**
[INTRODUCTION](#Introduction)
[OBJECTIVES](#Objectives)
[KEY FINDINGS](#Keyfindings)
[OBSERVATIONS](#Observations)
[CONCLUSION](#Conclusion)

---
### **INTRODUCTION**
The rapid evolution of technology has influenced how developers engage with various programming languages. Stack Overflow, as one of the largest Question and Answer platforms for programmers, provides a rich dataset that reflects real-world developer interest.
This report analyzes the popularity trends of programming languages from 2008-2020 based on the number of questions asked per year. By computing proportions, identifying top languages, and visualizing trends, we gain insights into how developer preferences have shifted over time.

---
#### **OBJECTIVES** 
1. Compute the proportion of questions asked about each programming language relative to the total questions per year
2. Identify the top five most popular programming languages for each year based on these proportions
3. Visualize the trend of five selected programming languages
    - `Python`
    - `Java`
    - `JavaScript`
    - `C#`
    - `C++`
4. Provide observations and insights, especially highlighting a language of personal interest.

---
##### **KEY FINDINGS**
- __Proportion of Questions per Language__
    - Each language's popularity was expressed as:
    `proportion = num_question/year_total`
    - This normalizes language activity per year, accounting for the platform's growth over time.
- __Top Five Programming Languages Per Year__
    - A DataFrame of the yearly top 5 was generated. See sample excerpt below:

Year | Rank | Language | Proportion|
| -- | -- | -- | -- 
| 2008 | 1 | C# | 4.44% |
| 2008 | 2 | .NET | 3.49% |
| 2008 | 3 | Java | 2.55% |
| ... | ... | ... | ... |
| 2020 | 1 | Python | 4.75% |
| 2020 | 2 | JavaScript | 3.62% |
| 2020 | 3 | Java | 2.13%

___Insights from the Table above___
    - Early years were dominated by **C#, .NET, and Java**.
    - By 2020, **Python and Javascript** surged significantly.

- __Trend Plot for Five Programming Languages__
    - The selected programming Languages above show clear shifts in popularity. The trend plot will be embedded in the  `Python code` section below.

---
###### **OBSERVATIONS**
- __Python's Meteoric Rise__
    - Python shows a **steady and powerful upward trend**, surpassing all others around 2017-2018 and continuing to rise through 2020.

***Reasons:***
1. Machine learning and data science boom
1. Simplicity
1. Massive community adoption
- __JavaScript Growth__
JavaScript steadily rises untill around 2016, fueled by:
    - Rise of Node.js
    - Front-end frameworks (React, Angular, Vue)
- __Decline of C# and C++__
Both languages show clear downward trends. Their early dominance fades after 2012 as developer interest shifts to multi-paradigm, web-friendly languages.
- __Java's Stability__
Java remains consistent but slowly declines as newer languages grow in popularity.

---
###### **CONCLUSION**
This analysis demonstrates a significant shift in developer interest over the 12-year period.
- **Python** has become the most dominant language due to its versatility and ease of use.
- **JavaScript** remains essential for web development and maintains strong popularity.
- **Older languages like C# and C++** see reduced attention but continue to hold niche importance.
- The dynamic improvement of language popularity reflects the changing landscape of technology, frameworks, and industry demand.

From the dataset, it is clear that **Python is now the langugae at the center of modern programming conversations** - a great choice to admire and consider mastering.