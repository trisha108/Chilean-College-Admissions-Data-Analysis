# Chilean-College-Admissions-Data-Analysis
This project analyzes the 2007 Chilean college admissions process for students graduating from Osorno (10th region). The admissions system is run annually by the Chilean College Board, where students take national exams (Math, Verbal, Science, History) and are evaluated alongside their NEM score (high school performance).

Dataset

	•	Majors – Information about schools and programs.
	•	Scores – Demographics and exam scores of students.
	•	gender: 1 = male, 2 = female
	•	high_school_type: 2 = public, 3 = voucher, 4 = private
	•	Applications – Records of student applications to programs in ranked order.

Key Analyses

	1.	Data Cleaning & Consolidation
	•	Restructured the scores dataset into clean, columnar format using text functions and transformations.
	2.	Average Scores by Gender & High School Type
	•	Computed average NEM, LYC, and MATE scores by gender.
	•	Added slicers to compare across school types (public, voucher, private).
	3.	University Preferences
	•	Ranked universities by number of first-choice applicants.
	4.	Average Cutoff Scores by University
	•	Calculated cutoff scores and compared with applicant preferences to identify demand vs. selectivity.
	5.	Regional & Demographic Insights
	•	Counted applicants per region and university.
	•	Analyzed with slicers by gender and school type to explore equity and opportunity patterns.

Tools & Methods

	•	Excel / Google Sheets: data cleaning, PivotTables, slicers, VLOOKUP functions
	•	Data Analysis: descriptive statistics, rankings, cross-tab analysis
	•	Visualization: pivot charts, comparative plots

Insights

	•	Score distributions vary significantly across gender and high school type.
	•	Universities with the most first-choice applicants do not always have the highest cutoffs, highlighting prestige vs. selectivity differences.
	•	Private school students often dominate in high-demand programs.
