# Student Success Input Form Questions

## Consolidated Questionnaire 

sex - student's sex (binary: 'F' - female or 'M' - male)
    - initial_predictions.ipynb, analyze_math_read_write.ipynb, and analyze_student_prediction.ipynb
    
age - student's age (numeric: from 15 to 22)
    - initial_predictions.ipynb, analyze_math_read_write.ipynb, and analyze_student_prediction.ipynb

address - student's home address type (binary: 'U' - urban or 'R' - rural)
    - initial_predictions.ipynb

famsize - family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3)
    - initial_predictions.ipynb
    
Pstatus - parent's cohabitation status (binary: 'T' - living together or 'A' - apart)
    - initial_predictions.ipynb

Medu - mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)
    - initial_predictions.ipynb

Fedu - father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education 4 – associates  5 - bachelors 6 - masters 7 - phd)
    - initial_predictions.ipynb or analyze_student_prediction.ipynb(4 or higher) depending on numeric

General Parental education - (some college, associate's degree, other)
    - analyze_math_read_write.ipynb (should be derived from average of Medu + Fedu)

Mjob - mother's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
    - initial_predictions.ipynb

Fjob - father's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
    - initial_predictions.ipynb

reason - reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other')
    - initial_predictions.ipynb

guardian - student's guardian (nominal: 'mother', 'father' or 'other')
    - initial_predictions.ipynb

traveltime - home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)
    - initial_predictions.ipynb

studytime - weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)
    - initial_predictions.ipynb and analyze_student_prediction.ipynb

failures - number of past class failures (numeric: n if 1<=n<3, else 4)
    - initial_predictions.ipynb

schoolsup - extra educational support (binary: yes or no)
    - initial_predictions.ipynb and analyze_math_read_write.ipynb

famsup - family educational support (binary: yes or no)
    - initial_predictions.ipynb

paid - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)
    - initial_predictions.ipynb

activities - extra-curricular activities (binary: yes or no)
    - initial_predictions.ipynb and analyze_student_prediction.ipynb

nursery - attended nursery school (binary: yes or no)
    - initial_predictions.ipynb

higher - wants to take higher education (binary: yes or no)
    - initial_predictions.ipynb

internet - Internet access at home (binary: yes or no)
    - initial_predictions.ipynb

romantic - with a romantic relationship (binary: yes or no)
    - initial_predictions.ipynb and analyze_student_prediction.ipynb

famrel - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
    - initial_predictions.ipynb

freetime - free time after school (numeric: from 1 - very low to 5 - very high)
    - initial_predictions.ipynb

goout - going out with friends (numeric: from 1 - very low to 5 - very high)
    - initial_predictions.ipynb

Dalc - workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
    - initial_predictions.ipynb

Walc - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
    - initial_predictions.ipynb

health - current health status (numeric: from 1 - very bad to 5 - very good)
    - initial_predictions.ipynb

school lunch status (free/reduced, standard)
    - analyze_math_read_write.ipynb

scholarship (yes, no)
    - analyze_student_prediction.ipynb

work (yes,no)
    - analyze_student_prediction.ipynb

salary (amount range)
    - analyze_student_prediction.ipynb

reading frequency (hour range)
    - analyze_student_prediction.ipynb

science reading frequency (hour range)
    - analyze_student_prediction.ipynb

attendance (number of absences)
    - analyze_student_prediction.ipynb
    
takes notes (yes,no)
    - analyze_student_prediction.ipynb


## From "Student_predictions" (analyze_student_prediction.ipynb)

1. AGE
2. SCHOLARSHIP 
3. WORK 
4. SALARY 
5. STUDY_HRS 
6. READ_FREQ 
7. READ_FREQ_SCI 
8. ATTEND_DEPT 
9. IMPACT 
10. ATTEND
11. PREP_STUDY 
12. PREP_EXAM 
13. NOTES 
14. LISTENS 
15. LIKES_DISCUSS 
16. CUML_GPA 
17. EXP_GPA 
18. GENDER_1 
19. GENDER_2 
20. HS_TYPE_1 
21. HS_TYPE_2 
22. HS_TYPE_3 
23. ACTIVITY_1 
24. ACTIVITY_2 
25. PARTNER_1 (yes, no)
27. MOTHER_EDU (none, highschool, associates, bachelors, masters, phd)
28.  FATHER_EDU (none, highschool, associates, bachelors, masters, phd)   

## from "student alcohol consumtion dataset" (initial_predictions.ipynb)

1. school - student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira) not needed since school data will only affect samples in the same school as in the test data
2. sex - student's sex (binary: 'F' - female or 'M' - male)
3. age - student's age (numeric: from 15 to 22)
4. address - student's home address type (binary: 'U' - urban or 'R' - rural)
5. famsize - family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3)
6. Pstatus - parent's cohabitation status (binary: 'T' - living together or 'A' - apart)
7. Mother's level of education - mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)
8. Fedu - father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)
9. Mjob - mother's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
10. Fjob - father's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
11. reason - reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other')
12. guardian - student's guardian (nominal: 'mother', 'father' or 'other')
13. traveltime - home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)
14. studytime - weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)
15. failures - number of past class failures (numeric: n if 1<=n<3, else 4)
16. schoolsup - extra educational support (binary: yes or no)
17. famsup - family educational support (binary: yes or no)
18. paid - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)
19. activities - extra-curricular activities (binary: yes or no)
20. nursery - attended nursery school (binary: yes or no)
21. higher - wants to take higher education (binary: yes or no)
22. internet - Internet access at home (binary: yes or no)
23. romantic - with a romantic relationship (binary: yes or no)
24. famrel - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
25. freetime - free time after school (numeric: from 1 - very low to 5 - very high)
26. goout - going out with friends (numeric: from 1 - very low to 5 - very high)
27. Dalc - workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
28. Walc - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
29. health - current health status (numeric: from 1 - very bad to 5 - very good)
30. absences - number of school absences (numeric: from 0 to 93)

## From "Students performance in exams" (analyze_math_read_write.ipynb)

1. gender
2. race
3. parental level of education
4. school lunch status (free/reduced, standard)
5. test prep course completed ?

grade scores / 100:
1. math
2. reading
3. writing
