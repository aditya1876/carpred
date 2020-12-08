# CAR PRICE PREDICTOR

## Requirements
	* Dataset - https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho?select=car+data.csv

### Steps to follow:
	1. Download the dataset to local
	2. Create new conda environment
		* conda create -n <envname> python
		* conda activate <envname>
		* jupyter notebook (install jupyter notebook with - conda install notebook)
	3. Create new Notebook
	4. Work with the notebook to make the model
	5. Once the model is finalized, create a pickle file(see notebook for details) to save the model information.
	6. Create front end for the app and test the predictions
	7. Create a requirements.txt file to save all dependencies (like imported libraries) from the virtual env
		* navigate to the project folder
		* activate the virtual env
		* pip freeze > requirements.txt
	8. Upload to Heroku
		* Create a new app
		* select name of app
		* select deploy as 'Github' (upload code to github first)
		* deploy branch