# Spam Mail Detector

## What is this?
This is a tool that filters out junk mail. It looks at the text of a message and decides if it is a real message (Ham) or unwanted junk (Spam).

## The Model
The project uses a machine learning classifier to sort the messages. First, it uses a **Vectorizer** to turn the words in the email into numbers. Then, the model looks at these numbers to find patterns that usually indicate spam.

## The Code
The process is straightforward:
1. **Vectorization:** Converts the text message into a numerical format the computer understands.
2. **Prediction:** The model calculates the probability of the message being spam.
3. **Usage:** There is a function called `check_spam`. You can type in any message you want, and it will tell you if it is safe or if it is spam.
