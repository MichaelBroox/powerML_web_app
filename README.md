# powerML_web_app
Flask web app to predict power generation of a hydropower dam base on discharge and norminal head features

### Project Structure
This project has 3 major parts :
1. Power Generation Prediction.ipynb - This contains code for the Machine Learning model.
2. app.py - This contains Flask API that receives the norminal head and discharge and computes the precited value of power to be generated.
3. templates - This folder contains the HTML template to allow user to enter values for discharge and nornimal head and displays the predicted power to be generated. 

### Running the project
1. Run app.py using below command to start Flask API
```
python app.py
```
By default, flask will run on port 5000.

2. Navigate to URL http://localhost:5000

3. Enter valid numerical values in all input boxes and hit Predict Power.

If nothing fails, you should be able to see the predcited value of the power to be generated on the HTML page!
