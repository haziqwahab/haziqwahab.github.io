
## 101,000 Voices: What SQL Reveals About Healthcare Operations
#### Software : SQL

When I started my project analysing healthcare data, I thought I was just crunching numbers. Little did I know, I was about to stumble into a treasure trove of insights that could shape how we understand hospital operations. Imagine revealing that patients are often discharged in less than a week or exploring the fascinating world of medical specialties and their volume of procedures. This journey turned out to be an eye-opener for me.


<img src="images/Centers_for_Medicare_and_Medicaid_Services_logo.svg.png"/>

### Why THIS Project?

Healthcare has always held a special place in my heart. It's not just about numbers it's about people and how we can improve their lives. With a significant portion of national budgets allocated to healthcare, I felt compelled to dig deeper into hospital performance. This project was my way of contributing by studying how hospitals operate and preparing for future challenges based on solid data.

### What Readers Will Gain

Through this article, you will gain insights into hospital readmission trends, understand the average length of stays, and discover how different medical specialties perform. You'll also learn about patient treatment fairness across races and the relationship between the number of lab procedures and hospital stays.

### Key Takeaways

- Most patients are discharged within an average of **4.4 days**.

- **Cardiology and related surgeries** are the most common hospital procedures.

- **Race does not influence** the administration of lab procedures in hospitals.

- A **higher number of lab procedures** is associated with **longer hospital stays**.

- Patients prescribed **numerous medications** are **less likely to be readmitted**.

### Dataset Details

For this project, I used a dataset sourced from Kaggle, which contains information about diabetes patients from 130 US hospitals between 1999 and 2008. This dataset was perfect for my analysis as it included patient demographics, health history, hospital usage metrics, and outcomes related to readmission risk.

The origin of the data can be found [here](https://www.kaggle.com/code/iabhishekofficial/prediction-on-hospital-readmission/notebook).

### Visuals and Insights

#### Average length of hospital stays

<img src="images/H carbon bar chart.png"/>
<img src="images/H bar chart.png"/>

I showcased the average length of hospital stays . This graph illustrates that most patients leave the hospital within 7 days, with an **average of 4.4 days**, translating to an estimated cost of **$12,469.20** per patient.

#### Busiest sector of the hospital

<img src="images/H carbon avg procedures.png"/>
<img src="images/H avg procedures.png"/>

Another key highlighted the prevalence of cardiology procedures. It's evident that this specialty plays a critical role in hospital operations and ensuring resource availability is vital.

#### Does Race Influence the Quality of Hospital Treatment?

<img src="images/carbon race treatment.png"/>
<img src="images/H race treatment.png"/>

Interestingly, the data indicated that all races received equitable treatment regarding lab procedures, which was a positive finding.

#### Do More Lab Procedures Increase the Length of Hospital Stay?

<img src="images/H carbon avg time.png"/>
<img src="images/H avg time.png"/>

I also explored the correlation between **lab procedures** and **hospital duration**. The results suggested that **reducing unnecessary lab tests** or improving their efficiency could help **free up hospital beds**, which is crucial for patient care.

#### List of African American Patients or Those with Metformin 'Up'

<img src="images/H carbon race.png"/>
<img src="images/H race.png"/>

By using UNION, I efficiently combined two distinct patient groups while maintaining data integrity. Documenting my query logic and validating key assumptions (like the meaning of 'Up') transformed a simple data pull into reproducible research

#### Admission Details, Medical Specialties, and Procedure Volumes  

<img src="images/H carbon avg time 2.png"/>
<img src="images/H avg time 2.png"/>

The data hints at potential efficiency in care delivery (short stays despite multiple procedures), this really blew my mind but further analysis is needed to explore specialty-specific outcomes or missing specialty impacts.

#### How Are Insulin, Metformin, and Glipizide Ranked by Usage Across Age Groups?

<img src="images/H carbon medicine.png"/>
<img src="images/H medicine.png"/>

Across all age groups, **insulin consistently ranks as the most used medication**, followed by **metformin**, then glipizide highlighting a clear treatment hierarchy regardless of age.

#### Summarising Each Patient to Uncover Key Patterns

<img src="images/carbon race by madecine.png"/>
<img src="images/H race by medecine.png"/>

Many patients receive extensive medication yet are not readmitted, suggesting that high medication use does not necessarily indicate poor outcomes.

### Main Takeaways

The project underscored that most patients are **discharged well within a week**, with **cardiology** procedures being the **most common**. It was reassuring to find no racial bias in treatment for lab procedures. Furthermore, the analysis revealed a strong correlation between the number of lab procedures performed and the length of hospital stays. This insight suggests that **hospitals could enhance efficiency by reviewing their lab testing protocols**, ultimately improving patient flow.

Through this project, I learned that even with extensive medication regimens, **many patients do not experience readmissions**. This indicates that effective treatment strategies are in place, but there's always room for improvement in how we manage patient care.

### Conclusion and Personal Reflections

This project was not without its challenges. Analysing a large dataset and visualising the findings required patience and creativity. However, these hurdles helped me grow both as a data analyst and as someone deeply interested in healthcare. I now view hospital operations through a more informed lens, understanding the delicate balance between resource management and patient care.

### Call To Action

If you're interested in discussing these findings or have questions about healthcare data analysis, feel free to connect with me. I’d love to hear your thoughts or share more about this fascinating journey!


