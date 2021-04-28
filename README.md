# investment_gap
For the project we have used dataset from the website "https://federalreporter.nih.gov/". I have downloaded all the project data (both the cost related and the abstract related) and this dataset is further used for the creation of category based database and the analysis

Folder "Category data extraction" contains jupyter notebook "investment gaps files processing" that contains code to retrieve and merge cost related and abstract data for each of the project for each of the category. Files obtained from this jupyter notebook are also present in the folder.

Folder "Dataset" contains the jupyter notebook "Remove Duplicates" that removes the project with zero funding and are duplicates. All the csv file corresposnding to this are also present in the folder. These are the files which are used for the final analysis.

Folder "Analysis" contains the notebook presenting the analysis done for each category.
	1. "Analysis" jupyter notebook contains following analysis for each of the following
		- total number of projects
		- total number of projects with no funding 
		- Totla number of words.
		- total number of projects 
		- count of non-zero funded projects 
		- count of zero fundings project
		- Zero funding project in duplicates
		- Non zero funding project in duplicates
		- Figures represnting Count of Zero and Non-Zero funding project in each category
	2. "Basic Text and Funding Analysis" jupyter notebook contains following analysis for each of the following
		- Wordcloud figures representing most occurring words in each category
		- Figures represnting Count project in each category for each agency
		- Figures represnting Total Yearly Funding for project in each category
	2. "Basic Text and Funding Analysis" jupyter notebook contains following analysis for each of the following
		- Funding Distribution Analysis for each category and for all categories
		- Figures represnting Total Funding Amount for project in each category
	
