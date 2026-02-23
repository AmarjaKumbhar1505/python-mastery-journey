# **Basic Command Lines**

* ### **Windows**
* **go to cmd**
* **cd - shows current directory**
* **dir - shows content list in that directory**
* **cd .. - goes back to directory**
* **cd directoryName -change to directory**
* **cd press Tab will fill Autocompalete shows all option in directory**
* ### **Linux/Mac** 
* **go to terminal**
* **pwd- current directory**
* **ls - list of all folder/ directory**  
*  **cd folder/file - change folder**
* **clear- clear command line**
* **cd .. - clear cmd line**
* **vi file.txt - to edit**
* **to edit file press i**
* **to save file press ESC+:+wq without saving :q**
* **cd directory/ hit tab it swill show subdirectory/files**

* ### **Steps to activate venv**



&nbsp;python -m venv .venv   

&nbsp;.venv\\scripts\\activate   

&nbsp;

##### **Using Poetry on existing repo**

&nbsp; python -m venv .venv   

&nbsp;.venv\\scripts\\activate  

&nbsp;poetry init

&nbsp;poetry add dependencyName

poetry add $(cat requirements.txt)

$ poetry run python -m pip freeze > requirements.txt



$ poetry install	if anything mentioned manually  in toml filename

poetry lock

poetry lock --no-update





##### if venv is not configured

poetry config 

poetry run python {filename}

poetry add $(cat requirements.txt) 



deactivate venv

deactivate







##### Already cloned env with poetry



use 

poetry env activate



or poetry shell







##### without poetry if we have only .env files

&nbsp;python -m venv .venv   

&nbsp;.venv\\scripts\\activate   

&nbsp;   pip install -r requirements.txt



# 

