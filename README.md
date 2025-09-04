# Students’ Performance in Exams – ML Project  

This project walks you through an **end-to-end Machine Learning workflow** using the **StudentsPerformance dataset**.  
You will learn how to:  
- Explore and clean data (EDA).  
- Visualize relationships between features.  
- Train and evaluate machine learning models.  
- Understand how factors like gender, parental education, lunch, and test preparation affect exam performance.  

---

## Repository Contents
- **`StudentsPerformance.csv`** → Dataset with 1000 students and their exam scores.  
- **`1_EDA_STUDENT_PERFORMANCE_.ipynb`** → Notebook for **Exploratory Data Analysis (EDA)**.  
- **`2_MODEL_TRAINING.ipynb`** → Notebook for **training ML models** and making predictions.  

---

## How to Run in Google Colab
1. Open [Google Colab](https://colab.research.google.com/).  
2. Upload both notebooks (`1_EDA_STUDENT_PERFORMANCE_.ipynb` and `2_MODEL_TRAINING.ipynb`).  
3. Upload the dataset `StudentsPerformance.csv`.  
4. Run the cells step by step.  

---

## Dataset Info
The dataset contains the following columns:  
- **gender** → male / female  
- **race_ethnicity** → student’s ethnic group (A, B, C, etc.)  
- **parental_level_of_education** → highest education level of the parents  
- **lunch** → standard or free/reduced  
- **test_preparation_course** → completed or none  
- **math_score** → exam score in math  
- **reading_score** → exam score in reading  
- **writing_score** → exam score in writing  

---

## Required Libraries
Google Colab already has most libraries pre-installed. Just in case, you can run:  

```python
!pip install --upgrade numpy pandas matplotlib seaborn
