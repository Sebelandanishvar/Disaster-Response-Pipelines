# Disaster-Response-Pipelines
In this project, we have a data set containing real messages that were sent during disaster events. We will be creating a machine learning pipeline to classify these events to send the messages to an appropriate disaster relief agency.
This project will include a web app where an emergency worker can input a new message and get classification results in several categories. The web app will also display visualizations of the data. This project will show off your software skills, including your ability to create basic data pipelines and write clean, organized code!

Below is an screenshots of the web app.

<img src="/doc/disaster-response-project2.png" width="500">

Project Components
There are three components you'll need to run for this project.

Data Pipelines: Python Scripts
If someone in the future comes with a revised or new dataset of messages, they should be able to easily create a new model just by running your code. These Python scripts should be able to run with additional arguments specifying the files used for the data and model.

python process_data.py disaster_messages.csv disaster_categories.csv DisasterResponse.db

python train_classifier.py ../data/DisasterResponse.db classifier.pkl

Flask App
In the last step, you'll display your results in a Flask web app. We have provided a workspace for you with starter files. You will need to upload your database file and pkl file with your model.

This is the part of the project that allows for the most creativity. So if you are comfortable with html, css, and javascript, feel free to make the web app as elaborate as you would like.

In the starter files, you will see that the web app already works and displays a visualization. You'll just have to modify the file paths to your database and pickled model file as needed.

There is one other change that you are required to make. We've provided code for a simple data visualization. Your job will be to create two additional data visualizations in your web app based on data you extract from the SQLite database. You can modify and copy the code we provided in the starter files to make the visualizations.

Starter Code
The coding for this project can be completed using the Project Workspace IDE provided. Here's the file structure of the project:
 
<img src="/doc/config1.png" width="500">

#Running the Web App
When working in the Project Workspace IDE, here is how to see your Flask app.

Open a new terminal window. You should already be in the workspace folder, but if not, then use terminal commands to navigate inside the folder with the run.py file.

Type in the command line:
python run.py

Your web app should now be running if there were no errors.

Now, open another Terminal Window.

Type

<img src="/doc/config2.png" width="500">





