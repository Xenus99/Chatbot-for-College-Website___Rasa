# Chatbot-for-College-Website___Rasa
This project is a chatbot for our College's(Fr. Conceicao Rodrigues College of Engineering) Website.It uses Rasa technology which makes it very easy to to create and train the bot.

# Requirements
1. Python and pip
2. Rasa or RasaX (https://rasa.com/docs/rasa/installation/)

# How To Run
1. Open the project in a Python Compilation Tool(e.g. Pycharm) or open the project location in terminal
2. Run the command " rasa train " and wait for the process to complete (This will create a new folder and save your models in the folder whenerver you run "rasa train")
3. Run " rasa shell " (With this you can test your bot on the commandline i.e. without GUI)

# How To Run(GUI)
1. Open the project in a Python Compilation Tool(e.g. Pycharm) or open the project location in terminal
2. Run the command " rasa train " and wait for the process to complete (This will create a new folder and save your models in the folder whenerver you run "rasa train")
3. Run " rasa run --enable-api --cors "*" "
4. Open another Terminal and Run " python -m http.server " in the project folder
5. Open "http://localhost:8000/" in a web browser

# To Edit the Responses
1. The Chatbot will answer according to my responses that i have addded. If you want to add your responses you need to edit the domain.yml, nlu.yml, stories.yml and rules.yml.
2. I would suggest you undersatnd how those files in Rasa work before editing them.
3. To do so you can refer Rasa documentation "https://rasa.com/docs/rasa/training-data-format/" or watch informative videos "https://youtube.com/playlist?list=PL75e0qA87dlHQny7z43NduZHPo6qd-cRc"
