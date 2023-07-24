NLP with Steam Reviews
David Lappin - (www.linkedin.com/in/david-lappin93)
5/2023 -7/2023
Github: https://github.com/Dlappin93/NLP_With_Video_Game_Reviews


This project explores various Natural Language Processing techniques and modeling strategies. The following files are included for the project.

If you have any questions please DM me or reach out via LinkedIn DM (www.linkedin.com/in/david-lappin93)

Files Included:

	Notebooks:
		- '1.0_EDA_and_Exploration' - general data set EDA and discussion of potential data set imbalances
		- '2.0_DataCleaning_and Prep' - text cleaning and preprocessing code
		- '3.0_Tokenize_and_Split' - text tokenization with bag of words model and test/train split fot modeling
		- '4.0 Exploratory_modeling' - exloplore, analyze, and compare performance of Logistic Regression, Known Nearest Neighbors,
			Decision Tree, and Convolutional Neural Network models

	Misc:
		- 'modelcomparison.png' - performance metric summary for various modeling techniques
		- 'steam_reviews_lap.yml' - enviroment used in notebooks
			- The file can be saved in your working directory and re-created using the line of code below:

				conda env create -f steam_reviews_lap.yml

Folders:

'bannerphoto' - simply includes header photo for notebooks
'models' - saved .pkl and .h5 models from Notebook 4
'data' - contains intitial data set as well as preproccessed and split data set used in Notebook 4 for modeling


**Additional Notes on folder structure:**

- The code for loading data and the code for saving files is specific to the file  paths of my working directory. You may need to adjust
	the filepaths where relevant if you deviate from the file structure in this repository.


