# s22-team7-project

Project : CHATBOT

Hello! And thank you for wanting to talk to our little buddy.
Before we begin however, there's just a couple things you need to know. You will need Jupyter to be able to talk to our robot but no worries, we'll explain in details how to do that. And the choice is yours whether to download or just use your browser. Our project's objective was to have an A.I that can simulate a basic human interection. A little pocket buddy or in this case lap buddy. The horrible naming of Replying_Tom came from it's inspiration being Talking Tom, but with a less on sided conversation. So beware, this robot will not always tell you what you want to hear!

Installation:

Launch Jupyter Notebook:

1. Open the command prompt (cmd) and give the Administrator access to it.

2. Then move to the directory where your python is installed. If you have already added Python to your environment variable, then there is no need to look for the Python folder in the directory.

3. Go into the Scripts folder > run this cmd command: ‘pip install jupyter.’

4. After completion, let’s run the Jupyter notebook, using the following command: jupyter notebook.’

5. After this, it will open the Jupyter notebook in your default browser.

OR

1. Download the latest version of anaconda. (Google download anaconda)
2. Follow the steps for proper installation
3. On Windows, you can run Jupyter via the shortcut Anaconda adds to your start menu, which will open a new tab in your default web browser

Features:

1. This project uses machine learning, neural nets model to develop chatbot which responds to the questions from user.

2. Main libraries used are tflearn, nltk, numpy, tensorflow.

3. chat.json is created which has tags and responses.

4. Bag of words is created, which tokenizes a sentence and generate the vector representation.

5. Final chat() function allows to receive questions from user and model sends responses based on training.



Steps to run:

1. Upload chatbot.ipynb file to jupyternotebook.

2. Run each cell, starting from the first cell or hit restart kernel and run all cells.

3. After completion, while provide the user a textbox foor inputs. (eg: Hey, how are u? and program shall return a response.) 
