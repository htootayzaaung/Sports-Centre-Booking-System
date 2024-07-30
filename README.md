## ERD Diagram Final Revision
This is what we expect our Database system to look like.<br>
Changes may occur in upcoming sprints<br>
![Untitled Diagram (1)](https://user-images.githubusercontent.com/110325018/226272837-9fcdae6b-7057-4288-b8c0-ea31bd268364.jpg) <br>

## WireFrames

The wireFrames for the website can be found in the given links below.

Initial HomePage Design: https://drive.google.com/file/d/1co3_UN786UDzIs74yimlorcFceo7ApJZ/view?usp=sharing <br>
Login and Create Account: https://drive.google.com/file/d/1Lhoh1ZlPNLHhpZJBQk7uxAD-X2yYFHVR/view?usp=sharing <br>
User HomePage: https://drive.google.com/file/d/1ELrEev4Ecvqq0O6cBEJR_AQHz1-X2e8y/view?usp=sharing <br>
User UI: https://drive.google.com/file/d/1a9SQmoWbNrO_TrykAYo8tfmKy1ac-djw/view?usp=sharing <br>
Employee Homepage: https://drive.google.com/file/d/1TtKAniRDu4eUusUIocXUl9BwMD3hHybe/view?usp=sharing <br>
Employee UI: https://drive.google.com/file/d/19k9Y155jMHVSjrxd7ciE78AsIg0rakzB/view?usp=sharing <br>
Manager HomePage: https://drive.google.com/file/d/14UlkKe6OiK_NrJSSFZTO6vMBdZtJLl8f/view?usp=sharing <br>
Manager UI: https://drive.google.com/file/d/1PUD01VW2O8iGAxRW-vcX1c3DQTTgji1u/view?usp=sharing <br>

## For Windows Machines:
All necessary files are inside the code directory. <br>
To create a virtual environment:<br>
code - 'python -m venv /path/to/new/virtual/environment'<br>
To activate your virtual environment: go to the directory where your environment is located and type - '.venv\Scripts\Activate'<br>
When your venv is activated, go to the directory with requirements.txt file in it (inside the code directory) and type- 'pip install -m requirements.txt'<br>
After all modules are installed:
* If app.db is present: just set the flask app- 'set FLASK_APP=run.py' and run the application using 'flask run'
* If app.db is not present: initialize the db- 'flask db init' , create migrations -'flask db migrate -m "message", 'flask db upgrade' and then run the script 'python add_roles.py' followed by the script 'python add_sessions.py'  after which follow the steps mentioned above as we now have app.db.

To Test the application:<br>
In the code directory type - pytest

## For Mac computers:
To activate your virtual environment: go to the home directory and enter the command- 'source flask/bin/activate' or 'conda activate venv_name"<br>
When your venv is activated, go to the directory with requirements.txt file in it (inside the code directory) and type- 'pip install -m requirements.txt'<br>
After all modules are installed:
* If app.db is present: Run the application using 'flask run'
* If app.db is not present: initialize the db- 'flask db init' , create migrations -'flask db migrate -m "message", 'flask db upgrade' and then run the script 'add_roles.py' followed by the script 'python add_sessions.py' after which follow the steps mentioned above as we now have app.db.

To Test the application:<br>
In the code directory enter the command- pytest

## For SOC Linux machines:
Follow the WEB APP module content.Only Section 1 content is required.<br>
To activate your virtual environment: go to the home directory and enter the command- 'source flask/bin/activate'<br>
When your venv is activated, go to the directory with requirements.txt file in it (inside the code directory) and type- 'pip install -m requirements.txt'<br>
After all modules are installed:
* If app.db is present: Run the application using 'flask run'
* If app.db is not present: initialize the db- 'flask db init' , create migrations -'flask db migrate -m "message", 'flask db upgrade' and then run the script 'add_roles.py' followed by the script 'python add_sessions.py' after which follow the steps mentioned above as we now have app.db.

To Test the application:<br>
In the code directory enter the command- pytest


### IF Your Python version is 3.7 and above
remove the dataclasses=0.8 module from requirements.txt as this is included in all versions from 3.7 and above. applicable to those who want to run this code on their personal machines.

