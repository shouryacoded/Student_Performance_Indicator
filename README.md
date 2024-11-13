# Student Performance Indicator


## Prerequisites


Chroium based browser (Google Chrome, Brave, Opera, etc.)

git

conda 

python 3.10+

Visual Studio Code

## Usage

### Clone the repository

```markdown
git clone https://github.com/shouryacoded/Student_Performance_Indicator.git
```

### Setting up the virual environment

Open Terminal in Visual Studio Code

```markdown

conda create -p venv/ python=3.11 -y
activate venv/

```
### Installing the requirements

```markdown
pip install -r requirements.txt
```
This will install all the required libraries and dependencies and also trigger setup.py.

### Generate the logger file

```markdown
python .\src\logger.py
```
Creates 2 files in the logs folder. log.log and log.txt

### Running the pipleline
```markdown
python .\src\components\data_ingestion.py

```
This includes data ingestion, data transformation, model training, model evaluation, and model prediction.
Outputs 2 files in the artifacts folder. model.pkl and preprocessor.pkl
Outputs model accuracy and execution time in the terminal

### Running the flask app to test the model on new data provided by the user.

```markdown
python .\app.py
```
Go to http://127.0.0.1:5000/predictdata in your browser to test the model.

## Screenshots
![Flask Instance](<demos/Screenshot 2024-11-14 043600.png>)

![Flask Interface](<Screenshot 2024-11-14 045056.png>)

## Video Demo 

https://github.com/user-attachments/assets/72a3b9ab-f6cd-43ec-8afc-e50bcadecdb0

