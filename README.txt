//////////////////////////////////////////////////
//// FIELD EXPERIMENT SIMULATION AND ANALYSIS ////
//////////////////////////////////////////////////



//////// code ////////
Folder including the executable code files.

//// code.ipynb
The file with all the code in the project.
Produces 3 .csv datasets in data/raw from scratch.
Uses these 3 datasets to produce data/experiment_merged.csv.
Generates output tables in folder results.
Please consult the comments in the code for more details.



//////// data ////////
Folder including simulated datasets, as well as the ones that 
are produced during the analysis.

//// raw/assignment.csv
The file with the groups randomly assigned to the participants
by their ids.
0 - control group
1 - "reason" treatment
2 - "emotions" treatment

//// raw/baseline_survey.csv
The file with demographic and COVID-related information on the 
subjects, collected at the beginning of the experiment.

//// raw/endline_survey.csv
The file containing the vaccination takeup as reported by the 
subjects at the end of the experiment. 



//////// results ////////
Folder including the output regression tables.

//// full_sample.tex
Regressions that help compare the efficiency of the treatments.

//// treatment_emotion.tex
Regression that explores heterogeneity in "emotions" treatment
effects.



//////// Report.pdf //////// 
Current write-up with tables from folder results and comments
on their interpretation.