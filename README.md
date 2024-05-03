This script, echoImageChat, is a Streamlit app. Users can input text and images.  They can even directly talk 
with the underlying Google Gemini. Based on the RealtimeTTS (https://github.com/KoljaB/RealtimeTTS),
the speech can be converted into text and sent to Gemini as a text prompt.

To run this script, install the package first.

$ pip install streamlit

$ pip install google-generativeai

$ pip install RealtimeSTT

After the installation, run the command to launch the app.
Don't forget to create the GOOGLE_API_KEY in a local .env file first.

$ streamlit run echoImageChat.py
