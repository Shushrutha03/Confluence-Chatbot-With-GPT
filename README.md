# Confluence-Chatbot-With-GPT

This repository hosts a Confluence chatbot project that leverages OpenAI's GPT-3.5 Turbo model for enhanced search and contextual retrieval of information from your Confluence documentation. The chatbot allows users to ask questions, and it intelligently retrieves relevant content from your Confluence space, providing a more in-depth and context-aware response. Explore the power of AI-driven knowledge retrieval and chat with your Confluence documentation like never before

**How to Use**

1.Install Libraries

pip install -r requirements.txt

2.Beginning of the file internal_doc_chatbot.py, constant values are defined for confulence space name, URL, OpenAI API Key, Confluence API Key etc. Update these to your values. Note that OpenAI API Calls are not free as of March 2023. Confluence site is free to create at this time.

3.gpt.py is the main file, run it from your IDE or terminal. This would open a flask app running at http://127.0.0.1:5000
