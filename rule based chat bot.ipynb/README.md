"# CODSOFT" 
This project is a simple rule-based chatbot implemented in Python. The chatbot mimics a conversation by matching user input with predefined patterns using regular expressions. It operates without any AI or machine learning model, relying entirely on hardcoded rules for interaction logic. Here's a professional overview of the project:

📌 Project Overview: Rule-Based Chatbot
This project implements a rule-based conversational chatbot that simulates interaction using pattern matching. The chatbot is built using Python and is designed to recognize specific keywords or phrases and respond with appropriate, pre-programmed replies. It serves as an introductory demonstration of how basic Natural Language Processing (NLP) concepts can be applied to create a text-based dialogue system.

🧠 Core Features:
Greeting & Initialization:
The chatbot starts by asking the user for their name and whether they are willing to help, setting the tone for interaction.

Pattern Matching with Regex:
The chatbot uses regular expressions (re.match) to identify the user's intent from their input.

Intent Mapping:
It supports a limited number of conversational intents, such as:

Describing a fictional planet (describe_planet_intent)

Answering "why" questions (answer_why_intent)

Providing information about "Intellipaat" and "Disaster Management"

Conversation Flow Control:
The chatbot can detect certain commands like "quit", "pause", or "ok thanks" to end the conversation gracefully.

Fallback Handling:
If user input doesn't match any known intent, the chatbot prompts the user for clarification.

🛠️ Technical Implementation:
Python Modules Used:

re: For pattern matching of user input.

random: To vary responses and starter questions for more natural conversation flow.

Class-based Design:
Encapsulated in a RuleBot class, making the bot easy to manage, extend, and maintain.
