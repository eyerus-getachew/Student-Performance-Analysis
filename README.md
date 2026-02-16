# Student Performance Analysis

## Project Objective
The goal of this project is to analyze student performance data and identify factors that influence academic outcomes in mathematics, reading, and writing. This includes exploring how demographic features and test preparation impact student scores, and understanding relationships between subjects.

---

## Dataset Description
The dataset contains **1000 student records** with the following columns:

- `gender` – Male or Female  
- `race/ethnicity` – Student group  
- `parental level of education` – Highest education level of parents  
- `lunch` – Standard or free/reduced  
- `test preparation course` – Completed or None  
- `math score` – 0 to 100  
- `reading score` – 0 to 100  
- `writing score` – 0 to 100  

The dataset is in CSV format: `data/StudentsPerformance.csv`.

---

## Tools Used
- Python  
- pandas  
- matplotlib  
- Jupyter Notebook (for analysis and visualization)  

---

## Key Insights

### Overall Performance
- Students performed best in **reading**, followed by **writing**, while **mathematics** had the lowest average score.  
- Score distribution shows moderate variability, indicating differences in student performance levels.

### Gender Differences
- Male students outperform females in **mathematics**.  
- Female students significantly outperform males in **reading** and **writing**.  
- The largest gender gap appears in writing.

### Impact of Test Preparation
- Students who completed the **test preparation course** scored higher in all three subjects.  
- The greatest improvement was observed in **writing**, with nearly a 10-point increase.  
- Academic support programs can meaningfully improve student outcomes.

### Relationship Between Subjects
- Strong positive correlation exists between all three subjects.  
- **Reading and writing** show an extremely high correlation (r ≈ 0.95).  
- Mathematics also has strong positive correlations with both reading and writing.  
- Students who perform well in one subject are likely to perform well in others.

### Final Insight
- **Test preparation** and **gender** are influential factors in student performance.  
- Strong subject correlations highlight the interconnected nature of academic skills.  
- Educational interventions, particularly test preparation programs, can significantly enhance student achievement across multiple subjects.

---

## Visualizations
Key plots illustrating the analysis:

1. Average Scores by Gender  ![Average Scores by Gender](images/gender_scores.png)

2. Impact of Test Preparation on Scores  ![Impact of Test Preparation on Scores](images/prep_scores.png)

3. Correlation Heatmap Between Subjects  ![Correlation Between Subjects](images/corr.png)


