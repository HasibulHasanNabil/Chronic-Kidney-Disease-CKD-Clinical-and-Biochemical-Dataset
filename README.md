# Chronic-Kidney-Disease-CKD-Clinical-and-Biochemical-Dataset
Dataset Overview & Brief Summary
This dataset is an extended, high-dimensional Chronic Kidney Disease (CKD) risk evaluation dataset. Unlike standard baseline CKD datasets, this version includes comprehensive clinical, biochemical, lifestyle, and inflammatory biomarker attributes.

-Total Samples: 20,538 patient records.
-Total Features: 42 predictive clinical attributes + 1 multi-class target variable.
-Data Completeness: 0 missing values across all features (fully cleaned and pre-processed).
-Task Type: Multi-class Classification / Risk Stratification.

Target Class Distribution (Target)
The dataset classifies patients into 5 distinct risk stages based on disease severity:

ClassLabel                           Description     	            Sample Count	                 Percentage
No_Disease	             Normal / Healthy kidney function           	16,432                      	~80.0%
Low_Risk	                  Early-stage risk markers present	          2,054	                       ~10.0%
Moderate_Risk	                   Moderate renal impairment	              821                        	~4.0%
High_Risk	                      Advanced stage kidney damage             	821                        	~4.0%
Severe_Disease	               End-stage renal disease (ESRD) risk       	410	                        ~2.0%

Feature Categorization
The 42 clinical variables are structured into five key medical domains:

Renal & Function Markers: eGFR, Urine protein-to-creatinine ratio, Serum creatinine, Blood urea, Cystatin C level, Urine output, Specific gravity, Serum albumin.

Inflammatory & Specialized Biomarkers: C-reactive protein (CRP), Interleukin-6 (IL-6), Parathyroid hormone (PTH), Serum calcium, Serum phosphate, Urinary sediment microscopy.

Routine Blood & Urine Tests: Random blood glucose, Hemoglobin, Packed cell volume, WBC count, RBC count, Sodium, Potassium, Cholesterol, Albumin, Sugar, Pus cells, Pus cell clumps, Bacteria.

Vitals & Demographics: Age, Blood pressure, Body Mass Index (BMI).

Medical History & Lifestyle: Hypertension (and duration), Diabetes mellitus (and duration), Coronary artery disease, Family history of CKD, Smoking status, Physical activity level, Appetite, Pedal edema, Anemia.

Key Highlights 
Class Imbalance Handling: Since ~80% of the data falls under No_Disease, techniques like SMOTE, Class Weighting, or Focal Loss are recommended for training balanced Machine Learning models.

Biomarker Analysis: Features like Cystatin C, eGFR, IL-6, and CRP make this dataset ideal for studying inflammatory pathways linked to chronic kidney disease progression.
