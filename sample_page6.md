
## The Chemistry of Concentration: Analysing Iron, Silica, and Their Impact
#### Software : Pyhton

**The original dataset can be found** [here](https://www.kaggle.com/datasets/edumagalhaes/quality-prediction-in-a-mining-process/data).

When I first took on the project of analysing a dataset related to the **flotation extraction** process for iron ore, I wasn't sure what to expect. As I sifted through rows and rows of numbers, it struck me how much complexity lies behind something we often take for granted iron, a common element in our daily lives. I remember feeling a mix of excitement and curiosity, wondering how my analysis could help improve industrial processes.

**Flotation**: Mineral processing, method used to separate and concentrate ores by altering their surfaces to a hydrophobic or hydrophilic condition

### Why THIS Project?

I chose this project because I wanted to connect with real world industrial challenges. The idea of helping manufacturing plants boost their efficiency truly resonated with me. I’ve always been fascinated by how data can shed light on processes that seem straightforward but are filled with intricate relationships.

### What Readers Will Gain

By reading this article, you'll gain insights into the flotation extraction method, learn about key factors impacting iron ore quality, and see how data analysis can inform operational improvements. I’ll share some surprising findings from my analysis and explain the significance behind them.

### Key Takeaways

- **Iron** and **Silica** Concentrates show an **inverse relationship**; better flotation control means higher purity.
- Maintaining **stable pH levels is crucial**, as even slight changes can affect quality.
- **Amina Flow** and **Ore Pulp Density** are highly **correlated**, playing a significant role in process efficiency.
- Operations tend to be more stable during weekdays compared to weekends, indicating a potential area for improvement.

### Dataset Details

The dataset I worked with comes from Kaggle and focuses on a **flotation plant**, which is a common method for concentrating iron ore. It contains **737,453** entries, recorded over six months, and reflects various process parameters such as **Iron Feed, Silica Feed, and pH levels**. This extensive dataset provided a solid foundation for uncovering insights into the extraction process.

### Analysis Process

My analysis began by cleaning and transforming the dataset to focus on the most relevant columns. I used **Python** to filter for essential metrics like **Iron Concentrate and pH levels**, simplifying my analysis. I was surprised to see how closely related some variables were, particularly **Amina Flow** and **Ore Pulp Density**, which had a correlation of 0.82. This strong relationship suggests they are key levers for enhancing froth stability and, ultimately, process efficiency.

### Visual and Insights

<img src="images/D 5.png"/>

In my analysis, I worked with a dataset entries collected between March and September 2017 from a mining process. The key parameters include **Iron Feed (average 56.29%), Silica Feed (average 14.65%**, showing the highest variability), Starch Flow (highly variable at an average of 2,869.14), **Amina Flow (488.14), Ore Pulp Flow (397.58)**, and **Ore Pulp pH** (tightly controlled at 9.77). Notably, while Silica Feed fluctuates significantly, the stable pH reflects strong process control measures.

<img src="images/D 8.png"/>

For my analysis, I selected key columns from June , % Iron Concentrate, % Silica Concentrate, Ore Pulp pH, and Flotation Column 05 Level. This focused dataset helps me study how factors like pH and flotation levels affect concentrate quality, making it easier to spot trends and assess process efficiency.

<img src="images/D 9.1.png"/>

<img src="images/D 9.png"/>

All the graphs shows how different ore characteristics relate to each other, helping to uncover insights that could guide operations or future flotation research.

<img src="images/D 11.png"/>

The graph displays Iron Concentrate levels over two days in June 2017, showing noticeable **fluctuations** between **63%** and **66.5%**. These ups and downs suggest possible process instability from factors like feed changes or equipment issues. Identifying these variations is important for maintaining product quality and targeting areas for improvement.

<img src="images/D 11.1.png"/>

This graph shows % Silica Concentrate over time, fluctuating between 1% and 4%. The sharp spikes suggest instability in impurity removal, with lower values indicating good performance and higher peaks pointing to possible process issues.

<img src="images/D 11.2.png"/>

This graph illustrates Ore Pulp pH, mostly staying between 9.8 and 10.0 with small dips to around 9.6. These slight changes reflect real-time reagent adjustments and are important because **pH affects how well minerals separate**, impacting concentrate quality.

<img src="images/D 11.3.png"/>

This graph shows Flotation Column 05 Level over time, which helps monitor process stability. **Consistent levels are ideal**, while big changes may point to issues like feed or airflow problems. Comparing this with other metrics can help explain quality variations and identify process inefficiencies.

<img src="images/D 12.png"/>

I did a comparison of hourly averages of Iron and Silica Concentrate, showing they move in **opposite patterns**. Iron peaks around midday while silica drops, indicating consistent process cycles and helping identify the best operating times and possible inefficiencies.

<img src="images/D 13.png"/>

The scatter plot illustrates that while starch flow varies widely, the **iron concentrate** percentage **remains relatively stable**, clustering mostly between 64.5% and 66.5%, indicating limited direct correlation between starch flow and iron concentrate levels.

<img src="images/D 14.png"/>

<img src="images/D 14.1.png"/>

Correlation matrix reveals that **Amina Flow** and **Ore Pulp Density** are strongly positively correlated (0.82), while % Silica Concentrate shows a moderate negative correlation with both % Iron Concentrate (-0.27) and Amina Flow (-0.46), suggesting critical interplay in controlling product quality.

<img src="images/D 15.png"/>

<img src="images/D 15.1.png"/>

The scatter plot visualizes the relationship between Starch Flow and % Iron Concentrate for June . Each point’s size represents Ore Pulp Density (scaled for visibility), showing how density varies with flow and concentrate levels. The plot helps identify patterns where changes in starch flow and pulp density impact iron concentrate quality.

<img src="images/D 16.png"/>

<img src="images/D 16.1.png"/>

This scatter plot shows the relationship between **Starch Flow and % Iron Concentrate**, with bubble sizes representing Ore Pulp Density and colors indicating % Silica Concentrate. This multi-variable visualization helps reveal how changes in flow, density, and silica levels interact and affect iron concentrate quality.

<img src="images/D 17.png"/>

What we’re seeing here is boxplot compares weekly Iron and Silica Concentrate quality, showing **stable iron purity (64–67%)** with less variation on weekdays. **Silica impurities drop when iron is high**, especially table iron purity (64–67%) with less variation on weekdays. Silica impurities drop when iron is high, especially midweek, suggesting better process conditions then. Slightly more variability on weekends may be due to staffing or maintenance, highlighting chances to improve consistency.


<img src="images/D 18.png"/>

**Best Days:**

Sunday: Highest **iron (65.18%)** and lowest **silica (2.28%)**

Thursday: Most stable process (lowest variability in both iron and silica)

**Worst Day:**

Tuesday: Lowest **iron (64.96%)** and lowest **silica (2.28%)**

Saturday: Highest silica **(2.41%)** and more variation

**pH Stability:**

Remains consistent **(9.68-9.83)** across all days

**Recommendation:** 

Study Sunday/Thursday's operational settings (like chemical doses or equipment speeds) to improve consistency on other days, especially Tuesday and Saturday.

### Main Takeaways 

In summary, my analysis revealed key insights about the flotation process:

- The inverse relationship between Iron and Silica Concentrate highlights the importance of controlling flotation conditions.
- Keeping pH levels stable is essential for maintaining product quality, as even minor changes can have significant effects.
- Amina Flow and Ore Pulp Density are critical for process efficiency, indicating that focusing on these factors could lead to improvements in output quality.
- Weekday operations show greater consistency, guiding us toward replicating these conditions on weekends for better results.

### Conclusion and Personal Reflections

This project was both challenging and rewarding. One of the biggest hurdles was navigating the vast amount of data and identifying the most relevant metrics. However, each step deepened my understanding of the flotation process and its complexities. This experience has certainly impacted my future goals, reinforcing my belief in the power of data to drive operational improvements.

### Call To Action 

I invite you to connect with me if you have insights or questions about this project! Let's start a conversation about how data analysis can inform decision-making in industrial processes.





