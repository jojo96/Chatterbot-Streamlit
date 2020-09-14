# Chatterbot-Streamlit
A chatbot made using the Chatterbot library in Python and locally hosted using Streamlit. Dataset used were collected during ConvAI2 competition.

# Implementation

#### A web implementation of [ChatterBot](https://github.com/gunthercox/ChatterBot) using [Streamlit](https://www.streamlit.io/).

## Local Setup:
 1. Ensure that Python, Spacy, Streamlit, and ChatterBot are installed.
 2. To install chatterbot, activate a virtual environment, follow these steps:	
 3. conda create --name chatterbot_example python=3.7
 4. conda activate chatterbot_example
 5. pip install chatterbot
 6. pip install chatterbot_corpus
 7. pip install streamlit
 8. Run *cbv2.py* with `streamlit run cbv2.py`.
 9. The demo will be live at [http://localhost:8501/](http://localhost:8501/)

## How do I deploy this to a web server?
You can try: [PythonAnywhere](https://www.pythonanywhere.com/), [AWS](https://aws.amazon.com/getting-started/projects/deploy-python-application/) or [Heroku](https://devcenter.heroku.com/articles/getting-started-with-python#introduction) to host your application.

## Training
The training has been done using conversations from datasets collected during ConvAI2 competition.[Dataset](http://convai.io/data/)
<img src="https://github.com/jojo96/Chatterbot-Streamlit/blob/master/bot.png" width=99% height=600 alt="Normal">

## Medium Tutorial
https://medium.com/@aprajit09041996/chatbot-tutorial-using-streamlit-d8af6a21d80d

## License
This source is free to use, but ChatterBot does have a license which still applies and can be found on the [LICENSE](https://github.com/gunthercox/ChatterBot/blob/master/LICENSE) page.
