# Aging-Clock

## Introduction 
- Biological age refers to the physical and functional state of an individual's body as they age, which may be different from their chronological age (i.e., the number of years since their birth).
- Biological age can provide valuable insights into an individual's health status and their risk of age-related diseases such as cardiovascular disease, diabetes, and certain cancers.
- There are various biomarkers that can be used to assess biological age, as well as  DNA methylation, telomere length, and circulating proteins.
- Age-related changes in the body can lead to an increased risk of age-related diseases such as heart disease, cancer, and Alzheimer's disease.

## Goal 
- Develop a machine learning model that can  predict biological age based on biomarkers extracted from laboratory, which can be affordable by all socio-economic classes. 
- This model can also help identify individuals who may be at increased risk of age-related diseases and mortality, majorly Cardiovascular diseases.
- Machine learning algorithms can be used to predict the likelihood of an individual developing cardiovascular diseases and estimate their biological age. This can help in early detection and diagnosis, which is essential for timely intervention and treatment.

## Motivation / Community Contribution
- To build a Cost-effective Biological Age prediction Model which can help people to monitor their health at same time they can see their vulnerability to age related diseases.
- A cost-effective model should be easily accessible, allowing people from various socioeconomic backgrounds to monitor their biological age and make informed decisions about their health.
- The biological age prediction model can be used to monitor the effectiveness of various health interventions, allowing individuals and healthcare providers to make data-driven decisions about treatment plans and lifestyle modifications.

! ![12](https://github.com/Rahulreddy1020/Aging-Clock/assets/83365184/ad9cca52-afd5-4939-ac02-929a5c1b88d0)

## Data Pipeline and Architecture 

![13](https://github.com/Rahulreddy1020/Aging-Clock/assets/83365184/f4b821f0-7642-4e1e-b2d7-de3ca8b942c0)

## Data Source

●	The data is collected from a program called The National Health and Nutrition Examination Survey (NHANES), which is designed to assess the health and nutritional status of adults and children in the United States.
●	NHANES 1999-2021 dataset is downloaded from https://wwwn.cdc.gov/nchs/nhanes/sea rch/datapage.aspx?Component=Demog raphics&Cycle=2001-2002
●	Cardiovascular Heart disease data is collected from Kaggle. https://www.kaggle.com/datasets/sulian ova/cardiovascular-disease-dataset
### Note : 
●	Every Biomarker has separate XPT ﬁle for each year, which has also has a SEQN ID.
●	All the ﬁles are concatenated based on SEQN ID.
●	Additional features which is need to work for predicting cardiovascular disease are collected through examination and Questionaire data







