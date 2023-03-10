Once you unzip the modular_code.zip file, you can find the following folders within it.

1. input
2. lib
3. ML_pipeline
4. output
5. engine.py
6. app.py
7. Procfile
8. property_price_prediction_voting.sav
9. PropertyVariables.py
10.readme.md
11. requirements.txt

---
1. The input folder contains the raw data that we have for analysis. In our case, it
contains Pune Real Estate Data.xlsx

2. The ML_pipeline is a folder that contains all the functions put into different python
files, which are appropriately named. The engine.py script then calls these
python functions to run the steps in one go. It can be used to train the model or
use the web application as mentioned in the readme.md file.

3. The output folder contains the models and training data python objects saved for
inference while training the model through engine.py.

4. The lib folder is a reference folder, and it contains the original ipython notebooks

5. The FastAPI for the model can be accessed by running the app.py script and
Procfile along with app.py, saved voting regressor model, propertyvariables.py
and requirements.txt will be used to deploy the application on localhost.

6. The requirements.txt file has all the required libraries with respective versions.
Kindly install the file by using the command pip install -r requirements.txt

7. All the instructions for running the code are present in readme.md file Below:


### Install all the dependencies

>> pip install -r requirements.txt

### Run the engine.py file to execute the code

### Enter 1 to train the model

### Enter 2 to run the FastAPI app.py file to run the web application
