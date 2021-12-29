# Machine-Learning-Classifiers-on-Traditional-and-Modern-Tobacco-Use

## Overview
Tobacco use has an evidence-based association with many chronic diseases such as cancer, cardiovascular disease, mental disorders, etc. Although combustible cigarette use has declined in the US, the percentage of some users of modern tobacco products such as e-cigarette users who initiated at a young age is 3 times
higher in 2018 than 2014 [4]. Therefore, more attention should be focused on modern tobacco products with increasing prevalence. However, most machine learning papers only focus on traditional combustible cigarette use. This motivated us to use machine learning methods to classify an individuals use status of modern tobacco products (Never user, Former user, and Current user) based on their use of other tobacco products combined with sociodemographic factors including age,
ethnicity, and marital status. Our results show that the Kernel Ridge Regression yields the best performance when compared with other machine learning methods
when evaluated using MSE and AUC scores. Future work includes the application of these machine learning methods to a more balanced dataset and the inclusion of
more information-rich features.

## Problem Statement
* In this project, we will use six machine learning methods to classify tobacco use status using an individual’s use status of other tobacco products combined with sociodemographic factors. While relevant mathematical equations and variables for all models used are shown, the external library, sklearn, was imported and used for actual implementation due to its prior optimization with respect to the python coding language in addition to the availability of built-in evaluation functions.

## Conclusion
Generally, machine learning algorithms such as Kernel Ridge, SVM perform better than traditional statistical models such as Logistic Regression and Lasso Linear Regression. More specifically, the Kernel Ridge Regression yields the best performance (highest AUC and similarly low test error compared with SVM and Random Forest) compared with other methods. In addition, the classification of modern and minor tobacco product use status based on the other products and sociodemographic factors yielded lower MSE than the classification of traditional tobacco products. In addition, the large class imbalances between current, former, and never users in modern and minor tobacco product use status classification may be causing a bias towards our low MSE results.

## Analysis limitations and potential
Although our model results shows relatively low test error and high AUC, there are other factors we did not consider such as education level, Annual household income due to the great number of missing values of these variables in the dataset, and we could even tobacco related policy like Menthol Ban in several states. Besides that, our sample only included part of participants in the US, which might yield selection bias. However, we can multiply "weight" by using inverse probability weight method to each participant to represent the national level population. In addition, we did not have time to apply class balancing efforts to our dataset in the time allotted. Large class imbalances may have been a large contributing factor to the low MSE results achieved by the Kernel Ridge Regression
method and balancing the classes may have resulted in a large improvement in true positive and true negative rate.

## References
[1] Neal L. Benowitz, M.D. Nicotine Addiction. New England Journal of Medicine.
[2] Graham W Warren, K Michael Cummings. Tobacco and lung cancer: risks, trends, and outcomes
in patients with cancer. Soc Clin Oncol Educ Book.
[3] Rebecca Evans-Polce PhD, Phil Veliz PhD, etc. Trends in E-Cigarette, Cigarette, Cigar, and
Smokeless Tobacco Use Among US Adolescent Cohorts, 2014–2018. American Journal of Public
Health.
[4] Ali A, Hossain SM, Hovsepian K. mPuff: automated detection of cigarette smoking puffs from
respiration measurements. 2012 ACM/IEEE 11th International Conference on Information Processing
in Sensor Networks (IPSN), 2012.
[5] Cole CA, Thrasher JF, Strayer SM. Resolving ambiguities in accelerometer data due to location
of sensor on wrist in application to detection of smoking gesture. IEEE, 2017: 489–92.
[6] Senyurek VY, Imtiaz MH, Belsare P, et al. A CNN-LSTM neural network for recognition of
puffing in smoking episodes using wearable sensors. Biomed Eng Lett 2020;10:195–203.
[7] Visweswaran S, Colditz JB, O’Halloran P, et al. Machine learning classifiers for Twitter surveillance
of Vaping: comparative machine learning study. J Med Internet Res 2020;22:e17478.
[8] Chu K-H, Colditz J, Malik M, et al. Identifying key target Audiences for public health campaigns:
Leveraging machine learning in the case of Hookah tobacco smoking. J Med Internet Res
2019;21:e12443.
[9] Culotta A. Towards Identifying Leading Indicators of Smoking Cessation Attempts from Social
Media. In: 2016 IEEE International Conference on Healthcare Informatics (ICHI), 2016: 7–9.
[10] Kostygina G, Tran H, Shi Y, et al. ’Sweeter than a Swisher’: amount and themes of little cigar
and cigarillo content on Twitter. Tob Control 2016;25:i75–82.
[11] Patel J, Siddiqui Z, Krishnan A, et al. Leveraging electronic dental record data to classify patients
based on their smoking intensity. Methods Inf Med 2018;57:253–60.
[12] Kim N, McCarthy DE, Loh W-Y, et al. Predictors of adherence to nicotine replacement therapy:
machine learning evidence that perceived need predicts medication use. Drug Alcohol Depend
2019;205:107668.
[13] Mamoshina P, Kochetov K, Cortese F, et al. Blood biochemistry analysis to detect smoking
status and quantify accelerated aging in smokers. Sci Rep 2019;9:142.
