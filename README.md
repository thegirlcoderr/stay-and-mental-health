# stay-and-mental-health
This project explores how the length of stay impacts the average mental health diagnostic scores of international students at a Japanese university.
The analysis is based on a 2018 student survey that studied the connection between:
* Depression (PHQ-9 test)
* Social Connectedness (SCS test)
* Anxiety and Stress (ASISS test)

What This Project Explores 🔍
* Do international students experience higher mental health risks than domestic students?
* Does social connectedness reduce the risk of depression?
* Does the length of stay affect mental health outcomes?

Tech Stack 🛠️
* PostgreSQL
* SQL Queries
* Data Aggregation
* Grouping & Filtering

Dataset Overview
* inter_dom	= Student Type (Inter = International, Dom = Domestic)
* stay =	Length of Stay (in months or years)
* todep =	Depression Score (PHQ-9 Test)
* tosc	= Social Connectedness Score (SCS Test)
* toas	= Anxiety and Stress Score (ASISS Test)
  
How I Solved It:
1. Filtered the data to only international students.
2. Grouped students by length of stay.
3. Calculated:
    * Total number of international students for each stay length.
    * Average Depression Score (PHQ-9)
    * Average Social Connectedness Score (SCS)
    * Average Anxiety & Stress Score (ASISS)
4. Rounded all average scores to two decimal places.
5. Sorted the results in descending order by length of stay.

Conclusion
Based on this analysis:
* International students with longer stays tend to have better social connectedness scores.
* Higher social connectedness is linked to lower depression scores.
* Anxiety and stress levels vary with the length of stay, but longer stays show lower average ASISS scores.





