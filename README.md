# Amazon Lex Chatbot Project

This project involves building a conversational chatbot using **Amazon Lex**, a fully managed service for creating conversational interfaces using voice and text. The chatbot is designed to understand and process user inputs through text, providing natural and engaging interactions.

---

## Features

- **Intents**: The chatbot is built around intents, which represent specific actions or tasks a user wants to perform. Examples include greeting users, providing help, or handling unrecognized inputs.
- **Fallback Intent**: A default intent to handle unrecognized or unclear user inputs, ensuring the conversation doesn’t break.
- **Variations**: The chatbot can recognize and respond to different ways of asking the same question or making similar requests, providing a flexible and natural conversation experience.

---

## Key Components

### Intents
Intents are the core building blocks of the chatbot. Each intent includes:
- **Sample Utterances**: Example phrases users might say to trigger the intent.
- **Responses**: The chatbot’s reply when the intent is triggered.

#### Example Intents:
1. **WelcomeIntent**: Greets users with a friendly introduction and guides them on how to proceed.
   - Sample Utterances: "Hi", "Hello", "Hey", "What's up?"
   - Response: "Hello! How can I assist you today?"

2. **FallbackIntent**: Handles unrecognized or unclear user inputs.
   - Sample Utterances: "I don’t understand", "What does this mean?"
   - Response: "I’m sorry, I didn’t get that. Can you please rephrase or ask something else?"

---

## How It Works
1. **User Input**: The user interacts with the chatbot by typing text.
2. **Intent Matching**: Amazon Lex processes the input and matches it to the most relevant intent based on sample utterances and confidence scores.
3. **Response**: The chatbot responds based on the matched intent.
4. **Fallback Handling**: If the input doesn’t match any intent or has a low confidence score, the FallbackIntent is triggered to guide the user back to valid interactions.

---

## What I Learned
- **Fine-Tuning Confidence Scores**: Balancing confidence scores was crucial to ensure the chatbot accurately handled user inputs without triggering fallback intents too often.
- **FallbackIntent Configuration**: Configuring the FallbackIntent was essential to handle unexpected inputs and maintain a smooth conversation flow.
- **Variations**: Adding variations to intents allowed the chatbot to recognize different phrasings of the same question, improving the user experience.

---

## Time Spent
This project took approximately **2-3 working hours** to complete, including configuring intents, testing, and fine-tuning.

---

## How to Use
1. Clone this repository.
2. Set up an Amazon Lex environment.
3. Import the intents and sample utterances provided in this project.
4. Test the chatbot in the Amazon Lex console or integrate it into your application.

---

## License
This project is open-source and available under the [MIT License](LICENSE).

---

Feel free to contribute or provide feedback! 😊
