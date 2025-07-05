# capstone-project-hacktiv8 : Student Mental Health Analysis

## Project Overview

### Student Mental Health
This project focuses on analyzing **student mental health** conditions based on survey data. 
It explores factors like age, gender, stress levels, lifestyle habits, and academic pressure.

### Why This Project Matters
Mental health issues among students are increasingly common but often overlooked. Academic pressure, lifestyle habits, and lack of mental health 
awareness can silently affect students' well-being, performance, and overall life quality. Despite growing awareness, many students still don't seek help or access 
available support services. This project aims to highlight these patterns through data, so institutions can respond with better, more targeted support.

### Project Goals
- To explore and understand key factors influencing student mental health, such as stress levels, academic pressure, lifestyle habits, and access to support services.
- To identify patterns and relationships within the data using visualization techniques.
- To generate structured insights and actionable recommendations using IBM Granite AI.
- To help universities, mental health staff, and student communities make more informed decisions in supporting student well-being.

### Methodology
This project uses an exploratory data analysis (EDA) approach to examine student mental health survey data. Several visualization techniques are used to highlight patterns related to stress, lifestyle, and academic pressure.
To support deeper understanding, AI (IBM Granite) is used to generate structured insights and recommendations based on the analysis results.

### Tools Used
- **Python** For data analysis and visualization
- **Pandas & NumPy** Data processing and manipulation
- **Seaborn & Matplotlib** Data visualization
- **IBM Granite (via LangChain + Replicate)** To generate AI-driven insights, conlusion, and recommendations
- **Google Colab** As the development environment


## Raw Dataset Link
https://github.com/NidhiU-24/Student-Mental-Health-Assessment

## Insight & Findings
### Insights from EDA 
**Student Demographics**
- Most students are aged between 18–22
- The gender distribution is relatively balanced, with a slight majority of male students.
- Most students are from Medical, followed by Law and Engineering. Fewer are enrolled in Business and Other courses.

**General Mental Health Condition**
- The majority of students report moderate stress levels (level 3).
- Most students have moderate levels of depression and anxiety scores, with fewer students at the highest levels. This suggests a widespread but varied mental health burden.

**lifestyles and wellness**
The median stress levels appear consistent across different categories of sleep quality, physical activity, and diet quality, suggesting no strong direct relationship in this dataset.

**Support and Counseling Services**
- Most students have never used counseling services, indicating a potential gap in mental health support utilization.
- Stress levels appear relatively consistent across different levels of social support and relationship status, suggesting these factors may have limited impact on stress variation.
- A significant number of students reported no family history of mental health issues, suggesting a majority may not have genetic predispositions.

**Academic and Financial Pressure**
- There is no clear relationship between CGPA and stress level, suggesting that academic performance may not directly reflect students' emotional burden.
- There is no significant change in stress level across different levels of financial stress, suggesting financial stress alone may not be a dominant factor influencing students'   emotional state.
- Stress level appears to be evenly distributed across different semester credit loads, suggesting no strong correlation between course load and stress.

### AI-Generated Insights (IBM Granite) 
AI-Generated Insights

1. Student Demographics 
- Age Distribution: The majority of students fall within the age range of 18 to 22, indicating a typical college or university student population.
- Gender Balance: The gender distribution is relatively even, with a slight preponderance of male students over female students.
- Academic Majors: Medical students constitute the largest group, reflecting a significant interest in healthcare-related fields.
Law and Engineering majors follow closely in number, highlighting a strong inclination towards professional and technical disciplines.
The remaining students are distributed among Business and other miscellaneous fields, showcasing diversity in academic interests.

2. General Mental Health Condition
- Stress Levels: Most students report experiencing moderate stress, rated at level 3 on an unspecified scale. This suggests a substantial number of students are facing challenges that require attention but are not overwhelming.
- Depression and Anxiety: Both depression and anxiety are reported predominantly at moderate levels within the student body. This indicates that while mental health issues are present, they are not acute or widespread.

3. Lifestyles and Wellness
- Stress-Related Factors: There is no discernible correlation between stress levels and key lifestyle factors such as sleep quality, diet, or engagement in physical activity. This implies that students' stress management strategies may not be directly influenced by their sleep habits, nutritional intake, or exercise routines. Further investigation into specific coping mechanisms or support systems could be beneficial to enhance overall well-being.
In summary, the student body exhibits typical demographic patterns for higher education, with a noticeable emphasis on health-related and professional disciplines. Mental health indicators are primarily at moderate levels, suggesting an area for proactive support rather than crisis intervention. Lifestyle factors do not appear to moderate stress levels, underscoring the need for targeted wellness programs tailored to students' unique stressors.

4. Support and Counseling Services
- Underutilization: A significant portion of students, approximately 70%, reported never having utilized campus counseling or mental health services, indicating a potential underutilization of available resources. This could imply a lack of awareness, stigma, or accessibility issues surrounding these services.
- Stress Persistence: Despite variations in students' social support systems and relationship statuses, stress levels remained consistent. This suggests that external support networks may not significantly alleviate internal psychological pressures experienced by students.
- Family History: The majority of students, around 85%, indicated that there was no family history of mental health issues. This lack of familial precedent might contribute to students' underestimation of their vulnerability to mental health challenges or their recognition of symptoms.

5. Academic and Financial Pressure
- CGPA and Stress: There was no clear correlation between students' Cumulative Grade Point Average (CGPA) and reported stress levels. This finding challenges the common assumption that academic performance directly influences student stress, suggesting other factors play a more critical role.
- Financial Stress: Financial concerns did not emerge as the dominant source of stress among students. While financial pressures were acknowledged, they did not rank higher than other stressors like coursework demands or personal life issues.
- Course Load and Stress: Stress levels remained relatively stable irrespective of the course load. This indicates that the perceived academic workload alone may not be the primary driver of stress, hinting at other underlying factors such as personal expectations, time management, or broader life concerns impacting students' mental well-being.

These insights highlight areas for intervention, such as increasing awareness and reducing stigma around utilizing counseling services, addressing the persistent nature of stress independent of external support, and exploring the complex interplay of factors contributing to student stress beyond academic and financial pressures. Institutions might consider targeted programs to enhance emotional resilience and stress management, irrespective of academic performance or financial situations.

## AI Support Explanation
To support deeper understanding and make the insights more structured, this project uses IBM Granite AI via LangChain + Replicate. After performing Exploratory Data Analysis (EDA), AI was used to:
- Summarize key patterns found in the data
- Generate clear, structured insights across several categories (demographics, mental health, lifestyle, etc.)
- Provide conclusion and actionable recommendations for universities and mental health stakeholders

Using AI helps streamline the reporting process and ensures that important insights are communicated clearly and effectively.

