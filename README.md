
<h1>TECHNICAL REPORT - PREDICTING THE WEST NILE VIRUS<span class="tocSkip"></span></h1>

Authors: Amir Yunus, Michelle Ng, Ragunathan Theleeban<br>
GitHub: https://github.com/AmirYunus/GA_DSI_Project_4
***

# Preface

## Problem Statement

West Nile virus is most commonly spread to humans through infected mosquitos. Around 20% of people who become infected with the virus develop symptoms ranging from a persistent fever, to serious neurological illnesses that can result in death.

In 2002, the first human cases of West Nile virus were reported in Chicago. By 2004, the City of Chicago and the Chicago Department of Public Health (CDPH) had established a comprehensive surveillance and control program that is still in effect today.

Every week from late spring through the fall, mosquitos in traps across the city are tested for the virus. The results of these tests influence when and where the city will spray airborne pesticides to control adult mosquito populations.

Given weather, location, testing, and spraying data, we are tasked to predict when and where different species of mosquitos will test positive for West Nile virus. A more accurate method of predicting outbreaks of West Nile virus in mosquitos will help the City of Chicago and CPHD more efficiently and effectively allocate resources towards preventing transmission of this potentially deadly virus. 

## Executive Summary

In this report, we will consider 4 datasets, namely, df_train, df_test, df_spray and df_weather. We will also import df_sample as the sample submission for Kaggle.

Once the datasets are imported, we will explore each feature. Feature engineering comes next as we transform the date and weather features. Categorical features are also transformed to dummy variables.

Finally, we will train our model using GridSearch, of which, the best model will be used for our Kaggle submission.

# Data Visualisation and Investigation

![Image](/images/01.png)

![Image](/images/02.png)

![Image](/images/03.png)

![Image](/images/04.png)

![Image](/images/05.png)

![Image](/images/06.png)

![Image](/images/07.png)

![Image](/images/08.png)

![Image](/images/09.png)

![Image](/images/10.png)

![Image](/images/11.png)

![Image](/images/12.png)

![Image](/images/13.png)

![Image](/images/14.png)

![Image](/images/15.png)

![Image](/images/16.png)

![Image](/images/17.png)

![Image](/images/18.png)

![Image](/images/19.png)

![Image](/images/20.png)

![Image](/images/21.png)

![Image](/images/22.png)

![Image](/images/23.png)

![Image](/images/24.png)

![Image](/images/25.png)

![Image](/images/26.png)

![Image](/images/27.png)

![Image](/images/28.png)

![Image](/images/29.png)

![Image](/images/30.png)

# Data Modelling

![Image](/images/gridsearch.png)

# Predictions

![Image](/images/31.png)

![Image](/images/32.png)

![Image](/images/33.png)

![Image](/images/34.png)

![Image](/images/35.png)

![Image](/images/36.png)

![Image](/images/37.png)
