# Side-Effect-classification-of-a-drug

Objective

Side effects and Effectiveness of a particular drug need to be addressed. The objective of this project is to build a classification model with the help of machine learning algorithms to classify the side effects of a particular drug based on features such as age, gender, race etc.
In this paper, the approach is to use machine learning technique for evaluating all the features that influences the side effects of a drug and attempts to choose the most significant features and build a system based on these features to classify the side effects of a drug. The proposed system classifies the side effects of a drug based on age, genders and race from the gathering of past data.

Introduction

Drugs, an important way to treat various diseases, inevitably produce side effects bringing great risks to human bodies and pharmaceutical companies. A side effect is usually regarded as an undesirable secondary effect which occurs in addition to the desired therapeutic effect of a drug or medication. Side effects can occur when commencing, decreasing/increasing dosages, or ending a drug or medication regimen. 
Side effects may vary for each individual depending on the person's disease state, age, weight, gender, ethnicity and general health. How to predict the side effects of drugs is a perennial challenge in drug research.
For this project, a dataset of WebMD sourced from Kaggle has been used. As this dataset lacked ‘Name’ and ‘Race’ features, the two were randomly generated using Faker Python Module and then concatenated with it. The master dataset featured 14 columns and 362806 rows.
The dataset used for classification include reviews, conditions etc. of different users of the drugs. These can be analysed to find side effects of drugs with the help of machine learning algorithms. Here, we consider a drug named Lisinopril for detailed analyis. The machine is trained with data using various algorithms. After training, the machine predicts the output against unseen inputs. Supervised machine learning classifiers are used in building the model and fitting the data into the model.

Conclusion

Based on the derived EDAs, the following findings were noted in regard with the use of Lisinopril:
1. This drug is normally used by people with high blood pressure.
2. Majority of consumers did not have any side effects from the consumption of this drug.
3. The drug can be considered mostly safe for use by those between the age group 45-74 years (maximum nil side effects)
4. Females in general are better to use the drug as majority of them did not have any side effects from the consumption of this drug.
5. Effectiveness of the drug is almost same regardless of race and gender.
6. By race, Whites topped in the usage of this drug with a higher female ratio. 
7. Domination of female users were consistent across age groups above 24 and below 75 years.
8. People in the age groups 45 to 64 accounted for maximum usage of the drug Lisinopril. 
9. Most rated it highly for its ease of use. 
10. Side effects of the drug proved race neutral. 
11. Gender wise, side effects proved least in females.
12. It cannot be considered the best drug as its effectiveness is not that great.

The best classification model was obtained by Gradient Boosting model. On performance evaluation, maximum accuracy of 55.86% has been achieved.
