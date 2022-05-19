# Abnormal-Blood-Pressure-Detection-

Classification of Patients with Abnormal Blood Pressure

Background

Hypertension with aging is a major medical concern even in this ultramodern era of advanced therapies. Preliminary
testing is a key element in analyzing the procedures of mild abnormality of blood pressure for a substantial period of
time, but presently has a limited value in the prediction of progression to hypertension. Although hypotension, low
blood pressure in common parlance is less common among the ones with abnormal blood pressure, but the adverse
the effect it has on their health is equivalent to that of hypertension.
Although recent studies have hypothesized that, keeping other factors constant, hemoglobin level is positively
associated with blood pressure in a large cohort of healthy individuals, genetic causes are also prominent in some
individuals. However, there are numerous other factors that determine whether an individual is likely to develop this
abnormality.
Data scientists layout the hypothesis that newer statistical classification methods derived from data mining and
machine-learning methods are capable of reducing the prediction error manifolds and help cardiologists to conduct a
two-tailed preliminary prediction of abnormality of blood pressure in an individual.
Objective
Employing statistical techniques, conduct a preliminary prognosis of Hypertension/hypotension, based on the level of
hemoglobin and genetic history of the individual and also when other factors like Smoking, obesity (BMI), Lack of physical activity, salt content in the diet, alcohol consumption per day, Level of Stress, Age, Sex, Pregnancy, Chronic kidney disease, and Adrenal & thyroid disorders.

Total Number of Patients (N) = 2000

    Blood_Pressure_Abnormality (0 = Normal , 1 = Abnormal, Nominal Target )
    Level_of_Hemoglobin (g/dl) Ratio Input
    Genetic_Pedigree_Coefficient (Ratio Input)
    Age (Ratio Input)
    BMI (Ratio Input)
    Sex (0 = Male , 1 = Female, Nominal Input)
    Pregnancy (0 = No ,1 = Yes, Nominal Input)
    Smoking (0 = No ,1 = Yes, Nominal Input)
    Physical activity (No. of steps/day) - Ratio Input
    salt_content_in_the_diet (mg/per day) - Ratio Input
    alcohol_consumption_per_day (ml/day) - Ratio Input
    Level_of_Stress 13 (Cortisol Secretion)(1 = Less, 2 = Normal , 3 = High, Ordinal Input)
    Chronic_kidney_disease (0 = No, 1 = Yes, Nominal input)
    Adrenal_and_thyroid_disorders ( 0 = No,1 = Yes, Nominal Input)

*Genetic Pedigree Coefficient (GPC) of an individual for a particular disease is a continuum between 0 and 1, where
GPC closer to 0 indicates a very distant occurrence of that disease in her/his pedigree, and
GPC closer to 1 indicates a very immediate occurrence of that disease in her/his pedigree]
