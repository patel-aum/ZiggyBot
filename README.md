# ZiggyBot
A Rasa bot based on chatgpt 

Steps to Recreate Ziggy:
1) open it in Code editor
2) Go to RasaFramework >> action >>.env file and fill ChatGPT API key and path for authenticated Google OAuth File
3) create a virtual environment by typing following in terminal
	python -im env1 .\myenv
	.\env1\Scripts\activate
4) install following dependencies:

pip install openai
pip install pandas
pip install pathlib
pip install requests
pip install ruamel.yaml
pip install python-dotenv

 5) Go to RasaFramework directory
 6) Run Command "  rasa init "
 7) Run Command " rasa run --enable-api --cors "*"  " in one shell to activate RASA api hook server
 8) Run Command " rasa run actions " in other shell to activate action server
