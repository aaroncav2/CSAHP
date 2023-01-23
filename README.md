# Constant Sum AHP
A constant sum AHP inspired by PhD level dissertation work. This is a student PhD project to assess Cybersecurity Readiness for the Energy Industry using expert opinions in pairwise comparisons to enable validation of experts consistency through Analytical Hierarchy Process (AHP). This tool helps organizations evaluate their need to enhance cyber security controls. The tool is most suited for situtations where an outage is taking place within the organization.  
---
Huerarchical Decision Model (HDM) terminology used in this project compared to AHP  
Levels, HDM, AHP  
Level 1, Mission, Focus  
Level 2, Perspective, Actors  
Level 3, Criterion, Objectives  
Level 4, Alternative, Scenario  
***
Constant sum scale in Excel  
1,	0  
2,	0.11111  
3,	0.25  
4,	0.42857  
5,	0.66667  
6,	1  
7,	1.5  
8,	2.33333  
9,	4  
10,	9  
***
What's new in this implementation?
Step 1:  
Density - a customizable baseline measurement to make account of outliers  
Focus charts - deep dive reference when debating one individual implementation over another  
Skip level comparisons (Alternatives "Level 4" to Perspectives "Level 2")  
Step 2:  
Desirability Global Weights based on Perspectives weighting (rather than local weight mulitplication) from step 1  
New Sensitivity calculation
***
Note: That number of variables 4,5,6,7, and 11 have been put into the spreadsheet and tested. If you want to use variables matrices of 3, 8, 9, or 10 you will need to create that in the tool spreadsheet (work backwards from 11 and make space in the spreadsheet).  
***
Note: The Alternatives (Level 4) are an optional component (and an additional spreadsheet for processing output of survey) of the model in order to include cost/aquisition decisions and management personnel into a final report.
