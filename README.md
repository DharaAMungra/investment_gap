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
		- 
	2. "Basic Text and Funding Analysis" jupyter notebook contains following analysis for each of the following
		- Wordcloud figures representing most occurring words in each category
		- Figures represnting Count project in each category for each agency
		- Figures represnting Total Yearly Funding for project in each category
		
	3. "Funding distribution Analysis" jupyter notebook contains following analysis for each of the following
		- Funding Distribution Analysis for each category and for all categories
		- Figures represnting Total Funding Amount for project in each category
		- Figures represnting count of for project in each category
Folder "Topic Modelling" contains the notebook presenting the 3 Topic Modelling algorithms implementation and analysis done for each category.

	1. "Topic Modelling LDA" jupyter notebook contains implementation results of LDA algorithm for each crop category

	2. "Topic Modelling Corex" jupyter notebook contains implementation results of Corex algorithm for each crop category
		
	3. "Topic Modelling Corex Distribution" jupyter notebook contains analysis regarding the distribution of topics in each category. Folders "topic_distribution" and "topic_funding" contaings images related to the same for each of the categories.
	
	4. "Investment_gap_Zero_shot" jupyter notebook contains implementation results of Zero_shot algorithm for each crop category
	
	5. "Zero shot Legume topic Distribution Analysis" jupyter notebook contains analysis of results of Zero_shot algorithm for Legume category.
	
