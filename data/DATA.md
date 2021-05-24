# Data columns
File: `twins2013_matched.csv`
Columns:

    - X1: could ignore this - just the row number
    
    - idnumber: the id number used to match the mortality dataset to the denominator dataset with all other birth information. We have 2397 non-missing values which means there are 2397 deaths out of 110731 kids in our dataset. All live births are NA in this column.
    
    - dob_yy: birth year - all are 2013
    
    - dob_mm: birth month - values 1 to 12
    
    - dob_wk: birth weekday - values 1 to 7
    
    - mager41: mother's age - values 13 to 50 with 13-49 indicating 13-49 years old, 50 indicating 50-64 years old
    
    - mager14: mother's age recoded in 14 levels - 01: Under 15 Years; 03: 15 years; 04: 16 years; 05: 17 years; 06: 18 years; 07: 19 years; 08: 20-24 years; 09: 25-29 years; 10: 30-34 years; 11: 35-39 years; 12: 40-44 years; 13: 45-49 years; 14: 50-64 years
    
    - mager9: mother's age recoded in 9 levels - 1: Under 15 years; 2: 15-19 years; 3: 20-24 years; 4: 25-29 years; 5: 30-34 years; 6: 35-39 years; 7: 40-44 years; 8: 45-49 years; 9: 50-64 years
    
    - meduc: mother's education coded in 9 levels - 1: 8th grade or less; 2: 9th through 12th grade with no diploma; 3: High school graduate or GED completed; 4: Some college credit, but not a degree; 5: Associate degree (AA,AS); 6: Bachelor’s degree (BA, AB, BS); 7: Master’s degree (MA, MS, MEng, MEd, MSW, MBA); 8: Doctorate (PhD, EdD) or Professional Degree (MD, DDS, DVM, LLB, JD); 9: Unknown
    
    - mracerec: mother's race coded in 4 levels: 1: White; 2: Black; 3: American Indian / Alaskan Native; 4: Asian / Pacific Islander
    
    - fracerec: father's race coded in 5 levels: 1: White; 2: Black; 3: American Indian / Alaskan Native; 4: Asian / Pacific Islander; 9: Unknown or not stated
    
    - fagerec11: father's age recoded in 11 levels: 01: Under 15 years; 02: 15-19 years; 03: 20-24 years; 04: 25-29 years; 05: 30-34 years; 06: 35-39 years; 07: 40-44 years; 08: 45-49 years; 09: 50-54 years; 10: 55-98 years; 11: Not stated
    
    - lbo: live birth order recode - 1-7 Number of live birth order; 8: 8 or more live births; 9: Unknown or not stated
    
    - uprevis: number of prenatal visits - 00-49: Number of prenatal visits; 99: Unknown or not stated
    
    - wtgain: weight gain in pounds - 00-97: Weight gain in pounds; 98: 98 pounds and over; 99: Unknown or not stated
    
    - cig_1: number of cigarettes daily during 1st Trimester - 00-97: Number of cigarettes daily; 98: 98 or more cigarettes daily; 99: Unknown or not stated
    
    - cig_2: number of cigarettes daily during 2nd Trimester - 00-97: Number of cigarettes daily; 98: 98 or more cigarettes daily; 99: Unknown or not stated
    
    - cig_3: number of cigarettes daily during 3rd Trimester - 00-97: Number of cigarettes daily; 98: 98 or more cigarettes daily; 99: Unknown or not stated
    
    - mar: mother's marital status - 1: Yes; 2: No
    
    - rf_diab: prepregnancy diabetes - Y: Yes; N: No; U: Unknown or not stated
    
    - rf_gest: gestational diabetes - Y: Yes; N: No; U: Unknown or not stated
    
    - rf_phyp: prepregnancy hypertension - Y: Yes; N: No; U: Unknown or not stated
    
    - rf_ghyp: gestational hypertension - Y: Yes; N: No; U: Unknown or not stated
    
    - rf_eclam: hypertension eclampsia - Y: Yes; N: No; U: Unknown or not stated
    
    - rf_ppterm: previous preterm birth - Y: Yes; N: No; U: Unknown or not stated
    
    - rf_ppoutc: poor pregnancy outcome - Y: Yes; N: No; U: Unknown or not stated
    
    - rf_cesar: previous cesareans - Y: Yes; N: No; U: Unknown or not stated
    
    - rf_ncesar: number of previous cesareans - 00: None; 01-30: Number of previous cesareans; 99: Unknown or not stated
    
    - md_route: route/methods of delivery - 1: Spontaneous; 2: Forceps; 3: Vacuum; 4: Cesarean; 9: Unknown or not stated
    
    - dmeth_rec: delivery method recode - 1: Vaginal; 2: C-Section; 9: Unknown
    
    - apgar5: 5 min APGAR score - 00-10: A score of 0-10; 99: Unknown or not stated
    
    - sex: sex of infant - F: female; M: male
    
    - dbwt: imputed birth weight - 0227-8165: Number of grams; 9999: Not stated birth weight
    
    Abnormal Conditions of the Newborn
    
    - ab_vent: assisted ventilation - Y: Yes, Complication reported; N: No Complication reported; U: Unknown or not stated
    
    - ab_vent6: assisted ventilation > 6 hrs - Y: Yes, Complication reported; N: No Complication reported; U: Unknown or not stated
    
    - ab_nicu: admission to NICU - Y: Yes, Complication reported; N: No Complication reported; U: Unknown or not stated
    
    - ab_surfac: surfactant - Y: Yes, Complication reported; N: No Complication reported; U: Unknown or not stated
    
    - ab_antibio: antibiotics - Y: Yes, Complication reported; N: No Complication reported; U: Unknown or not stated
    
    Congenital Anomalies of the Newborn
    
    - ca_anen: Anencephaly - Y: Yes, Complication reported; N: No Complication reported; U: Unknown or not stated
    
    - ca_menin: Meningomyelocele / Spina Bifida - Y: Yes, Complication reported; N: No Complication reported; U: Unknown or not stated
    
    - ca_heart: Cyonotic Congenital Heart Disease - Y: Yes, Complication reported; N: No Complication reported; U: Unknown or not stated
    
    - ca_hernia: Congenital Diaphragmatic Hernia - Y: Yes, Complication reported; N: No Complication reported; U: Unknown or not stated
    
    - ca_ompha: Omphalocele - Y: Yes, Complication reported; N: No Complication reported; U: Unknown or not stated
    
    - ca_gastro: Gastrochisis - Y: Yes, Complication reported; N: No Complication reported; U: Unknown or not stated
    
    - ca_limb: Limb Reduction Defect - Y: Yes, Complication reported; N: No Complication reported; U: Unknown or not stated
    
    - ca_cleftlp: Cleft Lip w/ or w/o Cleft Palate - Y: Yes, Complication reported; N: No Complication reported; U: Unknown or not stated
    
    - ca_cleft: Cleft Palate alone - Y: Yes, Complication reported; N: No Complication reported; U: Unknown or not stated
    
    - ca_downs: Downs Syndrome - Y: Yes, Complication reported; N: No Complication reported; U: Unknown or not stated
    
    - ca_chrom: Suspected Chromosomal Disorder - C: Confirmed; P: Pending; N: No; U: Unknown
    
    - ca_hypos: Hypospadias - Y: Yes, Complication reported; N: No Complication reported; U: Unknown or not stated
    
    - aged: age at death in days, only has 2397 non-missing values - 000-365: number of days
    
    - manner: manner of death, 1937 non-missing values - 1: Accident; 2 - Suicide; 3: Homicide; 4: Pending investigation; 5: Could not determine; 6: Self-inflicted; 7: Natural; NA: Not specified if death = 1, infants alive otherwise
    
    - precare: month prenatal care began - 00: No prenatal care; 01-10: Month prenatal care began; 99: Unknown or not stated
    
    - dplural: plurality - 1: Single; 2: Twin; 3: Triplet; 4: Quadruplet; 5: Quintuplet or higher
    
    - restatus: residence status - 1: RESIDENT: State and county of occurrence and residence are the same; 2: INTRASTATE NONRESIDENT: State of occurrence and residence are the same but county is different; 3: INTERSTATE NONRESIDENT: State of occurrence and residence are different but both are one of the 50 US states or District of Columbia; 4: FOREIGN RESIDENT: The state of residence is not one of the 50 US states or District of Columbia.
    
    - tbo: total birth order - 1-7 Number of total birth order; 8: 8 or more total births; 9: Unknown or not stated
    
    - ucod130: 130 infant cause recode for underlying cause of death, only 2397 non-missing values, code level descriptions see https://wonder.cdc.gov/wonder/sci_data/natal/linked/type_txt/cohort99/130Cause99.pdf
    
    - death: indicator of infant deaths - 0: alive; 1: died
    
    - identifier: variable with values of all covariates used for matching
    
    - number: Child group number
    
    - n_children: Number of children in the groups
    
    - orderable: If you run the birth order.Rmd, it will add in a orderable variable which is 1 if the pair has birth order info and 0 otherwise
    
