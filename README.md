# Student Mental Health Analysis

## Overview
Depression among students is a growing global concern, often leading to academic decline, social isolation, and even suicidal ideation.  
This project aims to develop a predictive model that identifies students at risk of depression using behavioral, academic, and demographic data. The goal is to enable early detection and provide support services to at-risk students.

## Dataset Details
We use the Student Depression Dataset from OpenML.

- **Source:** [OpenML Dataset #46753](https://www.openml.org/search?type=data&status=active&id=46753&sort=runs)  
- **Instances:** 27,901  
- **Features:** 18  
- **Target Variable:** `Depression`

**Key Features include,**
- Demographic info (Age, Gender, City, Profession)  
- Academic performance (CGPA, Academic pressure, Study satisfaction)  
- Lifestyle factors (Sleep duration, Dietary habits, Work/study hours)  
- Mental health history (Suicidal thoughts, Family history)  

## Group Members
- IT24102409 – Herath H. H. A. D. S. J  (Outlier detection)
- IT24102703 – Gunawardena D. H.  (Class balance)
- IT24102735 – Perera K. S. D  (Normalization and scaling)
- IT24102870 – Jayasundara M. H. L. J  (Handling missing values)
- IT24102332 – Sathnara H. D. M  (Converting categorical data)
- IT24103114 – Muthumali R. M. P. V  (Feature engineering)

## How to Run the Code
1. **Clone the repository**
   ```bash
   git clone https://github.com/MihiniSathnara/student-mental-health-analysis.git
   cd student-mental-health-analysis

2. **Set up environment**
    ```bash
    pip install -r requirements.txt

3. **Run the group_pipeline.ipynb**

