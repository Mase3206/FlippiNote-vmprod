Flippinotes

How to run:
Go to a terminal and run
git clone https://github.com/Kylie-f/FlippiNote.git
cd /path/to/project/directory
(Check to see the installed files are there with ls)
For Windows:
python -m venv .venv
.venv\Scripts\Activate.ps1

For Mac/Linux:
python3 -m venv.venv
source .venv/bin/activate

from the venv line you can install the requirements from the txt file by:
pip install -r requirements.txt

From this, the project should work out of the box, when you are trying to run the webserver locally, do:

python manage.py runserver

then navigate to a web browser of choice, and navigate to either 127.0.0.1:8000 or localhost:8000 and you should see the server running.