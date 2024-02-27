# ChatbotPDF
LLM Chatbot to interact with user PDF and answer questions regarding the same

For this project, I have used the following:

**FLASK**
Flask is a fast and easy-to-use Python web framework that is lightweight and adaptable. An application framework created to facilitate the development of online applications, including web server setup and HTTP request and response management, is known as a web framework.

Our chatbot's server side, or back-end, will be built using Flask. This entails receiving and managing user communications, processing them, and responding to the user with pertinent information.

**Langchain**
A flexible tool for creating AI-powered language apps is Langchain. By utilizing pre-trained language models, it offers a multitude of features, including text retrieval, summarization, translation, and much more. The goal of this project is to properly integrate Langchain into our chatbot so that it can comprehend and react to a variety of user inputs.

**Chatbots**
Software programs called chatbots are made to converse with users in a human-like manner. They are frequently utilized in many different fields, such as customer service, eCommerce, and education, and they can reply to text inputs from users. In this project, you will create a chatbot that can respond to inquiries based on specific documents in addition to interacting with people in general.

**Routes in Flask**
Routes are an essential part of web development. When your application receives a request from a client (typically a web browser), it needs to know how to handle that request. This is where routing comes in.

In Flask, routes are created using the @app.route decorator to bind a function to a URL route. When a user visits that URL, the associated function is executed. In our chatbot project, we will use routes to handle the POST requests carrying user messages and to process document data.

Objective of the project:
1. Understand the basics of langchain and AI applications
2. Set up a development environment for building an assistant using Python Flask
3. Implement PDF upload functionality to allow the assistant to understand file input from users
4. Integrate the assistant with OpenAI’s GPT-3 model to give it a high level of intelligence and the ability to understand and respond to user requests
5. Understand how to deploy the PDF assistant to a web server for use by a wider audience
