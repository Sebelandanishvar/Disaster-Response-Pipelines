# Disaster-Response-Pipelines
In this project, we have a data set containing real messages that were sent during disaster events. We will be creating a machine learning pipeline to classify these events to send the messages to an appropriate disaster relief agency.
This project will include a web app to input a new message and get classification results in several categories. The web app will also present visualizations of the data. 

Below is a screenshot of the web app.

<img src="/doc/disaster-response-project2.png" width="500">


## Install
This project requires Python 3.6 or newer and the following Python libraries installed:

- nltk
- joblib
- flask 
- numPy
- pandas
- sklearn
- sqlalchemy 
- plotly
- json
- sys



### Data Pipelines: Python Scripts

In a Python script, process_data.py, write a data cleaning pipeline that:

- Loads the messages and categories datasets
- Merges the two datasets
- Cleans the data
- Stores it in a SQLite database

Type in command line:
python process_data.py disaster_messages.csv disaster_categories.csv DisasterResponse.db


In a Python script, train_classifier.py, write a machine learning pipeline that:

- Loads data from the SQLite database
- Splits the dataset into training and test sets
- Builds a text processing and machine learning pipeline
- Trains and tunes a model using GridSearchCV
- Outputs results on the test set
- Exports the final model as a pickle file

Type in command line:
python train_classifier.py ../data/DisasterResponse.db classifier.pkl


## Flask App
In the last step, we'll display your results in a Flask web app. We will need to upload our database file and pkl file with our model.

In the starter files, you will see that the web app already works and displays a visualization. You are be able to create two additional data visualizations in  web app based on data extract from the SQLite database. You can modify and copy the code we provided in the starter files to make the visualizations.

## Starter Code
Here's the file structure of the project:
 
<img src="/doc/config1.PNG" width="500">


## Running the Web App
When working with the Project, here is how to see your Flask app.

Open a new terminal window. You should already be in the workspace folder, but if not, then use terminal commands to navigate inside the folder with the run.py file.

Type in the command line:
python run.py

<img src="/doc/config2.png" width="500">


Your web app should now be running if there were no errors.

Now, open another explorer (Chrome, Edge , etc) and copy/paste the http address (for exmple: http://127.0.0.1:5000/) in address bar.

All done!









