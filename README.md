# COGS109 Final project

(change this to description of project later)

## Dataset description

UCI repo link: http://archive.ics.uci.edu/ml/datasets/Mammographic+Mass

Data Set Information:

Mammography is the most effective method for breast cancer screening available today. However, the low positive predictive value of breast biopsy resulting from mammogram interpretation leads to approximately 70% unnecessary biopsies with benign outcomes. To reduce the high number of unnecessary breast biopsies, several computer-aided diagnosis (CAD) systems have been proposed in the last years.These systems help physicians in their decision to perform a breast biopsy on a suspicious lesion seen in a mammogram or to perform a short term follow-up examination instead. This data set can be used to predict the severity (benign or malignant) of a mammographic mass lesion from BI-RADS attributes and the patient's age. It contains a BI-RADS assessment, the patient's age and three BI-RADS attributes together with the ground truth (the severity field) for 516 benign and 445 malignant masses that have been identified on full field digital mammograms collected at the Institute of Radiology of the University Erlangen-Nuremberg between 2003 and 2006. Each instance has an associated BI-RADS assessment ranging from 1 (definitely benign) to 5 (highly suggestive of malignancy) assigned in a double-review process by physicians. Assuming that all cases with BI-RADS assessments greater or equal a given value (varying from 1 to 5), are malignant and the other cases benign, sensitivities and associated specificities can be calculated. These can be an indication of how well a CAD system performs compared to the radiologists.

Class Distribution: benign: 516; malignant: 445


Attribute Information:

6 Attributes in total (1 goal field, 1 non-predictive, 4 predictive attributes)

1. BI-RADS assessment: 1 to 5 (ordinal, non-predictive!)

2. Age: patient's age in years (integer)

3. Shape: mass shape: round=1 oval=2 lobular=3 irregular=4 (nominal)

4. Margin: mass margin: circumscribed=1 microlobulated=2 obscured=3 ill-defined=4 spiculated=5 (nominal)

5. Density: mass density high=1 iso=2 low=3 fat-containing=4 (ordinal)

6. Severity: benign=0 or malignant=1 (binominal, goal field!)


Missing Attribute Values:

- BI-RADS assessment: 2

- Age: 5

- Shape: 31

- Margin: 48

- Density: 76

- Severity: 0



# Project overview

The Cogs 109 final project is meant to challenge students to apply data analysis techniques to real, large data sets to demonstrate their skills in data analysis, visualization, and communication.

# Project objectives

Identify the problems and goals of a real situation and dataset.

Choose an appropriate analysis for the problem and the goals.

Defend your choice of analysis by explaining how it helps to answer your research question.

Implement one or more data analysis techniques for your dataset.

Display data and/or results using appropriate visualizations, such as histograms, scatterplots, error calculations, etc.

Interpret and evaluate the results of the analysis by stating whether the analysis was appropriate and whether the research question was answered.

Communicate your results effectively to both experts and non-experts.

Work effectively to manage a project as part of a team.

Students will work in teams of 4 students to complete an analysis project and present theirresults during a poster presentation on the final day of class.


## Estimated project timeline –subject to change


### Week 7

Review datasets by identifying what the data represents and understanding the structure of the data. Identify and evaluate research questions for datasets you find interesting. Search for teammates in your section who share similar interests.

### Week 8

Teams of 4 will be finalized by Monday of Week 8. Section attendance during Weeks8-10is highly recommended.Students are required to meet with or communicate with their teammates during these weeks.Section time and potentially some class time during Weeks 8-9 will be used to work on group projects.

### Week 10

Project posters should be nearing completion bythe end of Week 10. By Friday, each group member should be ready to present the team’s poster. Every student will take a turnindividuallypresentingthe entire posterduring the class’s final exam period.

Student presentations will be viewed by other students and assessed using (kind, constructive) peer grading. The exact nature of student presentations will be updated with more details later in the quarter. Presentations are typically about 5 minutes, similar to how a research poster would be presented at an academic conference.

## Grading

Poster (group grade) 70%

Presentation (individual grade) 15%

Written report (group grade) 15%
