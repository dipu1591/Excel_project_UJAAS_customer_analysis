# Interactive Dashboard Using Microsoft Excel to Analyze Data: A Case Study of UJAAS

<br/>

<br/>

<br/>

## Problem

<br/>

<br/>

UJAAS is an international brand that manufactures and sells bikes in Bangladesh. They basically maintain two datasets, where in the first dataset, they collect the personal information of the potential customer, and in the second dataset, there is information about whether the potential customer purchased a bike or not.

<br/>

![1st dataset personal data](https://github.com/dipu1591/Excel_project_UJAAS_customer_analysis/blob/main/Screenshots/1.PNG)

<br/>

![2nd dataset bike purchase decision](https://github.com/dipu1591/Excel_project_UJAAS_customer_analysis/blob/main/Screenshots/2.PNG)

<br/>

UJAAS wants to increase their market share in Bangladesh by making informed decisions using this data. Specifically, the CEO of UJAAS had a total of six questions, based on which the stakeholders will decide in the board meeting how to further increase the market share. The questions are:

1) What is the minimum income, average income, and maximum income of male and female potential customers?

2) In which salary range did customers buy more bikes?

3) How far did the customers who bought the bike typically travel each day?

4) Which age group of customers is more dependent on bikes?

5) Show the percentage of customers who have or have not purchased a bike by gender and marital status.

6) For those who are buying bikes, how many cars have they bought before?

Moreover, since not all stakeholders have a technical background, the manager wants a presentation prepared using simplified Excel charts to facilitate their understanding at the board meeting.

<br/>

<br/>

<br/>

## Solution

<br/>

<br/>

To merge both the two datasets, I took the help of 'Power Query Editor'. I clicked on 'Merge Queries as New' from the 'Merge Queries' option and merged two datasets based on the ID column.

<br/>

![Dataset after merging](https://github.com/dipu1591/Excel_project_UJAAS_customer_analysis/blob/main/Screenshots/3.PNG)

<br/>

Then, for ease of understanding, the values of the marital status and gender columns have been renamed through 'Replace Values'. Then I divided the total income range of all visitors into 10 income categories, where Scale J means income between 0 and 20000 taka, and thus specified Scale I to A for every 20000 taka. As with income range, I divided visitor age and average daily commuted distance into multiple categories.

<br/>

![Dataset after cleaning and merging](https://github.com/dipu1591/Excel_project_UJAAS_customer_analysis/blob/main/Screenshots/4.PNG)

<br/>

'Pivot Table' and 'Chart' have been added to separate sheets for each answer. 'Conditional Formatting' has also been added for ease of understanding in pivot tables. All charts are added to a single sheet for CEO viewing, along with multiple 'slicers'. Slicer basically works as a filter. By clicking on one or more options, the value can be seen on all the charts at once. Moreover, 'Hyperlink Navigation' has been added to all sheets for ease of use.

<br/>

![1st dashboard](https://github.com/dipu1591/Excel_project_UJAAS_customer_analysis/blob/main/Screenshots/5.PNG)

<br/>

![2nd dashboard](https://github.com/dipu1591/Excel_project_UJAAS_customer_analysis/blob/main/Screenshots/6.PNG)

<br/>

![3rd dashboard](https://github.com/dipu1591/Excel_project_UJAAS_customer_analysis/blob/main/Screenshots/7.PNG)

<br/>

![4th dashboard](https://github.com/dipu1591/Excel_project_UJAAS_customer_analysis/blob/main/Screenshots/8.PNG)

<br/>

![5th dashboard](https://github.com/dipu1591/Excel_project_UJAAS_customer_analysis/blob/main/Screenshots/9.PNG)

<br/>

![6th dashboard](https://github.com/dipu1591/Excel_project_UJAAS_customer_analysis/blob/main/Screenshots/10.PNG)

<br/>

![Final dashboard](https://github.com/dipu1591/Excel_project_UJAAS_customer_analysis/blob/main/Screenshots/11.PNG)

<br/>

<br/>

<br/>

## Presentation Slide

<br/>

<br/>

![1st insight](https://github.com/dipu1591/Excel_project_UJAAS_customer_analysis/blob/main/Screenshots/12.PNG)

<br/>

![2nd insight](https://github.com/dipu1591/Excel_project_UJAAS_customer_analysis/blob/main/Screenshots/13.PNG)

<br/>

![3rd insight](https://github.com/dipu1591/Excel_project_UJAAS_customer_analysis/blob/main/Screenshots/14.PNG)

<br/>

![4th insight](https://github.com/dipu1591/Excel_project_UJAAS_customer_analysis/blob/main/Screenshots/15.PNG)

<br/>

![5th insight](https://github.com/dipu1591/Excel_project_UJAAS_customer_analysis/blob/main/Screenshots/16.PNG)

<br/>

![6th insight](https://github.com/dipu1591/Excel_project_UJAAS_customer_analysis/blob/main/Screenshots/17.PNG)

<br/>

<br/>

<br/>

## Acknowledgements

<br/>

<br/>

I would like to acknowledge [ALEX THE ANALYST](https://www.youtube.com/@AlexTheAnalyst/), [CHANDOO](https://www.youtube.com/@chandoo_/), and [STORYTELLING WITH DATA](https://www.youtube.com/@storytellingwithdata/) for providing a comprehensive tutorial on Microsoft Excel, which helped me in completing this project. Their step-by-step guidance was invaluable in understanding the concepts and techniques used in this project.

<br/>

<br/>

<br/>

## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dipu1591/)
