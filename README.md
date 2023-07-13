# ZiggyBot
A Rasa bot based on chatgpt 
<p align="center"><img height="300" width="600" src="https://github.com/patel-aum/ZiggyBot/assets/73774338/138ef80b-22fc-452a-8422-f4d6e14e9d8b"></img></p>

Our Youtube Tutorials link:
https://www.youtube.com/playlist?list=PLv5TuIj35e2Cj4vhdLRWbsjtUf27KUete


Steps to Recreate Ziggy:
clone the repo
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
 6) Run Command "pip install rasa[full] " OR  Run Command "  rasa install "
 6) Run Command "  rasa init "
 7) Run Command " rasa run --enable-api --cors "*"  " in one shell to activate RASA api hook server
 8) Run Command " rasa run actions " in other shell to activate action server
